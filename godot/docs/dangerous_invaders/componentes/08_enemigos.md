# Componente 08 — Enemigos (fase de pilotaje)

**Estado:** propuesta v0.1 — análisis de tipos, pendiente de validación
**Prioridad:** P1 (formación base + picador); el resto por capas
**Relación:** [Plan de Componentes](../Plan_Componentes_v0.1.md) · presiona a [Nave (02)](02_nave.md) y [Estaciones (03)](03_estaciones.md)
**Referencias:** *Space Invaders*, *Galaga*, *1943*, *B-Wings*

> **Alcance:** este documento cubre exclusivamente los enemigos de la **fase de pilotear la nave**. Los enemigos de la fase plataformera tendrán mecánicas distintas y sus propias referencias (*Zelda II: The Adventure of Link*, *Castlevania* de NES/Famicom); se diseñarán junto al componente 12 (Exploración).

---

## Criterio rector

Como el jugador no esquiva con reflejos sino que **administra atención**, cada tipo de enemigo debe **presionar una decisión distinta** — es decir, empujar al piloto hacia una estación en particular. Un enemigo que no cambia hacia dónde corre el piloto es decoración.

### Regla de velocidad y presión

**La presión viene de la cantidad de decisiones simultáneas, no de la velocidad de reacción.**

- Proyectiles y enemigos lentos siempre. La dificultad escala agregando *frentes* (una oleada + un picador + un bombardero), no acelerando.
- Las **lluvias de balas** existen, pero como *eventos telegrafiados*: se anuncian con 2–3 segundos de aviso, y ese aviso es la ventana para correr al escudo o reposicionar la nave. Clímax visual de danmaku, jugado con anticipación en vez de reflejos — quien "esquiva" es una nave lenta operada desde adentro.
- Nunca debe volverse imposible tomar decisiones: si el jugador no llega a *ninguna* respuesta razonable, el encuentro está mal calibrado.

---

## Familias de enemigos

### 1. Formación invasora (base)

Aparecen todos de pronto y descienden lentamente en bloque, moviéndose de un costado al otro (*Space Invaders*).

- **Rol:** el **reloj del combate** — presión de fondo constante y predecible que castiga la inacción total.
- **Presiona:** mantener el ataque ligero activo (y por lo tanto el presupuesto de energía).

### 2. Oleadas coreografiadas

Entran por tandas coordinadas con trayectoria curva y movimiento sincronizado, una nave detrás de otra — por ejemplo **6 naves** (*Galaga*).

- **Regla:** destruir la oleada **completa** desbloquea un power-up o item.
- **Rol:** capa de **riesgo/recompensa opcional**: ¿invierto atención en cazarlas todas mientras la formación sigue bajando, o las dejo pasar?
- **Sinergia:** la recompensa cae al espacio y hay que capturarla con imán/gancho (comp. 16) — dos decisiones encadenadas: cazar y luego recolectar.
- **Presiona:** ataque ligero/pesado + recolección.

### 3. Picadores

Se desprenden de la formación y se lanzan en picada hacia la nave (el *dive* de Galaga). Lentos y bien telegrafiados.

- **Rol:** la crisis puntual que pregunta directamente **"¿me muevo o me protejo?"** — la tensión construida al poner timón y escudo en pisos distintos.
- **Presiona:** Timón vs. Escudo (elección excluyente).

### 4. Bombarderos / artillería

No persiguen; sueltan proyectiles lentos que caen en vertical o en arco (*1943*).

- **Rol:** presionar el **posicionamiento anticipado del escudo**: se ve dónde va a caer y hay unos segundos para decidir si cubrir ahí o dejar que el casco absorba.
- **Presiona:** Escudo (y la evaluación de cuánto casco arriesgar).

### 5. Escuadrones laterales

Entran desde los costados a baja altura, por debajo de la cobertura del escudo (*B-Wings*, *1943*).

