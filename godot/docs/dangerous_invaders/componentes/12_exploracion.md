# Componente 12 — Fase de exploración / plataformas

**Estado:** propuesta v0.1 — movimiento definido sobre base existente; niveles y enemigos pendientes
**Prioridad:** P3 (no entra en el primer prototipo)
**Relación:** [Plan de Componentes](../Plan_Componentes_v0.1.md) · comparte protagonista con [Piloto (01)](01_piloto.md)
**Referencias:** *Campanella 2* (UFO 50), *Jump King*, *Super Mario Bros.* (estructura de avance); para enemigos: *Zelda II: The Adventure of Link*, *Castlevania* (NES/Famicom)

---

## Propósito

Cambio de ritmo respecto de la presión sistémica del combate espacial: el jugador controla directamente al piloto en segmentos de plataformas, exploración y combate ligero. Debe sentirse deliberado y legible, nunca extremadamente castigador.

---

## Movimiento: base heredada de sci-fy-jumper

**Decisión (2026-09-01):** el movimiento del personaje se apoya en el controller ya desarrollado en [sci-fy-jumper](https://github.com/linkinmjs/sci-fy-jumper) (`godot/scenes/player/player.gd`), un juego propio inspirado en Jump King. No se parte de cero: se hereda una FSM probada y sus valores tuneados.

### Lo que el controller ya resuelve

| Mecánica | Cómo funciona en sci-fy-jumper | Valores actuales |
|----------|-------------------------------|------------------|
| **Caminar** | Movimiento horizontal libre en piso (a diferencia de Jump King puro) | `MOVE_SPEED = 80` |
| **Salto cargado** | Mantener salto → `CHARGING` (inmóvil), la potencia acumula hasta el máximo; al soltar (o llegar al tope) salta | potencia 0.3–2.0, carga 3.0/s, altura máx. 250 px |
| **Sin control aéreo** | La velocidad X se fija al despegar (`direction * 150`); el salto es un compromiso | — |
| **Rebote en paredes** | Chocar un lateral en el aire invierte X al 50% — el toque Jump King | factor 0.5 |
| **Splat** | Aterrizar demasiado fuerte aturde al personaje unos instantes | umbral 550 px/s de impacto |
| **Disparo en piso** | Disparo láser parado o caminando, con duración fija; consume energía | 1.0 s por disparo |
| **Daño / i-frames** | Freeze breve al ser golpeado + ventana de invulnerabilidad con parpadeo | 0.3 s + 1.0 s |
| **Caída fuera de pantalla** | Daño + respawn en checkpoint | — |
| **FSM** | 9 estados: IDLE, WALKING, CHARGING, JUMPING, FALLING, SPLAT, SHOOTING_IDLE, SHOOTING_WALKING, HITTED | — |

### Qué se conserva

- La combinación **caminar libre + salto cargado sin control aéreo**: es exactamente el híbrido buscado (avance tipo Mario, saltos tipo Jump King).
- El **rebote en paredes** y el **splat**: son el sabor Jump King que hace deliberado cada salto grande.
- Checkpoints con respawn (la penalización es retroceso, nunca muerte instantánea).

### Qué se ajusta o revisa

- **Salto corto sin carga:** evaluar que un toque rápido dé un saltito inmediato (para ritmo Mario en tramos llanos), reservando la carga para saltos grandes. Hoy el mínimo (0.3) ya es bajo; puede alcanzar con tunearlo.
- **Splat menos frecuente que en Jump King:** el umbral se calibra para que solo castigue caídas claramente temerarias — el GDD pide accesibilidad.
- **Energía del disparo:** en sci-fy-jumper el disparo consume energía del GameManager; acá debe integrarse al modelo de energía del juego (componente 4) o simplificarse.

---

## Estructura de niveles

**Decisión (2026-09-01):**

- **Avance horizontal tipo Mario Bros., pero bidireccional:** el nivel progresa hacia la derecha con una salida/objetivo, y **siempre se puede volver atrás** — no hay scroll que empuje ni bordes que bloqueen el regreso. Volver sirve para recolectar lo que quedó pendiente o reintentar un desvío.
- **Más altura que un Mario clásico:** las secciones tienen desarrollo vertical (más de una pantalla de alto) para que el salto cargado tenga dónde lucirse — desvíos hacia arriba con recompensas, atajos que exigen un salto bien medido, caídas que devuelven a la ruta principal (penalización de retroceso, estilo Jump King suavizado).
- **Minimalista:** pocos elementos por pantalla, lectura clara del espacio (pilar del GDD §2 sobre Jump King). La dificultad viene de medir el salto, no de la densidad de amenazas.

### Penalización por caída

Caerse de un desvío vertical **no mata ni resta salud**: devuelve al jugador a la plataforma inferior (el costo es el retroceso + posible splat). La salud se reserva para enemigos y trampas.

---

## Controles (esquema de 2 botones, consistente con la fase de pilotaje)

| Input | Acción |
|-------|--------|
| ←→ | Caminar / dirección del salto |
| **Botón A** (entrar/acciones) | Salto cargado (mantener y soltar) · interactuar |
| **Botón B** (salir/cancelar/disparar) | Disparo |

Encaja natural con el esquema definido en [Piloto (01)](01_piloto.md): A = acción principal, B = disparo/cancelar. Si B termina disparando también dentro de la nave, ambas fases quedan simétricas.

---

## Enemigos de esta fase

Diseño aparte de los enemigos espaciales ([08_enemigos.md](08_enemigos.md)), con referencias *Zelda II* y *Castlevania* NES: enemigos lentos, patrones legibles, encuentros como obstáculos de posicionamiento (dónde pararse, cuándo saltar) más que de reflejos. Pendiente de análisis propio cuando esta fase entre en diseño activo.

---

## Qué validar jugando

1. ¿El híbrido caminar + salto cargado se siente coherente, o los dos "feels" chocan?
2. ¿La verticalidad extra justifica el salto cargado, o los jugadores lo evitan y bordean por abajo?
3. ¿El retroceso por caída se percibe como penalización justa (tensión sin frustración Jump King)?
4. ¿El cambio de ritmo respecto del combate espacial funciona como respiro?

---

## Preguntas abiertas

- Cámara: el GDD pide no depender de cámara móvil como desafío; definir si es por pantallas fijas, scroll suave o híbrido.
- ¿Salto corto sin carga o todo salto es cargado?
- Integración del disparo con el modelo de energía (componente 4).
- Estructura y cantidad de niveles por sector; qué se recolecta (componente 16) y cómo alimenta la fase espacial (componente 13).
- Enemigos y trampas concretos (análisis futuro).
