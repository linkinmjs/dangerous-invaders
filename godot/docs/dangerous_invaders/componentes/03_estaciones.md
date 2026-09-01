# Componente 03 — Estaciones / comandos

**Estado:** propuesta v0.1 — pendiente de validación
**Prioridad:** P1
**Relación:** [Plan de Componentes](../Plan_Componentes_v0.1.md) · operadas por el [Piloto (01)](01_piloto.md), ubicadas por la [Nave (02)](02_nave.md)

---

## Propósito

Las estaciones son la interfaz física entre el piloto y los sistemas de la nave. Cada estación expone **un** sistema. Son el mecanismo que transforma "quiero hacer X" en "tengo que estar parado *ahí* para hacer X".

---

## Modelo común

Todas las estaciones comparten el mismo contrato, lo que permite agregar o quitar estaciones sin tocar al piloto.

### Estados

| Estado | Significado |
|--------|-------------|
| **Libre** | Nadie la opera; su sistema está inactivo (o en el estado en que quedó) |
| **Ocupada** | Un piloto está anclado operándola; recibe sus inputs |
| **Activa autónoma** | *Solo estaciones conmutadas:* el sistema sigue funcionando sin piloto |

### Contrato (para la implementación)

- `puede_interactuar(piloto)` — ¿está libre y en rango?
- `ocupar(piloto)` / `liberar()` — anclaje y desanclaje.
- `procesar_input(input)` — qué hace la estación con los inputs del piloto anclado.
- Señales: `ocupada`, `liberada`, `sistema_activado`, `sistema_desactivado`.

---

## Dos tipos de operación

Esta es la distinción central del componente:

### Sostenida
El sistema **solo actúa mientras el piloto está anclado**. Soltarla detiene el efecto.
→ Timón (movimiento), Escudo, Ataque pesado.

### Conmutada (toggle)
El piloto la **enciende o apaga**; el efecto **persiste sin piloto** (estado "activa autónoma"), normalmente a cambio de consumo continuo de energía.
→ Ataque ligero.

El intercambio del GDD (§7.1) — tiempo del jugador ↔ potencia de la nave — vive exactamente en esta distinción: lo sostenido compra precisión con presencia; lo conmutado compra libertad con energía.

---

## Lista mínima para el prototipo

| Estación | Tipo | Sistema | Piso (propuesta en [Nave](02_nave.md)) |
|----------|------|---------|------|
| Timón | Sostenida | Movimiento lateral de la nave (04, 05) | 1 (abajo) |
| Control de escudo | Sostenida | Reposicionar el escudo (07) | 2 (arriba, al fondo) |
| Interruptor de ataque ligero | Conmutada | Fuego automático (06) | 2 (arriba, cerca del ascensor) |
| Cañón pesado *(P2)* | Sostenida | Disparo manual (10) | 1 (abajo, al fondo) |

**Sin estación de energía en el prototipo.** La energía se gestiona implícitamente (cada sistema consume de un pool común). Una estación de gestión/redistribución solo se agrega si pasa el filtro del GDD: *¿mejora la decisión de priorización?* — con 3 estaciones y un pool, la priorización ya existe.

---

## Ocupación y multijugador

- Una estación admite **un piloto a la vez**.
- Cada nave tiene su propio juego de estaciones (los interiores no se comparten físicamente).
- **Sistemas compartidos:** las estaciones de escudo de ambas naves manipulan **el mismo escudo** (confirmado 2026-08-30). Si ambos pilotos lo operan a la vez: *pregunta abierta* — propuesta inicial: los inputs se **suman** (empujan juntos más rápido; en direcciones opuestas se cancelan), porque genera negociación en vez de arbitrariedad.

---

## Feedback

Cada estación debe comunicar su estado **a distancia** — el jugador decide hacia dónde correr mirando de reojo:

- Libre → apagada / luz tenue.
- Ocupada → iluminada.
- Activa autónoma → parpadeo o luz de color distinto (se ve que "quedó trabajando").

El detalle visual es del componente 11; aquí solo se fija el requisito.

---

## Qué validar jugando

1. ¿La diferencia sostenida vs. conmutada se entiende jugando, sin tutorial?
2. ¿El toggle del ataque ligero produce el intercambio tiempo↔energía en la práctica (jugadores que van, lo activan y vuelven)?
3. ¿Tres estaciones alcanzan para que exista priorización real, o el prototipo pide la cuarta (cañón pesado) de entrada?

---

## Preguntas abiertas

- Resolución exacta del input simultáneo sobre el escudo compartido (propuesta: suma).
- ¿Las estaciones pueden dañarse/deshabilitarse (post-prototipo, ligado a reparación)?
- ¿Operación con minijuego/gesto propio por estación, o inputs directos uniformes? (v0: inputs directos.)
