# Dangerous Invaders — Plan de Componentes

**Versión:** 0.1
**Fecha:** 30 de agosto de 2026
**Estado:** Documento vivo
**Relación:** deriva del [GDD v0.1](Dangerous_Invaders_GDD_v0.1.md), en particular de las secciones 12 (Sistemas principales), 19 (Alcance del primer prototipo) y 21 (Próximos temas de diseño).

---

## Propósito

Identificar los componentes del juego como unidades de diseño y desarrollo independientes. Cada componente se describe aquí de forma resumida; a medida que se desarrolle, tendrá su propio documento en `componentes/`.

**Convención de estados:**

- 🟢 **Definido** — concepto cerrado, listo para diseñar en detalle.
- 🟡 **Parcial** — concepto base existe, faltan decisiones.
- 🔴 **Abierto** — todavía no diseñado.

**Prioridad** = relación con el primer prototipo (P1 = imprescindible, P2 = deseable, P3 = post-validación).

---

## Resumen de componentes

| # | Componente | Estado | Prioridad | Documento |
|---|-----------|--------|-----------|-----------|
| 1 | Piloto (personaje) | 🟡 | P1 | pendiente |
| 2 | Nave (interior y layout) | 🟡 | P1 | pendiente |
| 3 | Estaciones / comandos | 🟡 | P1 | pendiente |
| 4 | Sistema de energía | 🟡 | P1 | pendiente |
| 5 | Movimiento de la nave | 🟡 | P1 | pendiente |
| 6 | Ataque ligero (automático) | 🟢 | P1 | pendiente |
| 7 | Escudo móvil | 🟢 | P1 | pendiente |
| 8 | Enemigos / formación invasora | 🟡 | P1 | pendiente |
| 9 | Loop de combate (victoria/derrota) | 🔴 | P1 | pendiente |
| 10 | Ataque pesado (manual) | 🟡 | P2 | pendiente |
| 11 | Pantalla / HUD / feedback | 🟡 | P2 | pendiente |
| 12 | Fase de exploración / plataformas | 🟡 | P3 | pendiente |
| 13 | Conexión entre fases / progresión | 🔴 | P3 | pendiente |
| 14 | Sectores / estructura de partida | 🔴 | P3 | pendiente |
| 15 | Multijugador (2 naves) | 🟡 | P3 | pendiente |

---

## 1. Piloto (personaje)

El avatar que el jugador controla directamente. Se desplaza por el interior de la nave y es el único medio para operar sistemas.

- **Responsabilidades:** movimiento interno, interactuar con estaciones (entrar/salir de un comando), estar ocupado en un solo lugar a la vez.
- **Depende de:** Nave (2), Estaciones (3).
- **Preguntas abiertas:** ¿movimiento libre o por posiciones discretas? ¿El piloto queda "anclado" mientras opera? ¿Tiene salud propia dentro de la nave?

## 2. Nave (interior y layout)

El espacio jugable de la fase de combate: el interior de la nave donde vive el piloto. Su layout **es** el diseño de niveles del combate — las distancias entre estaciones son el costo de repriorizar.

- **Responsabilidades:** definir distancias y recorridos entre estaciones, recibir daño exterior, contener al piloto.
- **Depende de:** Estaciones (3).
- **Definido por boceto (2026-08-30):** interior de **2 pisos** conectados por un **ascensor**, con tableros de comando repartidos entre ambos pisos. El ascensor agrega un costo de tiempo vertical a la repriorización.
- **Preguntas abiertas:** dimensiones exactas, qué estación va en qué piso, tiempo/comportamiento del ascensor, cómo se representa el daño.

## 3. Estaciones / comandos

La interfaz física entre piloto y sistemas de la nave. Cada estación expone un sistema (mover, disparar, escudo, energía).

- **Responsabilidades:** detección de interacción, ocupación/liberación por el piloto, activar o modular el sistema asociado.
- **Depende de:** Piloto (1); cada sistema (4–7, 10) se conecta a una estación.
- **Preguntas abiertas:** lista mínima de estaciones para el prototipo, ¿operación instantánea o sostenida?, ¿una estación puede quedar activa sin piloto (ej. ataque ligero)?

## 4. Sistema de energía