- **Rol:** **invalidar temporalmente el escudo** como respuesta universal; evitan que "estacionar el escudo en el medio" sea siempre correcto.
- **Presiona:** Timón / Cañón pesado.

### 6. Blindados / élites

Coraza que el ataque ligero no atraviesa (o tarda demasiado): solo el **disparo pesado** los rompe.

- **Rol:** justificar la existencia del cañón pesado — sin ellos, nadie abandona las estaciones de alta frecuencia para ir a esa estación.
- **Presiona:** comprometerse al Cañón pesado.

### 7. Transportes de recompensa

Cruzan la pantalla sin atacar (el transporte de *1943*, la nave bonus de *Space Invaders*). Sueltan items si se los derriba a tiempo.

- **Rol:** puro premio por atención; dan trabajo al imán/gancho fuera de los momentos de crisis. Baratos de implementar.
- **Presiona:** Recolección.

---

## Jefes

### Piñata

Gran barra de HP que, literal como una piñata, **suelta items al recibir daño** — no solo al morir.

- **Por qué funciona acá:** pegarle hace caer recompensas *que hay que recolectar mientras el jefe sigue atacando* — atacar, defender y recolectar compiten por el mismo piloto.
- Fases por umbral de vida que cambian el patrón de ataque.

### Punto débil

Invulnerable salvo un núcleo que se expone por ventanas de tiempo, o tras romperle partes (los acorazados de *1943*). El núcleo **solo recibe daño del disparo pesado**.

- **La mecánica real no es apuntar:** es que el jugador debe *comprometerse* a estar anclado en el cañón justo cuando la ventana se abre, abandonando defensa y movimiento. Castiga al que no planifica el viaje con antelación.

### Capturador (candidato post-validación)

Con un rayo tractor **roba algo** — el escudo, un item, o en multijugador podría inmovilizar una de las dos naves — y hay que recuperarlo (*Galaga*).

- El más temático para coop (rescate), pero el más caro de diseñar. Anotado como candidato, no como compromiso.

### Lluvia de balas en jefes

Los jefes son el lugar natural para los eventos de danmaku: el jefe telegrafia la tormenta (2–3 s), el jugador corre al escudo o reposiciona. Espectáculo controlado, no estado permanente.

---

## Matriz resumen

| Tipo | Decisión que presiona | Estación implicada |
|------|----------------------|--------------------|
| Formación base | mantener ofensiva activa | Ataque ligero |
| Oleada coreografiada | ¿persigo la recompensa? | Ataque ligero/pesado + recolección |
| Picador | ¿esquivo o bloqueo? | Timón vs. Escudo |
| Bombardero | ¿dónde cubro? | Escudo |
| Escuadrón lateral | flanco sin cobertura | Timón / Cañón pesado |
| Blindado | comprometerse al cañón | Cañón pesado |
| Transporte | premio por atención | Recolección |
| Jefes | todas a la vez, por fases | rotación completa |

---

## Alcance del prototipo

Solo **formación base + picador**: son los dos que validan la hipótesis central — presión de fondo constante + crisis puntual que obliga a soltar lo que se estaba haciendo. El resto se suma por capas, cada tipo pasando el filtro: *¿presiona una decisión que los tipos existentes todavía no presionan?*

---

## Qué validar jugando

1. ¿La formación base sola ya genera la sensación de reloj (urgencia sin pánico)?
2. ¿El picador produce la elección timón-vs-escudo o los jugadores encuentran una respuesta dominante?
3. ¿El ritmo de aparición deja *ventanas de decisión* legibles o se percibe como ruido?

---

## Preguntas abiertas

- Cantidades, HP, cadencias y patrones exactos de cada tipo (post-prototipo).
- ¿Las oleadas coreografiadas premian solo la destrucción total o hay premio parcial?
- Orden de introducción de las familias a lo largo de los sectores.
- Enemigos de la fase plataformera: diseño aparte con referencias *Zelda II* / *Castlevania* NES (ver componente 12).
