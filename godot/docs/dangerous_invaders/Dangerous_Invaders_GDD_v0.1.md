# Dangerous Invaders — Game Design Document

**Versión:** 0.1  
**Fecha:** 30 de agosto de 2026  
**Estado:** Documento vivo / Preproducción  
**Formato de trabajo:** Minimalista e incremental

---

## 1. High Concept

**Dangerous Invaders** es un juego de ciencia ficción para 1–2 jugadores centrado en la **tensión por priorizar**.

El jugador no controla directamente una nave mediante controles tradicionales. Controla a un **piloto que se desplaza físicamente por el interior de una pequeña nave espacial**, moviéndose entre comandos y sistemas para decidir qué atender en cada momento.

Mientras el jugador se ocupa de una tarea, el resto de la situación continúa evolucionando.

La pregunta central del juego es:

> **¿En qué invierto mi tiempo ahora, sabiendo que todo lo demás sigue avanzando?**

El juego alterna dos fases principales:

1. **Combate espacial:** enfrentamientos inspirados estructuralmente en *Space Invaders*, operando la nave desde su interior.
2. **Exploración / plataformas:** segmentos a pie inspirados en *Campanella 2* y *Jump King*, con mayor énfasis en exploración y combate ligero.

---

## 2. Referencias

Las referencias se utilizan como **principios de diseño**, no como plantillas a copiar.

### Space Invaders

Aporta:

- Enemigos que aparecen por encima del jugador.
- Movimiento lateral de las formaciones enemigas.
- Descenso progresivo de la amenaza.
- Aumento de presión a medida que los enemigos avanzan.
- Sensación de defensa frente a una fuerza que gana terreno.

### Lovers in a Dangerous Spacetime

Aporta:

- Control indirecto de la nave.
- Personajes que se desplazan físicamente entre estaciones o comandos.
- Sistemas que compiten por la atención del jugador.
- Priorización constante.
- Cooperación basada en reparto espontáneo de tareas.

### Campanella 2 — UFO 50

Aporta:

- Nave pequeña como elemento central de la experiencia.
- Alternancia entre pilotaje y exploración.
- Sensación de expedición.
- Gestión de recursos vinculada al desplazamiento.
- Contraste entre navegar y abandonar temporalmente la nave.

### Jump King

Aporta principalmente una referencia para:

- Movimiento de plataformas deliberado.
- Lectura clara del espacio.
- Desafíos de navegación.

Dangerous Invaders no busca replicar su nivel de castigo. La fase de plataformas debe ser **más accesible y ligera**.

---

## 3. Pilares de diseño

### 3.1. Tensión por priorización

El desafío principal no consiste solamente en ejecutar bien una acción.

Consiste en decidir **qué acción merece atención ahora**.

Operar un sistema significa, potencialmente, descuidar otro.

---

### 3.2. Pilotear desde adentro

La fantasía central es:

> **Ser un pequeño piloto operando una nave espacial desde su interior bajo presión.**

El jugador controla al piloto.

La nave responde a los sistemas que el piloto activa, modifica o abandona.

---

### 3.3. Todo continúa mientras decidís

El juego no debería detenerse cada vez que el jugador cambia de sistema.

Mientras el piloto:

- cambia de posición,
- manipula un arma,
- mueve el escudo,
- administra energía,
- o atiende otro comando,

los enemigos continúan avanzando.

---

### 3.4. Minimalismo sistémico

Dangerous Invaders no busca convertirse en un simulador complejo de nave espacial.

Cada sistema nuevo debe justificar su existencia respondiendo:

> **¿Mejora la decisión de priorización?**

Si una mecánica añade trabajo pero no genera una decisión interesante, no debería incorporarse.

---

## 4. Jugadores

### Un jugador

Un único piloto opera su nave y debe desplazarse entre sus diferentes comandos.

La presión surge de no poder atender todos los sistemas simultáneamente.

### Dos jugadores

El multijugador utiliza **dos naves**.

Cada jugador controla su propio personaje y su propia nave.

Sin embargo, determinados sistemas o comandos pueden tener comportamiento compartido entre ambas naves.

### Principio cooperativo

La cooperación no depende exclusivamente de que ambos jugadores ocupen la misma nave.

El diseño debe permitir que las decisiones de una nave afecten las posibilidades de la otra.

---