El recurso central que comparten movimiento y ataque ligero. Es el mecanismo que convierte la atención del jugador en decisiones excluyentes.

- **Responsabilidades:** capacidad, consumo por sistema, regeneración, reparto cuando varios sistemas compiten.
- **Depende de:** consumidores — Movimiento (5), Ataque ligero (6), potencialmente Escudo (7) y Ataque pesado (10).
- **Preguntas abiertas:** modelo exacto (pool único vs. distribución por sistema), fórmula de regeneración, ¿existe una estación de gestión de energía?

## 5. Movimiento de la nave

Desplazamiento lateral de la nave, operado desde una estación y con costo de energía.

- **Responsabilidades:** trasladar la nave, consumir energía, competir con el ataque ligero por la potencia disponible.
- **Depende de:** Estaciones (3), Energía (4).
- **Preguntas abiertas:** velocidad, ¿movimiento continuo mientras se opera o por impulsos?, costo exacto.

## 6. Ataque ligero (automático)

Disparo sostenido que se activa desde una estación y sigue funcionando sin el piloto, a cambio de consumo de energía. Es el intercambio central: tiempo del jugador ↔ potencia de la nave.

- **Responsabilidades:** disparar automáticamente al estar activo, drenar energía, poder activarse/desactivarse.
- **Depende de:** Estaciones (3), Energía (4), Enemigos (8).
- **Preguntas abiertas:** cadencia, daño, ¿apunta solo o dispara recto?, ¿se apaga solo si no hay energía?

## 7. Escudo móvil

Defensa única y posicionable (lectura espacial tipo paleta de *Breakout*). Obliga a decidir dónde protegerse; en multijugador es compartido entre ambas naves. **Confirmado (2026-08-30):** es la **plataforma flotante de la vista exterior** del boceto, entre la formación enemiga y la nave. No se duplica en multijugador: existe una sola y **ambos jugadores pueden manipularla**.

- **Responsabilidades:** interceptar proyectiles/amenazas, ser reposicionado desde una estación, cubrir solo una porción del espacio.
- **Depende de:** Estaciones (3); posible dependencia de Energía (4).
- **Preguntas abiertas:** ¿bloqueo total o con desgaste?, arco de cobertura, velocidad de reposicionamiento, ¿consume energía?

## 8. Enemigos / formación invasora

La amenaza exterior: formación que aparece arriba, se desplaza lateralmente, desciende y acelera. Genera la presión temporal que hace valiosa cada decisión del piloto.

- **Responsabilidades:** movimiento de formación, descenso progresivo, disparos hacia la nave, escalado de presión.
- **Depende de:** Loop de combate (9) para condiciones de fin.
- **Preguntas abiertas:** para el prototipo alcanza un solo tipo; familias, jefes y comportamientos especiales quedan para después.

## 9. Loop de combate (victoria/derrota)

Las reglas que abren y cierran un enfrentamiento: cuándo se gana, cuándo se pierde, qué pasa con el daño a la nave.

- **Responsabilidades:** condición de victoria (¿eliminar la formación?), condición de derrota (¿descenso completo? ¿destrucción de la nave?), sistema de daño de la nave.
- **Depende de:** Nave (2), Enemigos (8).
- **Preguntas abiertas:** todo — es el componente P1 menos definido junto con el layout de la nave.

## 10. Ataque pesado (manual)

Pulso/disparo puntual que exige presencia del piloto. Contrapunto del ataque ligero: atención concentrada a cambio de impacto puntual.

- **Responsabilidades:** disparo manual de alto impacto, cooldown o costo, requerir operación sostenida.
- **Depende de:** Estaciones (3), Energía (4).
- **Preguntas abiertas:** daño, cooldown, ¿apuntado manual?, ¿para qué amenazas específicas es la respuesta correcta?

## 11. Pantalla / HUD / feedback

Comunicación del estado del juego: energía disponible, sistemas activos, amenaza entrante. En este juego el feedback es crítico porque el jugador decide con información periférica mientras hace otra cosa.

