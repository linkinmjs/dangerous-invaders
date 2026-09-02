# Componente 02 — Nave (interior y layout)

**Estado:** propuesta v0.1 — pendiente de validación
**Prioridad:** P1
**Relación:** [Plan de Componentes](../Plan_Componentes_v0.1.md) · contiene al [Piloto (01)](01_piloto.md) y a las [Estaciones (03)](03_estaciones.md)

---

## Propósito

El interior de la nave es el espacio jugable de la fase de combate. Su layout **es el diseño de niveles**: las distancias entre estaciones son el precio en tiempo de cada repriorización. Diseñar la nave = diseñar cuánto cuesta cambiar de opinión.

---

## Estructura (definida por boceto, 2026-08-30)

- **2 pisos** de igual ancho.
- **1 ascensor** que los conecta, ubicado en el **extremo izquierdo** (según boceto).
- Tableros de comando repartidos entre ambos pisos.

Consecuencia del ascensor en el extremo: la esquina inferior-derecha y la superior-derecha son los puntos **más lejanos entre sí** de la nave. Qué estaciones van en esas esquinas es la principal palanca de tuning de tensión.

---

## Distribución de estaciones (recomendación inicial)

**Tanto la lista de estaciones como su distribución son una recomendación inicial** (aclarado 2026-08-31): sirven para arrancar el prototipo y se espera que cambien — incluso por nave, ver *Variantes* más abajo.

Criterio: las dos estaciones de **operación sostenida de alta frecuencia** (timón y escudo) van en **pisos distintos**, para que nunca se puedan atender ambas sin viajar.

```
Piso 2 (arriba):   [ascensor] ........ [ataque ligero] ...... [escudo]
Piso 1 (abajo):    [ascensor] ........ [timón/movimiento] ... [ataque pesado*]
```

\* El ataque pesado es P2; el prototipo arranca con 3 estaciones.

- **Timón (movimiento)** abajo: es la estación "hogar", cerca de donde se lee la posición de la nave en la vista exterior.
- **Escudo** arriba y al fondo: defenderse exige el viaje más caro desde el timón. Proteger es una decisión, no un reflejo.
- **Ataque ligero** arriba pero más cerca del ascensor: activarlo es un viaje corto de ida y vuelta — inversión puntual de tiempo a cambio de fuego sostenido.

Esta distribución es una **hipótesis de partida** para el prototipo; se ajusta jugando.

A la lista se sumará una estación de **recolección de items** — un **imán** que los atrae o un **gancho con cuerda** estilo barco pesquero (a definir cuál; ver [Estaciones](03_estaciones.md) y componente 16 del plan).

---

## Variantes de nave (post-validación)

Habrá **naves distintas para elegir** — unas **3 en un primer momento** — con propiedades diferentes que balanceen el juego entre sí. Ejemplos anotados (2026-08-31):

- **Recolección:** una nave tiene imán, otra tiene gancho con cuerda.
- **Ataque ligero:** una dispara balas, otra un láser.
- **Circulación interna:** una tiene 2 ascensores en lugar de 1, u otra un **caño de bomberos** en el medio que agiliza bajar al piso inferior.
- **Aporte al escudo:** cada nave puede aportar una propiedad al escudo compartido (ver componente 07 en el plan).

Es decir: el layout interno y las estaciones **son parte de la identidad de cada nave** — la variante es la unidad de balance. El prototipo usa **una sola nave base**; las variantes se diseñan después de validar el core.

---

## Ascensor

- **Propuesta v0:** teletransporte con **delay fijo** — el piloto entra, espera un tiempo corto, aparece en el otro piso. Siempre disponible, sin cabina que llamar.
- Razón: costo de tiempo predecible y tuneable con un solo número; la espera variable de una cabina real agrega frustración antes que decisión.
- Si el prototipo muestra que falta tensión vertical, se evalúa cabina única con llamada (espera variable).

---

## Casco y daño

- La nave tiene **integridad de casco** (HP). Los impactos enemigos no bloqueados por el escudo la reducen.
- **Casco 0 = derrota** (una de las condiciones; ver Loop de combate, componente 09).
- En el prototipo no hay reparación.
- Representación del daño dentro del interior (chispas, alarmas, luces): deseable para feedback, queda para el componente 11 (Pantalla/HUD).

---

## Valores iniciales (a tunear jugando)

| Parámetro | Valor inicial | Razón |
|-----------|--------------|-------|
| Ancho de piso | ~2.0 s de carrera del piloto | Heredado de [Piloto](01_piloto.md); el ancho en px se deriva de la velocidad, no al revés |
| Delay del ascensor | 1.0 s | Cambiar de piso ≈ medio piso de carrera: se siente, pero no bloquea |
| Viaje máximo (esquina a esquina) | ~4–5 s | Peor caso de repriorización; si supera ~5 s probablemente frustre |
| Integridad de casco | 5 impactos | Legible sin HUD elaborado; margen para 2–3 errores de priorización |

---

## Interfaz con otros componentes

- **[Piloto (01)](01_piloto.md):** define límites de movimiento y posición del ascensor.
- **[Estaciones (03)](03_estaciones.md):** la nave declara qué estación va en qué posición (dato de layout, no de lógica).
- **Enemigos (08) / Loop de combate (09):** los impactos enemigos reducen el casco; el casco reporta su estado para la condición de derrota.
- **Vista exterior (11):** la posición lateral de la nave en el espacio de combate la controla el timón; el interior no se desplaza visualmente (la franja inferior es estática).

---

## Qué validar jugando

1. ¿El viaje máximo (~4–5 s) genera tensión o frustración?
2. ¿El ascensor se lee como costo estratégico o como fricción molesta?
3. ¿La separación timón/escudo en pisos distintos produce la decisión "¿me muevo o me protejo?" de forma natural?
4. ¿5 impactos de casco dan partidas con arco (sustos, remontadas) o terminan demasiado rápido/lento?

---

## Preguntas abiertas

- ¿Imán o gancho con cuerda para la recolección de items (o ambos, repartidos entre variantes)?
- ¿El ascensor en el extremo izquierdo (boceto) o centrado? El extremo maximiza distancias; el centro las empareja.
- ¿Habrá zonas de la nave sin estaciones con otro propósito (almacén, ventanas, entrada/salida para Fase II)?
- Qué propiedades exactas aporta cada variante y cómo se balancean entre sí.
- Cómo se representa visualmente el daño en el interior.