## 5. Estructura general

El juego se organiza alrededor de sectores.

### Core Loop

**Entrar en un nuevo sector**  
↓  
**Combatir desde la nave**  
↓  
**Descender / abandonar la nave**  
↓  
**Explorar**  
↓  
**Obtener recursos o mejoras**  
↓  
**Regresar a la nave**  
↓  
**Avanzar al siguiente sector**

La forma exacta de transición entre estas etapas todavía no está cerrada.

---

# 6. Fase I — Combate espacial

## 6.1. Estructura básica

La nave del jugador se encuentra en la parte inferior del espacio de combate.

Las naves enemigas aparecen por encima.

Los enemigos:

- se desplazan lateralmente;
- descienden progresivamente;
- incrementan la presión a medida que avanzan;
- pueden aumentar su velocidad durante el enfrentamiento.

La amenaza se inspira en la estructura espacial de *Space Invaders*, pero el jugador no controla la nave directamente.

---

## 6.2. Movimiento de la nave

La nave puede desplazarse lateralmente.

Para hacerlo, el piloto debe utilizar los controles correspondientes desde el interior.

El movimiento utiliza energía.

Por lo tanto, desplazarse no es una acción gratuita.

Mover la nave implica utilizar un recurso que también puede ser necesario para otros sistemas.

### Objetivo de diseño

El movimiento debe generar decisiones como:

- ¿Me desplazo para evitar esta amenaza?
- ¿Mantengo energía disponible para disparar?
- ¿Puedo permitirme moverme mientras el arma automática está activa?
- ¿Conviene depender del escudo en lugar de reposicionarme?

---

## 6.3. Energía / potencia

La energía es un recurso central de la fase espacial.

Al menos las siguientes acciones están vinculadas a ella:

- movimiento;
- ataque ligero automático.

La activación de sistemas puede reducir la capacidad disponible para otros.

### Estado actual

La fórmula exacta de energía, regeneración, capacidad máxima y distribución todavía está **abierta**.

---

# 7. Sistema de combate

Actualmente existen dos familias de ataque.

## 7.1. Ataque ligero

El ataque ligero funciona de manera **automática** una vez activado.

### Funcionamiento

1. El piloto activa el sistema.
2. La nave comienza a disparar automáticamente.
3. Los disparos consumen energía.
4. El piloto queda libre para abandonar ese comando y realizar otras tareas.

### Consecuencia

Activar fuego automático libera **tiempo del jugador**, pero consume **potencia de la nave**.

Esto genera un intercambio entre:

- atención;
- energía;
- movilidad;
- capacidad ofensiva.

La activación del ataque automático reduce la capacidad de movimiento disponible al consumir potencia.

---

## 7.2. Ataque pesado

Existe un segundo ataque de uso manual.

Conceptualmente es un **pulso / disparo pesado**.

Está pensado para amenazas o defensas específicas y requiere una intervención directa del jugador.

### Diferencia buscada

**Ataque ligero**

- automático;
- sostenido;
- consume energía;
- permite que el piloto atienda otros sistemas.

**Ataque pesado**

- manual;
- puntual;
- requiere atención;
- destinado a situaciones específicas.

Los valores, cooldowns, daño y comportamiento definitivo permanecen abiertos.

---

# 8. Sistema de defensa

## 8.1. Escudo móvil

Existe **un único escudo**.

El escudo funciona como un elemento móvil de defensa, conceptualmente cercano a la lectura espacial de una paleta de *Breakout*.

Debe colocarse para interceptar amenazas.

No se trata de una protección completa y permanente alrededor de la nave.

El jugador debe decidir **dónde protegerse**.

---

## 8.2. Escudo en multijugador

Incluso con dos naves continúa existiendo **un único escudo**.

El escudo puede ser manipulado por una o por ambas naves.

Esto convierte la defensa en un recurso compartido.

### Consecuencia cooperativa

Proteger una nave puede implicar dejar expuesta a la otra.

El escudo debe favorecer decisiones de coordinación y no simplemente duplicarse para cada jugador.

---

# 9. Micro-loop de combate espacial

Durante un enfrentamiento, el jugador repite aproximadamente:

**Detectar amenaza**  
↓  
**Priorizar**  
↓  
**Desplazarse hasta un comando**  
↓  
**Operar un sistema**  
↓  
**Observar la consecuencia**  
↓  
**Repriorizar**