- **Definido por boceto (2026-08-30):** **pantalla dividida simultánea** — la vista exterior del combate ocupa la parte superior (formación enemiga arriba, nave como ícono en la base, escudo/plataforma visible en el espacio) y el/los interiores de la nave ocupan una franja inferior. El jugador nunca deja de ver la amenaza mientras opera el interior: la pantalla misma implementa el pilar "todo continúa mientras decidís".
- **Responsabilidades:** composición de las dos vistas, legibilidad del estado de energía, señales de amenaza, estado de cada sistema visible desde lejos.
- **Depende de:** prácticamente todos los sistemas P1.
- **Definido (2026-08-30):** en single player el interior ocupa el **lado izquierdo** de la franja inferior y el lado derecho muestra una invitación a unirse (ej. "presione START para unirse") — la franja mantiene el mismo layout con 1 o 2 jugadores.
- **Preguntas abiertas:** proporción entre vista exterior e interior, ¿HUD tradicional superpuesto o feedback diegético dentro de la nave (paneles, luces, alarmas)?, correspondencia visual entre posición de la nave en la vista exterior y lo que hace el piloto adentro.

## 12. Fase de exploración / plataformas

Segmentos a pie entre combates: plataformas, exploración, disparo ligero. Cambio de ritmo, no de castigo.

- **Responsabilidades:** controller de plataformas, niveles explorables, obstáculos y combate ligero, objetivo/salida.
- **Depende de:** Piloto (1) — idealmente comparte controller base; Conexión entre fases (13).
- **Preguntas abiertas:** cámara, estructura de niveles, enemigos terrestres. **No entra en el primer prototipo.**

## 13. Conexión entre fases / progresión

Lo que hace que explorar alimente el combate y el combate motive explorar: recursos, mejoras, reparación.

- **Depende de:** ambas fases funcionando.
- **Preguntas abiertas:** todo. El GDD (sección 14) indica explícitamente no cerrar esto antes de validar el core.

## 14. Sectores / estructura de partida

El macro-loop: encadenar combate → exploración → siguiente sector, y la eventual estructura roguelite.

- **Depende de:** Loop de combate (9), Exploración (12), Conexión (13).
- **Preguntas abiertas:** todo.

## 15. Multijugador (2 naves)

Cooperativo con una nave por jugador y sistemas compartidos (en particular el escudo único).

- **Definido (2026-08-30):** cada jugador tiene su **propia nave y su propio interior**. Ambos interiores son visibles a la vez en la franja inferior ("Interior de la nave P1" / "Interior de la nave P2"), compartiendo la misma vista exterior de combate. El modo es **cooperativo local drop-in**: en single player, el panel derecho muestra "presione START para unirse". Sistemas como el escudo no se duplican: son compartidos y manipulables por ambos jugadores.
- **Depende de:** todos los sistemas P1 funcionando en single player primero.
- **Preguntas abiertas:** ¿además de local habrá online?, qué otros sistemas son compartidos además del escudo, ¿el drop-in se permite en medio de un combate o solo entre sectores?

---

## Orden de desarrollo propuesto

El orden sigue las dependencias y el objetivo del prototipo (validar la fantasía de correr entre sistemas bajo presión):

1. **Piloto + Nave + Estaciones** (1, 2, 3) — la base física: un piloto que camina y puede ocupar comandos.
2. **Energía + Movimiento + Ataque ligero** (4, 5, 6) — el primer intercambio real de priorización.
3. **Enemigos + Loop de combate** (8, 9) — la presión exterior que da urgencia a todo lo anterior.
4. **Escudo** (7) — segunda dimensión de decisión: defensa posicional.
5. **HUD mínimo + Ataque pesado** (11, 10) — legibilidad y variedad ofensiva.
6. **Checkpoint de validación** — ¿aparece la tensión de priorización? (hipótesis de la sección 20 del GDD). Solo si la respuesta es sí, continuar con 12–15.

---

## Cómo se desarrolla cada componente

Cuando un componente pase a diseño detallado:

1. Se crea `componentes/NN_nombre.md` con: propósito, reglas concretas, valores iniciales, interfaz con otros componentes y qué se quiere validar jugando.
2. Se actualiza su fila en la tabla de este documento (estado + link).
3. Toda mecánica nueva dentro del componente responde primero al filtro del GDD: **¿mejora la decisión de priorización?**
