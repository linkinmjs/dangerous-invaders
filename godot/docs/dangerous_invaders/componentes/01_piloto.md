# Componente 01 — Piloto

**Estado:** propuesta v0.1 — pendiente de validación
**Prioridad:** P1
**Relación:** [Plan de Componentes](../Plan_Componentes_v0.1.md) · depende de [Nave (02)](02_nave.md) y [Estaciones (03)](03_estaciones.md)

---

## Propósito

El piloto es el avatar que el jugador controla directamente y la **única interfaz** con los sistemas de la nave. Nada ocurre en la nave si un piloto no lo opera (con la excepción de sistemas conmutados que quedaron activos, ver [Estaciones](03_estaciones.md)).

Su función de diseño: convertir la atención del jugador en **desplazamiento físico con costo de tiempo**.

---

## Reglas propuestas

### Movimiento

- Vista lateral dentro del interior de la nave.
- Movimiento **horizontal libre** (izquierda/derecha), velocidad constante.
- **Sin salto en la fase de combate.** La verticalidad se resuelve únicamente con el ascensor. El plataformeo queda reservado para la Fase II (exploración), lo que además diferencia el "feel" de ambas fases.
- El piloto no puede salir de la nave durante el combate.

### Interacción con estaciones

- Al estar en el área de una estación, un **botón de interacción** la ocupa.
- Mientras opera, el piloto queda **anclado**: no se desplaza y sus inputs van a la estación.
- **Salir es instantáneo**: moverse (o presionar interacción de nuevo) libera la estación al momento. No hay animación de salida que retenga al jugador — la sensación buscada es poder *soltar todo y correr*.
- Un piloto ocupa **una sola estación a la vez**.

### Daño

- En el prototipo, el piloto **no tiene salud propia**: todo el daño lo recibe el casco de la nave (ver [Nave](02_nave.md)).

### Controles (prototipo)

| Input | Acción |
|-------|--------|
| Stick / flechas ←→ | Moverse |
| Botón A (interacción) | Ocupar / liberar estación · usar ascensor |
| Inputs contextuales | Definidos por la estación ocupada (ej. ←→ mueve la nave desde el timón) |

---

## Valores iniciales (a tunear jugando)

| Parámetro | Valor inicial | Razón |
|-----------|--------------|-------|
| Tiempo de cruzar un piso completo | ~2.0 s | Suficiente para que "ir hasta allá" sea una decisión, no un trámite |
| Entrar/salir de estación | Instantáneo (0 s) | Toda la fricción debe venir de la distancia, no de la interacción |
| Aceleración | Casi instantánea | Control directo, sin inercia — el piloto debe sentirse ágil en contraste con la nave |

---

## Interfaz con otros componentes

- **[Estaciones (03)](03_estaciones.md):** el piloto emite `interactuar` y, mientras está anclado, reenvía sus inputs a la estación ocupada. La estación decide qué hacer con ellos.
- **[Nave (02)](02_nave.md):** el interior define los límites de movimiento y la posición del ascensor.
- **Multijugador (15):** cada jugador controla un piloto en su propio interior; no comparten espacio físico.

---

## Qué validar jugando

1. ¿Correr entre estaciones se siente bien en sí mismo (game feel básico)?
2. ¿La distancia + anclaje generan la tensión de "estoy acá y debería estar allá"?
3. ¿La salida instantánea alcanza para que abandonar una tarea se sienta como decisión y no como castigo de input?

---

## Preguntas abiertas

- ¿Conviene algún verbo extra dentro de la nave (correr/dash) o la velocidad única alcanza?
- ¿El piloto tendrá salud propia en fases posteriores (enemigos que abordan, daño interno)?
- Animaciones/poses al operar cada tipo de estación (cosmético, post-prototipo).