Este loop representa actualmente el núcleo de Dangerous Invaders.

No importa únicamente ejecutar correctamente una acción.

Importa decidir **cuándo dejar de hacerla y correr hacia otra**.

---

# 10. Fase II — Exploración / plataformas

Después de determinados enfrentamientos espaciales, el piloto puede abandonar la nave.

La segunda fase cambia la escala de la experiencia.

El jugador controla directamente al personaje en un segmento de plataformas y exploración.

---

## 10.1. Referencias

Esta fase toma como inspiración:

- la exploración fuera de la nave de *Campanella 2*;
- la lectura de movimiento y plataformas de *Jump King*.

Sin embargo:

> **No debe convertirse en una experiencia extremadamente castigadora.**

Debe funcionar como un cambio de ritmo respecto de la presión sistémica del combate espacial.

---

## 10.2. Acciones confirmadas

Fuera de la nave, el personaje puede:

- desplazarse;
- realizar plataformas;
- explorar;
- disparar;
- enfrentarse a obstáculos o enemigos;
- avanzar hacia una salida u objetivo.

---

## 10.3. Micro-loop de exploración

**Explorar**  
↓  
**Superar obstáculo**  
↓  
**Combatir cuando sea necesario**  
↓  
**Obtener recursos / progreso**  
↓  
**Continuar hacia la salida**

---

## 10.4. Cámara

La intención inicial es evitar depender de una cámara móvil como elemento central del desafío.

La implementación definitiva de cámara permanece abierta.

---

# 11. Relación entre ambas fases

Las dos fases no deberían sentirse como dos juegos completamente independientes.

La exploración debe alimentar la siguiente fase espacial.

La fase espacial debe generar una razón para explorar.

La conexión puede realizarse mediante:

- recursos;
- mejoras;
- reparación;
- progresión;
- nuevas posibilidades sistémicas.

### Estado actual

La naturaleza exacta de esa conexión todavía **no fue definida**.

---

# 12. Sistemas principales

Actualmente el diseño necesita desarrollar las siguientes áreas:

## Navegación

Cómo se desplaza la nave y qué decisiones genera ese desplazamiento.

**Estado:** parcialmente definido.

---

## Estaciones / comandos

Cómo interactúa físicamente el piloto con los sistemas internos.

**Estado:** estructura general definida; cantidad y disposición exactas pendientes.

No se considera cerrada todavía una lista definitiva de estaciones.

---

## Combate

Ataque automático ligero + ataque pesado manual.

**Estado:** concepto base definido.

---

## Defensa

Escudo único móvil.

**Estado:** concepto base definido.

---

## Potencia

Recurso compartido por distintos sistemas de la nave.

**Estado:** concepto definido; reglas numéricas pendientes.

---

## Exploración

Segmentos a pie con plataformas, disparo y exploración.

**Estado:** concepto base definido.

---

## Progresión

Debe conectar sectores y potencialmente ambas fases.

**Estado:** pendiente de diseño.

---

# 13. Recursos

La energía/potencia es actualmente el único recurso sistémico claramente establecido.

Durante la exploración pueden existir recursos, mejoras u otros elementos de progresión.

Estos todavía no fueron definidos.

---

# 14. Progresión

La progresión general todavía está abierta.

No se ha decidido:

- estructura exacta de upgrades;
- cantidad de mejoras;
- árboles de habilidades;
- economía;
- desbloqueos;
- duración de una partida;
- estructura roguelite definitiva;
- persistencia entre partidas.

Estas decisiones no deben cerrarse antes de validar el core gameplay.

---

# 15. Enemigos

La lógica general establecida para los enemigos espaciales es:

- aparecen por encima;
- se desplazan lateralmente;
- descienden;
- generan presión espacial;
- pueden acelerar.

Todavía no se han definido:

- familias;
- estadísticas;
- cantidad;
- comportamientos especiales;
- jefes;
- enemigos terrestres.

---

# 16. Tono y ambientación

## Género

Ciencia ficción.

## Alcance

La ambientación debe apoyar al gameplay sin convertir inicialmente el proyecto en un ejercicio de construcción de lore.

Actualmente no están cerrados:

- contexto político;
- origen de los invasores;
- planeta;
- facciones;
- personajes;
- historia;
- cronología.

El lore se desarrollará cuando sea útil para sostener las decisiones jugables.

---

# 17. Principio de evaluación de nuevas mecánicas

Toda mecánica propuesta deberá probarse primero de la forma más pequeña posible.

La pregunta de evaluación será:

> **¿Esta mecánica hace más interesante la priorización?**

Si la respuesta es no, deberá:

- simplificarse;
- reformularse;
- o descartarse.

Este criterio busca evitar que la combinación de referencias termine produciendo sistemas redundantes o complejidad innecesaria.

---

# 18. Qué NO está decidido todavía

Esta sección es deliberada. El documento debe distinguir decisiones reales de ideas potenciales.

Actualmente permanecen abiertos:

- número definitivo de estaciones;
- layout interno de las naves;
- controles exactos;
- tipos definitivos de enemigos;
- sistema de daño;
- reparación;
- comportamiento exacto de la energía;
- duración de cada combate;
- duración de cada sector;
- estructura completa de exploración;
- generación procedural;
- mejoras;
- economía;
- progresión;
- condiciones exactas de victoria;
- condiciones exactas de derrota;
- bosses;
- narrativa;
- lore;
- dirección artística;
- interfaz;
- audio;
- estructura final de campaña o runs.

---

# 19. Alcance del primer prototipo

El objetivo del primer prototipo no es demostrar el juego completo.

Debe comprobar exclusivamente si funciona esta fantasía:

> **Mover físicamente un piloto entre sistemas mientras una amenaza exterior continúa avanzando.**

El prototipo debería permitir validar:

1. Una nave.
2. Un piloto desplazándose dentro de ella.
3. Movimiento lateral de la nave mediante un comando.
4. Enemigos descendiendo desde arriba.
5. Ataque automático.
6. Consumo de energía.
7. Escudo móvil.
8. Necesidad real de abandonar una tarea para atender otra.

No necesita todavía:

- progresión;
- arte definitivo;
- lore;
- múltiples tipos de enemigos;
- upgrades;
- exploración completa;
- campaña.

---

# 20. Hipótesis principal a validar

El proyecto depende de una hipótesis central:

> **Es entretenido decidir qué sistema atender cuando no existe tiempo suficiente para atenderlos todos al mismo tiempo.**

Antes de ampliar el juego, el prototipo debe demostrar que esa tensión aparece de manera natural.

---

# 21. Próximos temas de diseño

Las próximas áreas a desarrollar son:

1. **Layout interno de la nave.**
2. **Lista mínima de comandos/estaciones.**
3. **Modelo de energía.**
4. **Comportamiento del escudo.**
5. **Reglas del ataque pesado.**
6. **Condición de victoria/derrota del combate espacial.**
7. **Relación concreta entre combate y exploración.**
8. **Primer prototipo jugable.**

---

# 22. Metodología de diseño

El desarrollo utiliza como referencia metodológica *The Game Design Toolbox* de Martin Annander.

Principios aplicados actualmente:

- definir primero la experiencia deseada;
- trabajar con verbos y acciones;
- tratar las referencias como inspiración y no como soluciones prefabricadas;
- explorar mediante prototipos pequeños;
- diseñar sistemas por capas;
- evitar añadir features redundantes;
- registrar explícitamente qué está decidido y qué permanece abierto;
- validar las ideas jugando antes de comprometerse con ellas.

---

## Resumen ejecutivo

**Dangerous Invaders** es un juego de ciencia ficción para uno o dos jugadores donde cada jugador controla a un pequeño piloto dentro de una nave espacial.

Durante los combates, enemigos inspirados estructuralmente en *Space Invaders* avanzan desde la parte superior mientras el piloto corre entre sistemas internos para mover la nave, atacar, administrar potencia y controlar un escudo móvil.

El ataque ligero puede dejarse funcionando automáticamente a cambio de energía, mientras un ataque pesado exige intervención directa. En multijugador hay dos naves, pero ciertos sistemas —particularmente el único escudo— pueden ser compartidos.

Entre enfrentamientos, el jugador abandona la nave para recorrer segmentos de plataformas, exploración y combate ligero inspirados en *Campanella 2* y *Jump King*.

Todo el diseño gira alrededor de una pregunta:

> **¿En qué invierto mi tiempo ahora, sabiendo que todo lo demás sigue avanzando?**
