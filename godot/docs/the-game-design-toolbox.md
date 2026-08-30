# The Game Design Toolbox — Traducción al español

> Traducción completa al español del libro *The Game Design Toolbox* de **Martin Annander** (CRC Press / Taylor & Francis, primera edición 2024).
> Fuente: [The Game Design Toolbox.pdf](pdfs/The%20Game%20Design%20Toolbox.pdf) (190 páginas).
>
> **Sobre esta traducción**
> - Es una traducción íntegra, sin resúmenes ni comentarios añadidos. Se omitieron únicamente los encabezados y pies de página corridos (números de página, títulos repetidos, códigos DOI) y los logotipos editoriales de las páginas de apertura de capítulo.
> - Las 76 ilustraciones del libro (dibujos a mano con texto en inglés) se extrajeron del PDF y se guardaron en [img/game-design-toolbox/](img/game-design-toolbox/). Cada una se embebe en el lugar que ocupa en el original y va seguida de un bloque **"Texto de la ilustración"** con la traducción del texto que contiene. El nombre de archivo indica la página del PDF de donde proviene (`p031.png` = página 31 del PDF = página 23 del libro impreso).
> - Los nombres de las 71 herramientas se dan en español seguidos del nombre original en cursiva, para poder cruzarlos con el índice y con el libro en inglés.
> - Los números de página que aparecen en el índice de contenidos y en el índice alfabético son los de la edición impresa en inglés.

![Portada de The Game Design Toolbox](img/game-design-toolbox/p001.png)

---

---

# The Game Design Toolbox

Este libro presenta 71 herramientas prácticas de diseño de juegos que los lectores pueden usar para resolver problemas reales de diseño de juegos. Escrito para ser una "caja de herramientas" para diseñadores de juegos, ofrece un enfoque práctico con herramientas claras y fáciles de usar, de modo que los lectores puedan encontrar rápidamente la solución adecuada al problema que están enfrentando.

Este libro está dividido en seis fases del diseño de juegos: ideación, exploración, compromiso, resolución de problemas, balanceo y ajuste. Cada categoría contiene un conjunto de herramientas relevantes, y los índices que las acompañan ofrecen sugerencias de herramientas para usar ante problemas específicos. Los Materiales de apoyo (*Support Materials*) ofrecen material didáctico adicional, ejercicios y preguntas frecuentes complementarias.

Escrito para ser un recurso práctico, este libro será una caja de herramientas útil tanto para diseñadores de juegos junior como veteranos.

Martin Annander ha trabajado con juegos desde 2006 como diseñador de juegos, programador, gerente de estudio y director de diseño. Actualmente es diseñador de juegos independiente y freelancer.

---

# The Game Design Toolbox

(La caja de herramientas del diseño de juegos)

**Martin Annander**

---

Imagen de portada diseñada: Shutterstock

Primera edición publicada en 2024
por CRC Press
2385 NW Executive Center Drive, Suite 320, Boca Raton, FL 33431

y por CRC Press
4 Park Square, Milton Park, Abingdon, Oxon, OX14 4RN

CRC Press es un sello de Taylor & Francis Group, LLC

© 2024 Martin Annander

Se han hecho esfuerzos razonables para publicar datos e información confiables, pero el autor y el editor no pueden asumir responsabilidad por la validez de todos los materiales ni por las consecuencias de su uso. Los autores y los editores han intentado localizar a los titulares de los derechos de autor de todos los materiales reproducidos en esta publicación y piden disculpas a los titulares de derechos de autor si no se ha obtenido permiso para publicar en esta forma. Si algún material con derechos de autor no ha sido reconocido, por favor escríbanos y háganoslo saber para que podamos rectificarlo en cualquier reimpresión futura.

Salvo lo permitido por la Ley de Derechos de Autor de los Estados Unidos, ninguna parte de este libro puede ser reimpresa, reproducida, transmitida o utilizada de ninguna forma por ningún medio electrónico, mecánico o de otro tipo, conocido actualmente o inventado en el futuro, incluidos la fotocopia, la microfilmación y la grabación, o en ningún sistema de almacenamiento o recuperación de información, sin el permiso escrito de los editores.

Para obtener permiso para fotocopiar o usar material de esta obra por medios electrónicos, acceda a www.copyright.com o contacte al Copyright Clearance Center, Inc. (CCC), 222 Rosewood Drive, Danvers, MA 01923, 978-750-8400. Para obras que no estén disponibles en el CCC, por favor contacte a mpkbookspermissions@tandf.co.uk

Aviso de marcas registradas: los nombres de productos o corporativos pueden ser marcas comerciales o marcas registradas y se usan únicamente con fines de identificación y explicación, sin intención de infringir.

ISBN: 978-1-032-36587-9 (tapa dura)
ISBN: 978-1-032-36551-0 (tapa blanda)
ISBN: 978-1-003-33275-6 (libro electrónico)

DOI: 10.1201/9781003332756

Composición tipográfica en Minion
por codeMantra

Acceda a los Materiales de apoyo: www.Routledge.com/9781032365879

---

# Contenidos (*Contents*)

- INTRODUCCIÓN (*INTRODUCTION*), 1
- Capítulo 1 — Diseño de juegos (*Game Design*), 5
  - DISEÑADOR DE JUEGOS (*GAME DESIGNER*), 5
  - ETAPAS DEL DISEÑO DE UN JUEGO (*STAGES OF A GAME'S DESIGN*), 10
  - MECÁNICAS, DINÁMICAS, ESTÉTICAS (MDA) (*MECHANICS, DYNAMICS, AESTHETICS (MDA)*), 13
  - BUCLES Y AROS (*LOOPS AND HOOPS*), 15
  - ABRAZAR LA SUBJETIVIDAD (*EMBRACING SUBJECTIVITY*), 18
  - LAS HERRAMIENTAS (*THE TOOLS*), 20
- Capítulo 2 — Ideación (*Ideation*), 21
  - HAZ MENOS PREGUNTAS (*ASK FEWER QUESTIONS*), 22
  - HAZ LLUVIA DE IDEAS EN PAPEL (*BRAINSTORM ON PAPER*), 24
  - ACERCA Y ALEJA EL ZOOM (*ZOOM IN, ZOOM OUT*), 26
  - VERBALIZA (*VERBALIZE*), 28
  - DI "SÍ, Y…" (*SAY "YES, AND…"*), 30
  - PRUÉBALO (*TRY IT*), 32
  - ESTABLECE UN TEMA (*SET A THEME*), 34
  - INVENTA UNA MECÁNICA (*INVENT A MECHANIC*), 36
  - DECIDE A QUIÉN JUEGA EL JUGADOR (*DECIDE WHO THE PLAYER PLAYS*), 38
  - ASUME MENOS (*ASSUME LESS*), 40
  - EMPIEZA DESDE EL CONFLICTO (*START FROM CONFLICT*), 42
  - FINGE QUE JUEGAS (*PRETEND TO PLAY*), 44
  - HAZ REUNIONES ESTRUCTURADAS (*HOLD STRUCTURED MEETINGS*), 46
- Capítulo 3 — Exploración (*Exploration*), 49
  - DETECTA EL PASTEL DE SALCHICHAS (*SPOT THE SAUSAGE CAKE*), 50
  - HAZ PROTOTIPOS ANALÓGICOS (*MAKE ANALOG PROTOTYPES*), 52
  - USA TIMEBOXES (*USE TIMEBOXES*), 54
  - DISEÑA EN CAPAS (*DESIGN IN LAYERS*), 56
  - HAZ PROTOTIPOS CON DIAGRAMAS DE FLUJO (*MAKE FLOWCHART PROTOTYPES*), 58
  - HAZ JUEGO DE ROL CON TU DISEÑO (*ROLE PLAY YOUR DESIGN*), 60
  - AÑADE INCERTIDUMBRE (*ADD UNCERTAINTY*), 62
  - ¡HAZLO MÁGICO! (*MAGIC IT!*), 64
  - PIENSA EN LOS DATOS (*THINK OF THE DATA*), 66
  - AÑADE ASPEREZAS (*ADD ROUGH EDGES*), 68
  - ENTRADA, SALIDA, GRITO (*INPUT, OUTPUT, SCREAM*), 70
  - DESAFÍA EL JUEGO CON LA TRAMA (*CHALLENGE PLAY WITH PLOT*), 72
  - ARMA GRUPOS DE TRABAJO (*BUILD TASK FORCES*), 74
- Capítulo 4 — Compromiso (*Commitment*), 77
  - CUENTA UNA HISTORIA (*TELL A STORY*), 78
  - CONSTRUYE UN PARQUE DE DIVERSIONES (*BUILD AN AMUSEMENT PARK*), 80
  - DILO DE NUEVO (*SAY IT AGAIN*), 82
  - DEFINE LAS FEATURES (*DEFINE THE FEATURES*), 84
  - PÁRATE SOBRE PILARES (*STAND ON PILLARS*), 86
  - CRUZA TODO EN UNA MATRIZ (*CROSS-MATRIX EVERYTHING*), 88
  - CONVIERTE EN HECHOS (*FACTUALIZE*), 90
  - ESCRIBE ONE-PAGERS (*WRITE ONE-PAGERS*), 92
  - ESTABLECE MÉTRICAS (*SET METRICS*), 94
  - JUEGA, NO MUESTRES (*PLAY, DON'T SHOW*), 96
  - VERIFÍCALO (*CHECK IT*), 98
- Capítulo 5 — Resolución de problemas (*Problem Solving*), 101
  - CREA PLAYER PERSONAS (*MAKE PLAYER PERSONAS*), 102
  - OBSERVA Y ANALIZA (*OBSERVE AND ANALYZE*), 104
  - TESTEA A CIEGAS (*TEST BLIND*), 106
  - DIBUJA UN MAPA DE ESTRATEGIAS (*DRAW A STRATEGY MAP*), 108
  - VERIFICA CON CHECKLISTS (*VERIFY WITH CHECKLISTS*), 110
  - VALIDA TUS PILARES (*VALIDATE YOUR PILLARS*), 112
  - DEJA UN RASTRO (*LAY A TRAIL*), 114
  - HAZ QUE ESCALE (*MAKE IT ESCALATE*), 116
  - DALES ZANAHORIAS (*GIVE THEM CARROTS*), 118
  - QUÉMALOS EN LA ESTUFA (*BURN THEM ON THE STOVE*), 120
  - RESUELVE PROBLEMAS (*SOLVE PROBLEMS*), 122
  - DEJA COSAS ATRÁS (*LEAVE THINGS BEHIND*), 124
- Capítulo 6 — Balanceo (*Balancing*), 127
  - UNA COSA A LA VEZ (*ONE THING AT A TIME*), 128
  - HAZ PREGUNTAS ASTUTAS (*ASK SLY QUESTIONS*), 130
  - EVITA LA DOMINACIÓN (*AVOID DOMINATION*), 132
  - DUPLICA O DIVIDE A LA MITAD (*DOUBLE OR HALVE*), 134
  - POR 10 (*BY 10*), 136
  - PRUEBA LOS EXTREMOS (*TEST FOR EXTREMES*), 138
  - ELEVA LAS COSAS (*LIFT THINGS UP*), 140
  - USA CONTRAPUNTOS (*USE FOILING*), 142
  - BALANCEA LA COBERTURA (*BALANCE COVERAGE*), 144
  - SIMPLIFICA TU MATEMÁTICA (*SIMPLIFY YOUR MATH*), 146
  - INTERPOLA MÁS (*TWEEN MORE*), 148
  - PON LA PUERTA ANTES QUE LA LLAVE (*PUT THE DOOR BEFORE THE KEY*), 150
- Capítulo 7 — Ajuste (*Tuning*), 153
  - REFINA TU AUDIENCIA (*REFINE YOUR AUDIENCE*), 154
  - EXTERMINA A TUS FAVORITOS (*EXTERMINATE YOUR DARLINGS*), 156
  - PON LO GENIAL PRIMERO (*PUT THE COOL THING FIRST*), 158
  - ELIMINA LAS DECISIONES DESINFORMADAS (*REMOVE UNINFORMED CHOICES*), 160
  - PERMITE LA PERSONALIZACIÓN (*ALLOW CUSTOMIZATION*), 162
  - OFENDE A PROPÓSITO (*OFFEND ON PURPOSE*), 164
  - PONLO EN OTRO LADO (*PUT IT ELSEWHERE*), 166
  - HAZ QUE SEA DIVERTIDO DE VER (*MAKE IT FUN TO WATCH*), 168
  - PIENSA COMO UN JUGADOR (*THINK LIKE A PLAYER*), 170
  - SATISFACE LAS INTENCIONES DEL JUGADOR (*MEET PLAYER INTENTIONS*), 172
- REFERENCIAS (*REFERENCES*), 175
- ÍNDICE (*INDEX*), 177

---

# Introducción (*Introduction*)

> "Estamos algo atascados. ¿Puedes sugerirnos alguna buena herramienta que podamos usar?"

Esta pregunta me la hicieron en un taller de diseño de juegos que di una vez. No tenía una buena respuesta y en realidad no sabía qué se suponía que era una "herramienta". Los diseñadores de juegos no son carpinteros, son magos, y los magos usan varitas. ¿No?

La pregunta, sin duda, me hizo sentir como un inútil [en el original hay un juego de palabras con *tool*, "herramienta" y "tonto"].

Más adelante en el taller, algo que cubrí resultó encajar con lo que se suponía que debía ser una "herramienta", y los asistentes al taller pudieron llevársela consigo con cierta sensación de satisfacción (y para mi alivio).

La herramienta en cuestión era algo que yo había usado muchas veces para encontrar inspiración cuando no había ninguna a la vista, y algo a lo que ellos podían sacarle buen provecho en el taller y, con suerte, también en su futuro.

Pero después del taller, seguí volviendo a esa pregunta. ¿Puedes sugerirnos alguna buena herramienta que podamos usar?

Sentía que la forma en que realmente hacemos nuestro diseño de juegos parecía suelta, indefinida y profundamente propensa a la subjetividad. Llámalo instinto, experiencia o reacción visceral —como prefieras—, sigue siendo solo una varita mágica con otro nombre.

Mi conclusión fue que las varitas mágicas simplemente no son suficientes y que tiene que haber algo más en nuestro oficio. Algo de profesionalismo genuino que haga que nuestros trabajos sean trabajos y no brujería. El diseño de juegos no puede consistir simplemente en tener opiniones sobre juegos a diario, y que lo que salga al final sea accidental o incluso incidental.

Al mismo tiempo, de vuelta en las minas del diseño de juegos de mi trabajo diario, estaba claro que nuestra comunicación no funcionaba realmente. Como no teníamos ninguna forma estandarizada de hablar del oficio, había una notable falta de terreno común. Los malentendidos eran la norma y la antigüedad era quien tomaba las decisiones.

¿Es difícil Dark Souls? ¿Es Battlefield V de ritmo rápido? ¿Es estratégico el *gameplay* de Candy Crush Saga? ¿Es satírico Monopoly? ¿Deberían todos los shooters en primera persona tener sprint? ¿Tiene el juego de mesa Mage Knight demasiados componentes?

Puedes responder esas preguntas como quieras, y tendrás razón, porque las respuestas son perfecta e innegablemente subjetivas.

Esto se veía agravado por el hecho de que el diseño de juegos carece de cualquier tipo de lenguaje disciplinar establecido. La naturaleza del entretenimiento hace que la propia conversación creativa sea subjetiva. Como consecuencia, los diseñadores de juegos a menudo juran por la sagrada ley de improvisar hasta que funcione y llamarlo con algún nombre que encaje o que oyeron una vez en una charla de la Game Developers Conference (GDC). Con frecuencia, no se formula como una estrategia real hasta mucho después de los hechos.

La combinación de esta subjetividad y la falta de un lenguaje común hace que recurramos a referirnos a otros juegos. Otros juegos se convierten en el único terreno común en el que a veces podemos ponernos de acuerdo. Pero esto es problemático. Como nuestras experiencias al jugar dichos juegos serán tan subjetivas como el proceso de diseño que los creó, significa que solo podemos estar de acuerdo cuando llegamos a las conclusiones más generales posibles. Esto significa que los juegos FPS deben tener sprint, porque todos los que hemos jugado recientemente lo tienen.

Puede que no veamos esto como un problema en nuestras tareas diarias, pero lo es. Si no podemos hablar de nuestro oficio con objetividad, las cosas caerán invariablemente en las trampas del diseño por referencia o el diseño por comité, y estaremos condenados a repetir los mismos errores para siempre sin reconocer que son errores. Unas herramientas comunes nos ayudarían a hablar de la ejecución del diseño de un juego en sus propios términos y a establecer un lenguaje informado por el juego que estamos desarrollando. El producto tangible y jugable que tenemos delante.

El diseño de juegos no es ningún misterio, y si lo convertimos en uno, estamos admitiendo que no tenemos ni idea de lo que hacemos. Por eso me molestó tanto no poder responder de forma inmediata y espontánea a aquella pregunta sobre herramientas.

No es suficiente.

De ahí en adelante, armado con las razones antes mencionadas —la necesidad de herramientas prácticas y la falta de un lenguaje común—, empecé a pensar en cuáles son realmente los destornilladores, los martillos y las herramientas eléctricas de nuestro oficio. Cada vez que se me ocurría algo, lo escribía en un documento. Dondequiera que estuviera, hiciera lo que hiciera y a quienquiera que se lo estuviera robando.

Esta caja de herramientas es el resultado.

Está llena de algunos de los trucos prácticos y ejercicios extraños que he usado a lo largo de los años para resolver distintos tipos de problemas de diseño o para encontrar un nuevo camino cuando me quedaba atascado. Muchos han sido robados de diseñadores que son mucho más inteligentes que yo, a quienes daré el debido crédito donde pueda recordarlos. Otros se han convertido en buenas prácticas por costumbre.

Lleva esta caja de herramientas contigo, y cuando necesites un destornillador para apretar un tornillo flojo del diseño de un juego, mete la mano, encuentra la herramienta que encaje y sigue con el trabajo.

Martin Annander
Abril de 2023

---

# Capítulo 1 — Diseño de juegos (*Game Design*)

Como marco para la caja de herramientas, usaremos dos plantillas informales, solo para tener una definición de trabajo de lo que hace un diseñador de juegos para ganarse la vida. Esto no es un intento de definir nada: es simplemente el marco para las herramientas de este libro.

- La primera se relaciona con qué es el diseño de juegos y sirve para separar las conversaciones cotidianas sobre juegos del trabajo de un diseñador de juegos. Lo hace dividiendo el rol del diseñador de juegos en cuatro niveles separados, algo parecido a los niveles de experiencia de un juego de rol.
- La segunda presenta seis etapas del diseño de juegos y funciona como los capítulos de todas las herramientas que forman el grueso de este libro. Cada etapa es una parte distinta del proceso de diseño, aunque rara vez se las trate así en la realidad práctica de los cronogramas.

## Diseñador de juegos (*Game Designer*)

Lo que sigue intenta exponer de manera práctica el trabajo y las responsabilidades que vienen con el diseño de juegos.

Si haces juegos analógicos —juegos de cartas, juegos de mesa, juegos de rol de mesa, etc.—, lo más probable es que trabajes solo o en un equipo pequeño. En el diseño de juegos digitales, los equipos varían enormemente de tamaño, desde desarrolladores en solitario hasta estudios gigantes y multidisciplinarios distribuidos en múltiples equipos por todo el mundo.

El tamaño del equipo cambia la dinámica del trabajo, pero en realidad no cambia el trabajo. Sin embargo, sí lleva a la especialización. En un equipo realmente grande, puede que estés completamente enfocado en una parte muy pequeña del rompecabezas del diseño y nunca toques las demás partes. Pero, para los fines de este marco, miraremos el diseño de juegos de forma holística. Solo recuerda que no siempre será tu responsabilidad hacerlo todo.

Para que sea más fácil hablar de las obligaciones de un diseñador de juegos, esas obligaciones se han dividido en cuatro niveles de diseño de juegos. Como con los niveles de experiencia en los juegos de rol, empiezas en el Nivel 1 y subirás de nivel ganando experiencia.

De lo que debes ser consciente es de que fácilmente puedes alcanzar niveles distintos en distintos tipos de diseño de juegos, o incluso entre distintos proyectos individuales, o incluso entre partes del mismo proyecto.

Si alcanzas el Nivel 3 en un proyecto, es muy posible que caigas de vuelta al Nivel 1 en el siguiente, porque es demasiado distinto del proyecto anterior o porque entra en detalles con los que no estás tan familiarizado.

Muchos diseñadores de juegos digitales con experiencia batallan para hacer juegos analógicos, porque sus ideas sobre qué funciona y qué no se transfieren con menos facilidad de lo que podrían haber pensado. En efecto, un diseñador de juegos digitales de Nivel 4 puede perfectamente ser un diseñador analógico de Nivel 1, o viceversa.

Tu nivel como diseñador de juegos tiene que ver con lo que estás haciendo ahora mismo y no es una progresión lineal hacia un tope de nivel inevitable.

### Nivel 0: No diseñador

Cualquiera sin conocimiento práctico, o incluso sin interés, en los juegos será un diseñador de juegos de Nivel 0. Cada vez que alguien se sorprende al enterarse de que no todos los juegos de mesa tienen dados, o piensa que jugar videojuegos es lo mismo que apostar, es un diseñador de Nivel 0.

Esto suele deberse a que no les interesa y nunca han tenido una buena razón para interesarse. Puede que algún día "suban de nivel" a uno más alto jugando y empezando a tener opiniones sobre los juegos, pero lo más probable es que sigan sin interesarse indefinidamente.

Esto está bien, siempre que quede entendido que esta persona no va a contribuir al diseño de tu juego. Deja esto claro lo antes posible, para que no haya malentendidos.

### Nivel 1: Diseñador con opiniones

En su mayor parte, esto es todo lo que el diseño de juegos realmente es: tener opiniones sobre juegos. Te gusta la cosa; no te gusta la cosa. Quieres cambiarla; no quieres cambiarla. Quieres un helicóptero y tres mazos de cartas más, movimiento más rápido y más munición; o no los quieres.

Los juegos, igual que otras formas de entretenimiento, nos hablan a un nivel instintivo. Incluso cuando no puedes explicar los porqués ni los cómos, puedes tener sentimientos y opiniones de todos modos. Pero todo el mundo tiene estos sentimientos y opiniones. Si esto es todo lo que se le permite ser al diseño de juegos, todo el mundo lo está haciendo todo el tiempo.

Cuando el tester dice que el personaje se mueve demasiado lento, el gerente de IT piensa que el juego se ve demasiado oscuro, o tu hijo quiere ver un personaje tortuga en tu juego, eso también es diseño de juegos, y es al menos tan valioso como los sentimientos y opiniones de cualquier otro diseñador de juegos de Nivel 1. No importa si tu cargo dice "diseñador" o no. En este nivel, sigues diseñando juegos en igualdad de condiciones con todos los demás.

Así que, si tú, el diseñador de juegos con el título, te quedas en este nivel, no ayudarás a tu equipo ni a tus *playtesters*. Serás solo otra voz expresando opiniones. Debes hacer algo que nadie más pueda hacer si quieres alcanzar un nivel más alto. Debes dar un paso más allá de tener opiniones.

Recuerda siempre que cualquiera con sentimientos y opiniones es un diseñador de juegos de Nivel 1.

### Nivel 2: Diseñador probado

Lo primero que debes hacer para subir tu nivel de diseño de juegos es iterar tus diseños y usar esa iteración para validar todas las opiniones del Nivel 1. No solo tus opiniones: las opiniones de todos.

Hay tres pasos para esto.

Primero, debes recordar que lo que importa es el producto final. No tu idea del producto final, ni tus propias opiniones sobre lo que el equipo está entregando. La validación tiene que ver con la iteración. Con ocurrírsete ideas geniales y verlas estrellarse y arder al chocar con la realidad. Cada vez que esto ocurre, aprenderás algo nuevo que podrás llevar al resto del equipo, y madurarás como diseñador de juegos. Si te aferras con terquedad a la idea que tenías al principio, incluso frente a la evidencia creciente de los problemas de tu idea, te estás quedando en el Nivel 1.

Segundo, debes hacer tu tarea: investigar temas de diseño de juegos, jugar juegos similares, leer lo que piensan los fans de juegos similares en Reddit, en reseñas, etcétera, y ampliar tu vocabulario tanto sobre el diseño de juegos en general como sobre el juego específico que estás haciendo en particular. Esto es para mantenerte al día en la conversación. Cuando alguien mencione algo relacionado con tu juego, debes ser capaz de responder con una buena respuesta, incluso si esa respuesta es "todavía no lo sé".

Tercero, debes explorar todas las ideas que vayan surgiendo. Hay cuatro maneras de explorar ideas, tomadas prestadas de la excelente charla de Chris Hecker sobre prototipado avanzado.

#### ¡Roba!

Antes de hacer cualquier otra cosa, fíjate si puedes usar la exploración de alguien más. Sin embargo, al contrario de lo que te dicta el instinto, evita tomarla de otros juegos. Roba de las matemáticas, de la psicología, de la historia, de las películas, de las series de televisión, de los libros, de una clase de caligrafía, de la carpintería, y de todo, en todas partes y de la vida cotidiana.

Esto es lo que hacen los artistas cuando arman *mood boards*. Lo que hace cualquiera cuando escribe cosas en una búsqueda de Google Imágenes o publica un enlace a un video en línea. Es la manera más rápida y eficiente de "prototipar" una idea, ya que alguien más ya habrá hecho este trabajo por ti.

#### Lápiz y papel

Haz prototipos de juego de mesa. Escribe cuentos cortos ambientados en la ficción del juego. Escribe historias de jugador que describan la experiencia de jugar el diseño terminado. Haz maquetas interactivas con papel. Dibuja figuras de palitos. Usa cartas, tablas aleatorias y dados para generar sesiones de juego falsas.

Esto es rápido y eficiente, y puede usarse tanto para hacer como para responder preguntas muy específicas sobre tu juego antes de que el juego "de verdad" tome forma.

#### Prototipo simulado

Toma tu motor de juego, u otro motor de juego en el que te sientas cómodo haciendo prototipos rápidos, y construye algo que finja ser un prototipo.

Esto es especialmente útil si ya te sientes cómodo con algunas partes del diseño de tu juego pero no con otras. Puedes entonces hacer abstracciones de las partes que ya conoces y concentrarte en las que no.

Por ejemplo, Nicholas Lovell habla de un "prototipo de la capa de retención" en su libro *The Pyramid of Game Design*. Se construye para prototipar las partes del juego que no son el *gameplay* central, y representa las partes conocidas del gameplay de forma abstracta con un botón que simplemente dice "Jugar" y muestra un temporizador corto al presionarlo. Un prototipo de retención así nunca lanza realmente ningún gameplay. En cambio, se construye para demostrar el bucle de retención del juego y cómo se mantiene el compromiso del jugador a lo largo del tiempo.

Hacer esto evita que te atasques en detalles que todavía no importan realmente.

#### Prototipo

Si ninguna de las otras maneras funciona, ve al juego mismo e itera. Solo evita iterar en el juego real y propiamente dicho, y mantente bien lejos de las *features* bonitas. Recuerda que solo estás mojándote los pies: no viniste a nadar.

### Nivel 3: Diseñador experimentado

Después de construir y quemar dolorosamente tus creaciones, habrás ganado una comprensión mucho más profunda de los temas involucrados. Lo importante es que sabes cómo funciona el juego y sabes por qué hubo que tomar ciertas decisiones. Preferiblemente con ejemplos reales y concretos, pero el conocimiento teórico puede ser suficiente mientras se pone en marcha un sistema complejo. Solo asegúrate de que no se quede en teórico para siempre. Al final, lo único que importa es el juego jugable.

El conocimiento que has construido hasta ahora es la parte importante, porque te convierte en la persona a quien preguntar. Te permite responder los cómos y los porqués con confianza, usando ejemplos, y no solo improvisando o apoyándote en la antigüedad.

En este punto ya no se trata de la confianza en ti mismo; para eso está el Nivel 2. En el Nivel 3, se trata de ganarte la confianza de tu equipo. Se trata de la confianza que ellos tienen en ti como su diseñador de juegos, y de convertirte en la persona a quien preguntar cuando necesitan una respuesta sobre el diseño del juego.

A decir verdad, seguirás improvisando a veces, pero ahí es donde entra la confianza. Has visto adónde te han llevado los pilares, los hechos y los prototipos, y puedes deducir adónde llevarían las nuevas entradas a partir de ahí. Cuando le comuniques esto a tu equipo, lo respetarán y estarán preparados para correr con ello. No porque diga "diseñador" en alguna placa por ahí, sino porque a estas alturas genuinamente confían en tu palabra.

Cuando has alcanzado este nivel y ganado la confianza del equipo, eso te lleva un paso más por encima de tener opiniones sobre juegos. Entonces simplemente tienes que seguir haciéndolo. Tanto para construir una mejor comprensión para ti mismo como para mantener la confianza del equipo.

### Nivel 4: Diseñador holístico

La discusión sobre si fueron los elfoenanos o los caballopandas los que invadieron el Reino del Bosque de pronto importa menos cuando el Reino del Bosque se recorta. Del mismo modo, la diferencia entre 0,155 y 0,1551 empieza a tener un impacto tan pequeño que ya apenas vale la pena la "Reunión de Balanceo" semanal de dos horas.

Aquí es donde se necesita un diseñador de Nivel 4.

Ahora estás tan cómodo en tus responsabilidades que puedes hablar con el equipo y el equipo confía en ti, pero también has entendido que es tu trabajo tomar las decisiones difíciles que hacen posible lanzar el juego. Recortar el Reino del Bosque; decir que ahora podemos cancelar la Reunión de Balanceo semanal.

El Nivel 4 consiste en dar un paso al frente, asumir la responsabilidad y entregar el juego. Mirar tu proyecto menos como un festival creativo sin reglas y más como un producto que hay que cerrar y entregar.

Esto no significa que hayas terminado con tus responsabilidades de los otros niveles. Ni de lejos. Solo significa que necesitas tomar decisiones cada vez más difíciles y sentirte cómodo, al mismo tiempo, tanto con las piezas más grandes como con las más pequeñas del rompecabezas del diseño.

Tu perspectiva tiene que ser holística porque concierne al juego entero y no solo a las partes. Ves el bosque, porque ayudaste a plantar todos los árboles.

También debes ser pragmático, porque tienes la responsabilidad última, y no delegas las decisiones difíciles en otras personas. Tú tomas las decisiones difíciles. Con respeto, por supuesto, pero las tomas, y asumes la responsabilidad por ellas. Si la cosa que dijiste que funcionaría no funciona, das un paso al frente para aceptar la responsabilidad, y luego dices cómo seguir adelante.

Todavía puedes tener opiniones sobre juegos, como todo diseñador de juegos de Nivel 1. Pero también te has convertido en la persona a la que le preguntarán "¿cómo resolvemos esto?", y serás capaz de dar una respuesta satisfactoria que encaje con la visión del juego, la comodidad del equipo, el presupuesto y todo lo demás que forma parte de un proyecto.

Como diseñador de Nivel 4, trabajas en el producto completo, no "solo" en el diseño del juego.

## Etapas del diseño de un juego (*Stages of a Game's Design*)

Las herramientas que encontrarás en el resto de este libro se han dividido en seis etapas separadas del diseño de juegos. Cada sección detalla lo que necesitas entregar en esa etapa.

Por ahora, veamos simplemente cuáles son estas etapas.

### Ideación (*Ideation*)

Las herramientas de Ideación te ayudan a generar y discutir ideas. Tiene que ver sobre todo con la conversación y la organización, con aprender a ser constructivo y colaborativo, y con entregar algo concreto al final del proceso.

Es la parte del proceso que debería invitar a tantos diseñadores de Nivel 1 como sea posible, de todo tu equipo, tus conocidos o las comunidades donde pasas el tiempo.

Durante la ideación, todo vale.

### Exploración (*Exploration*)

Las herramientas de Exploración profundizan en cómo comunicas, iteras y validas todo lo que sale de la ideación. En entender que está bien que los experimentos fallen, y que todo lo que ocurre debería evaluarse por sus propios méritos y no por preconceptos. Es donde tienes que aceptar las responsabilidades de un diseñador de Nivel 2.

Cada vez que retrocedes a la Ideación, vuelves a estar en el Nivel 1. La razón por la que esta distinción es importante es que estar en el Nivel 1 te pone en el mismo nivel de diseño de juegos que el tester de QA y el gerente de IT antes mencionados.

La Exploración es donde el diseño se vuelve concreto: es donde empiezas a trabajar de verdad con el diseño de juegos.

### Compromiso (*Commitment*)

Las herramientas de Compromiso te ayudan a decidir qué lecciones de la Exploración impulsar y cuándo abandonar por completo la Ideación. Es un paso complicado pero absolutamente fundamental para el diseño de un juego. Si nunca te comprometes, nunca terminarás tu juego, sin importar si ese juego es un proyecto divertido de tiempo libre o una empresa gigante de varios millones de dólares.

Les resulta más fácil a los diseñadores de Nivel 4, que ya han pasado por este rodeo antes, pero normalmente requerirá al menos un diseñador de Nivel 3 para que el equipo confíe en las decisiones que se están tomando.

Comprometerse demasiado pronto puede obligarte a idear y explorar cuando deberías estar enfocado en terminar el juego, pero comprometerse demasiado tarde no te dará tiempo suficiente para familiarizarte con el juego que estás haciendo.

### Resolución de problemas (*Problem Solving*)

Las herramientas de Resolución de problemas cambian tu atención hacia los problemas concretos de la versión jugable actual de tu juego: controles que no se sienten bien, *features* que se quedan cortas, o componentes demasiado engorrosos o imprecisos. Puede ser cualquier problema aparente del juego tal como está en este momento.

Es estrictamente para diseñadores de Nivel 2 o superior. Si abordas la resolución de problemas como un diseñador de Nivel 1, se convierte en un juego de adivinanzas y pasa a ser una forma extendida del proceso de ideación y exploración que puede continuar indefinidamente.

La resolución de problemas consiste en dar los últimos pasos importantes hacia un diseño finalizado.

### Balanceo (*Balancing*)

Las herramientas de Balanceo están aquí para permitirte dar pinceladas tanto gruesas como finas que hagan que el juego se sienta todavía mejor una vez resueltos los problemas más grandes. Ajustar números y pensar en cómo tu contenido puede darle al jugador la mejor experiencia de usuario posible.

Curiosamente, cualquiera puede sugerir cosas durante el balanceo. Muchos diseñadores de Nivel 1 aportarán ideas y sugerencias, pero necesitas diseñadores de Nivel 3 para recibir, procesar y manejar esta información. También necesitas la toma de decisiones de un diseñador de Nivel 4 para que el balanceo no continúe para siempre.

Nunca te sentirás completamente listo con el balanceo, pero debes aprender a conformarte con "suficientemente bueno".

### Ajuste (*Tuning*)

Las herramientas de Ajuste son la estación final. Los retoques, cambios y aclaraciones que toman tu juego casi terminado y le quitan el "casi". Cuando la gente habla de terminar algo, esta parte es de la que hablan. A veces se la llama el segundo 90 %, al que solo puedes llegar después de terminar el primer 90 %.

Es importante que en este punto no se haga caso a los diseñadores de Nivel 1, y tampoco hay mucho espacio para diseñadores de Nivel 2 o incluso de Nivel 3. Es estrictamente el dominio de los diseñadores que tienen la credibilidad y la autoridad para tomar decisiones difíciles basadas en lo que es bueno para el juego y no en lo que puede sonar bien para una parte específica de él.

Esta es la parte más difícil, por lejos, pero puede que también sea la más importante.

## Mecánicas, Dinámicas, Estéticas (MDA) (*Mechanics, Dynamics, Aesthetics (MDA)*)

*MDA: A Formal Approach to Game Design and Game Research* es un artículo escrito en conjunto por Robin Hunicke, Marc LeBlanc y Robert Zubek. Presenta un marco para el diseño de juegos en el que las perspectivas del jugador y del diseñador pueden separarse con facilidad.

El artículo es una lectura de apenas cinco páginas que deberías permitirte completa en algún momento. Por ahora, acepta que los juegos pueden dividirse en Mecánicas, Dinámicas y Estéticas. (Volveremos a esto al final mismo de la producción, por razones distintas).

Las Mecánicas son los datos, los componentes y los algoritmos; las Dinámicas abarcan el comportamiento interactivo de las mecánicas; y las Estéticas describen las emociones que quieres que el jugador sienta mientras juega. Hay más en el artículo, por supuesto, pero aquí es donde se pone interesante.

Un diseñador de juegos suele partir de las mecánicas y desde ahí profundizar en las dinámicas. También habrá un concepto de las estéticas, para muchos diseñadores, particularmente para aquellos que aplican su mente al tema antes de mirar el gameplay. Pero incluso entonces, un diseñador tiene que considerar los cómos y los porqués antes de profundizar demasiado en las Estéticas.

El jugador, en cambio, experimentará el juego desde el extremo opuesto. Mirará primero las estéticas, se sumergirá gradualmente en las dinámicas, y puede que con el tiempo aprenda sobre las mecánicas que subyacen a las dinámicas si se vuelve un gran fan del juego.

Este es un cambio de perspectiva increíblemente importante del que debes ser consciente como diseñador de juegos. Los jugadores que no entienden tus mecánicas no son "tontos" ni "idiotas", como quizás quieras llamarlos; simplemente lo abordan desde otro ángulo y nunca han sido introducidos a tus intenciones de diseño.

Cambiar tu perspectiva es, por supuesto, extremadamente difícil, pero es absolutamente necesario, y algunas de las herramientas de este libro usarán las implicaciones del marco MDA como referencia precisamente por esta razón.

![Ilustración: el marco MDA explicado con el ejemplo de correr (sprint) en un shooter](img/game-design-toolbox/p022.png)

> **Texto de la ilustración:** tres bloques apilados verticalmente, cada uno con un título, un dibujo y una caja de texto debajo.
> - **MECÁNICAS** (*MECHANICS*): dibujo de una tecla con una flecha hacia arriba (Shift) y un mando de consola. Caja: "Presionar Shift o el botón del stick izquierdo activa el 'sprint', que te mueve cuatro veces más rápido."
> - **DINÁMICAS** (*DYNAMICS*): dibujo de una figura de palitos corriendo hacia una cobertura mientras recibe disparos. Caja: "Cuando me hieren, puedo correr a cubierto para regenerar salud de forma segura sin que me disparen."
> - **ESTÉTICAS** (*AESTHETICS*): dibujo de un soldado disparando una ametralladora y otro soldado, con casco y fusil, agazapado tras un muro. Caja: "¡El Capitán Soldado corre lo más rápido posible a cubierto cuando la ametralladora abre fuego!"

## Bucles y aros (*Loops and Hoops*)

Algo a lo que nos referimos a menudo en diseño de juegos es el *loop* o bucle. Sin embargo, hay muchos bucles distintos; así que aclaremos de qué solemos hablar con un poco de vocabulario que te será útil cuando leas las herramientas.

Los bucles que se describen aquí existen para que el juego sea divertido de jugar (bucle de gameplay), para mantenerte jugando (bucle de compulsión) y para hacer que vuelvas por más (bucle de retención).

### Bucle de gameplay (*Gameplay Loop*)

Los tipos de decisiones e interacciones que se espera que el jugador haga una y otra vez pueden llamarse bucle de *gameplay*. Qué tan interesante es este bucle suele ser responsabilidad de un diseñador de juegos.

Muchos diseños de juegos empiezan por establecer un bucle de gameplay sólido y luego expandirlo.

- Objetos: cosas que existen para que se interactúe con ellas. Armas, herramientas, cartas, dados, llamas, tableros de juego, etc.
- Actores: cosas que realizan acciones usando objetos. Jugadores, personajes, inteligencia artificial, generadores aleatorios, etcétera.
- Acciones: cosas que hacen los actores. Los verbos del juego.
- Eventos: cosas que ocurren a partir de las acciones. El resultado de las acciones.

![Ilustración: diagrama circular del bucle de gameplay en tres pasos](img/game-design-toolbox/p023.png)

> **Texto de la ilustración:** título "BUCLE DE GAMEPLAY" (*GAMEPLAY LOOP*). Tres globos conectados por flechas que forman un ciclo:
> - 1) Los actores usan objetos para realizar acciones.
> - 2) Las acciones hacen que ocurran eventos.
> - 3) Los eventos dan *feedback* y actualizan el estado de los objetos y los actores.
> - Una flecha vuelve del paso 3 al paso 1, cerrando el bucle.

### Bucle de compulsión (*Compulsion Loop*)

"Por sí sola, la historia no daría para mucho como novela", dijeron Erik Wolpaw y Kim Swift sobre su juego Portal; y "el gameplay por sí solo sería seco".

De lo que hablan muchos diseñadores de juegos cuando hablan de bucles es del motor que impulsa el compromiso del jugador, y no solo del bucle de gameplay.

Ya sea que el corazón de este mecanismo sea un goteo de recompensas crecientes, o una progresión de uno u otro tipo, este bucle suele dividirse en tres bucles separados a los que puede hacerse referencia de maneras ligeramente distintas.

Primero, tienes el Micro bucle o compromiso segundo a segundo: jugar una carta, cambiar de arma, saltar un hueco, detectar un obstáculo o terminar tu turno. Suele ser lo mismo que el bucle de gameplay mencionado antes, pero es relevante pensarlo también en términos de compulsión, ya que el diseño de un juego rara vez es más fuerte que su capacidad de retener, y un bucle de gameplay repetitivo por sí solo puede perder atractivo con el tiempo.

Segundo, el Macro bucle o compromiso minuto a minuto: completar un objetivo o desafío, derrotar a un enemigo o ejecutar un buen combo de cartas. "Solo un turno más" en Civilization, o "solo una partida más" en un juego de pelea. Lo que sea que nos haga querer volver a sumergirnos en el micro bucle.

Tercero, el Meta bucle o compromiso hora a hora. Aquí es donde se revela la narrativa de un juego, donde ganas una partida, donde puede desarrollarse la maestría del sistema, y donde el compromiso del jugador se engancha a un nivel superior de compulsión. Esto es lo que te mantiene comprometido tanto en sesiones individuales muy largas como en tandas de muchas sesiones más cortas.

![Ilustración: los tres bucles de compulsión encadenados de menor a mayor escala](img/game-design-toolbox/p024.png)

> **Texto de la ilustración:** título "BUCLES DE COMPULSIÓN" (*COMPULSION LOOPS*). Tres bucles dibujados en fila, unidos por flechas que van de uno al siguiente por arriba y regresan por abajo:
> - MICRO BUCLE (segundo a segundo): acciones y eventos.
> - MACRO BUCLE (minuto a minuto): desafío y compromiso.
> - META BUCLE (hora a hora): narrativa y maestría.

### Bucle de retención (*Retention Loop*)

Algunos bucles están diseñados para hacer que los jugadores vuelvan al juego después de dejarlo, una y otra y otra vez, particularmente en juegos donde los diseñadores quieren que los jugadores gasten mucho tiempo (y/o dinero).

Esto vale por igual para los juegos por suscripción, los juegos *free-to-play* con compras dentro del juego, y también para los juegos de cartas intercambiables y los juegos de cartas coleccionables en el espacio de los juegos analógicos. Pero tampoco se trata solo de dinero. Cualquier juego para un jugador con una campaña masiva de 100 horas, o un juego de guerra basado en escenarios con más de 20 escenarios únicos, requiere algún tipo de incentivo para que los jugadores vuelvan.

Un bucle de retención sólido necesita oportunidades para que los jugadores dejen el juego de forma natural y vuelvan a entrar en él con la menor fricción posible.

La primera etapa de la retención es el compromiso. Lograr que el jugador se involucre en jugar el juego. Aquí es donde el Bucle de gameplay y el Bucle de compulsión hacen el trabajo pesado, y no es algo que maneje el bucle de retención.

Segundo, tienes la progresión. Ya sea ganando partidas, desbloqueando recompensas o avanzando por un *battle pass* mensual, esta es una parte central de la retención. Muchos diseños de juegos dependen de añadir contenido para esta etapa: nuevos paquetes de cartas, nuevos modos de juego y niveles adicionales; más de algo.

En tercer lugar, tiene que haber una llamada de retorno. Algo que programe al jugador para que vuelva después de terminar. Una vez más, en el libro de Nicholas Lovell *The Pyramid of Game Design*, el autor se refiere a tener una rampa de entrada natural para que los jugadores vuelvan al juego, pero también una rampa de salida natural para que puedan irse fácilmente cuando terminaron de jugar.

Por último, muchos juegos con una retención exitosa ofrecen comunidad más allá del juego. No solo comunidades en línea reales que discuten el *lore* y las estrategias, sino también interfaces adicionales; por ejemplo, Destiny 2 y su aplicación complementaria, donde puedes manipular tu equipamiento sin tener que lanzar el juego. Los torneos de prelanzamiento de nuevas cartas de Magic: The Gathering cumplen el mismo propósito: hacer que los fans mantengan jugando a otros fans.

![Ilustración: diagrama del bucle de retención con sus cuatro etapas](img/game-design-toolbox/p026.png)

> **Texto de la ilustración:** título "BUCLE DE RETENCIÓN" (*RETENTION LOOP*). Cuatro cajas apiladas verticalmente, unidas por flechas que forman un ciclo:
> - COMPROMISO (*ENGAGEMENT*): los bucles de gameplay y de compulsión.
> - PROGRESIÓN (*PROGRESSION*): sistemas de recompensas, *battle passes*, etc.
> - LLAMADA DE RETORNO (*RETURN CALL*): programarte para que vuelvas al juego, y facilitarte la entrada y la salida del juego. A la izquierda de esta caja, la etiqueta "RAMPA DE ENTRADA" (*ON-RAMP*); a la derecha, "RAMPA DE SALIDA" (*OFF-RAMP*).
> - COMUNIDAD (*COMMUNITY*): ofrecer maneras de relacionarse con otros fans, e interfaces adicionales con el contenido del juego.
> - Las flechas van de Compromiso a Progresión, de Progresión a Llamada de retorno (rampa de entrada), de Llamada de retorno de vuelta a Progresión (rampa de salida), y de Progresión de vuelta a Compromiso.

## Abrazar la subjetividad (*Embracing Subjectivity*)

Considera las preguntas retóricas planteadas en la introducción. ¿Dark Souls es difícil? ¿Battlefield V es acelerado? ¿El gameplay de Candy Crush Saga es estratégico? ¿Monopoly satiriza el capitalismo? ¿Todos los shooters en primera persona (FPS) deberían tener sprint? ¿El juego de mesa Mage Knight tiene demasiados componentes?

Sí y no; ambas cosas a la vez.

Mientras haces lluvia de ideas de juegos y hablas de juegos que disfrutas, observa siempre tu uso del lenguaje y tus propios sesgos, para que puedas tener en cuenta esta subjetividad. Si no, te toparás con el más común de todos los problemas del diseño de juegos: un discurso subjetivo que intenta llegar a conclusiones objetivas.

El primer problema viene de hablar de lo que pensamos que es divertido. Esto se debe en parte a que la diversión no siempre es un objetivo, y en parte a que la diversión es irremediablemente subjetiva. Muchos jugadores disfrutan la competencia, por ejemplo, y juegan horas y horas de juegos jugador contra jugador. Otros prefieren cooperar o jugar solitarios. Argumentar sobre la base de lo que es divertido es, por lo tanto, inútil. No porque alguien esté equivocado, sino porque todos tendrán razón subjetivamente.

En segundo lugar, el consenso general sobre lo que comúnmente se ve como bueno o malo puede discernirse de las voces ruidosas de las secciones de comentarios. Pero, igual que con la diversión, usar la bondad percibida de un juego como argumento da un argumento inútil, especialmente si lo usas para evaluar una parte diminuta de un juego, y peor aún si lo usas como ejemplo de una solución en tu propio diseño.

Imagina que estás hablando de que el jugador necesita una solución a un problema, y estás mirando juegos que tienen soluciones a dicho problema. En la mayoría de las conversaciones, es más probable que uses ejemplos de juegos que piensas que son divertidos o buenos (ver arriba), y entonces tomarás mecánicas de esos juegos para resolver tu problema, incluso si el problema no tiene ninguna relación. Esto puede llamarse prejuicio de *feature*: cometer el error de equiparar una dinámica con una de sus mecánicas subyacentes, y es una consecuencia directa de nuestra falta de respeto por la subjetividad en nuestro oficio.

### Abrazar la subjetividad en la práctica

Los siguientes son algunos recordatorios que puedes usar para abrazar la naturaleza subjetiva del diseño de juegos. Pueden ser mucho más útiles de lo que crees.

- Evita referirte a otros juegos: esto es difícil, porque los juegos que todos jugamos suelen ser el único terreno común que tenemos. Pero una vez que has pasado por la ideación y la exploración, y te has comprometido con tu juego, normalmente tendrás un lenguaje más establecido para él.
- Define un lenguaje en torno a tu propio juego: los Pilares, las Features, los Hechos y muchas de las otras herramientas del capítulo de Compromiso están hechas a medida específicamente para este propósito.
- Evita decir qué es divertido o no divertido; qué es bueno o malo. En cambio, habla de las razones por las que querrías usar esas palabras. Mejor aún, habla de las conclusiones que puedes sacar y de dónde se conectan con tu propio juego.
- Evita tomar prestadas mecánicas individuales de juegos donde sirven a una dinámica más amplia. Que pienses que un juego es divertido (o no) no valida automáticamente una mecánica para tu propio uso personal. A menudo hay detalles en juego que pueden no ser evidentes de inmediato.
- Apóyate lo menos posible en otros juegos cuando empieces tu propio proyecto. Apóyate más tarde, cuando tengas más confianza en tu idea. Si te apoyas en otros juegos demasiado pronto, hay riesgo de que se convierta en plagio, porque habrás reemplazado la identidad de tu propio juego con la del juego en el que te apoyaste.
- No hagas diferencia entre juegos: ya se jueguen en un tablero, con un mando, con una pantalla táctil, con un visor de realidad virtual o con naipes, hay muchísima superposición y polinización cruzada entre los distintos tipos de juegos. Aprovecha las similitudes; sortea las diferencias.
- No seas vengativo: si alguien estuvo en contra de tu idea, no vayas en contra de la suya como represalia. A veces esto puede ser casi inconsciente y no por rencor en absoluto —solo por ser humano—, así que intenta darte cuenta de cuándo estás a punto de rechazar algo por la razón equivocada.
- No uses "incorrecto"/"correcto" cuando esas palabras no aplican. En el diseño de juegos, como en tantos oficios creativos, rara vez hay una manera objetiva de estar equivocado o de tener razón. Intenta motivar tus argumentos por su mérito, incluso si el único mérito que tienen es que es algo que disfrutas o algo que prefieres. Sé honesto cuando ese sea el caso.
- No mueras en ninguna colina: a veces simplemente no quieres rendirte. Esa cosa que consideras importante es lo más importante que ha existido, y volverás a ella incluso cuando no sea relevante. Evita esto. No hay colinas por las que valga la pena morir.

## Las herramientas (*The Tools*)

El resto de este libro es la parte de herramientas de la caja de herramientas.

Cada herramienta tiene la misma estructura:

- Una breve descripción que motiva por qué deberías usarla y habla de cuándo es más útil.
- Una guía paso a paso, un ejemplo o una lista de verificación para seguir cuando uses la herramienta. Varía mucho entre herramientas, pero siempre hay alguna pauta práctica disponible.
- Una ilustración que demuestra cómo se ve la herramienta en uso y cómo aprovecharla, o que simplemente intenta burlarse de ella.

---

# Capítulo 2 — Ideación (*Ideation*)

Muchos diseñadores prosperan en la ideación. Inventar mecánicas locas y soluciones ingeniosas a problemas teóricos. Tener ideas a la velocidad del pensamiento, o quizá más rápido.

Las ideas son divertidas, y discutirlas lo es aún más. Pero hay algunas maneras de hacer que el proceso de ideación sea más constructivo, y unos cuantos principios esenciales que deberías tener en mente.

Hay varias cosas que necesitas lograr con la ideación:

- Una lista depurada de ideas que merecen ser exploradas, ya examinadas con lupa por ti y por cualquier colega.
- Preguntas viables para validar en la Exploración.
- Un medio para comunicar de qué tratan tus ideas, a ti mismo y a los demás.
- Formas de vender las mejores ideas a tu equipo, si tienes uno.

## HAZ MENOS PREGUNTAS (*ASK FEWER QUESTIONS*)

Muchas herramientas de esta sección te dirán que hagas preguntas. Eso hace que resulte raro empezar afirmando que deberías hacer menos preguntas. Así que pongámonos en contexto.

Imagina una reunión de lluvia de ideas o una conversación de diseño de juegos. Todos están hablando de cuál debería ser la perspectiva de la cámara. Quizá alguien lanza la pregunta aparentemente inocente: "¿podemos hacerlo en primera persona?".

Nuestros cerebros son nuestros mayores enemigos aquí. El cerebro no escucha una pregunta como una pregunta; a menudo escucha una pregunta como una sugerencia.

Hagámoslo en primera persona, entonces. Deja que tu mente hile su historia a partir de eso y olvida cualquier perspectiva que tuvieras en mente antes de esta pregunta aparentemente —e intencionalmente— inocente.

También importa quién hace la pregunta. ¿Y si es tu líder, o incluso el CEO de la empresa? Fácilmente adquiere un tono distinto.

Así que, antes de empezar la ideación en serio, considera cómo haces las preguntas. Puede incluso ser buena idea escribir las cosas antes de decirlas, y luego mirar bien lo que escribiste 5 minutos después. Lo más probable es que las cosas que querías decir ni siquiera necesiten decirse, porque la conversación ya siguió adelante. Especialmente si era una pregunta que habría llevado las cosas en una dirección distinta.

### Preguntas que (quizá) conviene evitar en la ideación

- **¿Es posible hacer X?** Nadie, en particular los desarrolladores, admitirá jamás que algo no es posible, lo que convierte a esta en una pregunta engañosa y no meramente una sugerencia velada.
- **¿Podemos hacerlo X?** Lo mismo. Sí, podemos, pero eso no aborda si deberíamos ni por qué.
- **¿Te refieres a algo como X o como Y?** Introduce una falsa dicotomía. Podría ser que la respuesta real sea Z, o el número 25. Si introduces selecciones binarias en tus propios términos, estás forzando una respuesta que se ajusta a tus ideas.
- **¿De verdad te gusta X?** Una pregunta cargada de valoración que implica que algo anda mal con la opinión sugerida y puede forzar a la persona a replanteársela.
- **¿Te gusta X? A mí me gusta mucho X.** Corre el riesgo de reemplazar las ideas propias de una persona con las tuyas sobre la base de un supuesto entendimiento mutuo.
- **¿No es esto simplemente X? / ¿No es esto exactamente como X? / ¿Te refieres a algo como en X?** Nada descarrila tanto una conversación como el etiquetado no deseado o innecesario, o lo que en broma puede llamarse "tenis de referencias", donde nos lanzamos títulos de juegos unos a otros hasta que alguien nombra un juego que nadie ha jugado.

### Preguntas para hacer a menudo en la ideación

- **¿Crees que X también implica Y?** Permite a la otra persona verificar lo que estás sugiriendo, o extrapolar.
- **¿Y si también hacemos X? / ¿Podríamos probar X, qué te parece?** De nuevo, delega la extrapolación en la persona que hizo la sugerencia.

![Ilustración: dos figuras de palo conversando; una pregunta por la primera persona y la otra, que pensaba en tercera persona, cambia de idea](img/game-design-toolbox/p031.png)

> **Texto de la ilustración:**
> - Globo de pensamiento de la figura de la derecha (arriba): "Quizá en tercera pers…"
> - Globo de diálogo de la figura de la izquierda: "¿Esto debería ser en primera persona? ¿Con algo de disparos?"
> - Globo de pensamiento de la figura de la derecha (abajo): "Oh… ¡disparos en primera persona suena genial!"

## HAZ LLUVIA DE IDEAS EN PAPEL (*BRAINSTORM ON PAPER*)

Todos entran en fila a la sala de reuniones. Hay una agenda, o no la hay (normalmente no la hay). Cuando empieza la reunión, hay 15 minutos de anécdotas contadas por esa persona que siempre cuenta anécdotas interminables. Luego cada discusión se desvía hacia lo que quiera hablar el participante más locuaz. Por alguna razón, a menudo es el megaéxito de videojuegos más reciente.

La gente que habla mucho tiende a ser la que se escucha. Pero, como ya se ha cubierto, todo el mundo es un diseñador de juegos de Nivel 1. Ser locuaz no debería ser un criterio.

Para darle a todos la oportunidad de ser escuchados, y para obtener todas las grandes ideas de la gente que prefiere quedarse callada, hacer lluvia de ideas en papel es una herramienta eficaz.

Si eres una persona locuaz, a menudo será tentador hablar sobre las notas que recibes o hablar por encima de todo el proceso. Pero es extremadamente importante que te mantengas en silencio durante todo el proceso y dejes que las cosas tomen su tiempo.

Hacer lluvia de ideas en papel también puede usarse como un medio para reunir *feedback* después de un *playtest*, para no contaminar el feedback con las opiniones de las voces más fuertes.

También hay una razón por la que esta es la segunda herramienta del libro. Cuando un proyecto nuevo despega, es genial reunir ideas de tantas personas como sea posible. No importa si la idea es completamente desconocida en esta etapa, o si ya sabes más o menos qué tipo de proyecto va a ser. Sigue siendo extremadamente valioso permitir que todos los diseñadores de Nivel 1 participen en igualdad de condiciones en la ideación inicial.

### Hacer lluvia de ideas en papel

1. Asigna un moderador (no tiene que ser un diseñador de juegos).
2. Recoge posibles temas de discusión por medios anónimos. Una oración como máximo. Quizá "¿Quién es el antagonista?" o "¿Qué tipos de verbos queremos en nuestro juego?".
3. Reúne a los participantes en una sala de reuniones (física o en línea).
4. Dale a cada uno una hoja de papel individual o su equivalente digital, para tomar notas.
5. Plantea uno de los temas de una sola oración para la lluvia de ideas. El moderador puede elaborar sobre el tema, si hace falta. Está bien hacer preguntas en esta etapa, pero solo el moderador debería responder, y no debería sacar a discusión ningún tema creativo.
6. Pide a todos que escriban su respuesta en su hoja de papel. Pero nadie puede hablar. Usa un despertador, manos levantadas, lapiceras apoyadas sobre la mesa u otro medio silencioso para que todos señalen que terminaron con esta etapa.
7. Una vez terminado, pasa la hoja a la siguiente persona en sentido horario alrededor de la mesa y repite el proceso para el mismo tema. Esto permite que todos se tomen su tiempo, vean lo que piensan los otros participantes y lo pongan todo por escrito.
8. Cuando recibas tus propias notas de nuevo, de modo que cada hoja haya dado una vuelta completa a la mesa, puedes tener una discusión abierta sobre lo que han escrito, dándole a cada uno un turno para hablar, o puedes volver al punto 4, empezando con una hoja de papel nueva y un tema nuevo.
9. El resultado de este proceso, una vez que las etapas 4–8 se han repetido la cantidad de veces deseada, es la suma de las ideas del grupo.

![Ilustración: cuatro figuras de palo alrededor de una mesa pasándose notas en sentido horario, con los pasos numerados del proceso](img/game-design-toolbox/p033.png)

> **Texto de la ilustración:**
> - Título: "Pregunta de la lluvia de ideas: '¿Qué armas deberíamos tener en nuestro juego?'"
> - Etiqueta 1) "Plantea la pregunta". Globo de pensamiento de la figura correspondiente: "Solo una pistola genial, nada más. ¡Estilo espía!"
> - Etiqueta 2) "Todos escriben sus respuestas". Globo de pensamiento: "¡Una escopeta en cada mano! ¡Un lanzacohetes en cada mano! ¿¡Una BOMBA NUCLEAR en cada mano!?"
> - Etiqueta 3) "Pasa las notas en sentido horario" (en el centro de la mesa, con flechas circulares).
> - Etiqueta 4) "¡Sigue hasta que tus propias notas regresen!". Globos de pensamiento de las otras dos figuras: "No me gustan las armas… ¿quizá un botón para enfundar?" y "Me encanta la escopeta de seis cañones de este juego…"

## ACERCA Y ALEJA EL ZOOM (*ZOOM IN, ZOOM OUT*)

A veces te atascas. Atascado discutiendo elementos de la trama general de tu juego, o quizá atascado hablando durante horas de la misma *feature* menor mejorada de forma incremental.

Estas conversaciones pueden ser formas valiosas de idear o explorar, pero no ayuda a tu ideación quedarse atascado demasiado tiempo en algo que no lleva a ninguna parte.

Muchas de las conversaciones que tenemos en el desarrollo de juegos son simplemente divertidas de tener, y aunque racionalmente sepamos que no podemos hacer existir un juego a base de hablar, a veces se siente genial hacerlo de todos modos.

Lo que puedes hacer para desatascarte es invertir el alcance de la conversación. Si te atascas en cosas pequeñas, alejas el zoom para hablar de algo grande. Si te atascas en cosas grandes, acercas el zoom para discutir algo pequeño.

Ninguna de las dos situaciones significa que abandones permanentemente el tema en el que te atascaste, pero puede mantenerte —a ti y a la ideación de tu juego— avanzando.

### Hacer zoom

Si te atascas en uno; prueba cambiar al otro.

Algunos ejemplos:

- **Una feature de gameplay específica:** el sistema del que forma parte esa feature.
- **Un personaje del juego:** el grupo al que pertenece el personaje.
- **Un único elemento de una carta o pantalla:** la disposición de las cartas o de la pantalla.
- **Un encuentro en el juego:** el sistema que usan los encuentros del juego.
- **Una situación de juego específica:** la motivación del jugador para jugar.
- **Una única regla del juego:** el propósito de las reglas de esa parte del juego.
- **Un evento de tu trama:** la historia de esa parte del juego.
- **La historia de una parte del juego:** la narrativa del juego entero.
- **Un único tipo de enemigo:** el diseño de los enemigos en general.
- **Una única tirada de dados:** qué dados usar en el juego.

![Ilustración: círculos concéntricos con el personaje principal del jugador en el centro y el mundo del juego en el exterior, con flechas de zoom en ambos sentidos](img/game-design-toolbox/p035.png)

> **Texto de la ilustración:**
> - Centro: "El personaje principal del jugador".
> - Exterior: "El mundo del juego".
> - Flecha hacia el centro: "Acerca el zoom cuando te atasques en temas de alto nivel".
> - Flecha hacia el exterior: "Aleja el zoom cuando te atasques en minucias."

## VERBALIZA (*VERBALIZE*)

Los juegos son a menudo actividades simuladas. Los jugadores o sus avatares están haciendo cosas, ya sea saltar, disparar, conquistar, hablar o algo completamente distinto.

Un verbo es una palabra que expresa acción. Los verbos son, en cierto modo, los hechizos mágicos del diseño de juegos. Nuestras palabras de poder.

Por eso, tiene sentido empezar la ideación proponiendo verbos que describan las acciones que quieres de tu juego. Estrictamente hablando, hay dos conjuntos de acciones que necesitas proponer: uno para el jugador que juega el juego, y otro para el avatar que representa al jugador. Pero sáltate eso por ahora. Deja que surja de forma natural (y del uso de otras herramientas de este capítulo).

Ayuda visualizar que juegas el juego mientras haces esto, e ir listando los verbos que van surgiendo.

Un ejercicio que puede ayudar es que extraigas los verbos más importantes ya en esta etapa y los asignes a un botón en un esquema de control, o que listes qué componentes representarán qué verbo en el diseño de un juego analógico.

Trata de pensar con un control (o los componentes) en la mano, tan pronto como sea posible.

- Aceptar (*Accept*)
- Elegir (*Choose*)
- Examinar (*Examine*)
- Acusar (*Accuse*)
- Escalar (*Climb*)
- Salir (*Exit*)
- Adquirir (*Acquire*)
- Colorear (*Color*)
- Explorar (*Explore*)
- Asaltar (*Assault*)
- Crear (*Create*)
- Caer (*Fall*)
- Atacar (*Attack*)
- Completar (*Complete*)
- Alimentar (*Feed*)
- Hornear (*Bake*)
- Consolar (*Console*)
- Pelear (*Fight*)
- Convertirse (*Become*)
- Llorar (*Cry*)
- Huir (*Flee*)
- Hacerse amigo (*Befriend*)
- Bailar (*Dance*)
- Volar (*Fly*)
- Morder (*Bite*)
- Destruir (*Destroy*)
- Dar (*Give*)
- Chantajear (*Blackmail*)
- Morir (*Die*)
- Chismear (*Gossip*)
- Romper (*Break*)
- Dividir (*Divide*)
- Crecer (*Grow*)
- Construir (*Build*)
- Dibujar (*Draw*)
- Dañar (*Harm*)
- Quemar (*Burn*)
- Beber (*Drink*)
- Odiar (*Hate*)
- Comprar (*Buy*)
- Conducir (*Drive*)
- Oír (*Hear*)
- Atrapar (*Catch*)
- Comer (*Eat*)
- Golpear (*Hit*)
- Cambiar (*Change*)
- Entrar (*Enter*)
- Sostener (*Hold*)
- Esperar (tener esperanza) (*Hope*)
- Gestionar (*Manage*)
- Correr (*Run*)
- Abrazar (*Hug*)
- Modificar (*Modify*)
- Vender (*Sell*)
- Imitar (*Imitate*)
- Necesitar (*Need*)
- Ver (*See*)
- Mejorar (*Improve*)
- Negociar (*Negotiate*)
- Buscar (*Seek*)
- Intimidar (*Intimidate*)
- Notar (*Notice*)
- Disparar (*Shoot*)
- Inventar (*Invent*)
- Operar (*Operate*)
- Ir de compras (*Shop*)
- Invertir (*Invest*)
- Poseer (*Own*)
- Cantar (*Sing*)
- Saltar (*Jump*)
- Pintar (*Paint*)
- Hundir (*Sink*)
- Improvisar un arreglo (*Jury-rig*)
- Planear (*Plan*)
- Dormir (*Sleep*)
- Emprender un viaje (*Journey*)
- Prometer (*Promise*)
- Resolver (*Solve*)
- Patear (*Kick*)
- Abandonar (*Quit*)
- Girar (*Spin*)
- Matar (*Kill*)
- Leer (*Read*)
- Estudiar (*Study*)
- Besar (*Kiss*)
- Recibir (*Receive*)
- Nadar (*Swim*)
- Liderar (*Lead*)
- Reducir (*Reduce*)
- Saborear (*Taste*)
- Aprender (*Learn*)
- Reemplazar (*Replace*)
- Cuidar (*Tend*)
- Mentir (*Lie*)
- Rescatar (*Rescue*)
- Tocar (*Touch*)
- Escuchar (*Listen*)
- Montar (*Ride*)
- Viajar (*Travel*)
- Perder (*Lose*)
- Rotar (*Rotate*)
- Ganar (*Win*)

![Ilustración: un control de videojuegos dibujado a mano con verbos asignados a sus botones y palancas](img/game-design-toolbox/p037.png)

> **Texto de la ilustración:** etiquetas con flechas sobre el control:
> - "Interactuar" (*Interact*) → botón superior izquierdo.
> - "Disparar" (*Shoot*) → gatillo superior derecho.
> - "Moverse" (*Move*) → palanca analógica izquierda.
> - "Saltar" (*Jump*) → botón frontal derecho.
> - "Mirar" (*Look*) → palanca analógica derecha.

## DI "SÍ, Y…" (*SAY "YES, AND…"*)

Con demasiada frecuencia, nuestro instinto es derribar las cosas. Decir "no, esa es una mala idea", o pasar a alguna tangente. Nuestro modo de discurso es a menudo divisivo o partidista: estamos a favor o en contra de las cosas, o leemos un subtexto pasivo-agresivo no intencionado en oraciones que no tienen segundas intenciones. Especialmente en la comunicación en línea.

Pero hay un gran punto intermedio que puedes aprender a utilizar, y es un concepto de la comedia de improvisación: "sí, y…".

La idea básica es que construyes algo más encima de lo que se acaba de decir. Si alguien dice "¿quizá lo hicieron los elfos?", y todo lo que realmente quieres es culpar a los enanos en su lugar, no lo haces: sigues construyendo encima. Dices "sí, y los enanos también estaban implicados".

Sin embargo, el refuerzo positivo es un proceso delicado. Existe el riesgo de que tu sí siga sonando como un no, si no tienes cuidado en cómo lo usas. "Sí, y entonces llegaron los enanos y tomaron el control" no sería una forma muy agradable de hacerlo, por ejemplo, ya que reemplazaría lo que la persona anterior acaba de decir con tu propia idea.

Básicamente: el "sí" acepta la afirmación anterior como verdadera, y el "y" sigue construyendo sobre ella. Cuando todos en una reunión o discusión de diseño usan esta técnica simple, puedes tener conversaciones mucho más gratificantes y podrás hacer lluvia de ideas con más eficacia.

Para que el "sí, y…" funcione, la afirmación a la que sigue no puede ser demasiado larga ni elaborada. Si tienes que escuchar toda la historia de los elfos durante 2 horas antes de poder decir tu "sí", se vuelve difícil saber a qué le estás diciendo que sí realmente.

Mantente breve y al grano en la ideación, e invita regularmente a más gente a la conversación.

### Usar el "sí, y…"

- Haz afirmaciones de una sola oración que sean fáciles de aceptar y sobre las que sea fácil construir.
- Escucha con atención lo que sugieren los demás participantes.
- Responde diciendo "sí" de inmediato, incluso si no tienes planeada la continuación o si tu instinto dice que no. Esto es para enseñarte a ti mismo a ser más positivo hacia las sugerencias de otros diseñadores.
- Di "y", y luego añade tu propio giro constructivo a lo que se acaba de decir.
- Como ejercicio, puedes seguir dando vueltas por la sala hasta que todos hayan contribuido con algo a la misma idea.

![Ilustración: una figura de palo entusiasmada propone una idea; a la izquierda, respuestas que la derriban, y a la derecha, respuestas que construyen sobre ella](img/game-design-toolbox/p039.png)

> **Texto de la ilustración:**
> - Globo principal (arriba): "¡¿Y si jugamos como roedores?! ¿Roedores inteligentes que juegan D&D en el sótano de alguien?"
> - Etiqueta: "Compara esto:"
>   - Globo: "¡Puaj! ¿Tienen que ser roedores? ¿En serio? Los roedores son asquerosos."
>   - Globo: "Creo que a los jugadores les gustarán más los cocodrilos. ¡Vamos con cocodrilos!"
> - Etiqueta: "…con esto:"
>   - Globo: "¡Sí! Y chillan muy fuerte y roen los dados si fallan críticamente. ¡Jaja! Podemos hacer cosas geniales con roedores."
>   - Globo: "Sí, y puedes personalizar tu roedor. Color del pelaje, largo de los dientes, ¿quizá cicatrices?"

## PRUÉBALO (*TRY IT*)

Los juegos no son más que la cosa jugable que tienes en la mano. Pero los diseñadores de juegos en particular son aficionados a las discusiones teóricas sobre todo y nada, al mismo tiempo.

Cuando te encuentres en una discusión así —especialmente si es del tipo "¿no sería genial si…?"—, siéntete libre de inyectar una sugerencia: "¡pruébalo!".

"Probarlo" es llevar algo directamente a la Exploración construyendo un prototipo, encontrando otro juego que haga algo similar y jugándolo, o de cualquier otra forma avanzando hacia una representación práctica de la idea específica. Para evitar atascarse en discusiones teóricas e ir directo a demostrar la validez de la idea. Incluso si esto se hace solo de forma aislada.

Esto hace tres cosas: reconoce si la idea tiene mérito, genera entusiasmo por ver cómo funciona y te obliga a pensar en todos los cómos y porqués en lugar de dejarlo en la etapa de las ideas. Si quieres que se quede en la etapa de las ideas, también te obliga a ser honesto al respecto.

Instar a alguien a "¡probarlo!" debería ser una respuesta espontáneamente positiva y nunca debería usarse de forma irónica o negativa. Debería venir de un lugar de interés genuino.

Lo que hace es que impide que la ideación del diseño de juegos se atasque en la etapa en la que todo lo que hacemos es hablar de posibilidades. Después de todo, tener ideas nunca hará un juego.

### Cuándo decir "¡pruébalo!"

- "Tengo una idea que se me ocurrió y que es…" ¡Pruébalo!
- "¿Y si tomamos esta feature y hacemos esto otro en su lugar?" ¡Pruébalo!
- "Este experimento curioso quizá podría tener resultados interesantes…" ¡Pruébalo!
- "No estoy seguro de que sea tan buena idea…" ¡Pruébalo!
- "¡Nunca vi esto antes!" ¡Pruébalo!
- "No creo que podamos hacer esto en nuestro motor…" ¡Pruébalo!

![Ilustración: una figura de palo lanza ideas de juegos y otra responde a cada una con "¡Pruébalo!"](img/game-design-toolbox/p041.png)

> **Texto de la ilustración:**
> - Globo: "¿Y si hay un juego de estrategia, y tienes como 100 unidades al principio, y eso es todo lo que recibes? Arréglatelas, repáralas, gana usando solo esas 100 unidades…" → Respuesta: "¡Pruébalo!"
> - Globo: "O un juego de parque temático, pero intentas hacer que los visitantes desaparezcan o tengan accidentes…" → Respuesta: "¡Pruébalo!"
> - Globo: "O un juego de mesa, pero usas las cartas para construir un laberinto…" → Respuesta (en grande): "¡PRUÉBALO!"
> - Globo pequeño: "O…"

## ESTABLECE UN TEMA (*SET A THEME*)

Una de las discusiones más antiguas del diseño de juegos es si los diseñadores deberían partir del tema o de las mecánicas. Es un dilema de causalidad tipo huevo-o-gallina, si somos honestos. Haz lo que te funcione. Pero partir de un tema puede tener un mérito increíble, en particular cuando trabajas con gente que tiene conjuntos de habilidades muy distintos de los tuyos. Un tema puede tender puentes sobre las brechas conversacionales mucho más rápido que otros tipos de lineamientos generales, y puede ayudarte a despegar con las partes mecánicas de tu juego.

"Tema" en diseño de juegos se usa con mayor frecuencia para describir el contexto del juego entero. Suele ser más que el tema literario lo que se incluye. Es todo el abanico de elementos literarios, o una selección escogida de ellos.

Cuando discutas el tema de un juego, ayuda ampliar la conversación para incluir el abanico completo de elementos literarios. Algunos o todos ellos son lo que se incluye de todos modos cuando se discute el "tema" en diseño de juegos. Así que hazlo parte de tu conversación.

Una vez que hayas establecido tu tema, úsalo para informar tu ideación. Úsalo para hacer mejores preguntas y para descubrir qué es importante explorar.

### Elementos literarios incluidos en el "tema" del diseño de juegos

- **Personajes:** quiénes son los personajes del juego, si hay personajes. Nota que un personaje no tiene que ser una persona: puede ser una nave espacial, un caballo, una casa, una tormenta o alguna otra cosa que refuerce el tema del juego. Algo sobre lo que el juego pueda tratar.
- **Tema narrativo:** un asunto o una emoción, como la paternidad, la supervivencia, el fanatismo o la redención.
- **Ambientación:** dónde y cuándo transcurre tu juego, como telón de fondo o como construcción de mundo explícita.
- **Trama:** la relación entre distintos eventos de la historia del juego, si la hay. En diseño de juegos, una trama también puede ser generada por la actividad del jugador.
- **Historia:** la narrativa específica que el juego está diseñado para contarle al jugador.
- **Conflicto:** el conflicto de intereses central que enfrenta a las fuerzas del jugador contra las del juego, o a jugadores contra jugadores.
- **Perspectiva:** de quién es el punto de vista que el juego retrata o ilustra.
- **Tono:** si es pesado, desenfadado, crítico, político o cualquier otra cosa.
- **Ritmo:** qué tan rápido es el concepto. Si tiene el ritmo de una película de acción, o de un drama, o de una obra de teatro, o de algo completamente distinto.
- **Estilo:** la forma en que se transmite un tema puede variar según la elección de palabras, el contenido del juego y aquello por lo que el jugador es recompensado. Piensa en la diferencia entre añadir una penalización de tiempo y darte puntos por atropellar a un peatón en un juego de carreras callejeras.
- **Género narrativo:** thriller, terror, comedia, tragedia o cualquier otro; lo que quieras.

![Ilustración: varias figuras de palo, cada una imaginando una idea de juego a partir de un tema o actividad, y una de ellas añadiendo un giro](img/game-design-toolbox/p043.png)

> **Texto de la ilustración:**
> - Globo de pensamiento (tenista): "¿'Tenis esquivo'? Ahí hay una idea de juego…"
> - Globo de pensamiento (persona en la cocina): "¿'Ayudante de cocina brutal deluxe'?"
> - Globo de pensamiento (persona en un acantilado): "Salto BASE con traje de ardilla…"
> - Globo de diálogo (figura con espada, señalada con una flecha desde el anterior): "…¡con espadas!"

## INVENTA UNA MECÁNICA (*INVENT A MECHANIC*)

Hay dos formas de proponer con bastante consistencia mecánicas "nuevas" para explorar: derivándolas de experiencias de juego existentes, e inventándolas a partir del tema, de restricciones, de hobbies que tengas o de alguna otra cosa que sirva para gamificar.

En esta etapa temprana, es extremadamente importante que no contamines demasiado tus ideas. Deberías referirte a la experiencia de gameplay que buscas a través de las mecánicas, pero evita referirte directamente a otros juegos. No es porque los otros juegos sean malos para ti de algún modo. Para nada. De hecho, si diseñas juegos, deberías asegurarte de jugar tantos juegos como el tiempo te permita.

La razón por la que no deberías referirte a otros juegos al hablar de mecánicas es la subjetividad mencionada antes. Corres el riesgo de confundir las dinámicas de un juego que te gusta con las mecánicas que en realidad producen esa dinámica. Sin mencionar que copiar otros juegos siempre corre el riesgo de convertirse en una versión peor de algo mejor.

Una vez que tengas tu propio juego funcionando, definitivamente puedes empezar a comparar tu juego con otros juegos e intentar informarte de las mejores prácticas que exhiben. Pero en ese punto, lo más probable es que tu juego cobre vida propia y no tengas que usar en absoluto la muleta del diseño basado en referencias.

### Formas de derivar mecánicas

- **A + B:** un juego de rol de acción de fantasía con armas de fuego. (Juego de rol de acción de fantasía + mecánicas de disparo.)
- **A – B:** un shooter en primera persona sin gravedad. (Shooter en primera persona – gravedad.)
- **A en B:** un juego de gran estrategia en una ciudad submarina. (Gran estrategia en ciudad submarina.)
- **A pero B:** un juego de cartas coleccionables, pero juegas con una sola mano de cartas. (Juego de cartas coleccionables, pero con una sola mano de cartas.)
- **A, B extra:** un juego de carreras donde los vehículos son mucho, mucho más rápidos. (Carreras, velocidad extra.)

### Formas de inventar mecánicas

- **Interacción de componentes:** dar vuelta cartas boca abajo, perder si sueltas un botón, o saltar automáticamente. Usa algo reconocible de una forma distinta.
- **Tema:** un tema interesante a menudo implicará mecánicas de forma directa. Explora los distintos elementos literarios para ver qué sale.
- **Actividad:** salto BASE, ingeniería de máquinas, tala de madera, matemáticas o programación. Cualquier actividad puede ser una gran inspiración para una mecánica.
- **Restricciones:** si no puedes hacer una cosa, algo tiene que reemplazarla.
- **Historia:** un evento histórico que sea extraño, oscuro o simplemente muy interesante.
- **Ficción:** un libro, película o serie de televisión que tenga una escena genial que quieras convertir en una experiencia de juego.
- **Hobby:** cocinar, coleccionar estampillas, teatro amateur, bailar o levantar pesas. La gente ha inventado incontables pasatiempos que podrían ser mecánicas excelentes.

![Ilustración: una figura de palo describe un juego sobre comer tortugas y otra la bombardea con preguntas](img/game-design-toolbox/p045.png)

> **Texto de la ilustración:**
> - Globo (figura de la izquierda): "¡Juegas como un COMEDOR DE TORTUGAS! Comes tortugas. Sobre todo tortugas malvadas, pero a veces es difícil saberlo."
> - Globos (figura de la derecha): "Entonces, o sea, ¿cómo te las comes?" / "¿Tenedor? ¿Cuchara? ¿Pajilla?" / "¿Qué hace malvadas a las tortugas malvadas?" / "¿Puedes jugar como tortuga en Nueva Partida+?"

## DECIDE A QUIÉN JUEGA EL JUGADOR (*DECIDE WHO THE PLAYER PLAYS*)

Decidir a quién está jugando tu jugador proporciona una manera de mirar tu concepto desde más de una dirección.

El avatar del jugador puede ser casi cualquier cosa. Una nación, un imperio histórico, un personaje o un grupo de personajes: los juegos han probado muchos tipos distintos de avatares a lo largo de las décadas. El avatar puede tener un nombre, puede ser un concepto muy amplio o puede ser completamente abstracto.

Imagina un juego sobre un conflicto armado, por ejemplo. Hay incontables maneras de construir un juego así. Unos cuantos avatares de ejemplo para que los jugadores controlen en un conflicto armado (que apenas rascan la superficie) podrían ser:

- Juegas como un soldado que sigue órdenes en el campo de batalla.
- Juegas como un oficial que da órdenes en el campo de batalla.
- Juegas como parte de una dotación de artillería que dispara un cañón.
- Juegas como un oficial de alto rango que da órdenes estratégicas.
- Juegas como un corresponsal que informa sobre crímenes de guerra.
- Juegas como un prisionero de guerra que intenta sobrevivir.
- Juegas como un inspector de armas químicas de la ONU que intenta recoger evidencia.
- Juegas como un político que le dice a los oficiales de alto rango qué hacer.
- Juegas como la logística del ejército, enviando tropas, comida y munición al frente, y bajas lejos de él.
- Juegas como el ejército entero.
- Juegas como una nación completa.
- Juegas como la autoridad política de todo el planeta Tierra.

### Definir un avatar

1. Mira lo que el jugador estará haciendo en tu juego. Si ya tienes una lista de verbos, parte de ahí.
2. Considera dónde encajan este tema o estas actividades, y quién se involucraría con ellas.
3. Lista todos los "quiénes" que se te ocurran.
   a. **El facilitador:** ¿quién exige o hace posibles las actividades?
   b. **El ejecutor:** ¿quién es el que tiene que involucrarse en todas las actividades que tu facilitador tiene en mente?
   c. **El enemigo:** ¿quién se opone a las actividades que tienes en mente?
   d. **El instrumento:** ¿alguien atrapado entre los otros tres, ocupándose de sus propios asuntos y, sin embargo, viéndose envuelto de algún modo?
   e. ¡Uno de estos cuatro podría ser tu avatar!
4. Haz lluvia de ideas sobre otros "quiénes" que puedan funcionar, incluyendo cosas que al principio parezcan descabelladas. Puede ser cualquier cosa. Un animal, una profesión (un plomero viene a la mente), etc.
5. Recorre la lista de quiénes y considera cada uno y lo que significaría:
   a. Para el tema del juego
   b. Para el/los jugador(es)
   c. Para la imagen, el ánimo y la atmósfera del juego
   d. Para el marketing del juego
6. Toma una decisión, incluso si esa decisión es probar dos o más de los "quiénes" que se te ocurrieron para ver cuál se queda.

![Ilustración: cuatro candidatos a avatar dibujados a mano: un monarca, un dragón, un caballero y una figura con signo de interrogación](img/game-design-toolbox/p047.png)

> **Texto de la ilustración:**
> - Título: "¿A quién juega el jugador?"
> - "¿El facilitador?" — Caja: "¿El monarca reinante, dando órdenes?"
> - "¿El enemigo?" — Caja: "¿El terrible dragón asesino con colmillos de la Cueva de la Calavera, enemigo de toda la tierra?"
> - "¿El ejecutor?" — Caja: "¿El caballero furioso, siguiendo órdenes (a duras penas)?"
> - "¿El instrumento?" — Una figura con un signo de interrogación sobre la cabeza.

## ASUME MENOS (*ASSUME LESS*)

Cada vez que digas "los jugadores quieren X", "los jugadores esperan Y" o "debería funcionar como en Z", en su lugar encuentra una manera de evaluarlo desde la perspectiva de tu propio juego.

Cada vez que te saltas hacer algo porque una suposición pudo más que tú, olvidas que el enormemente exitoso Fortnite no existía antes de 2017, que los *deck builders* se volvieron algo prominente con Dominion en 2008, y que los shooters en primera persona solían jugarse con las teclas de flecha y no con ratón y teclado ni con dos palancas analógicas. Incluso definiciones de género como "juego de rol" (RPG) significan cosas muy distintas para distintas generaciones de jugadores.

Asume lo menos posible: construye tu juego, no el de otro.

Está bien sentirse perdido o buscar salidas fáciles. Es normal. Pero hazte consciente de que es un problema y haz lo posible por recordarse mutuamente (o a ti mismo) que hay que verificar esas suposiciones.

Algunos proyectos tendrán, por supuesto, suposiciones incorporadas que simplemente tendrás que llevar a tus conversaciones. Si trabajas con una propiedad intelectual existente, por ejemplo, o si estás haciendo una secuela, algunas suposiciones pueden ser una obligación contractual.

Pero incluso entonces, sigue siendo buena práctica verificar tus suposiciones y encontrar formas de validarlas.

### Verificaciones de suposiciones

- No resuelvas tus ideas refiriéndote a soluciones de otros juegos. Primero necesitas establecer qué debería estar haciendo tu juego y qué experiencia quieres darle al jugador.
- No des por sentado lo que los jugadores quieren ni cómo se sentirán. Todavía no puedes saberlo. En su lugar, concéntrate en qué tipo de experiencia quieres crear y en el camino más corto para lograrla.
- Evita la jerga y las abreviaturas en la medida de lo posible. No todos estarán de acuerdo con tu definición de lo que significa ARPG o FPS, y no es una discusión que necesites tener todavía: solo hará perder tiempo.
- Desconfía de la palabra "debe", en particular en torno a las features. Ningún juego debe hacer una cosa determinada. Esto solo conduce a callejones sin salida y a derivados.
- Espera tanto como sea posible antes de introducir el lenguaje gamer estándar en la conversación. Una vez que empieces a hablar de cosas como "cámara en tercera persona" o "*deckbuilding*", también introducirás suposiciones subconscientes sobre lo que esas cosas significan y reducirás tu espacio de diseño.
- Trata de no ejercer presión de grupo. Cuando dices algo como "hicimos eso una vez en un proyecto, y no funcionó", no estás ayudando. Esto es aún menos valioso si nadie estaba allí contigo y, por lo tanto, nadie puede discutir las lecciones aprendidas. Si las lecciones pueden aprovecharse en la ideación, compártelas. Pero lo más probable es que sea anecdótico o incluso incidental respecto de las ideas que se están presentando.

![Ilustración: una figura entusiasmada propone una idea y otras dos la descartan con suposiciones](img/game-design-toolbox/p049.png)

> **Texto de la ilustración:**
> - Título: "Asume menos"
> - Globo (figura de la izquierda, entusiasmada): "…¡y luego hay un mazo de cartas, y usas una espátula para barajarlo!"
> - Globo (figura del centro, escéptica): "A los jugadores no les va a gustar. Les recuerda demasiado a cocinar."
> - Etiqueta: "¡No hagas esto!"
> - Globo (figura de abajo): "Nah… trabajé en un proyecto allá por 1805 que usaba una espátula. No funcionó."

## EMPIEZA DESDE EL CONFLICTO (*START FROM CONFLICT*)

El conflicto es central en la narrativa occidental. El guionista Aaron Sorkin lo resume como intención y obstáculo: "Alguien quiere algo. Algo se interpone en su camino para conseguirlo".

Esta es una gran forma de empezar, en particular teniendo los juegos ya una larga historia de batallas, combates y peleas. El conflicto puro es una materia que todo el mundo reconocerá.

Para plantear un conflicto, primero define algo por lo que valga la pena luchar. Puede ser un MacGuffin mágico de fantasía, secretos militares, el acceso a un lugar remoto, la pareja de baile de graduación más arrebatadora, o comida suficiente para sobrevivir la noche. La gente ha luchado y matado, tanto literal como metafóricamente, por las cosas más raras a lo largo de la historia, y en la ficción rara vez importa qué es en realidad. Un anillo dorado que te vuelve invisible vale unos cuantos ejércitos de muerte y destrucción, si tú dices que los vale.

Todo lo que la mayoría de los jugadores necesitará para subirse a bordo es saber que aquello por lo que luchan es mejor que aquello contra lo que luchan.

A continuación, planteas las facciones. La que tiene la intención y la que es el obstáculo. La otra persona o personas que también quieren a tu pareja de graduación. El ejército enemigo que invade tu hogar. El contraespía que intenta impedir que robes los secretos nacionales.

### Persona contra persona

Un enemigo formidable. Un agente del enemigo. El villano inmediatamente obvio, o el traidor secreto del que no sabes nada cuando comienza el juego.

### Persona contra sí misma

"Soy mi peor enemigo", decimos a veces. Cuando lidias con la depresión, la ansiedad o simplemente intentas batir tu propio récord de velocidad, estás en conflicto contigo mismo.

### Persona contra naturaleza

Ya sea persiguiendo a la odiada ballena blanca o intentando sobrevivir de la tierra con nada más que lo que puedas rebuscar, estás luchando contra la naturaleza.

### Persona contra sociedad

La opresión, la censura, la persecución y todas las otras cosas desagradables que la sociedad ha hecho, hace y probablemente seguirá haciendo, son conflictos de persona contra sociedad.

### Persona contra tecnología

El invento revolucionario que cambió la sociedad y el conflicto que causa. No necesariamente como ludismo antitecnológico, sino como una reflexión sobre nuestra humanidad.

### Persona contra lo sobrenatural

Dios, dioses, magia, demonios, espíritus, hechizos, etc. Pero también la fe, el hado, el destino, el bien contra el mal y otros conflictos espirituales.

![Ilustración: seis viñetas con figuras de palo que ejemplifican cada tipo de conflicto](img/game-design-toolbox/p051.png)

> **Texto de la ilustración:**
> - "Persona contra persona": dos figuras en pose de pelea; globo: "¡Pelea!"
> - "Persona contra sí misma": figura cabizbaja; globo de pensamiento: "Nadie me quiere…"
> - "Persona contra naturaleza": figura escalando; globo de pensamiento: "¡Puedo ver la cima! Si tan solo pudiera llegar antes de la tormenta…"
> - "Persona contra sociedad": figura arrodillada ante un hombre con sombrero de copa; globo: "Por favor, señor…"
> - "Persona contra tecnología": figura golpeando una máquina expendedora (rótulo "Snacky"); globo: "¡Dame mi bebida, máquina estúpida!"
> - "Persona contra lo sobrenatural": figura con los brazos alzados al cielo; globo: "¿¡Acaso no te he servido, gran Cthulhu!?"

## FINGE QUE JUEGAS (*PRETEND TO PLAY*)

Siéntate con un artista de UI, un tester, un buen amigo o alguien más, y simplemente finge que juegas el juego sobre una hoja de papel o una pizarra. Haz las preguntas más difíciles que se te ocurran sobre la marcha y respóndelas espontáneamente. Lleva un registro de cualquier pregunta que no puedas responder, para que puedas dedicarle esfuerzo más adelante.

Si hay un personaje, dibuja una figura de palo o busca una buena imagen para usar. Dale un nombre si no lo tiene, o agenda una reunión para decidir un nombre más tarde. Lo mismo si te topas con un enemigo o alguna otra cosa: simplemente reconoce que hace falta y sigue adelante.

Dibuja tu camino a través de una sesión de juego, haz maquetas de cualquier cosa que te des cuenta de que necesitas, y presiona para obtener respuestas rápidas y naturales a las preguntas que siguen surgiendo. No estás definiendo nada en este punto. Todo este ejercicio existe para que te familiarices mejor con tu diseño de juego, y es de vital importancia que no te atasques en ningún detalle específico.

Sigue adelante y no te empantanes hablando de una sola cosa. Mantén el ritmo y el flujo tan cercanos a las sesiones de juego previstas como sea posible. Toma abundantes notas.

Para un juego grande o complejo, quizá tengas que hacer esto varias veces. Para un juego así, considera cada uno de los pasos de "Dirigir una sesión simulada" y si deberías hacer cada uno de ellos como una sesión simulada aparte. Una para los menús, una para la creación de personajes y una para la exploración del mundo; cada juego grande tiene sus propios requisitos.

### Dirigir una sesión simulada

1. **Lo primero que encuentra el jugador:** la cinemática introductoria, desempacar los componentes del juego o lo que sea que aplique. ¿Cómo se ve, qué incluye y qué pasa antes incluso de que empiece el juego?
2. **El proceso de iniciar tu juego:** preparación del tablero, interacciones con los menús, modos de juego disponibles, si alguna elección la haces tú o la hacen por ti.
3. **El proceso de inicio típico dentro del juego:** cualquier instrucción de *onboarding* o tutorial y cómo se presenta. Reglas de inicio rápido, personalización opcional y ajustes de dificultad; todo lo que aplique.
4. **El bucle de juego o el turno de juego:** este es el verdadero "juego" de tu juego. Fingir que juegas una pelea, un nivel o una ronda completa de turnos. Probablemente deberías repetir este proceso y cambiar algunos de los parámetros que introdujiste, para obtener tanta información como sea posible de la sesión simulada. Distintos enemigos, distintos modos de juego y dificultades variables; lo que aplique.
5. **El proceso de salir del juego:** cualquier cosa que un jugador tenga que hacer para terminar el juego, sin importar si es solo presionar la tecla Escape y responder "Sí" a un aviso que aparece, o guardar todos los componentes en su caja.
6. **Volver al juego después de salir:** normalmente esto empieza desde el punto 1, pero también puede haber formas de hacer más rápida la transición de fuera del juego a dentro del juego. Piénsalas en tu sesión simulada. Quizá una opción "Continuar" desde el menú principal, o una sección en la caja de tu juego que permita guardar el estado del tablero.

![Ilustración: sesión simulada del juego "Lazerdude" dibujada a mano, con seis pasos numerados desde la caja hasta el regreso al juego](img/game-design-toolbox/p053.png)

> **Texto de la ilustración:**
> - 1) "Primer encuentro." — Globo: "¡La caja tiene a Lazerdude y nada más!" (dibujo de una caja con una figura de palo).
> - 2) "Preparación del juego." — Globo: "¡Título a pantalla completa! Hace 'wooooosh' bien fuerte cuando aparece en pantalla!" (logo "LAZERDUDE").
> - 3) "Inicio del juego." — Globos: "Primer nivel, ¡tienes que encontrar tu pistola! ¿Tutorial de movimiento, quizá?" / "¿Algo de saltos? ¿Enemigos que no puedes derrotar?" (figura, signo de interrogación y la etiqueta "¡Pistola!").
> - 4) "Bucles de juego." — Ciclo con flechas: 1) "Disparar láser." → 2) "¡Derrotar enemigos y destruir el nivel!" → 3) "Algo de plataformas." → 4) "¡Conseguir más colores para tu láser!" → vuelve al 1.
> - 5) "Abandono del juego." — Logo "LAZERDUDE" y globo: "Solo un menú rápido dentro del juego. Suspender, no cerrar del todo, ¿verdad?"
> - 6) "Regreso." — Globo: "¡Directo de vuelta al bucle de juego!"

## HAZ REUNIONES ESTRUCTURADAS (*HOLD STRUCTURED MEETINGS*)

Pocas cosas pueden hacer perder el tiempo como las reuniones. Incluso cuando son dos personas discutiendo un sistema de reglas para un juego de rol, las discusiones pueden desviarse y costar tanto tiempo como cordura.

Dado que muchos diseñadores de juegos —sin importar su nivel— son extremadamente apasionados por los detalles más ínfimos de lo que hacen, pueden hacer perder el tiempo a todos de maneras de las que solo los creativos apasionados son capaces. Esto no quiere decir que los demás desarrolladores no sean igual de apasionados. Pero aquí estamos hablando de ideación: el caos de todos contra todos en el que muchos diseñadores de juegos prosperan y que querrían que siguiera para siempre. Ahí radica el sumidero de tiempo.

Una regla general es tener menos reuniones y más específicas, con metas claramente establecidas, planes de acción y agendas escritas de antemano que se moderen de forma efectiva. Esto puede sonar tedioso y burocrático, y si eres un diseñador solo y no un equipo no se aplica a ti, pero se aplica más a menudo de lo que podrías pensar.

Hay uno de esos acrónimos ingeniosos y memorables que puedes usar para asegurarte de que las metas de la reunión sean relevantes, y es SMART:

- **Específica** (*Specific*), para que todos entiendan de qué trata la meta.
- **Medible** (*Measurable*), asegurando que sabremos si tiene éxito o no.
- **Alcanzable** (*Achievable*), ya que de lo contrario es innecesario tener un plan de acción para ella.
- **Relevante** (*Relevant*), preferiblemente para más gente que solo los diseñadores de juegos.
- **Con plazo** (*Timed*), con una fecha límite clara y un proceso de revisión predeterminado, para que no se desvanezca en el fondo ni siga para siempre.

### Antes de la reunión

1. Escribe una meta explícita para la reunión. Algo que necesites decidir, una tarea que necesites asignar, si la cosa debería eliminarse o conservarse, etc. Algo accionable y concreto.
2. Resume los asuntos relacionados con la agenda, punto por punto.
3. Deja espacio para un punto final llamado simplemente "Preguntas". Durante la reunión, empuja cualquier pregunta que surja hacia este punto. Conviértelo en tu cajón de sastre para las cosas que de otro modo retrasarían la toma de decisiones.
4. Antes de que empiece la reunión, informa a todos de la agenda para que puedan prepararse.

### En la reunión

1. Asigna un moderador para mantener el rumbo.
2. Asigna a alguien para tomar notas.
3. Modera con saña. ¿Encaja en este asunto? Adelante, continúa. ¿No encaja, pero sí en otro? Dile a la persona que tome nota pero posponga la conversación. O pasa al asunto relevante de forma natural, anunciando a todos que ahora pasan del punto X al punto Y. Asegúrate de que la conversación se mantenga en curso.
4. Al final de la reunión, revisa la meta de la reunión. Toma la decisión y formula el plan de acción (recuerda SMART). Escríbelo, junto con todas las notas relevantes sobre por qué se tomó de la forma en que se tomó, y asigna a alguien como responsable de la ejecución y del proceso de revisión.

![Ilustración: varias figuras de palo trepando alrededor de una mesa de reuniones mientras cada una habla de algo distinto](img/game-design-toolbox/p055.png)

> **Texto de la ilustración:**
> - Globo (arriba): "Hoy tenemos que agendar la reunión para decidir cuándo agendar la reunión que va después de la otra reunión agendada."
> - Globo: "¿Alguien jugó la última versión? Detesto el color verde, y todavía no hay ninguna tortuga en el segmento de comer tortugas."
> - Globo: "¿Saben lo que pasó anoche? ¡Mi pez dorado empezó a citar a Proust!"
> - Globo: "¿Y la reunión después de esa? ¿Se te olvidó?"
> - Globo: "¿Esta es la reunión de revisión de diseño?"
> - Globo: "¿No podemos simplemente añadir más gatos?"

---

# Capítulo 3 — Exploración (*Exploration*)

Hay incontables maneras de explorar los resultados de la ideación de tu equipo. Son hacer prototipos, cargar datos en hojas de Excel, usar lápices y papel, o imprimir versiones diminutas de todas tus cartas en una sola hoja de papel solo para poder repasarlas todas. Hay muchas herramientas para la exploración, y esta etapa del diseño es donde las usas.

A veces volverás a la ideación después de la exploración, para poder iterar sobre el material en bruto que sale de ella. Otras veces decidirás que la exploración ha sido exitosa o no según cómo se ve y cómo se siente, y pasarás al Compromiso.

Este proceso es lo que puede convertirte, con el tiempo, en un diseñador de juegos de Nivel 2, al hacer que estés más informado sobre tu diseño.

Lo que tiene que salir de la exploración es:

- Validación de qué ideas funcionan y cuáles necesitan más trabajo.
- Material para más ideación, si tienes tiempo de ir y venir.
- Registros de lo que aprendiste en la exploración, para que las lecciones no se pierdan con el tiempo.
- Decisiones sobre qué ideas pueden simplemente descartarse porque no funcionan como se pretendía, y cuáles vale la pena conservar.

## DETECTA EL PASTEL DE SALCHICHAS (*SPOT THE SAUSAGE CAKE*)

Las salchichas son geniales y el pastel es genial, ¡así que el pastel de salchichas tiene que ser aún más genial! Pero la crema batida y el chorizo no se mezclan muy bien, y lo mismo ocurre en el diseño de juegos.

Si estás mezclando A y B, lo que corres el riesgo de hacer es hornear un pastel de salchichas. Muchos juegos brillantes son híbridos de géneros establecidos, pero debes aprender a ver cuándo algo es un diseño híbrido funcional y cuándo es pastel de salchichas.

Una razón por la que terminamos horneando estos pasteles puede ser el compromiso. Si no tenemos un guardián de la visión —alguien responsable del concepto general de nuestro juego—, existe la posibilidad de que empecemos a aceptar las ideas de los demás como una especie de intercambio de favores. Yo apruebo la tuya; tú apruebas la mía.

También puede deberse a que tenemos disciplinas muy distintas y a que lo que nos atrae a nivel creativo varía. Si una persona tiene muchas ganas de diseñar un tablero de juego, entonces tenemos que tener un tablero de juego.

No hay nada inherentemente malo en el pastel de salchichas durante la ideación, pero la exploración es donde hay que detectarlo, y hay que decidir si es plato principal o postre.

### Detectar un pastel de salchichas

- **Redundancia de features:** Tener tanto armas de fuego como hechizos letales que matan enemigos de maneras similares y a un ritmo similar. Este tipo de pastel de salchichas puede tener valor estético, pero rara vez vale la pena para la experiencia de *gameplay*. Si tienes varias *features* disponibles al mismo tiempo que producen el mismo resultado, al menos una de ellas probablemente sea innecesaria.
- **Feature creep:** Esta cosa del tablero está un poco confusa, ¡agreguemos un mazo aparte para ella! Añadir features para resolver problemas muy específicos, o por otras razones espurias, suele ser innecesario. No, no necesita la salchicha.
- **Complacer a los stakeholders:** Al productor le gustan las armas de fuego y al inversor le encanta comprar zapatos, así que nuestro plataformero en tercera persona ahora soportará disparos y personalización de calzado. Features implementadas para complacer a los *stakeholders* (partes interesadas), en lugar de para hacer que el juego sea un mejor juego. A veces tienes que hacerlo para entregar tu juego, pero en el mejor de los mundos tienes la autoridad para decir que no. Solo recuerda que todo el mundo es un diseñador de juegos de Nivel 1, incluidos los stakeholders.
- **Seguir tendencias:** Ayer jugué a este juego genial en el que había una escena espectacular en una selva, ¡así que agreguemos una selva a nuestro juego! Hacer cosas porque otro juego las hace, y no porque ayuden a tu proyecto, rara vez mejorará el diseño de tu juego.
- **Features de vanidad:** Features por el capricho de un solo desarrollador. ¡Va a ser divertido cuando esté terminado, lo prometo! Este tipo de feature es una causa muy común de pasteles de salchichas. Las dejamos quedarse para darles un respiro a nuestros colegas, pero no siempre sirven al juego.

![Ilustración: un pastel con salchichas clavadas, cada una etiquetada con una feature de juego](img/game-design-toolbox/p059.png)

> **Texto de la ilustración:** Título: "¡No hornees pastel de salchichas! Es asqueroso." Un pastel al que se le ha cortado una porción, con salchichas clavadas encima. Etiquetas:
> - Salchicha: "Salchicha de chili de ciencia ficción"
> - Salchicha: "Salchicha de nave espacial"
> - Salchicha: "Salchicha de duelo con espadas al ajo"
> - Porción del pastel: "Dragones de limón furiosos"
> - Cuerpo del pastel: "Exploración cremosa de mundo abierto"
> - Salchicha: "Salchicha vegana de combate en primera persona"
> - Salchicha: "Salchicha picante de crafteo"
> - Base del pastel: "Personalización de vehículos de mazapán"

## HAZ PROTOTIPOS ANALÓGICOS (*MAKE ANALOG PROTOTYPES*)

Brenda Romero e Ian Schreiber escribieron en su libro *Challenges for Game Designers*: "Un pintor mejora haciendo muchas pinturas; los escultores perfeccionan su oficio haciendo esculturas; y los diseñadores de juegos mejoran sus habilidades diseñando muchos juegos".

Con el tiempo de respuesta de incluso el prototipo digital más simple contado en semanas, y con muchos juegos que tardan meses o incluso años en prototiparse correctamente, el diseño de juegos analógicos puede ser una forma más rápida de explorar ideas.

Por supuesto, si toda tu idea es un juego analógico, esto no es solo una herramienta; es todo tu proceso. Para muchos diseñadores de juegos digitales, puede incluso parecer poco intuitivo.

Pero la misma psicología se aplica a los juegos analógicos y a los digitales. Las motivaciones intrínsecas y extrínsecas, y los distintos modelos motivacionales, pueden aplicarse de igual manera a todo tipo de juego. Se aplican las mismas *affordances* (posibilidades de acción). Una carta en un juego digital es lo mismo que en un juego analógico, por ejemplo.

Los juegos analógicos son sistemas al desnudo. Son ideales para probar muchos tipos de mecánicas digitales de una manera informativa. También es mucho más fácil usar a un jugador humano para representar cosas complejas como la toma de decisiones de los enemigos o los sistemas generados procedimentalmente, antes de empezar el proceso de definir y programar esos sistemas.

Al construir un juego analógico que explore una parte o varias partes de tu idea, te informarás sobre tu diseño y descubrirás cosas que funcionan, que no funcionan, o en las que quizá nadie había pensado siquiera.

### Hacer un juego (rápido)

1. Piensa en una sola cosa que quieras verificar o explorar.
2. **Identifica hechos:** Enumera las cosas que ya has determinado como verdaderas sobre tu juego, expresadas de la manera más concisa posible. "Cada jugador juega con un único personaje" es un hecho posible. "Hay diez caballos distintos" es otro.
3. **Identifica a los jugadores:** Inteligencia artificial, oponente simulado, contador, árbitro, o quizá director de juego. Cada jugador puede actuar como simulador de un sistema clave o participar directamente como jugador.
4. **Resume las actividades:** Ahora que sabes quiénes son los jugadores, resume lo que harán en el prototipo y lo que eso representa. Los verbos.
5. **Reúne componentes:** Una vez que sabes lo que harán los jugadores, tienes que averiguar cómo representarlo con componentes.
   a. **Dados:** Tirar, Volver a tirar, Explotar (tirar de nuevo), Ocultar, Sumar/Restar, Tirar igual o menor (<X), Tirar igual o mayor (X+), y Símbolos personalizados.
   b. **Tablas aleatorias, diagramas de flujo u hojas**, para representar generadores, máquinas de estado y elecciones del jugador.
   c. **Cartas:** Barajar, Voltear, Girar, Apilar, Ocultar, Escribir texto, Sacar, Robar (quitar a otro), Robar del mazo, Descartar, y Colocar en cuadrículas o tableaus.
   d. **Tableros o terreno:** Puede ser simplemente un espacio vacío de la mesa, una cuadrícula, un tablero hecho a medida que represente las decisiones del juego, o algo más elaborado.
   e. **Peones o miniaturas:** Si ya tienes algunas esculturas 3D u otro arte, ¡deberías usarlo! Introducir algo de personalidad en un prototipo analógico marca una diferencia mucho mayor de lo que cualquiera está dispuesto a admitir.

![Ilustración: diseño de niveles analógico con trozos de papel recortados que forman un mapa](img/game-design-toolbox/p061.png)

> **Texto de la ilustración:** Título: "¡Diseño de niveles analógico!" Varios trozos de papel dibujados a mano, dispuestos como salas de un nivel conectadas entre sí; tres llevan etiqueta: "Boss" (jefe), "Exit" (salida) y "Start" (inicio). Texto inferior: "Con solo papel, tijeras y un bolígrafo, puedes probar muchos diseños mucho más rápido."

## USA TIMEBOXES (*USE TIMEBOXES*)

Hacer *timeboxing* significa fijar una fecha límite estricta, planificar de antemano qué decisión tomar cuando la alcances, y luego ponerte a trabajar para demostrar el punto que querías demostrar.

Si tienes un arma nueva o una *feature* nueva que quieres probar, acotar en un *timebox* su validez a una hora, un día, una semana o algún otro plazo significa que estás obligado a recortar atajos para llegar a alguna representación del objetivo final.

Cuando se acaba el tiempo, puedes probar la feature y ver si vale la pena seguir adelante, o decidir que no vale el esfuerzo.

Es una excelente manera de dejar que los desarrolladores jueguen con sus ideas sin afectar un cronograma más amplio. También es perfecta para decidir a qué comprometerse antes de comprometerse de verdad.

Donde los timeboxes realmente brillan es con las ideas espontáneas. Es demasiado fácil decir simplemente que no cuando alguien propone una idea interesante. Un timebox significa que puedes decir "mira qué puedes hacer en medio día", y luego evaluar la idea por sus méritos reales una vez pasado ese tiempo. El riesgo del que debes ser consciente es que el timebox sea demasiado pequeño, lo que lo condenará al fracaso y puede causar cierta frustración.

Para proyectos más informales, donde el tiempo no está tan atado al dinero, el timeboxing sigue siendo muy útil, porque es demasiado fácil quedarse atascado en una pequeña parte del juego cuando hay muchas cosas que cerrar antes de seguir adelante.

Si tienes un problema difícil de diseño de juegos que resolver, establece un timebox y, una vez que lo alcances, la solución o bien se descarta o bien puede verificarse como un camino viable.

### Timeboxing

1. Fija un objetivo, como una afirmación. "Un enemigo que corre mucho más rápido."
2. Fija una fecha límite estricta. "Mañana a la hora del almuerzo."
3. Asigna a una persona responsable. "Programador A."
4. Decide qué hacer si el timebox no tiene éxito. "Descartar la idea de enemigos más rápidos." Recuerda anotarlo como decisión, hecho o de alguna otra forma, para que en el futuro no vuelvas sobre el tema por haberlo olvidado.
5. Decide qué hacer si el timebox tiene éxito. "Programar el enemigo rápido en un sprint formal."

### El tamaño de un timebox debe…

- Ser menor a una semana, preferiblemente menor a un día.
- Caber dentro del cronograma y las responsabilidades actuales de la persona elegida sin generar horas extra adicionales.
- No dejar lugar a ambigüedades. Debe ser una fecha límite concreta.

![Ilustración: calendario semanal de enero con dos flechas que marcan el inicio y el fin de un timebox](img/game-design-toolbox/p063.png)

> **Texto de la ilustración:** Título: "Timeboxing". Una hoja de calendario titulada "Enero" con las columnas "Lun", "Mar", "Mié", "Jue", "Vie". Una flecha apunta al miércoles con la etiqueta: "'Ataque de salto del enemigo', ¡empieza el timebox!" Otra flecha apunta al viernes con la etiqueta: "'Ataque de salto del enemigo', termina el timebox. El líder evalúa."

## DISEÑA EN CAPAS (*DESIGN IN LAYERS*)

La exploración requiere iteración rápida. Tienes que poder aislar las partes en las que estás trabajando, para no abrumarte. Quizá jugar sin las cartas durante algunas sesiones, y luego volver a ponerlas. Retocar algo aquí, cambiar algo allá. Ver qué pasa con distintas partes del juego cuando tienen que funcionar aisladas.

Si este proceso se ve constantemente interrumpido por problemas prácticos, como un nivel que se cuelga o un tablero que hay que volver a imprimir, cuesta un tiempo valioso que debería usarse para más exploración.

Una solución es separar conscientemente el diseño en capas distintas. Una "capa", en este caso, es una parte de tu juego que no depende de otras partes.

En un juego de rol de mesa, por ejemplo, suele haber reglas de resolución de tareas que ofrecen maneras de saber cuándo los personajes tienen éxito en lo que intentan hacer. Estas reglas pueden probarse y testearse por separado de las demás reglas, de las ilustraciones, de la posible construcción del mundo y de otros aspectos del juego. Esto convierte a la "resolución de tareas" en una especie de capa de diseño para ese tipo de juego.

Qué capas puedes probar de forma aislada variará, pero es bueno hacerlo activamente, y en la exploración digital es absolutamente vital que no te quedes atrapado peleando con tu motor de juego o ahogándote en reimpresiones del tablero cuando lo que realmente necesitas hacer es explorar el diseño del juego.

### Capas de ejemplo

- **Entrada (input):** cómo el jugador interactúa con el juego. Manejo de entrada digital, o componentes físicos.
- **Datos:** cantidad de cartas, salud, tamaño de la mano, velocidad de movimiento, archivos de guardado, opciones de configuración, etc. Todo lo que necesita especificarse puede ajustarse por separado de todo lo demás.
- **Generación (spawning):** cómo las cosas entran y salen del juego, incluyendo la aparición de enemigos, cartas, objetivos y mucho más. La carga de niveles, la generación procedimental y un sinfín de otras técnicas pueden ajustarse en esta capa.
- **Suavizado (smoothing):** cómo se siente jugar, y cómo se manejan las transiciones. El *easing*, el mezclado de fotogramas y la separación de fases son versiones de suavizado.
- **Visuales:** cómo se representan todas las demás cosas, incluyendo efectos visuales, sonido, música, modelos, ilustraciones, etc.
- **Regiones:** cómo divides el juego en bloques, física o conceptualmente. Puede ser un nivel o parte de un nivel en un juego 3D, o un tablero o una zona específica del tablero en un juego de mesa.

![Ilustración: lista de capas de un juego con iconos de ojo que indican cuáles están visibles y cuáles ocultas](img/game-design-toolbox/p065.png)

> **Texto de la ilustración:** Globo de diálogo: "Hmm… quiero probar esta nueva forma de generar enemigos…". Debajo, una lista tipo panel de capas, cada fila con un icono a la izquierda:
> - Ojo abierto (visible): "Entrada del jugador"
> - Ojo abierto (visible): "Movimiento del jugador"
> - Ojo abierto (visible): "Generación de enemigos"
> - Ojo cerrado (oculta): "Combate"
> - Ojo cerrado (oculta): "Efectos de sangre"
> - Ojo cerrado (oculta): "Victoria y derrota"
>
> Texto inferior: "¡Ayuda mirar tu juego en 'capas', y asegurarte de que puedes explorar esas capas de forma aislada!"

## HAZ PROTOTIPOS CON DIAGRAMAS DE FLUJO (*MAKE FLOWCHART PROTOTYPES*)

Esta es una forma de prototipado mayormente abstracta, en la que ves cómo encajan las cosas y usas entradas y salidas sistémicas para ver qué tan bien funciona la idea a nivel teórico.

Primero deberías identificar qué se mueve a través del diagrama de flujo y qué recursos estás moviendo por los nodos. Puede ser útil usar componentes físicos como cartas y cubos de madera en esta etapa del prototipado, pero por supuesto no es obligatorio.

Cada nodo del diagrama de flujo debería tener algún tipo de función, y algunos tipos funcionales resultan muy útiles aquí:

- Una **fuente** genera un recurso.
- Un **depósito** almacena un recurso.
- Un **conversor** transforma un recurso en otro.
- Un **sumidero** gasta una cantidad de un recurso.
- Un **decisor** determina qué ocurre según su acceso a los recursos.

Si piensas en el típico sistema de subida de nivel, tiene fuentes que añaden puntos de experiencia (XP) a un depósito. Una vez que ese depósito contiene una cantidad determinada de XP, un decisor lo detecta y envía la XP a un conversor. Ese conversor enviará entonces la XP gastada a un sumidero y aumentará en uno el depósito de nivel.

Estos cinco nodos pueden usarse para representar casi cualquier tipo de sistema de juego en un diagrama de flujo muy simple. Cualquier idea de juego con un intercambio de recursos —salud, oro, dinero, peones, velocidad de movimiento, combustible, etc.— puede beneficiarse de este tipo de exploración.

### Hacer un prototipo con diagrama de flujo

1. Decide qué recursos usará el diagrama de flujo.
   a. Los **recursos finitos** se agotan y, una vez agotados, no hay más. Como tu mazo de cartas, o los minerales de StarCraft.
   b. Los **recursos ascendentes** son mejores cuanto más consigues, como la XP o el dinero.
   c. Los **recursos descendentes** tienen un tope y luego descienden a medida que se gastan. Como la salud o la estamina.
   d. Los **recursos de feature** son cosas que puedes gastar para generar una interacción. Una llave, una granada, o una carta de "Salir de la cárcel" en Monopoly.
   e. Los **recursos temporizados** funcionan con temporizadores o *cooldowns* (tiempos de recarga) y se vuelven temporalmente inaccesibles al usarse, pero luego vuelven a estar disponibles cíclicamente.
   f. Los **recursos meta** son cosas externas al juego. Cuánto tiempo tiene el jugador, cuánto espacio hay en la mesa, etc.
2. Identifica el estado inicial de los recursos y qué tipos de resultados son posibles. Considera también si hay decisiones que tomar en esos puntos:
   a. El recurso se agota por completo.
   b. No hay suficiente recurso.
   c. Hay justo el recurso necesario.
   d. Hay demasiado recurso.
   e. Tope del recurso.
3. Usa los cinco tipos de nodo para dibujar un diagrama de flujo del flujo de recursos: Fuente, Depósito, Conversor, Sumidero y Decisor.

![Ilustración: diagrama de flujo de un sistema de subida de nivel con fuentes, depósito, decisor, conversor y sumidero](img/game-design-toolbox/p067.png)

> **Texto de la ilustración:** Diagrama de flujo, de izquierda a derecha:
> - Tres triángulos etiquetados "+XP (Fuente)", con flechas que apuntan a un círculo "XP (Depósito)".
> - Flecha del depósito a un rombo "Decisor". Encima del decisor, la anotación: "Requisito de XP para subir de nivel = 500 * nivel * (nivel + 1)".
> - Flecha del decisor a un triángulo "Conversor".
> - Del conversor, una flecha hacia arriba a un triángulo invertido "−XP (Sumidero)" y una flecha hacia abajo a un círculo "Nivel (Depósito)".

## HAZ JUEGO DE ROL CON TU DISEÑO (*ROLE PLAY YOUR DESIGN*)

Si tu juego tiene personajes o facciones de cualquier tipo, interpretarlos en un juego de rol —a ellos y/o al mundo en el que vive el avatar— hace posible explorar la moral, la ética, la motivación, las agendas de las facciones y una larga lista de otras cosas sobre el mundo de tu juego.

Los juegos de rol de mesa pueden verse como una especie de conversaciones formalizadas. Dices lo que haces y generas resultados que llevan la conversación en distintas direcciones. A veces generas resultados adicionales usando el azar u otras mecánicas de *gameplay*, pero esto no es estrictamente necesario. Es un juego de fantasía improvisado con reglas de juego añadidas para darle contexto adicional. Las reglas del juego pueden usarse para simular la creación del mundo o acciones individuales dentro de él.

Usar esto como herramienta de diseño de juegos requiere un proceso de creación de personajes, aunque solo sea para representar a los posibles avatares o facciones y sus motivaciones. También requiere reglas, ya sea para determinar qué puedes o no puedes hacer, o para añadir la posibilidad de representar explícitamente las *features* de tu juego, como armas, equipo, puntos de experiencia, edificios y distancias; lo que sea que tu juego necesite.

Una ventaja adicional de hacer este trabajo es que tendrás listo un generador de personajes para poblar tu mundo con más individuos más adelante, si los necesitas.

La creación de personajes puede partir de la técnica de entrevista de las 5W + H: Quién, Qué, Dónde, Por qué, Cuándo y Cómo (*Who, What, Where, Why, When, How*). (Volveremos sobre esto más adelante, en el contexto de contar historias.) La intención es cubrir toda la extensión de una historia, ya sea como periodista que escribe una nota o como agente de policía que interroga a un sospechoso.

### Personajes

1. **Quiénes** son los personajes, para quién y con quién trabajan, y cómo encajan en el mundo.
2. **Qué** hacen los personajes. Enumera las actividades en las que quieres que participen.
3. **Dónde** ocurre.
4. **Por qué** los personajes hacen lo que hacen.
5. **Cuándo** ocurre: pasado, presente, futuro, o algún período de tiempo específico.
6. **Cómo**, para un juego, significa los verbos: las entradas y las intenciones de tus jugadores.

### Reglas

1. **Situaciones:** qué tipos de situaciones quieres que tu juego retrate. ¿Son atracos, peleas, competencias, planificación de proyectos, supervivencia, etc.?
2. **Habilidades:** esto prepara el escenario para saber a quién estás interpretando:
   a. ¿Qué pueden hacer, y qué no pueden hacer?
   b. ¿Qué les resulta particularmente difícil de hacer, aunque siga siendo posible, y qué les resulta especialmente fácil pero sigue siendo relevante?
3. **Conflicto:** teniendo en cuenta las situaciones y las habilidades, quién intenta detenerte, por qué y por qué medios. Escribe reglas para los conflictos más importantes; no simules, solo representa.
4. **Escenario:** dónde estás ahora mismo y qué estás haciendo. Elige opciones del Dónde y el Qué que escribiste sobre los personajes, y adelante.

### Jugar

1. Describe lo que hace tu personaje, siendo fiel a ese personaje.
2. Si te piden que hables, habla como hablaría tu personaje.

![Ilustración: tablas de dado de seis caras y globos de diálogo para improvisar un juego de rol sobre un diseño llamado Bullet Wizard](img/game-design-toolbox/p069.png)

> **Texto de la ilustración:** Título central: "¡Esto es suficiente para 'rolear' un diseño!"
> - Globo: "¡Este juego es BULLET WIZARD! ¡Piénsalo como un cruce entre John Wick y Harry Potter!"
> - Globo: "Necesitamos saber quién eres."
> - Tabla "¿Quién? Tira 1d6": 1. Una persona cualquiera de la calle. 2. Ex fuerzas especiales. 3. Criado en secreto por magos. 4. El clásico elegido. 5. Agente doble para el enemigo. 6. Vendedor de hot dogs iluminado.
> - Globo: "¡Necesitamos conocer tu motivación!"
> - Tabla "¿Por qué? Tira 1d6": 1. Mataron a tu perro. 2. Una profecía. 3. Para derrotar a la oscuridad. 4. Dinero, poder; lo de siempre. 5. Es tu trabajo. 6. Antiguo legado familiar.
> - Globo: "Necesitamos algunas reglas simples."
> - Tabla "Disparar a cosas": 1–3: Fallo. 4–5: Supresión. 6: Muerte.
> - Tabla "Hechizos": 1. Invisibilidad parcial. 2. Teletransporte de corto alcance. 3. Leer pensamientos superficiales. 4. Resucitar a los muertos. 5. Curación vistosa. 6. Superarmadura mágica.
> - Globo: "¡Ah! ¡También necesitamos algo que hacer!"
> - Tabla "¿Qué?": 1. Infiltrarse en… 2. Asaltar… 3. Vigilar… 4. Defender… 5. Sabotear… 6. Hacer una redada en…
> - Tabla "¿Dónde?": 1. …un sótano industrial. 2. …una mansión abandonada. 3. …un complejo de cuevas. 4. …un desguace clandestino. 5. …una guarida secreta. 6. …un almacén portuario.

## AÑADE INCERTIDUMBRE (*ADD UNCERTAINTY*)

El diseñador de juegos Greg Costikyan sostiene en la introducción de su libro *Uncertainty in Games* que "los juegos requieren incertidumbre para mantener nuestro interés", y a continuación identifica varios tipos distintos de incertidumbre y cómo se relacionan con el diseño de distintos tipos de juegos.

Cuando empiezas a explorar tus ideas, pensar en qué tipos de incertidumbre quieres incluir es una excelente manera de recordarte la perspectiva del jugador. Si quieres que el jugador tenga una experiencia narrativa increíble, todo gira en torno a la Anticipación narrativa, y debes considerar cómo lograrla a través de tu diseño.

De manera similar, un juego competitivo puede necesitar suficiente Incertidumbre de desempeño como para requerir práctica y permitir estrategias e interacciones, además de añadir Impredecibilidad del jugador por encima de eso.

Si descubres que tu juego es demasiado predecible o no mantiene el interés de la gente durante suficiente tiempo, puedes considerar los tipos de incertidumbre y si podrías añadir más de ellos.

### Tipos de incertidumbre

- **Incertidumbre de desempeño:** ¿puedo lograr el salto, o terminar la partida?
- **Incertidumbre del solucionador:** ¿puedo descubrir cómo abrir la puerta o resolver el puzle?
- **Impredecibilidad del jugador:** ¿mi oponente tiene una mano de cartas mejor que la mía?
- **Aleatoriedad:** ¿superaré la tirada de d20 de 15+, y qué pasa si no lo hago?
- **Complejidad analítica:** si los A odian a los B, y mis C intentan propagar la plaga, y los D están en plena revuelta, y los E, los F, y así sucesivamente.
- **Información oculta:** ¿hay zombis abajo en el sótano y, de ser así, cuántos, y vale la pena el peligro por el botín que hay allí?
- **Anticipación narrativa:** ¿qué pasa cuando abrimos la caja de Pandora?
- **Anticipación del desarrollo:** este juego está empezando a verse increíble, ¡no veo la hora de tenerlo en mis manos!
- **Incertidumbre de calendario:** ¿podré jugar de nuevo cuando se me recarguen las vidas, o debería comprar más ahora?
- **Incertidumbre de percepción:** ¿puedo interpretar la información correctamente y no ser alcanzado por uno de los 10.000 proyectiles que cruzan la pantalla?

![Ilustración: un personaje pensativo rodeado de nubes de pensamiento con distintas incertidumbres](img/game-design-toolbox/p071.png)

> **Texto de la ilustración:** Título: "Añadir incertidumbre". Un personaje con cara de duda piensa en una cadena de nubes de pensamiento:
> - "¿Puedo confiar en Bruto, mi buen amigo?" (junto a un personaje sonriente que esconde un cuchillo a la espalda)
> - "¿Robaré la carta que necesito?" (junto a un abanico de cartas)
> - "¿Sacaré ojos de serpiente?" (junto a dos dados)
> - "Hmmm…"
> - "¿Puedo lograr suficientes acciones por minuto para matar a los zerg?" (junto a dos criaturas alienígenas)

## ¡HAZLO MÁGICO! (*MAGIC IT!*)

En el juego de cartas coleccionables Magic: The Gathering, nunca ves una carta que sea simplemente un "oso": será un "Oso marcado por dragones", o un "Oso garrafilada", o alguna otra combinación que suene más amenazante e inspiradora, o que evoque imágenes del mundo en el que transcurre el juego.

Toma el sujeto ("oso") y luego le añade adjetivos relevantes ("marcado por dragones") diseñados para reforzar de qué trata la carta y para consolidar dónde encaja en el mundo del juego. La diferencia es mayormente cosmética, pero permite que la cosa sea más memorable y mucho más atmosférica simplemente mediante una cuidadosa selección de palabras.

Siempre que le pongas nombre a algo, ya sea un pilar de diseño, el título de una sección, un objeto del juego u otra expresión de tu juego dirigida al jugador, puedes sacarle mucho provecho a esta misma técnica. ¡Puedes hacerlo mágico!

Para facilitarlo, identifica una serie de adjetivos, lo más personalizados y relevantes posible, y ponlos en una lista. Luego escribe las cosas que necesitas transmitir usando palabras sueltas. Es aún mejor si estableces reglas específicas sobre cuándo usar ciertos adjetivos. Por ejemplo, uno puede estar ligado a una facción de la narrativa, o a las interacciones de un jugador específico.

Por último, repasa las cosas que quieres transmitir y añádeles algunos de esos adjetivos para descubrir qué hace que las cosas resulten más impactantes.

Asegúrate de no volver a llamar a algo simplemente "oso" nunca más.

### Hacer mágico algo

1. Saca los sustantivos u otros textos dirigidos al jugador que necesiten un poco de sazón. También puede ser texto dirigido al desarrollador, por ejemplo los nombres de tus pilares de diseño, pero es más relevante para las cosas que más adelante estarán de cara al jugador.
2. Reúne una lista de adjetivos, potencialmente categorizados según lo que se pretende que comuniquen. Ayuda escribir reglas para estas categorías. Por ejemplo: "usa un sinónimo de oscuridad al describir a un hada malvada".
3. Al crear tus adjetivos, no temas unir palabras como lo hacen muchas lenguas europeas. Elimina los guiones. "Nightborn" o "Blacknight" pueden resultar más impactantes y únicos que night-born o black-night. Pero mantener el guion también puede hacerse para emular ciertos estilos de escritura.
4. Añade los adjetivos. Haz varias tomas de la misma cosa, con los mismos objetos. "Hada Nightborn." "Hada Blacknight." Para un pilar de juego, llamar a algo "Combate de ritmo rápido" no dice nada, ¡pero "Muertes en dos segundos" sí!

![Ilustración: dos cartas de criatura idénticas, una llamada simplemente "Dragón" y otra con un nombre "magificado"](img/game-design-toolbox/p073.png)

> **Texto de la ilustración:** Dos cartas de criatura con el mismo dibujo de un dragón, el mismo coste (4) y las mismas estadísticas:
> - Carta 1: Nombre "Dragón". Tipo: "Criatura". Habilidad: "Volar". Fuerza/resistencia: "5/5". Globo de diálogo: "¿Solo una palabra a secas? ¡Aburrido!"
> - Carta 2: Nombre "Dragón asesino de Cuevacráneo" (*Skullcave Murder-Dragon*). Tipo: "Criatura". Habilidad: "Volar". Fuerza/resistencia: "5/5". Globo de diálogo: "¿Después de hacerlo mágico? ¡Genial!"
>
> Abajo, un personaje sonriente con los brazos abiertos.

## PIENSA EN LOS DATOS (*THINK OF THE DATA*)

Mientras exploras, a veces es útil recordarte que no debes pensar como un usuario. Por más poco intuitivo que le resulte al diseñador de juegos moderno, consciente de la experiencia de usuario.

El objetivo de esta herramienta es ayudar a maximizar la cantidad de iteraciones que tienes tiempo de hacer durante la exploración, y tiene dos componentes específicos que provienen ambos del desarrollo de software en general: hacer las cosas orientadas a objetos y guiadas por datos.

Orientado a objetos puede entenderse como que las cosas se definen por su comportamiento aislado. Un objeto describe una única pieza lógica de tu juego. Piensa en los personajes, por ejemplo. En tu juego, quizá los personajes se mueven y disparan. Personaje es un objeto y contiene cosas como el nombre del personaje en cuestión y quizá a qué equipo pertenece. Movedor podría ser otro objeto y lo único que hace es mover a quien lo use. Arma es otro objeto y lleva la cuenta de todos los asuntos relacionados con armas de tu juego. Como ejemplo, un soldado enemigo ES un personaje, y TIENE un rifle y también TIENE un movedor.

Todo eso está muy bien: ahora podemos definir el comportamiento de las entidades de nuestro juego mediante relaciones "tiene-un" y "es-un". Pero también necesitan datos.

El instinto suele ser escribir un número directamente en el código, y luego ir y venir entre simulación e implementación. Pero lo mejor que puedes hacer es desacoplar los números de la lógica en la mayor medida posible. Haz que los objetos lógicos operen como lo hacen, y luego conéctales los datos como recursos externos.

Esto también vale para los juegos analógicos, por ejemplo haciendo que las cartas hagan referencia a variables externas en lugar de a datos fijos.

### Orientado a objetos

**Es-un:** enemigo es-un personaje, bicicleta es-un movedor, y carta es-un arma. De qué tipo de objeto estamos hablando, y todo su comportamiento asociado.

**Tiene-un:** enemigo tiene-un arma, bicicleta tiene-un ciclista, y carta tiene-una barra de estadísticas. De qué tipo de componente estamos hablando, y cómo afecta por tanto al objeto que lo posee.

### Guiado por datos

**Base (baseline):** Un número base se conecta en todos los lugares donde es relevante y luego puede ajustarse globalmente para alterar cómo se comporta el juego. Un ejemplo es un daño base que usan todos los enemigos, que puede fijarse más alto para dificultades mayores. Otro ejemplo es el nivel en una economía de experiencia, que puede conectarse a cualquier cosa: velocidad de movimiento, altura de salto, alcance de visión, cantidad global de cartas, etc.

**Atributos:** Atributos específicos de un objeto, como velocidad de movimiento, daño cuerpo a cuerpo, duración de la partida, tamaño de la mano de cartas, etc. Recuerda que los objetos no son solo entidades del mundo del juego. Los modos de juego, los objetivos, las casillas del tablero, los botones clicables de los menús, etc., también son objetos.

**Modificadores:** Modificadores del mundo o del contexto. Cosas como la disminución de la fricción cuando te mueves sobre hielo, el +1 que deberías sumar al daño y a la probabilidad de impacto por tu espada larga mágica, o una carta sobre la mesa que dice que todos roban una carta extra cada turno. Cualquier dato que modifique un atributo o un número base es un modificador.

**Funciones:** Piensa en términos de base, atributos y modificadores; luego combínalos. Que sumes, dividas, multipliques o emplees trigonometría compleja depende de tu diseño.

![Ilustración: tabla con ejemplos de base, atributos, modificadores y funciones](img/game-design-toolbox/p075.png)

> **Texto de la ilustración:** Tabla de cuatro columnas: "Base", "Atributos", "Modificadores", "Funciones".
> - Fila 1: Base: "Daño de ataque". Atributos: "Atributo de fuerza (daño extra)". Modificadores: "Sensibilidad al fuego (daño extra)". Funciones: "Base + fuerza + fuego − armadura = daño total".
> - Fila 2: Base: "Altura de salto". Atributos: "Altura de salto del jugador". Modificadores: "Botas de supersalto". Funciones: "Altura de salto + altura de salto del jugador + (botas de supersalto) = altura de salto total".
> - Fila 3: Base: "Cantidad máxima de cartas". Atributos: "Tamaño de la mano del jugador". Modificadores: "Habilidad de robar una carta extra". Funciones: "Turnos por partida = cantidad máxima de cartas / cartas robadas por turno".
>
> Globo de diálogo de un personaje sonriente: "Si puedes entrar y ajustar los números individualmente —base, atributos, modificadores—, ¡esto hace mucho más fácil explorar tu diseño!"

## AÑADE ASPEREZAS (*ADD ROUGH EDGES*)

Imagina jugar a un juego que consiste en ir de un lugar a otro, y que no pase nada por el camino. Emprendes tu viaje, caminas un poco y corres un poco, y de repente estás en tu meta y ves los créditos finales.

A veces, mientras exploras tu juego, puede ocurrir que simplemente lo encuentres un poco insulso, igual que un viaje ficticio sin contratiempos. Cuando eso pase, hay algunas asperezas que puedes añadir a la experiencia actualmente pulida. Una aspereza, en este contexto, es cualquier tipo de costo.

El costo más común es el tiempo, ya que tener que rehacer cosas o volver a recorrer caminos es universalmente molesto y funciona casi sin importar qué juego estés haciendo. Desde obligarte a saltar un turno en un juego de mesa (algo que nunca deberías hacer) hasta hacerte volver a tu cadáver como fantasma tras un altercado fatal con un goblin furioso.

Los costos de tiempo pueden reemplazarse por otros costos. Cualquier recurso sirve: desde oro hasta estamina, pasando por vidas extra o descartar cartas. Lo importante es que el costo tenga sentido intuitivo y se convierta en algo que el jugador pueda planificar y manejar de maneras interesantes.

### Añadir asperezas

- **No expliques:** algunas *features* del juego pueden volverse más poderosas si no hablas de ellas y dejas que el jugador las descubra. Las soluciones de los puzles suelen entrar aquí, pero también las sinergias que aparecen orgánicamente a partir de tus features; lo que a los diseñadores les gusta llamar features emergentes.
- **Añade desafío:** haz que las cosas que el jugador hace a menudo sean difíciles de hacer. El sendero es resbaladizo o está lleno de cactus, un trol furioso custodia la puerta, o el anochecer lo deja todo a oscuras.
- **Cierra la puerta con llave:** haz que el camino más obvio para avanzar sea inaccesible, de modo que el jugador se vea obligado a buscar otro camino o a abrirse paso a la fuerza.
- **Quita cosas:** una vez que el jugador se siente demasiado cómodo con una feature u opción, elimínala o hazla ineficaz. Quizá el salto normal ya no es lo bastante alto, o el dado de cuatro caras no puede sacar el seis o más que se necesita.
- **Añade trampas:** las trampas pueden ser obvias, como fosos gigantes con pinchos en el fondo, o pueden ser más retorcidas, como elegir la poción de salud entre tres frascos rojos distintos. Una vez que los jugadores se dan cuenta de que puede haber trampas, serán más cautelosos.
- **Añade tesoros:** también puedes esparcir recompensas en lugar de trampas. Pueden ser coleccionables, aumentos de algún recurso, fragmentos de *lore*, o simplemente cosas divertidas por las que sentirse astuto al encontrarlas. Sean lo que sean, añaden un costo de tiempo para buscarlas.
- **Mira, no toques:** muestra cosas geniales con las que no dejas interactuar al jugador. Tras unos barrotes, lejos en un mapa, o restringidas por la progresión del juego.
- **Toca, no pruebes:** deja que el jugador interactúe con las cosas, pero limita su utilidad. Un arma genial sin munición. Una ranura de mejora, pero ninguna mejora que poner en ella.

![Ilustración: cuatro caminos de "aquí" a "allá", uno despejado y tres con obstáculos](img/game-design-toolbox/p077.png)

> **Texto de la ilustración:** Título: "¡Añade asperezas! Haz que cueste algo ir de 'aquí' a 'allá'." Cuatro filas, cada una con un personaje caminando a la izquierda ("Aquí") por un camino punteado hasta una X a la derecha ("Allá"):
> - Fila 1: camino despejado.
> - Fila 2: en medio del camino, una cueva con dientes y un cartel: "Cueva asesina de muerte instantánea".
> - Fila 3: en medio del camino, un personaje parapetado con un arma y el texto: "¡Bazucas sorpresa!"
> - Fila 4: en medio del camino, un cartel garabateado con el texto: "¡Puzles complicados!"

## ENTRADA, SALIDA, GRITO (*INPUT, OUTPUT, SCREAM*)

En lo más profundo de los cimientos de tu juego tienes lo que Michael Sellers llama la información "específica de hoja de cálculo" en su libro *Advanced Game Design: A Systems Approach*. Salud 100. Daño 15.

Pero también puedes tener un sistema de salud que se ocupe de cosas como la regeneración, distintos tipos de daño, armadura que absorbe parte del daño entrante, etc. Este sistema de salud es ahora parte de una red de entradas y salidas, con recursos y datos compartidos entre ellas. Ahora solo añade *feedback* para el jugador y tu sistema está listo para unirse a todos los demás sistemas que hacen que ocurra un juego interesante.

**Las entradas** son las cosas que conectas al sistema en cuestión. Salud 100 podría ser la entrada de salud base, pero cualquier dato, recurso o incluso interacción del jugador de la que la salud necesite enterarse es una entrada de algún tipo.

**Las salidas** son entonces lo que se genera como resultado de toda esa entrada. Cuando se envía algo de daño al sistema de salud, lo que sale es la salud actual o quizá el porcentaje de salud actual como salida, para que otros sistemas puedan usarla; digamos, el sistema de muerte.

**El feedback** no siempre es obligatorio, pero en algún momento tienes que comunicar lo que un sistema está haciendo realmente, o lo más probable es que el jugador no se dé cuenta de que está ocurriendo y piense que es un bug. El sistema de salud tendrá que avisar al jugador cuando lo hieren y en ciertos puntos del camino antes de que muera. Quizá a la mitad de la salud la barra verde se pone roja, y al 10% parpadea. Todo eso es feedback.

### Diseñar un sistema

1. **Entradas:** todas las cosas que el sistema necesita. Recursos, datos, o lo que sea.
2. **Salidas:** el resultado de lo que sea que el sistema haga. Pueden ser entradas manipuladas, comportamiento del juego, u otra cosa.
3. **Feedback:** eventos que comunican directamente al jugador lo que el sistema está haciendo.

### Atracción (A + A = Disparador)

Cuando dos cosas se encuentran, disparan un efecto. En Thief: The Dark Project y otros juegos del Dark Engine, este estilo de comportamiento se llamaba Act/React (acción/reacción) o Stim/Response (estímulo/respuesta).

Cuando una antorcha encendida toca algo inflamable (FireStim + FireResponse), por ejemplo, o cuando una flecha de agua golpea una antorcha encendida (WaterStim + WaterResponse), el objeto que responde tendrá un comportamiento predefinido (salida) basado en el estímulo en cuestión (entrada), y quizá eso signifique que se prende fuego (feedback).

### Repulsión (A − A = Disparador)

Cuando dos rasgos se desconectan, ocurre un efecto. Se quita un peso de un botón. El comportamiento puede definirse según los rasgos que lleve un objeto, igual que en la atracción, pero el disparador está invertido.

### Abstracción (A <-> B <-> A)

La salida y la entrada no interactúan directamente, sino a través de un intermediario abstracto. La cosa que arde genera una llama, y la llama enciende la cosa inflamable. La cosa inflamable no necesita saber nada de la antorcha que lleva la llama.

![Ilustración: una antorcha encendida como sistema, con sus entradas, salidas y feedback](img/game-design-toolbox/p079.png)

> **Texto de la ilustración:** Título: "¡Un sistema de antorcha!" En el centro, una antorcha encendida.
> - Arriba a la izquierda, "Algunas entradas", con dos globos que apuntan con una flecha a la antorcha: "Acciones del jugador, como recogerla." / "Acción 'fuego', que la enciende si no está ardiendo ya."
> - Abajo a la derecha, "Algunas salidas", con una flecha desde la antorcha hacia tres globos: "Luz parpadeante" / "Acción 'fuego' que puede prender fuego a cosas inflamables." / "Animación del jugador".
> - Abajo a la izquierda, "Algo de feedback", con una flecha desde la antorcha hacia dos globos: "Efectos de partículas" / "Sonidos de crepitar".

## DESAFÍA EL JUEGO CON LA TRAMA (*CHALLENGE PLAY WITH PLOT*)

No todo el mundo piensa en la experiencia de juego como una historia, y a algunos juegos, de entrada, no les importa demasiado la historia. Pero si escuchas a jugadores que han jugado a un juego contarlo, a menudo sale de todos modos como una especie de historia.

Yo hice esto, tiré los dados y robé la carta, luego tú hiciste aquello, y pasaron estas cosas, y ahora estás enojado porque alguien ya compró la calle en la que estás.

Esto es increíblemente útil, porque en los espacios entre cómo un jugador cuenta esta historia puedes encontrar maneras de seguir explorando el diseño de tu juego. También puede decirte algo sobre lo que los jugadores encuentran interesante, que no tiene por qué ser lo mismo que tú encuentras interesante.

Cuando analices algo de esta manera, enumera cómo describe un jugador su experiencia evento por evento. Un evento, en este caso, es cada interacción individual que realiza el jugador más cada instancia de salida del juego que esta genera. Encadénalos y tendrás una descripción de la "historia del jugador" que un jugador en particular experimentó. Pero también tienes la oportunidad de meterte en cada punto donde dos eventos se cruzan, y poner ahí un giro para ver si puedes hacer las cosas más interesantes.

### Convertir el juego en trama: Entonces…

La manera más lineal de construir hacia adelante es añadir "entonces" y hacer avanzar las cosas. Puede parecer obvio, pero puede ser realmente útil pensar en qué pasa a continuación. Especialmente si los jugadores indican que lo que están haciendo es un poco repetitivo.

Jugué una carta nueva, y entonces mi oponente jugó su carta.

Disparé el arma muchas veces, y entonces el enemigo me devolvió el fuego.

### Convertir el juego en trama: Pero…

Justo después de un evento que hayas identificado, puedes insertar la palabra "pero" y usarla para desafiar lo que acaba de ocurrir. Te obliga a idear cambios en la estructura.

Jugué una carta nueva, pero mi oponente jugó otra carta que canceló la carta que acababa de jugar.

Disparé el arma muchas veces, pero entonces me quedé sin munición.

### Convertir el juego en trama: Por lo tanto…

Una vez que el "pero" mete un palo en la rueda, estás listo con un "por lo tanto" para llevar las cosas más lejos.

Mi oponente jugó otra carta que canceló mi carta; por lo tanto, me vi obligado a terminar mi turno.

Mi arma se quedó sin munición; por lo tanto, cambié al cuchillo.

![Ilustración: tira cómica en tres pasos —entonces, pero, por lo tanto— de un soldado que dispara, cae en una trampa y huye](img/game-design-toolbox/p081.png)

> **Texto de la ilustración:** Viñetas en secuencia:
> - Un soldado apunta con un fusil. Globo: "¡Empiezo a disparar!"
> - Título: "Entonces…" Un enemigo tras un parapeto agita una bandera blanca. Globo: "¡El cobarde enemigo se rindió!"
> - Título: "Pero…" El soldado avanza confiado con el fusil al hombro mientras el enemigo saca un arma desde el parapeto. Globo de explosión: "¡Era una trampa!"
> - Título: "Por lo tanto…" El soldado corre huyendo mientras el enemigo lo persigue. Globo: "Huí valientemente…"

## ARMA GRUPOS DE TRABAJO (*BUILD TASK FORCES*)

Una de las trampas más comunes cuando exploras parte de un juego —o la idea completa de un juego— es que terminas desperdiciando la mayor parte de tu tiempo en otras cosas. La respuesta simple de esta herramienta es no desperdiciar tiempo.

Si estás explorando una mecánica de colocación de trabajadores, no pierdas tiempo diseñando los visuales del tablero. Si estás haciendo un sistema de combate, no pierdas tiempo peleando con los complejos sistemas de animación o consiguiendo que los efectos visuales queden bien; simplemente pon fotogramas provisionales para poder concentrarte en el sistema de combate y no en forcejear con el motor del juego.

Una manera práctica de hacerlo es armar un grupo de trabajo (*task force*) interdisciplinario. Este grupo debería incluir desarrolladores con experiencia valiosa, tanto para tener opiniones como para hacer que las cosas ocurran. Es un grupo de trabajo, no un *think tank*.

Este grupo se forma en torno a un concepto específico que necesita probarse, y la naturaleza mixta de la experiencia significa que la demora entre la discusión y la acción será tan corta como sea posible.

La responsabilidad principal del grupo de trabajo es asegurarse de que te mantengas concentrado en el objetivo singular hacia el que estás trabajando.

Si eres un desarrollador solitario o un equipo pequeño, puedes imitar esto evitando ponerte sombreros de más y actuando solo como el artista, o solo como el diseñador de juegos. Será un grupo de trabajo de una sola persona, claro, pero muchos grandes juegos se han construido así.

### Armar un grupo de trabajo

1. Define el área de enfoque del grupo de trabajo. Disparos, puntuación, *balance* del fusil de asalto, redacción de descripciones de cartas, o sistema de botín; puede ser cualquier cosa, pero debe ser específica.
2. Reúne un grupo que incluya a todas las personas cuyas disciplinas se vean afectadas por el área de enfoque. Para los disparos, probablemente necesites un programador, un animador de primera persona, un artista de efectos, y quizá un responsable creativo: un diseñador de juegos de Nivel 3 o 4. Es absolutamente imperativo que el grupo pueda trabajar de forma autónoma con lo que se le ocurra y no tenga que someterse a una toma de decisiones externa.
3. Programa reuniones regulares con este grupo de trabajo —al menos una vez por semana— y quizá incluso reúbicalo físicamente en la oficina, si tienes una oficina.
4. En estas reuniones, fija objetivos iterativos rápidos. Usa *timeboxes* para todos los objetivos y evita discutir demasiado las cosas antes de tener resultados.
5. Evalúa las cosas y fija nuevos objetivos con nuevos timeboxes en cada reunión, avanzando constantemente solo con la tarea específica con la que empezó el grupo de trabajo.

![Ilustración: comparación entre disciplinas aisladas en departamentos y un grupo de trabajo interdisciplinario reunido](img/game-design-toolbox/p083.png)

> **Texto de la ilustración:** Dos escenas:
> - Arriba, título: "Departamentalización: cada disciplina aislada". Tres personas en escritorios separados, cada una con un cartel: "Animador animando", "Artista haciendo arte", "Programador programando".
> - Abajo, título: "Grupo de trabajo: enfoque interdisciplinario". Las tres personas sentadas juntas en escritorios enfrentados; un globo de grito compartido dice: "¡Grupo de trabajo trabajando en grupo!" (*Taskforce taskforcing!*)

---

# Capítulo 4 — Compromiso (*Commitment*)

En algún momento necesitas comprometerte con las cosas que funcionan y abandonar las que no. ¡Aquí es donde lo haces!

En el mejor de los mundos, puedes comprometerte de forma gradual mediante un ir y venir iterativo entre la ideación y la exploración. Pero también puede convertirse en un corte abrupto, cuando ya has acelerado tu proceso de contratación y debes pasar a producción antes de que se acabe el dinero.

Comprometerse con un diseño es extremadamente difícil, y estarás tentado de seguir explorando e incluso ideando después de haberte comprometido. No lo hagas.

El compromiso, en este caso, debe ser real. Una división tajante entre la ideación/exploración y la entrega de un juego terminado.

Aquello con lo que necesitas comprometerte es:

- Una definición operativa de tu juego que todos hayan aprobado: diseñadores, desarrolladores, *stakeholders* y todos los demás.
- De qué trata el juego.
- Qué hacer; qué no hacer.
- Cronogramas de producción y de pruebas.
- Prioridades: Imprescindibles (*Musts*), Necesarios (*Needs*), Deseables (*Shoulds*) y Opcionales (*Wants*).

## CUENTA UNA HISTORIA (*TELL A STORY*)

Algo muy importante cuando llega el momento de comprometerse es explicar tu juego a otras personas. A los *stakeholders*, a las editoras, a tu equipo y a tus hijos; a todo el mundo, una y otra vez.

Como probablemente sabes, a la gente se le nubla la mirada cuando empiezas a extenderte sobre los detalles ingeniosos de tus fabulosas nuevas mecánicas centrales, ya que la jerga del desarrollo de juegos es mucho más densa y difícil de interpretar de lo que quisiéramos admitir.

Pero las personas tienen un sesgo narrativo y responden bien a las historias. Reconócelo y asegúrate de tener buenas respuestas para todas las preguntas implícitas. Cuenta una historia cuando describas tu juego, y no describas el juego. Haz que la descripción sea incidental, casi accidental.

Lo inmediatamente cercano resonará mejor con una audiencia. A algunas personas nunca les interesa lo que ocurre en Fantasilandia, pero puede importarles la lucha financiera personal de un personaje de Fantasilandia. Un empresario querrá saber cuánto puede vender tu juego y un escritor querrá conocer tus inspiraciones literarias.

Luego está la sangre. Sigue siendo preferible si es cercana, para que podamos pensar que nos alegra que no nos haya pasado a nosotros, pero la violencia y sus efectos pueden ser fascinantes por sí mismas. Tampoco tiene que ser sangre literal. Otros riesgos pueden bastar, como deudas, daños, lesiones, etcétera.

### Contar una historia

En entrevistas, interrogatorios y otros contextos en los que quieres obtener el panorama completo de lo sucedido, el "5W + H" es una especie de recordatorio para que no olvides ninguna de las piezas que cuentan una historia completa.

1. **Quién** (*Who*) es el personaje que encarna el jugador, sobre quién trata el juego o en la perspectiva de quién se centrará el juego.
2. **Qué** (*What*) estará haciendo el jugador, o qué está haciendo el álter ego del jugador. Puede expresarse como algo a punto de suceder o como algo que ya está sucediendo. Deja al oyente intrigado y con ganas de más.
3. **Dónde** (*Where*) transcurre el juego. Hagas lo que hagas, no entres en explicaciones largas a menos que la gente te lo pida.
4. **Por qué** (*Why*) se supone que el jugador o su álter ego debe hacer lo que va a hacer. Piensa en motivaciones y metas, y recuerda asegurarte de que valga la pena apoyarlas.
5. **Cuándo** (*When*) transcurre. Puede expresarse como nivel tecnológico, o como un tiempo y un lugar. Puede ser completamente ficticio, pero aun así usar términos como "hace mucho tiempo", "érase una vez" o "en un futuro lejano" para dar un poco de contexto.
6. **Cómo** (*How*) se supone que van a resultar las cosas. Si hay una historia específica que contar, explica un par de momentos clave. Dale al oyente algo por lo que entusiasmarse.

![Ilustración: dos personas presentan el mismo juego; una con jerga técnica y otra contando una historia](img/game-design-toolbox/p087.png)

> **Texto de la ilustración:** dos personajes de palitos conversan. El de la izquierda, con cara de aburrimiento, describe el juego en dos globos de diálogo; el de la derecha, entusiasmado, lo cuenta como una historia en tres globos.
> - Globo 1 (izquierda): "Es un RPG/FPS/RTS táctico, dinámico y de ritmo rápido."
> - Globo 2 (izquierda): "Se inspira en Battlemurder III, publicado en solo 5 copias de lujo a principios de 1984."
> - Globo 3 (derecha): "Es el futuro cercano y la humanidad está al borde del colapso climático."
> - Globo 4 (derecha): "Controlas una organización secreta encargada de resolver este colapso."
> - Globo 5 (derecha): "A veces tendrás que infiltrarte solo en territorio enemigo; otras veces, liderarás pequeñas fuerzas de unidades de élite contra la conspiración extraterrestre."

## CONSTRUYE UN PARQUE DE DIVERSIONES (*BUILD AN AMUSEMENT PARK*)

Contar una historia es una forma de hablar de tu juego. La otra es vender una experiencia y hablar de tu juego como si no fuera solo una atracción, sino todo un parque de diversiones lleno de atracciones.

Al llegar al parque, te recibe un área enorme con opciones infinitas para comer, comprar y entretenerte. Despliegas el mapa y comienza la batalla familiar de decidir adónde ir primero, adónde ir después, y averiguar dónde están los baños. Irás diciendo sí o no hasta que tome forma un plan.

Quizás te subes a la gran montaña rusa, o vas a la tienda del mago para escandalizarte con el precio de una réplica de varita de plástico. Hagas lo que hagas, cada cosa es breve y agradable y te deja con ganas de más. Aunque te subas a la montaña rusa varias veces, el miedo a morir hace que valga la pena.

A tu propio ritmo, con calma, has decidido qué hacer, lo has hecho y has seguido adelante. El día finalmente termina y vuelves a tu hotel.

A veces se agregan atracciones nuevas y se quitan atracciones viejas. Pero la experiencia de ir a un parque de diversiones hace que valga la pena repetirla una y otra vez sin cambiarla demasiado. Incluso hay bastantes probabilidades de que las eliminaciones provoquen el disgusto de los clientes, porque todos esperaban volver a hacer eso que hicieron la última vez.

Ahora apliquemos el mismo razonamiento a tu juego. Describe el juego como un parque de diversiones, empezando por la llegada, qué opciones hay disponibles y cómo se desarrolla la experiencia a partir de ahí.

Para algunos tipos de juegos, esto encaja mucho mejor que contar una historia.

### Construir un parque temático

1. **Llegada:** si es un juego en caja, una descarga digital u otra cosa.
2. **Atracciones:** lo que puedes hacer en este juego y que no puedes hacer en otros juegos.
3. **Comodidades:** cómo funciona la experiencia fuera de las actividades principales de juego.
4. **Partida:** cómo funciona el abandonar el juego, y de qué formas facilitas que el jugador vuelva.

![Ilustración: el juego como parque de diversiones en cuatro etapas: llegada, atracciones, comodidades y partida](img/game-design-toolbox/p089.png)

> **Texto de la ilustración:** cuatro escenas conectadas por flechas, en orden de lectura.
> - **1) Llegada** (¡y regreso!): tres personajes de palitos corren hacia las puertas de un castillo de parque de diversiones gritando "¡Yupi!".
> - **2) Atracciones** (bucles de juego; atracciones principales): dos personajes en un carrito de montaña rusa en lo alto de una cuesta.
> - **3) Comodidades**: dos cabinas de baño portátiles con un corazón en la puerta.
> - **4) Partida**: tres personajes se alejan caminando. Globo: "¡Eso estuvo genial! ¿Verdad?". Nube de pensamiento: "Un poco aterrador…". Globo: "La próxima vez me subo al tobogán…".

## DILO DE NUEVO (*SAY IT AGAIN*)

Presentar —ya sea contando una historia o hablando de diseño— requiere confianza. Por muy bien que creas conocer tu proyecto, casi siempre hay preguntas que te frenarán en seco. Cosas en las que no habías pensado o que nunca consideraste importantes.

Para ganar esa confianza, una gran manera de comprometerte con tu diseño es presentar lo mismo una y otra y otra vez. Cada vez que repitas el proceso te sentirás más cómodo y taparás agujeros que de otro modo pasarías por alto. Es aún mejor si tienes algo de presión cuando haces las presentaciones. Tal vez pídele a un productor que te exija, o presenta ante tu equipo una y otra vez. Que hagan las mismas preguntas y exijan respuestas más rápidas. Si no te frustras al menos un poco, no te están presionando lo suficiente.

El diseño del juego necesita sobrevivir al escrutinio de todas las disciplinas y también de todos los tipos potenciales de consumidores. En algunos proyectos, ayudará incluir a partes externas en este punto. En otros, es bueno simplemente presentarlo una y otra vez a las mismas pocas personas, hasta que puedas presentar el juego prácticamente dormido.

Si participas personalmente en el *playtesting*, parte de esto surgirá de forma natural al simplemente describir el juego a un flujo constante de *playtesters*. Está bien que no lo hagas bien de inmediato, siempre que aprendas de tus errores y mejores tu capacidad de leer las señales sociales.

Aprender a detectar cuándo alguien te encuentra aburrido es quizá la habilidad más fundamental que necesitarás jamás como diseñador de juegos.

### Volver a contar

- Presenta solo el gancho de tu proyecto y revísalo cada vez que lo presentes. ¿Cómo le presentas el gancho a un artista? ¿A un programador? ¿A un inversor? ¿A otro diseñador de juegos? Pruébalos todos, aunque solo tengas tu espejo como suplente.
- Hagas lo que hagas: nunca te pongas a la defensiva. Si alguien tiene preguntas, o bien respóndelas correctamente o di que no lo sabes y anota la pregunta como un problema potencial. Aunque sepas que no es importante, finge que lo es.
- Otra cosa: nunca pongas excusas. Nadie quiere oírlas. Es mejor seguir adelante que poner excusas cuando estás intentando generar interés.
- Ten a alguien a quien puedas presentarle una y otra vez, y que además sea capaz de presionarte para responder preguntas y corregirte hasta que ya no haga falta.
- ¡Practica! Si tienes un *pitch* de 10 minutos, preséntalo una y otra vez hasta haberlo hecho durante una jornada laboral completa. Ganas confianza y encuentras respuestas a las preguntas que la gente te hará de todos modos.

![Ilustración: un presentador repite el mismo pitch una y otra vez frente a un cartel](img/game-design-toolbox/p091.png)

> **Texto de la ilustración:** un cartel grande dice "AWESOMESAUCE III — PITCH". Un personaje de palitos, sonriente y con el brazo en alto, está a su lado. Alrededor del cartel hay cinco globos de diálogo que repiten la misma frase con énfasis creciente:
> - "Este es el pitch…"
> - "Este es el PITCH…"
> - "ESTE es el pitch…"
> - "Este es el pitch."
> - "Este. Es. El. ¡Pitch!"

## DEFINE LAS FEATURES (*DEFINE THE FEATURES*)

El jugador puede estar lanzando dados, recorriendo un mundo 3D, guardando/cargando, barajando el mazo de cartas, gestionando el inventario, etc. Mientras tanto, el avatar del jugador está disparando, saltando, corriendo, cumpliendo misiones y tal vez invadiendo Roma.

Habiendo tenido ya todas las ideas y habiéndolas explorado, ahora necesitas escribir una lista de las *features* que tu juego realmente va a utilizar. La lista no debería ser demasiado larga, pero aun así necesita abarcar tanto las obvias como las no tan obvias. No tiene que estar completa de inmediato, pero antes de pasar a los verdes prados de la Resolución de problemas, deben estar tan completas como sea posible.

Tu estilo de diseño y tus preferencias dictarán cuán exhaustivo eres con tu lista de features, pero como regla general, siempre debes listar las features directas del avatar y del jugador. No es raro que una lista de este tipo tenga un par de cientos de entradas, pero es importante evitar duplicados.

Solo recuerda que este es un ejercicio orientado al jugador. Evita pensar demasiado en las herramientas de desarrollo y en las cosas sofisticadas que tienes funcionando tras bambalinas. Esta herramienta trata por completo del juego que el jugador va a jugar, no de cómo se hace.

Algunas de las features en las que deberías pensar en esta etapa son cosas que no quieres que los jugadores hagan pero que sabes que harán de todos modos. En juegos con un componente social u oportunidades de contenido personalizado, deberías considerar las vías que tienen los jugadores para crear contenido ofensivo o acosar a otros jugadores de distintas maneras. Esas también son "features", aunque preferirías que no lo fueran, y necesitarás al menos ser consciente de ellas a medida que avanzas.

### Features obvias

- **Verbos:** ¡Una vez más, los verbos! Atacar, Defender, Apuntar y Robar carta. Saltar, Agacharse, Esquivar, Evitar ser detectado y Nadar.
- **Eventos:** Consecuencias de las cosas que ocurren en el juego, como el éxito y el fracaso. Morir, Ganar, Perder, Abandonar, Desempaquetar y Guardar la caja.
- **Feedback:** Caer, Explotar, Tropezar, Descartar y Reiniciar.

### "Features" menos obvias

- **Verbos de hardware:** Desconectar la red, Fallar (*glitching*), Perder la entrada, Tener *lag*, Colgarse (*crashing*) y Vibrar.
- **Verbos del jugador:** Ignorar instrucciones, Dejar el juego corriendo, Olvidarse de guardar y Malinterpretar.
- **Verbos de fallo:** Componentes perdidos, Componentes rotos, Archivos de guardado corruptos y Mal rendimiento.
- **Verbos sociales:** Maldecir, Abandonar con rabia (*rage-quitting*), Difamar, Acosar, Hacer amigos, Bloquear, Silenciar, Insultar y Ofender.

![Ilustración: dos listas de features y un personaje que explica qué es una feature](img/game-design-toolbox/p093.png)

> **Texto de la ilustración:** dos columnas de listas y, debajo, un personaje de palitos con dos globos de diálogo.
> - Columna "FEATURES": Disparar, Saltar, Robar carta, Morir, Volar, Descartar, Ganar, Perder, Moverse.
> - Columna "TAMBIÉN FEATURES": Explotar, Arder, Abandonar, Puntuar, Mensajes de la GUI, Minimapa, Fabricar (*crafting*), Coleccionar, Barajar el mazo, Abandonar con rabia (*rage-quitting*).
> - Globo 1: "Una feature está orientada al jugador."
> - Globo 2: "Una cosa con la que el jugador interactúa o que interactúa con él."

## PÁRATE SOBRE PILARES (*STAND ON PILLARS*)

Muchos diseñadores de juegos hablan de pilares de diseño. La analogía es, por supuesto, la de los pilares que sostienen el techo de un edificio. Los pilares de diseño también sostienen el techo del diseño de un juego. Si está bien diseñado, el techo evita que el torrente de ideas se convierta en un goteo de dudas que finalmente derrumba el edificio.

A veces ayuda ver un pilar de diseño como un meme de Internet. Un "meme" se concibe como una unidad de información cultural transferible de una mente a otra, casi como la transferencia de genes entre generaciones de organismos. Esto es exactamente lo que necesita hacer un pilar de diseño de juegos. Su trabajo es recordarle a todos los principios del proyecto.

Una sola línea de texto, o una imagen y una sola línea, y todo lo que necesitas hacer de ahí en adelante es reforzarlo mediante un uso repetido y consistente. Diviértete un poco con ello, también, tal como haces con los memes. La diversión puede hacer que el mensaje llegue con más eficacia.

Cuando funciona, se convierte en un descriptor consistente de tu proyecto que puede usarse en todas las disciplinas para comunicar de qué trata tu juego, y se repite casi instintivamente como respuesta a preguntas difíciles.

Solo evita hacer el pilar demasiado genérico. "Combate de ritmo rápido" no significa nada sin contexto, por ejemplo. "Muertes de un solo golpe" o "Peleas de cinco segundos" dirían más.

### Construir un pilar

- **Transferible:** El pilar tiene que ser fácil de decir y fácil de "memificar". No más de una sola oración; preferiblemente menos de cinco palabras. Si puedes encontrar una buena imagen o un juego con un meme de Internet muy conocido para transmitirlo con más eficacia, mejor aún.
- **Amplio:** Los pilares necesitan ser lo bastante amplios como para incluir una gran parte de tu juego, y deberían implicar tanto gameplay como tema, si es posible.
- **Superpuesto:** Los pilares deberían superponerse a distintas partes de tu juego y no deberían ser útiles solo para el diseño del juego. Considera qué significa "peleas de cinco segundos" para los animadores, o "mano de una sola carta" para los artistas de cartas.
- **Específico:** Los pilares pueden tener que ser amplios, pero tampoco deberían ser demasiado amplios. Cada uno debería aplicarse a una parte específica del juego y facilitar hablar de las metas creativas del juego. Un pilar pensado para el gameplay, como "peleas de cinco segundos", implicará por supuesto cómo se verán las cosas visualmente también; pero se ocupa sobre todo del gameplay y de sus muchas disciplinas conectadas.
- **Único:** Cada pilar tiene que ser único. A veces puede haber cierta superposición temática, pero tener más de un pilar diciendo cosas parecidas se vuelve confuso con facilidad. Si tienes combate, por ejemplo, solo un pilar debería tocar el combate, aunque otros pilares puedan implicar cosas relacionadas con él.

![Ilustración: tres pilares que sostienen el cartel de un juego, y un personaje que explica su función](img/game-design-toolbox/p095.png)

> **Texto de la ilustración:** un cartel con el título "AWESOMESAUCE III" descansa sobre tres columnas. Debajo de cada columna, su etiqueta:
> - "Muertes de un solo golpe"
> - "Fantasía de poder"
> - "Impulsado por los personajes"
>
> Debajo, un personaje de palitos con auriculares habla en dos globos:
> - "Juntos, los pilares deben resumir el diseño completo del juego."
> - "Son para beneficio de todos. De todo el equipo. No solo de los diseñadores."

## CRUZA TODO EN UNA MATRIZ (*CROSS-MATRIX EVERYTHING*)

Esta herramienta es particularmente útil cuando te atascas o no se te ocurren buenas soluciones para un problema en particular.

Una matriz cruzada es una tabla en cuadrícula en la que asignas algunos conceptos a las filas y otros conceptos a las columnas. Cada intersección entre columna y fila te ayuda a identificar una sinergia importante que necesitarás abordar, o una interacción específica del juego que necesitas resolver.

Encontrar dos cosas relacionadas de este modo es fácil. Ponerlas en una matriz cruzada también es fácil. Pero a veces puede ser tentador saltarse una o dos de las intersecciones porque es demasiado difícil o se siente demasiado abstracto. No lo hagas. Decide algo por ahora y sigue adelante, o al menos reserva algo de tiempo para decidirlo más tarde. Recuérdate a ti mismo que necesita decidirse.

### Ejemplos de conceptos para cruzar en una matriz

- Temas, Mecánicas o Conflictos de la ideación
- Features (features del jugador o del avatar)
- Pilares de diseño
- Momentos clave de la historia (*story beats*)
- Capas de diseño del juego
- Facciones del mundo

### Hacer una matriz cruzada

1. Dibuja una cuadrícula simple, preferiblemente en una pizarra, o abre un documento nuevo en un programa de hojas de cálculo.
2. Asigna algún conjunto de conceptos a las filas, por ejemplo, Features.
3. Asigna otro conjunto de conceptos a las columnas, por ejemplo, Pilares de diseño.
4. Usando la cuadrícula, escribe una descripción breve en cada intersección que defina cómo se comporta esa intersección. En la intersección entre el pilar "Peleas de cinco segundos" y la feature "Disparar", tienes que resolver algo. ¡Ahora estás haciendo diseño de juegos!

### Matriz de combinaciones

Imagina un juego en el que usas combinaciones de artefactos para lograr efectos mágicos. Si tienes un artefacto que te permite volverte invisible y otro que te prende fuego, necesitarás decidir si uno debería cancelar al otro o si está bien que el fuego se vuelva invisible junto con el personaje.

Luego agregas congelación, y levitación, y un montón de otras cosas, y de pronto necesitas saber cómo se combina cada una de ellas con cada una de las demás.

Una lista de verificación de combinaciones te permite hacer esto de forma simple. Listas todos los artefactos en una matriz cruzada, y cada vez que agregas uno nuevo lo agregas tanto como fila como columna. Esto te obliga a decidir cómo se combina un artefacto nuevo con todos los demás artefactos y garantiza que no olvides ningún caso límite.

![Ilustración: matriz cruzada de features (filas) contra pilares de diseño (columnas)](img/game-design-toolbox/p097.png)

> **Texto de la ilustración:** una tabla dibujada a mano. Columnas: "Muertes de un solo golpe", "Fantasía de poder", "Impulsado por los personajes". Filas: "Disparar", "Saltar", "Robar carta", "Morir", "Volar".
> - **Disparar:** Solo la cobertura salva a alguien de una muerte de un solo golpe. / ¡Todas las armas son enormes y disparan cosas que explotan! / Cada personaje tiene un arma única que refleja su personalidad.
> - **Saltar:** Fallar un salto te teletransporta de vuelta para intentarlo de nuevo. / Saltas altísimo, y el entorno parece real, así que sientes un ligero vértigo. / Cada personaje tiene un conjunto de animaciones de salto únicas, además de efectos de aterrizaje y de salto.
> - **Robar carta:** Si robas la última carta, mueres. / Todas las cartas tienen un efecto extremo. Beneficioso o perjudicial. / Cada personaje también tiene un mazo de cartas únicas.
> - **Morir:** Morir es rápido y recarga al instante. / Ninguna muerte se ve barata. ¡Siempre más grande que la vida! / Los personajes tienen animaciones de muerte únicas.
> - **Volar:** Si vuelas contra obstáculos, mueres. / ¡Vuelas muy, muy rápido! / El método de vuelo es distinto para cada personaje.

## CONVIERTE EN HECHOS (*FACTUALIZE*)

Un "hecho" es una afirmación simple que define un aspecto del juego y que ha sido establecida más allá de toda duda por todos los involucrados en la toma de decisiones del juego.

Cada hecho debería ser de solo unas pocas palabras, no más de una oración, que defina con claridad la cosa acordada.

*Nuestra heroína es Milla la Oruga* es un hecho. *Un jugador puede llevar dos armas cualesquiera* es otro. *El jugador usa WASD o el stick analógico izquierdo para moverse* es uno de esos hechos que también necesitas establecer, aunque pueda sonar evidente y pueda saturar innecesariamente tus listas de hechos. *Este nivel toma 10 minutos en completarse* es otro hecho, y puede enunciarse como meta antes de construir el nivel o como hecho establecido a posteriori.

Cada hecho debería ser corto, conciso y aprobado por todos los que trabajan en aquello a lo que se aplica. Una vez establecidos, puedes remitirte a los hechos continuamente a lo largo de tu trabajo. Tanto como proceso de aprobación como recordatorio de las cosas que ya has decidido.

A diferencia de los pilares, que pueden ser maleables a lo largo de un proyecto, los hechos deberían permanecer tal como están desde el momento en que se definen hasta que el proyecto se entrega. Por eso, es mejor discutir las cosas en términos sueltos antes de definir un hecho, para que todos estén de acuerdo con lo que se define.

Sin embargo, no tienes que usar todos los hechos establecidos de un juego todo el tiempo, sino que puedes elegir cuáles te importan más en cada etapa. También puedes optar por hacer excepciones de forma activa si quieres darle al jugador una experiencia específica en cierta parte del juego. Solo asegúrate de que todos estén de acuerdo primero. Se necesita una comprensión profunda de los hechos establecidos antes de poder hacer excepciones.

### Escribir un hecho

1. Una vez que algo se ha acordado en el equipo, encuentra una manera de enunciarlo como un hecho, y luego escribe una afirmación concisa, positiva y de una sola oración. Positiva significa que debería decir "puedes tener tres cartas en la mano" en lugar de "no puedes tener más de tres cartas". Puede sonar trivial, pero sí marca una diferencia en claridad.
2. Envía la afirmación a todos los afectados por ella para obtener su aprobación. Aunque hayan dicho que estaban de acuerdo al principio, puede haber matices en la redacción que afecten su opinión.
3. Reúne todos los hechos en un lugar de fácil acceso. Una wiki, un documento compartido, un servicio en la nube o cualquier otro sitio que se ajuste a los requisitos de seguridad y accesibilidad del proyecto.

### Usar los hechos

- Para los *one-pagers*, agregando listas de hechos relacionados.
- Al planificar tareas para desarrolladores que trabajan en sistemas o contenido relacionados, proporciona listas de hechos relevantes.
- Como recordatorios de diseño, señala los hechos que ya han acordado, y pon especial cuidado cuando la gente quiera hacer excepciones.
- Para servir como terreno común para todos los que trabajan en el juego, y como introducción accesible para los recién llegados.

![Ilustración: lista de hechos de un juego y un personaje que explica qué son](img/game-design-toolbox/p099.png)

> **Texto de la ilustración:** título "¡HECHOS DE AWESOMESAUCE III!". Debajo, una lista con viñetas:
> - Solo la cobertura salva a alguien de una muerte de un solo golpe.
> - Cada personaje tiene un arma única que refleja su personalidad.
> - Si robas la última carta, mueres.
> - Si vuelas contra obstáculos, mueres.
>
> Más abajo, un personaje de palitos con cara de preocupación habla en dos globos:
> - "A esta altura, puedes reunir afirmaciones sobre tu juego con las que todos hayan estado de acuerdo."
> - "Estos son HECHOS sobre el juego y su diseño."

## ESCRIBE ONE-PAGERS (*WRITE ONE-PAGERS*)

La comunicación es uno de los aspectos más desafiantes del trabajo de un diseñador de juegos. Aunque el recurso tradicional es el tomo gigante del tamaño de una biblia, a menudo conocido como Documento de Diseño del Juego (GDD, *Game Design Document*), la verdad es que pocos desarrolladores leen esos documentos. Es más probable que los GDD sean entregables obligatorios en beneficio de una editora u otro *stakeholder*.

Puedes perfectamente mantener un GDD para tu propio beneficio si eres el tipo de diseñador que usa la escritura como parte de su proceso. Puede usarse para llevar registro de todos los pormenores de tu juego, o para servir como caja de resonancia personal. En el diseño de un juego de mesa o de un juego de rol, probablemente sea el documento de reglas propiamente dicho. Pero para comunicar diseño, definitivamente deberías explorar las maravillas del *one-pager* en lugar del GDD.

Un one-pager es una sola página que detalla una sola idea de tu juego, y lo hace de la forma más sucinta posible.

La idea es que puedas juntar estos one-pagers como una especie de mosaico de diseño, en una pared u otro tablero de planificación, y que todos puedan remitirse a él como el conjunto del diseño del juego.

Puedes usar negritas o MAYÚSCULAS para señalar algo como otro one-pager al que remitirse. Puedes poner en mayúsculas cosas como hechos o pilares, o simplemente listarlos en una barra lateral para destacar los casos en que son particularmente relevantes. Cada vez que necesites especificar algo, escribes un one-pager para ello.

Muy pronto tendrás un resumen accesible de todo el diseño de tu juego.

### Escribir un one-pager

1. Escribe un título para el concepto del one-pager y agrega la fecha de hoy. Para el título, puedes tomar sin más un Pilar, una Feature o un Hecho de tu diseño, o algo que haya surgido en otro one-pager.
2. Anota quién es el autor del one-pager y cómo contactarlo. Esto muestra la propiedad de ese one-pager en particular, si tienes un equipo de diseñadores.
3. Agrega una ilustración clara del concepto que describes. Sirve para atraer la mirada de un vistazo, y también para construir una visión holística de todo el juego cuando se coloca junto a otros one-pagers.
4. Escribe una descripción de un solo párrafo sobre de qué trata este one-pager. Letra grande, pocas palabras.
5. Para los detalles, agrega barras laterales con viñetas que planteen el diseño de este one-pager. Cada una puede remitir a otro one-pager o repetir un hecho.
6. Agrega cualquier ilustración o llamada que consideres relevante para desarrollar el contenido del one-pager de forma visual, para quienes no leerán el texto a primera vista.
7. Si quieres ponerte elegante, puedes combinar varios one-pagers en conjuntos más grandes, por ejemplo como las cuatro esquinas de una habitación que detallan distintas features de esa habitación.

![Ilustración: anatomía de un one-pager de ejemplo ("Cuchillos") y un tablero de diseño con varios one-pagers](img/game-design-toolbox/p101.png)

> **Texto de la ilustración:** arriba, un one-pager de ejemplo con anotaciones alrededor indicadas con flechas.
> - Anotación "Versión, última actualización y autor" → en la hoja: "Versión 31 / 2023-04-24 / Martin".
> - Anotación "Título" → en la hoja: "CUCHILLOS".
> - Anotación "Ilustraciones: una ilustración principal; ilustraciones de cualquier detalle especial o variación relevante" → dibujo grande de un cuchillo y tres mangos pequeños con la nota "¿Mangos personalizados?".
> - Anotación "Descripción (una sola oración)" → en la hoja: "Los cuchillos son armas de respaldo que pueden usarse para muertes sigilosas."
> - Anotación "Hechos" → lista en la hoja: Un mango. / Una hoja. / Pueden ser sostenidos por los personajes. / Pueden lanzarse. / Se guardan en la bota.
> - Anotación "Interacción sistémica: si quieres, agrega campos de entrada, salida y feedback, donde puedas remitir a otros one-pagers" → en la hoja: "Entrada: Acción del jugador; Física. / Salida: Proyectil de cuchillo (lanzado); Corte; Apuñalamiento; Daño. / Feedback: Efectos de sangre."
>
> Abajo, una cuadrícula de doce tarjetas tituladas: Cuchillos, Espadas, Rifles, Hongos, Teletransportador, Gancho de agarre, Movimiento de dash, Plataformas de salto, Viaje en espejo, Daño por corte, Personaje principal, Motocicletas. Etiqueta: "TABLERO DE DISEÑO". Anotación: "Tablero de diseño: juntar todos tus one-pagers en algún lugar te da una gran visión general visual de todo el diseño del juego."

## ESTABLECE MÉTRICAS (*SET METRICS*)

Cuán alta y ancha es una puerta. Cuánto oro cuesta un tazón de fideos. Cuántos puntos de experiencia obtienes por matar a todos los goblins de la aldea goblin sin razón aparente. Cuántas cartas hay en el mazo.

El balanceo ocurre a lo largo de todo tu desarrollo, pero al establecer números base para todas las cosas de tu juego y asegurarte de almacenarlos en hojas de cálculo y/o bases de datos, puedes garantizar que nada se olvide ni se posponga. También puedes asegurarte de organizar la estructura de tal modo que puedas modificar fácilmente los números cuando, inevitablemente, llegues al balanceo. Ahora pueden ser métricas, pero en el futuro serán las palancas y diales que deberás usar para hacer que el juego se comporte como quieres.

Establecer métricas también sirve para permitir que los diseñadores de niveles, los desarrolladores de componentes y cualquier otra persona que necesite esas métricas pueda hacer su trabajo. Si olvidas establecer algo como la cantidad de sangrado (*bleed*) en el proceso de impresión, puedes terminar imprimiendo componentes que no se pueden usar.

Antes del final de la etapa de compromiso, debes tener todas tus métricas en orden.

### Una lista de métricas no exhaustiva

- **Componentes:** Qué cartas y cuántas en tus mazos. Cuántas entradas y qué números usar en tus tablas de botín. Cuántos personajes, armas y otras piezas de contenido. Sin estos componentes, el juego no existe.
- **Métricas de componentes:** Tamaño de los componentes. Cuánto "sangrado" necesitan los componentes para imprimirse. Ancho de un zapato. Rango de tallas de una camiseta personalizable.
- **Métricas de gameplay:** Cuán lejos y alto salta el jugador. Cuán rápido se mueve el jugador. Tiempo de juego objetivo o duración del turno. Número de cartas que puedes jugar en un turno.
- **Métricas de nivel:** Altura y ancho de puertas, ventanas y trampillas. Huellas (*footprints*) de los recursos del nivel.
- **Métricas de personajes:** Alturas y anchos mínimos y máximos. Cantidad de personajes. Número máximo de personajes en pantalla en un momento dado.
- **Métricas técnicas:** Máximo de polígonos por malla. Influencia de peso de piel (*skin weight*) por hueso. Número de cartas por plancha de impresión. Limitaciones de tamaño en disco para la distribución de la build del juego. Especificaciones mínimas para la plataforma objetivo.

![Ilustración: ejemplos de métricas: una puerta, componentes, moneda del juego y un salto](img/game-design-toolbox/p103.png)

> **Texto de la ilustración:** título "MÉTRICAS DE EJEMPLO". Cuatro dibujos con su etiqueta:
> - Una puerta con líneas de medición: "Altura y ancho de una puerta en 3D."
> - Dos pilas de cartas: "Cantidad de componentes."
> - Una bolsa de monedas: "Valor de la moneda del juego."
> - Un personaje de palitos saltando entre dos plataformas: "Longitud y altura de un salto."

## JUEGA, NO MUESTRES (*PLAY, DON'T SHOW*)

A veces pensamos en la experiencia del jugador como algo que hay que dirigir y controlar.

El jugador entra por aquí, hace esto y luego va hacia allá. Esto puede ser exactamente lo que nos propusimos hacer, una experiencia cinematográfica, pero lo que funciona en el cine no es necesariamente lo mismo que funciona en los juegos. Esto puede ilustrarse extrapolando el clásico adagio "muestra, no cuentes". En los juegos, puede ser "juega, no muestres".

"[C]uando trates con tu narrativa, crea una prioridad para contar tu historia de la siguiente manera: juégalo, muéstralo, dilo", escriben Flint Dille y John Zuur Platten en su libro *The Ultimate Guide to Video Game Writing and Design*. Es una lista de verificación eficaz, ya que te recuerda que la principal atracción de los juegos es que son interactivos.

Pero si jugar o mostrar también es una herramienta de compromiso importante, porque saber cómo pretendes presentar tu juego resolverá de forma preventiva muchos problemas potenciales del desarrollo.

Si quieres que el juego sea una experiencia cinematográfica en lugar de una sistémica, debes haberlo decidido antes de dejar esta etapa del proceso de diseño. Debes decidir qué partes del juego dejarás que los jugadores jueguen, cuáles hará que el juego muestre, y cuáles dirá directamente.

### La lista de prioridad interactiva

1. **Juégalo:** deja que el jugador haga que la cosa suceda.
2. **Muéstralo:** muéstrale el evento al jugador.
3. **Dilo:** enúnciale el evento al jugador.

### Ejemplos prácticos de "juega, no muestres"

Si estás usando alguna de las siguientes técnicas, le estás mostrando al jugador algo que, en cambio, podría jugar.

- Las **cinemáticas de exposición** explican detalles de la historia que son externos al jugador y que pueden no ser obvios. Hacer que el jugador juegue la escena en su lugar implica que debes examinar tanto lo que muestras como cómo puedes hacerlo atractivo como actividad.
- La **dirección de escena** es cuando tomas el control de la cámara para dirigir la atención del jugador hacia donde necesita ir o lo que necesita hacer. En cambio, puedes dejar que el jugador lo descubra por sí mismo, asegurándote de que eventualmente tendrá que ir allí una vez que haya agotado todas las demás opciones.
- La **narración de escena** es cuando tiras de una palanca y una cinemática te muestra una puerta abriéndose, o cuando una cinemática te muestra que llegan refuerzos. Estas cosas rara vez necesitan explicación: simplemente se puede dejar que ocurran.
- Los **cambios de control** son cuando un juego normalmente permite ciertas acciones pero, de forma repentina y arbitraria, quita la capacidad de realizarlas.
- Las **indicaciones verbales o escritas** son los "ve allá", "trae aquello" y "quizás necesites abrir la puerta roja" que algunos diseñadores llaman *nag lines* (líneas de fastidio). Confiar en que el jugador resolverá las cosas por su cuenta a veces puede ser un mejor camino.
- Las **indicaciones visuales** son los gráficos de puntos de ruta dentro del juego y otras señales que te muestran claramente adónde ir. El riesgo de estas es que el jugador deje de interactuar con el juego en sí y solo interactúe con la interfaz de usuario.

![Ilustración: tres formas de comunicar un evento: jugarlo, mostrarlo o decirlo](img/game-design-toolbox/p105.png)

> **Texto de la ilustración:** tres viñetas, cada una con un héroe y una torre.
> - **1) Juégalo:** el héroe camina hacia la torre pensando: "Quizás esa torre tenga cosas geniales…".
> - **2) Muéstralo:** una pantalla muestra al héroe llegando a la torre; rótulo: "La cinemática muestra al héroe llegando a la torre."
> - **3) Dilo:** un personaje con bastón junto a la torre le dice al héroe: "¡Debes entrar en la Torre Furiosa de la Oscuridad Eterna, oh Elegido!".

## VERIFÍCALO (*CHECK IT*)

Asegúrate de no usar términos, lugares, etc., que sean marcas registradas o tengan derechos de autor. Puede sonar evidente, pero, por favor, simplemente búscalo para ver si ya está tomado.

Para un lego, los detalles finos de la legislación pueden ser extremadamente difíciles de predecir. Incluso algo que parece intuitivo o que parece imposible de malinterpretar puede ser y será malinterpretado. Incluso el uso de palabras comunes o axiomas puede meterte en problemas si esas mismas palabras y axiomas los usan organizaciones más grandes con equipos legales muy activos.

Pero esto va mucho más allá de las meras ramificaciones legales. Las consideraciones de representación, accesibilidad y muchas otras cosas son igual de importantes, si no más.

Cuando "lo verificas", te aseguras de que la mayor cantidad posible de personas pueda disfrutar de tu juego. Por supuesto, también debes considerar qué audiencias son relevantes. Si estás haciendo un juego de temática de terror, probablemente no se venderá bien entre los niños de todos modos y probablemente puedas ignorar sin riesgo algunas restricciones de clasificación por edad.

Esta herramienta es el último guardián antes de que te comprometas con el diseño de tu juego. Pregúntate si puedes hacer lo que pretendes hacer, pero si sientes siquiera un atisbo de duda, también deberías preguntarte si deberías.

### Lista de verificación

- **Marcas registradas con un uso similar de palabras:** Tampoco tiene que ser la expresión exacta. Si usas onomatopeyas o expresiones comunes, las corporaciones con nombres parecidos pueden considerarlo una violación de su marca registrada.
- **Marcas registradas específicas relacionadas con lo que podrías pensar que son términos comunes:** "Droid" es una marca registrada de Lucasfilm Entertainment Company Ltd., por ejemplo, y no puedes usarla para los robots de tu juego sin un acuerdo de licencia.
- **Referencias culturales con contexto local problemático:** Algunos países pueden no querer que muestres los símbolos políticos de su pasado, o pueden prohibir tu juego porque usa estereotipos dañinos o muestra esqueletos visibles o entrañas humanas. Un lanzamiento global requiere conciencia global.
- **Clasificaciones:** Puedes encontrar en línea las pautas de los servicios de clasificación más populares, y es buena idea llevar registro de lo que puedes y no puedes hacer según tu audiencia prevista. Las maldiciones y los insultos pueden limitarse, así como las representaciones más gráficas de la violencia pueden restringirse.
- **Detonantes (*triggers*):** Cierto contenido es detonante y puede requerir advertencias si no quieres alienar a ciertas audiencias. Esas advertencias aplican al miedo a las arañas, al miedo a ahogarse y a muchos más.
- **Accesibilidad:** Si aún no lo has considerado, deberías revisar la accesibilidad antes de comprometerte por completo con tu juego. Hacer posible que alguien juegue tu juego aunque tenga alguna variación funcional es una buena forma de llegar a una audiencia más amplia. Como mínimo, deberías saber quién tendrá dificultades para jugar tu juego a causa de las decisiones de diseño que has tomado.

![Ilustración: dos listas de verificación: "¿Puedes?" (legal, financiera) y "¿Deberías?" (moral, ética)](img/game-design-toolbox/p107.png)

> **Texto de la ilustración:** dos listas con viñetas y, a la derecha, un personaje de palitos pensativo con cara de preocupación.
> - **¿PUEDES?** (legal y financieramente)
>   - Marcas registradas o derechos de autor existentes.
>   - Otros juegos que son DEMASIADO parecidos.
>   - Lugares o semejanzas del mundo real.
>   - Nombres de empresas o marcas.
> - **¿DEBERÍAS?** (moral y éticamente)
>   - Ofensivo o detonante.
>   - Alienar a ciertas audiencias.
>   - Features inaccesibles.
>   - Features bloqueadas tras un pago.

---

# Capítulo 5 — Resolución de problemas (*Problem Solving*)

Ahora estás comprometido y sabes qué se supone que será tu juego cuando esté terminado. En este punto ya no puedes volver a la ideación ni a la exploración. Es hora de ponerse serios y lanzar tu juego. Si se te ocurren ideas geniales, por supuesto anótalas en algún lado, pero no son para este proyecto.

Sin embargo, no temas: el diseño sigue siendo necesario. La ideación y la exploración no hacen falta, pero averiguar qué hacer cuando una combinación de botones no funciona o cuando los *testers* del focus test no logran descubrir adónde ir es muy necesario. Además, aunque la iteración de alto nivel ya no ocurra, todavía puedes quitar cosas del juego.

Resolver problemas reales demostrados por el juego jugable, aunque esté en un estado tosco o solo lo jueguen tú y tus aliados más cercanos: de eso se trata la resolución de problemas.

Qué haces durante la resolución de problemas:

- Juega tu juego y haz que otras personas lo jueguen todo el tiempo. Concéntrate en encontrar problemas y en probar distintas soluciones.
- Piensa en tus clientes y en las *personas* (arquetipos) que podrían describirlos, e intenta imaginar con qué problemas se toparían.
- Organiza focus tests aislados e incluye pruebas de Control de Calidad (QA) en tu proceso, si tienes los recursos.
- Con toda probabilidad, escribe una lista de los problemas con los que podrías vivir si siguieran ahí en tu juego terminado.

## CREA PLAYER PERSONAS (*MAKE PLAYER PERSONAS*)

Una "*persona*" es un individuo inventado que representa a alguien que jugaría tu juego. Hay *personas* estimadas a ojo y *personas* obtenidas a partir de métricas extensas. Para las segundas, el informe Gamer Segmentation and Gamer Personas de NewZoo es un excelente punto de partida, disponible en NewZoo. Para las primeras, las inventas a medida que las necesitas y lo mejor que puedas.

Examinar tu juego como lo harían estas *personas* es una buena manera de encontrar problemas que resolver, ya que puede abrirte los ojos sobre por qué surge cierto problema o incluso advertirte antes de que ocurra. Si sabes que algunos jugadores solo jugarán 10 minutos por sesión, por ejemplo, y tu juego requiere al menos 15 minutos por sesión, ahí tienes un problema muy claro y, con suerte, soluble.

Puedes pensar en una *persona* como en un personaje creado para un juego de rol. Es una persona imaginaria modelada a partir de personas reales y solo cumple su propósito si es lo bastante real como para resultar convincente.

Después de inventar unas cuantas *personas*, observas cómo jugarían tu juego de forma distinta a ti y qué tipos de problemas surgen cuando lo hacen. Luego puedes seguir volviendo a tu biblioteca de *personas* y ver cómo provocan nuevos problemas con tus diseños ajustados.

### Crear un player persona

- Escribe una breve biografía —nombre, edad y profesión— para tu *persona* imaginaria. Quizás quieras tocar también la clase social, el nivel de riqueza y otros factores, dependiendo de tu juego.
- Define cómo interactúa la *persona* con los juegos:
  - ¿Cuál fue el primer juego que jugó?
  - ¿En qué plataformas prefiere jugar?
  - ¿A qué hardware tiene acceso?
  - ¿Cuánto dinero gasta en juegos por mes?
  - ¿Cuánto tiempo le dedica a un juego nuevo la primera vez que lo juega?
  - ¿Cuántas horas juega por semana?
  - ¿Juega principalmente multijugador, principalmente un jugador, o una mezcla de ambos?
  - ¿Tiene un grupo habitual de juegos de mesa o de rol con el que juega?
  - ¿Juega principalmente juegos en línea?
  - ¿Juega muchos tipos de juegos, o se queda con géneros específicos, o incluso con un solo juego?
  - ¿Juega juegos o principalmente mira *streams* de otras personas jugando, o ambas cosas?
- Explora cómo interactuaría la *persona* con tu juego, basándote en la información que has proporcionado.
- Explora si podrías hacer algo para que el juego sea más viable para ella, o si tienes que aceptarla como una "causa perdida", y qué significa eso para tu diseño. Si es poco probable que cierto tipo de jugador juegue tu juego en primer lugar, puede haber concesiones que hiciste antes y que ahora puedes deshacer.
- Juega el juego como imaginas que lo haría la *persona*: más rápido, más lento, o con más cuidado o más imprudencia. Usa la *persona* para variar tu propio estilo de juego y asegúrate de anotar cualquier problema que surja y que necesite solución.

![Ilustración: tres fichas de player personas dibujadas a mano — jugador joven, jugador adolescente y jugador mayor](img/game-design-toolbox/p111.png)

> **Texto de la ilustración:** tres hojas superpuestas, cada una con un retrato y una ficha de *persona*.
> - **JUGADOR JOVEN** (*Young gamer*): "Gasta tanto dinero como tiempo jugando juegos y prefiere los juegos competitivos; tiene mucho tiempo pero poco ingreso disponible." — ¿Primer juego? FORTNITE. — ¿Plataformas? TELÉFONO y CONSOLA. — ¿Horas por semana? 10–30. — ¿Mira streams? Sí, varios.
> - **JUGADOR ADOLESCENTE** (*Teenage gamer*; la hoja está parcialmente tapada por la de al lado): "[…] intereses además de los juegos, […] sigue jugando juegos. Tanto […] como en línea, […] los mismos amigos que antes." — [¿Primer juego?] CALL OF DUTY. — [¿Plataformas?] [C]ONSOLA. — [¿Horas por semana?] 10–20. — [¿Mira streams?] Sí, y no solo streams de juegos.
> - **JUGADOR MAYOR** (*Old gamer*): "Tiene ingreso disponible, pero sobre todo compra juegos antiguos en caja grande en subastas en línea. Compra muchos juegos, pero tiene poco tiempo para jugar." — ¿Primer juego? ELITE. — ¿Plataformas? Todas. — ¿Horas por semana? 1–5. — ¿Mira streams? Sí, debido al poco tiempo de juego.

## OBSERVA Y ANALIZA (*OBSERVE AND ANALYZE*)

Una de las primerísimas cosas que deberías hacer cuando tu juego se puede jugar es mirar a la gente jugarlo. Esto es igual de cierto para todo tipo de juegos. Al quitarte a ti mismo del juego, pero no del *playtest*, verás qué tan fácil (o difícil) es entender tu juego y aprenderás cosas que jamás habrías anticipado.

La parte más difícil de esta observación es que probablemente querrás decirles a tus *testers* qué hacer cuando se equivocan. Pero es absolutamente esencial para el proceso que no sucumbas a esta tentación. En el momento en que empiezas a explicar cosas, has arruinado las observaciones que podrías haber hecho.

Si haces preguntas, debes hacerlas de una manera que no guíe al jugador, y no deberías preguntar nada en absoluto hasta que la sesión de juego haya terminado. Puede ser tentador preguntar "¿qué crees que hace el botón de la derecha?", porque desesperadamente quieres que lo presionen, pero no deberías. Si no están presionando ese botón, puede que haya un problema con tu diseño.

Simplemente ronda cerca de los jugadores y absorbe todo lo que puedas. O usa uno de esos espejos unidireccionales que siempre aparecen en las escenas de interrogatorio de las películas, si tienes acceso a uno. O simplemente asegúrate de grabar la sesión de juego para poder verla después.

Por último, nunca uses una única observación de test como base para una decisión de diseño. Trae más *testers* para ver si las conclusiones se repiten con más consistencia. Cuantos más tests, mejor.

### Lista de verificación del observador y preguntas de seguimiento

- Anota dónde se atascan. Pregúntales si hubo lugares o situaciones en los que se sintieron atascados.
- Anota qué hacen mal o malinterpretan. Pregúntales qué estaban intentando hacer que ocurriera, y por qué; no des a entender que algo estuvo mal.
- Anota qué *features* usan mucho. Pregúntales qué cosas les gustaron y cuáles no, y por qué, pero no preguntes por *features* específicas. Deja que ellos mencionen las *features*.
- Anota qué *features* no usan en absoluto. Pregúntales qué cosas no les gustaron, y por qué, pero de nuevo sin dar a entender que te refieres a algo específico.
- Anota si hay cosas que eligen saltarse o evitar. Pregúntales sobre saltarse y evitar cosas; ten cuidado de no sugerir qué pudieron haberse saltado, ya que también puede ser un error involuntario.
- Anota cualquier comportamiento inesperado que no hubieras previsto cuando diseñaste o hiciste las *features*. Esto sirve tanto para el descubrimiento, es decir, encontrar cosas geniales que no esperabas, como para resolver posibles problemas con la presentación del juego. Si de algún modo los jugadores se ven alentados a hacer cosas que no quieres que hagan, necesitas averiguar por qué.
- Finalmente, después de que el test haya terminado y hayas hecho cualquier otra pregunta, pregúntales a los *playtesters* de manera más general si hay cosas que habrían cambiado y, de ser así, qué, cómo y por qué. Esta debería ser la última pregunta, o algunos tipos de *testers* se quedarán "atascados" en sus propias ideas.

![Ilustración: dos diseñadores conversan mientras un playtester apila cajas con letras que forman "HEHEHE" y se ríe](img/game-design-toolbox/p113.png)

> **Texto de la ilustración:** globos de diálogo entre dos personajes que observan a un tercero apilando cajas marcadas con las letras H y E; el jugador ríe "JEJEJEJEJEJEJEJEJE…".
> - "¿Cómo va?"
> - "Llevan cinco horas seguidas apilando cajas."
> - "Uy… quizás deberíamos hacer el puzzle más fácil."
> - "Quizás no. ¡Han estado riéndose todo el tiempo!"

## TESTEA A CIEGAS (*TEST BLIND*)

Un test a ciegas es cuando envías tu *build* o prototipo a alguien que no te conoce y no tiene ninguna conexión con tu proyecto. Como todo el mundo es (al menos) un diseñador de Nivel 1, este tipo de testeo es muy valioso, ya que elimina por completo tu propio sesgo personal de creador de los datos del test. La desventaja, por supuesto, es que no siempre puedes observar la sesión de juego directamente.

Los *testers* que testean a ciegas tendrán que aprender el juego igual que cualquier otro jugador primerizo que compre tu juego y, por lo tanto, son sujetos de prueba valiosos. A diferencia de muchos otros *playtests*, donde estás presente para explicar el juego o ayudar (contra tu mejor criterio) cuando alguien se atasca, un test a ciegas excluye cualquier aporte tuyo que afecte el resultado del test.

Idealmente, el test se puede grabar y compartir contigo, para que puedas oír a los jugadores hablar sobre su sesión y ver cómo interactúan con el juego. Si eso no es posible por alguna razón, la segunda mejor opción es que todos completen un formulario con preguntas no inductivas para que puedas saber qué sintieron al respecto.

En muchas comunidades de diseño de juegos de mesa y comunidades de desarrolladores indie, el testeo a ciegas de los juegos de los demás se hace *quid pro quo*. "Tú testeas el mío y yo testeo el tuyo." Si tienes el lujo de formar parte de una comunidad así, consigue todo el testeo que puedas. Pero asegúrate de devolver al menos tanto como recibes.

### Qué buscar en los tests a ciegas

- **Enseñanza:** si los jugadores logran entrar en el juego a la velocidad que esperas, así como cualquier obstáculo específico con el que se topen en el camino.
- **Comprensión básica:** si los jugadores están haciendo lo correcto en el momento correcto o se están perdiendo algo importante.
- **Duración de la sesión:** durante cuánto tiempo juegan los jugadores y en qué puntos de tu juego parecen desconectarse. Usa un cronómetro con juegos de mesa y similares. Con juegos digitales, puedes rastrear el abandono de jugadores usando analíticas; por ejemplo, enviando datos a una base de datos al final de cada nivel o a intervalos regulares.
- **Comentarios espontáneos:** cuando no estás ahí, y la gente no te conoce, lo que dicen sobre el juego suele ser mucho más honesto y directo. Puede que incluso critiquen abiertamente algunas decisiones de diseño que has tomado. Esto es invaluable y, en muchos sentidos, la mejor parte de los tests a ciegas. Escucha con atención y absórbelo todo.
- **Reacciones:** si tienes grabaciones, ver cómo reacciona la gente en ciertos momentos del juego también es invaluable; por ejemplo, cuando roban la carta genial y desbalanceada, o cuando caen en la trampa de un oponente. Si ves cosas que te sorprenden, genial. Si ves lo que esperabas, también genial. ¡Significa que tu juego está funcionando como se pretendía!
- **"El juego" vs. "Yo":** algo a lo que vale la pena prestar atención es cuando la gente habla de lo que hizo ella versus lo que hizo el juego. Es común que las cosas buenas sean "yo" y las cosas malas sean "el juego", lo que te da pistas relevantes que recoger.

![Ilustración: dos jugadores con cartas en la mano y un tablero entre ellos discuten una regla mal entendida](img/game-design-toolbox/p115.png)

> **Texto de la ilustración:** dos personajes sentados frente a un tablero, cada uno con cartas en la mano.
> - Jugador de la izquierda: "'Juega en la fase de tu oponente' debe estar mal escrito, ¿no? ¿Querrán decir 'cara' (*face*)?" [Juego de palabras intraducible entre *phase* (fase) y *face* (cara).]
> - Jugador de la derecha: "No sé. ¡Probablemente!"

## DIBUJA UN MAPA DE ESTRATEGIAS (*DRAW A STRATEGY MAP*)

Cuando tu diseño permite muchas soluciones o estrategias diferentes, es fácil olvidar algunas de ellas porque te has familiarizado mucho con otras. También puede que hayas evitado algunas estrategias porque los componentes no estaban terminados o todavía no se habían implementado. Incluso una vez que están ahí, puede que olvides usarlas.

En todos los casos en los que tienes múltiples rutas alternativas para alcanzar objetivos o para terminar una partida, necesitas verificar que todas funcionen y que todas estén enganchando a tus jugadores.

¡Aquí entra el mapa de estrategias! Un mapa de estrategias enumera todas las estrategias viables para una situación dada en tu juego y proporciona maneras de comprobar si todas están recibiendo suficiente atención.

Por ejemplo, si tienes un juego con dos condiciones de victoria distintas, un mapa de estrategias puede mostrar todas las distintas maneras previstas de alcanzar cada una de ellas. Las estrategias que están disponibles para el jugador.

Documentando cada *playtest* —el tuyo o el de otra persona— puedes entonces anotar qué condición de victoria se activó y qué estrategia se usó. Si el 90% de las sesiones termina por la misma estrategia, significa que las otras estrategias están subrepresentadas y que necesitas ajustar el juego para hacer más interesantes las estrategias poco usadas.

Si tienes un juego donde el combate y el *parkour* son *features* importantes, por ejemplo, pero solo el *parkour* está teniendo un uso consistente, quizás necesites potenciar el combate o incluso considerar si el combate debería estar ahí en absoluto.

Un mapa de estrategias es un recordatorio de cómo quieres que se juegue el juego, y una manera simple de verificar que has cubierto todos los frentes.

### Mapa de estrategias general

- Enumera cualquier condición inicial relevante, incluidos los resultados de cualquier elección inicial que los jugadores tengan que hacer. Facción, arma, ubicación de inicio, etc.
- Enumera las condiciones de fin del juego. El personaje del jugador muere, el mazo se queda sin cartas, Roma es invadida por los bárbaros, etc.
- Yendo hacia atrás desde cada condición de fin, enumera las elecciones o eventos que llevan a ellas, hasta que llegues a las condiciones iniciales y completes el mapa.
  - Mantén cada elección amplia. Enumera solo unos pocos pasos por estrategia.
  - No tienes que enumerar cada acción concebible que el juego permite, solo las estrategias de alto nivel que se espera que lleven a giros interesantes en el juego.
  - Está bien que las flechas que dibujes se encuentren en lugares donde ciertas elecciones llevarían a los mismos resultados.
  - También está bien que algunas estrategias requieran más pasos que otras. Esto en sí mismo no es necesariamente un problema, ya que los pasos pueden variar en complejidad.

### Verificaciones de refuerzo

Una vez que tienes un mapa de estrategias, puedes usarlo para verificar tanto que las estrategias sean iguales entre sí como que las actividades en sí refuercen el juego que estás haciendo. Por ejemplo:

- **Verificaciones de personalidad:** usar el mapa para comprobar que las actividades sean algo que el personaje principal haría.
- **Verificaciones de marca:** asegurarte de que cada actividad del mapa de estrategias refuerce la marca en la que estás trabajando.

![Ilustración: mapa de estrategias con estrategias ofensivas a la izquierda, defensivas en el centro y formas de ganar a la derecha, unidas por flechas](img/game-design-toolbox/p117.png)

> **Texto de la ilustración:** diagrama de tres columnas unidas por flechas.
> - Encabezados: **ESTRATEGIAS OFENSIVAS** ← (PATRULLAR) → **ESTRATEGIAS DEFENSIVAS** — **FORMAS DE GANAR**. ("Patrullar" aparece en un óvalo entre las dos primeras columnas, con flechas hacia ambos lados.)
> - Fila 1: CAPTURAR → (escudo) MANTENER → VICTORIA ESTRATÉGICA (tomar el objetivo).
> - Fila 2: INCURSIÓN → (explosión) ¡EMBOSCADA! → VICTORIA POR NEGACIÓN (destruir el objetivo).
> - Fila 3: ASALTO → (cerca) PERÍMETRO → VICTORIA TÁCTICA (el enemigo se rinde). Una flecha adicional va desde ASALTO hacia ¡EMBOSCADA!
> - Pie: "Un mapa de estrategias te recuerda las condiciones de fin y las distintas maneras en que los jugadores pueden alcanzarlas."

## VERIFICA CON CHECKLISTS (*VERIFY WITH CHECKLISTS*)

Es fácil perderse mientras haces un juego. Empiezas el juego sabiendo ya todo lo que debería ocurrir. Te acostumbras a los íconos rojos en el registro que te dicen que algo salió mal, o pasas de largo tus notas sobre qué arreglar en las reglas del juego. Tu memoria muscular atraviesa el menú principal tan rápido que ni siquiera notas las palabras mal escritas o las opciones que ahora están rotas.

A veces se instala la repetición o incluso una especie de fatiga, y ya no puedes ver realmente el juego tal como es. El bosque no te deja ver los árboles, como dice el proverbio.

En momentos como estos, es bueno tener *checklists* (listas de verificación) preparadas para hacerte recordar cómo se supone que funciona el juego. Sin embargo, esto no se trata de estrategias; hay una diferencia clave aquí. Estas *checklists* tienen que estar para recordarte las cosas repetitivas en las que no piensas; los mapas de estrategias están para asegurarse de que les estás dando a los jugadores lo que quieres que tengan.

Estas *checklists* también pueden ayudarte con el trabajo de diseño en sí e informarán a nuevos compañeros de trabajo, posibles *playtesters* y otros sobre cómo jugar tu juego.

### Checklists de acciones

Una *checklist* de acciones o de interacción de *features* es probablemente la cosa más autoexplicativa que tendrás que hacer jamás como diseñador de juegos. Pero aun así deberías hacerlas.

Imagina la clásica lista de orden de turno, y eso es exactamente lo que es:

1. Fase de robo: roba una carta.
2. Fase de juego: juega hasta tres cartas de la mano.
3. Fase de descarte: descarta una carta.

Qué tan granulares quieres que sean estas *checklists* depende del nivel de detalle de tu juego, pero hacer *checklists* de todos los pasos por los que tienes que pasar para realizar tareas estándar, como cambiar la resolución o consultar qué botón presionar, te mantendrá enfocado durante toda la entrega de tu juego y garantizará que cualquier cambio grande pueda detectarse más fácilmente.

También es una buena manera de encontrar dónde se pueden simplificar o incluso eliminar pasos.

![Ilustración: dos checklists con casillas — cambiar la resolución de pantalla y jugar un turno — y un personaje que comenta sobre ellas](img/game-design-toolbox/p119.png)

> **Texto de la ilustración:**
> - **CAMBIAR LA RESOLUCIÓN DE PANTALLA** (lista con casillas):
>   - Iniciar el juego
>   - Ver la secuencia de título completa
>   - Esperar a que termine la cinemática de introducción
>   - Presionar cualquier botón en el menú de inicio
>   - Hacer clic o presionar "Configuración"
>   - Hacer clic o presionar "Gráficos"
>   - Hacer clic o presionar "Resolución de pantalla"
>   - Elegir la resolución deseada
>   - Hacer clic o presionar "Aplicar"
>   - Si se pide confirmar, hacer clic o presionar "Sí" o "No".
> - **JUGAR UN TURNO** (lista con casillas):
>   - Comprobar si ganaste
>   - Si no ganaste, roba tres cartas
>   - En cada carta, resuelve cualquier efecto de "jugar inmediatamente"
>   - Juega tantas cartas como puedas
>   - Termina tu turno
> - Globo de diálogo: "Puede que algunas checklists no se usen tanto. Pero consérvalas. ¡Nuestra capacidad para olvidar cosas importantes es notable!"
> - Globo de diálogo: "Estas checklists también pueden ayudarte a eliminar pasos de interacciones innecesariamente complejas."

## VALIDA TUS PILARES (*VALIDATE YOUR PILLARS*)

El "Crate Review System" (sistema de reseñas por cajas) fue creado por el sitio web Old Man Murray a principios de los 2000. Es una sección en tono de broma que enumera algunos juegos populares de la época y los puntúa según cuántos segundos pasaban antes de que el jugador viera una caja de madera, un barril u otro objeto parecido a una caja. La puntuación se denomina "segundos hasta la caja". Cuanto más alta, mejor, ya que aparentemente implicaría mayor imaginación por parte de los desarrolladores.

Dejando de lado que este seguiría siendo un sistema de reseñas preciso aún hoy, el principio de usar puntuaciones para determinar problemas con tu diseño de juego es algo que tú también puedes aplicar. Se puede usar para revisar tu propio trabajo y para asegurarte de que estás a la altura de tus afirmaciones, estableciendo pruebas de validación concretas y medibles.

La parte más complicada de la validación de diseño es evitar falsos positivos y falsos negativos. Con las muchas maneras en que podemos usar software de analíticas en los juegos digitales modernos, por ejemplo, o construir hojas de cálculo elaboradas, las estadísticas generadas pueden usarse fácilmente de manera selectiva. Esto destruye los beneficios de dichos datos.

La mejor manera de evitar estos resultados falsos es usar datos que sean concretos y no den lugar a la especulación. El tiempo y otros números nítidos, como el número de muertes, cartas robadas o turnos de juego. Cualquier dato que no deje lugar a interpretación y sobre el que se pueda actuar fácilmente. Contar segundos es uno de los más efectivos, ya que puedes comprobar fácilmente si los cambios futuros suman o restan segundos en los nuevos resultados. Pero se puede usar cualquier número que pueda compararse directamente entre iteraciones de *gameplay*.

### Ejemplos de verificaciones de validación de diseño

- **Segundos hasta matar:** si quieres un juego de acción más intenso, medir el número de segundos desde la pantalla de presentación hasta la primera muerte es una herramienta efectiva. Te obliga a reconsiderar las pantallas de inicio de sesión y otros procesos previos al juego. Por supuesto, se puede aplicar a otras acciones además de matar: segundos hasta saltar, segundos hasta construir, segundos hasta robar una carta, y así sucesivamente.
- **Segundos por muerte:** otra métrica interesante para la acción es medir cuántos segundos sobrevive cada enemigo en la simulación. Este número puede bajar a 3–5 segundos en algunos estilos de juegos de acción y puede subir hasta cerca de una hora en una pelea de jefe particularmente abrumadora. Al igual que con Segundos hasta matar, esto también puede aplicarse a otras interacciones.
- **Duración de la sesión:** si fijas un objetivo de 5 minutos, y el juego tarda menos o más en jugarse, necesitas encontrar maneras de ajustar la duración de la sesión añadiendo o quitando elecciones, contenido o fricción.
- **Cantidad de turnos:** para comprobar qué tan largo es tu juego, en un juego por turnos, puedes medir el número total de turnos jugados en cada sesión. Se dice que una sesión completa de Civilization 6 promedia alrededor de 500 turnos.
- **Duración del turno:** con los turnos, también puedes medir cuánto tarda en completarse cada turno individual, teniendo en cuenta que los jugadores juegan de manera distinta.
- **Test de las dos horas:** por razones de la política de devoluciones de Steam, una prueba de validación común es el Test de las Dos Horas, donde quieres que tu juego se juegue un mínimo de 2 horas antes de que un jugador lo abandone.
- **Rotación de jugadores:** comprobar cuántos jugadores abandonan antes de terminar el juego y ver si puedes cambiar esa tendencia ajustando el diseño.

![Ilustración: tablas de cantidad promedio de turnos y de tasas de abandono por nivel, con dos personajes que las comentan](img/game-design-toolbox/p121.png)

> **Texto de la ilustración:**
> - **CANTIDAD PROMEDIO DE TURNOS**
>   - Civilization, 200–350
>   - Diplomacy, 20–24
>   - Encuentro de Dungeons & Dragons, 2–5
>   - Magic: The Gathering, 10
>   - Warhammer 40,000, 10
> - Globo de diálogo: "¡Algo genial de las métricas de validación es que puedes hacer comparaciones relevantes con otros juegos!"
> - **TASAS DE ABANDONO POR NIVEL**
>   - Tutorial: 50%
>   - Angry Tower: 15%
>   - Skullcave: 2,5%
> - Globo de diálogo: "¿Por qué tantos abandonan durante el tutorial?"
> - Globo de diálogo: "¿Podemos lograr que se queden?"
> - Globo de diálogo: "¿Podemos testear sin el tutorial?"

## DEJA UN RASTRO (*LAY A TRAIL*)

A veces, los jugadores simplemente no lo entienden. Tienen que doblar esa esquina para llegar a la siguiente etapa del nivel pero parecen no estar dispuestos a hacerlo, o de alguna manera olvidan dar vuelta la carta que tienen en la mano y por lo tanto se pierden la información que necesitan.

Aquí es donde un rastro puede ser útil, igual que Hansel dejando un rastro de migas de pan para encontrar el camino de vuelta a casa. En honor a ese cuento en particular, puedes referirte a esta herramienta como "dejar migas de pan" (*breadcrumbing*).

Si tienes un objetivo que el jugador necesita alcanzar, dejas un rastro a lo largo del camino hacia ese objetivo.

Las migas de pan del rastro pueden ser monedas de oro giratorias que recoger, galletas que comer, rocas que romper, cofres del tesoro que abrir, u otra cosa. En muchos diseños de juegos de mesa, el tablero físico actúa como rastro, donde solo puedes moverte a cierta ubicación siguiendo un camino especificado. El jugador tiene casi garantizado obtener toda la información crucial a lo largo del camino, a partir del propio tablero.

Aun así puede ser útil añadir incentivos para ir a ciertos lugares o tomar ciertas decisiones, como hacen algunos juegos de mesa basados en roles, que añaden una recompensa creciente a los roles que se eligen con menos frecuencia. Por ejemplo, añadiendo una moneda adicional a una opción específica cada turno en que no se selecciona.

En muchos juegos de acción con combate, dejas migas de pan usando enemigos que el jugador tiene que derrotar. Los jugadores normalmente se mueven hacia los enemigos que no han sido derrotados sin que tengas que decírselo, y así son guiados hacia donde necesitan ir sin pensarlo realmente.

### Dejar un rastro de migas de pan

- Identifica tus migas de pan:
  - **Progresión:** cargar el siguiente nivel. Desbloquear una nueva *feature*. Puedes dejar migas de pan con carteles claros de SALIDA, puntos de referencia en la interfaz, puertas, flechas, iluminación, elecciones de color, y así sucesivamente.
  - **Acciones:** enemigos que combatir, casillas del tablero con forma de carta donde jugar cartas, plataformas elásticas desde donde rebotar y casillas que marcar en tu hoja de personaje. Muchas acciones marcarán el camino hacia adelante con suavidad, especialmente si se pueden vincular a elementos visuales del mundo del juego o de la interfaz de usuario.
  - **Incentivos:** monedas, munición, coleccionables, robos de cartas adicionales y tesoros; todos los que alguna vez jugaron un juego 3D y miraron debajo de una escalera para encontrar algo de munición extra fueron guiados hasta ahí "con migas de pan" por la promesa de jugosos objetos que recoger.
- Averigua adónde quieres que vaya el jugador o qué decisiones quieres que tome y no está tomando.
- Añade migas de pan hacia esas decisiones:
  - Primero, usa Incentivos, ya que son menos disruptivos y guían al jugador con más suavidad. Es una promesa tentativa más que llevarlo de la mano.
  - Segundo, usa Acciones. Cosas que el jugador hará de todos modos, solo que ahora las usas para guiarlo hacia adelante. El riesgo de hacer esto demasiado es que las migas de pan se vuelvan demasiado obvias o la acción tediosa.
  - Tercero, usa migas de pan de Progresión. Si nada más funciona, esta puede ser tu única opción. Pero es la última opción porque corre el riesgo de disminuir la sensación personal de descubrimiento del jugador.

![Ilustración: tres tipos de migas de pan — incentivos (Pac-Man con puntos, un cofre), acciones (un enemigo custodia una puerta) y progresión (cartel de salida)](img/game-design-toolbox/p123.png)

> **Texto de la ilustración:**
> - Izquierda: un Pac-Man seguido de una fila de puntos, un símbolo de poder y un cofre del tesoro. Etiqueta: **1) INCENTIVOS** (tesoros, objetos que recoger, galletas, etc.)
> - Arriba a la derecha: un enemigo con casco y espada en alto frente a una puerta grita: "¡Nunca pasarás por encima de mí, hacia esta puerta! ¡Nunca!". Etiqueta: **2) ACCIONES** (derrotar al enemigo que custodia la puerta.)
> - Abajo a la derecha: una puerta con un cartel de "SALIDA" (*EXIT*) y una flecha con el texto "¡La salida está por aquí!". Etiqueta: **3) PROGRESIÓN** (finalización y condiciones de fin.)

## HAZ QUE ESCALE (*MAKE IT ESCALATE*)

Yo ataco; tú bloqueas. Tú atacas; yo bloqueo.

Dos secuencias de acción sin exactamente ningún resultado en su haber, salvo quizás algo de suspenso. Podría haber un millón de secuencias de acción del mismo intercambio repetido y nunca pasaría nada. Nos quedaremos ahí parados, turnándonos para atacar y bloquear hasta que nos aburramos y abandonemos el juego.

Un intercambio en el que la suma total de los recursos del juego no cambia puede denominarse un intercambio de "suma cero". Es de suma cero porque la ganancia de una persona es igual a la pérdida de otra. Es algo que fácilmente conduce a un ida y vuelta sin interés.

En general no quieres intercambios de suma cero en tus interacciones de *gameplay*. En cambio, quieres que tus escenas escalen, haciendo que cuesten o generen recursos para construir hacia un desenlace convincente. Hacer que ocurra algo que genere impulso hacia adelante y garantice que el juego siempre se sienta como si fuera hacia algún lado.

De aquí vienen las barras de resistencia, los contadores de munición, los temporizadores de cuenta regresiva y muchos otros diseños. Hacen que el juego escale, moviéndose constantemente hacia una condición de derrota que el jugador solo puede evitar interactuando con el juego.

### ¡Escala!

- **Haz que crezca:** dale al jugador una sensación de escalada desde el sistema. Desde sus propias habilidades en mejora, que le permiten manejar mayor complejidad, y desde la representación visual o física del juego. Por ejemplo, haciendo que al principio lance un dado y luego lance más dados a medida que progresa. Combatir a un enemigo al principio; luego combatir a 100 cerca del final.
- **Añade un costo:** para variar el ritmo, puede haber costos o rendimientos decrecientes para las acciones repetitivas. Piensa en el maná para lanzar hechizos, la resistencia para seguir atacando, o la munición o durabilidad de tu arma que disminuye gradualmente y te obliga a repararla, recargarla o cambiar a otra cosa.
- **Añade una ganancia:** añadir más recursos a la simulación le dará ventaja al bando que acumule la mayor parte. Si la ganancia es algo que se puede disputar, como potenciadores que aparecen al azar o robos de cartas, también crea un incentivo para que los jugadores lleguen al recurso antes que los demás.
- **Añade elecciones:** la escalada también puede convertirse en una elección del jugador. Qué arma usar; a qué distancia enfrentarse; cuándo pasar del sigilo al combate; cómo cronometrar la micro bomba nuclear; cuándo usar tu carta de contraataque de "juégala en cualquier momento".
- **Permite movimientos de remate:** algunos juegos permiten a los jugadores acumular gradualmente recursos que les permiten no solo escalar, sino ir directamente por un final. Un movimiento de remate es victorioso, sea lo que sea que eso signifique para tu juego.
- **Permite la retirada:** lo opuesto a un movimiento de remate. Cuando el jugador da un primer paso tentativo sobre el puente de cuerdas y oye el crujido ominoso, puede decidir no apoyar su peso e ir a buscar otro camino. O, cuando ve que la competencia por los recursos se vuelve en su contra, puede irse para pelear otro día.

![Ilustración: dos luchadores intercambian golpes en un bucle infinito; abajo, tres maneras de escalar: escalado, gestión de recursos y movimientos de remate](img/game-design-toolbox/p125.png)

> **Texto de la ilustración:**
> - Título superior: "Esto podría seguir para siempre:" — dos personajes que se golpean mutuamente, con flechas circulares que indican un bucle.
> - Título inferior: "A menos que de alguna manera escale:"
>   - **ESCALADO** (*Scaling*): un personaje enfrenta a dos oponentes.
>   - **GESTIÓN DE RECURSOS**: un golpe con una barra de resistencia y la etiqueta "−5 resistencia".
>   - **MOVIMIENTOS DE REMATE**: un golpe que deja al oponente noqueado (ojos en X).

## DALES ZANAHORIAS (*GIVE THEM CARROTS*)

Si te olvidas de desayunar en algunos juegos de supervivencia, mueres de hambre antes del almuerzo. Difícilmente sea una experiencia divertida para un jugador que lucha por recolectar bayas mientras aprende los controles.

De manera similar, un jugador puede no haber usado nunca la habilidad de robar cartas de su personaje y sentir que, como resultado, nunca tiene suficientes cartas. Esto se convierte en un problema para tu juego porque significa que los jugadores no se divertirán, y es muy probable que culpen al juego por ello.

Algunos juegos se sienten demasiado castigadores, o no logras que los jugadores interactúen con lo que crees que son las *features* más geniales del juego. Esta es una excelente oportunidad para recurrir a las zanahorias, recompensando el éxito del jugador en lugar de castigar su fracaso.

En el ejemplo del juego de supervivencia, podría ser cambiarlo de que la inanición cause la muerte a que el jugador se beneficie de haber comido, por ejemplo ganando puntos de experiencia extra, moviéndose más rápido, o algo similar.

En el juego de cartas, puede ser simplemente que puedas robar más cartas si juegas más cartas, por ejemplo, permitiéndote robar siempre hasta un número fijo de cartas al comienzo de tu turno.

### Añade zanahorias

- **Potenciación (*boosting*):** a pocos jugadores hay que convencerlos de agarrar potenciadores cuando los encuentran. Son las cosas que los hacen moverse más rápido, hacer más daño, ganar más puntos, robar más cartas, etc. Un potenciador de algún tipo es una zanahoria eficiente. Compara comer para ganar más puntos con comer para no recibir daño por inanición.
- **Premios por completar:** repetir cierta acción o actividad un número de veces para obtener una recompensa acordada. Para algunos jugadores, el acto de tachar una tarea así ya es recompensa suficiente.
- **Premios por participación:** solo por hacer que el jugador se presente a algo, le das una recompensa. La primera vez que usa una *feature*, gana algo, o la primera vez que visita una nueva ubicación o entra en una nueva casilla del tablero.
- **Premios de consuelo:** cuando llegas último, o no logras completar una tarea a tiempo, aun así puedes obtener algo. Un premio de consuelo. En el mejor de los casos, esto enseñará a los jugadores a seguir intentando y les quitará parte del estrés del fracaso. Pero también puede devaluar la sensación de logro al superar un desafío, así que debe usarse con cuidado.
- **Recompensas aleatorias:** al describir la psicología del condicionamiento operante, B.F. Skinner escribe: "hacemos que una consecuencia dada dependa de ciertas propiedades físicas del comportamiento […], y entonces se observa que el comportamiento aumenta en frecuencia". Es decir, si te damos una recompensa consistente por un comportamiento físico, te involucrarás más en ese comportamiento. Esta es un área en la que las recompensas aleatorias se usan a menudo en los juegos. Botín que cae, robos de cartas y cofres del tesoro. Si no logras motivar a tus jugadores de otras maneras, repartir recompensas aleatorias puede ser el último recurso. Para muchos jugadores, es la zanahoria más jugosa.

![Ilustración: tres tipos de zanahorias — potenciación por desayunar, logro por completar la introducción y premio de consuelo bajo una escalera](img/game-design-toolbox/p127.png)

> **Texto de la ilustración:**
> - Personaje con globo: "¡Acabo de desayunar!" y un cartel: "¡+100% de experiencia!". Etiqueta: **POTENCIACIÓN** — Incentiva ciertas acciones haciendo que vuelvan más efectivas otras acciones.
> - Cartel con un candado abierto: "LOGRO DESBLOQUEADO — Viste toda la introducción". Etiqueta: **COMPLETAR** — Recompensas por terminar algo.
> - Una escalera con un par de objetos debajo. Etiqueta: **PREMIOS DE CONSUELO** — No queríamos que miraras debajo de la escalera, pero ya que lo hiciste, ¡aquí tienes algunas cosas!

## QUÉMALOS EN LA ESTUFA (*BURN THEM ON THE STOVE*)

A los niños les dices que no pongan la mano en la proverbial estufa. Cuando inevitablemente lo hacen de todos modos, aprenden por las malas por qué no deberían, y esto refuerza tu mensaje mucho más de lo que cualquier cantidad de regaños podría hacerlo jamás.

Esto puede ser igual de efectivo para enseñar a los jugadores qué hacer, demostrando claramente lo que deberían evitar. Primero les dices lo que no deberían hacer, y luego, cuando lo hacen de todos modos, les das un "dolor" duradero: los quemas en la estufa.

Mientras este efecto se active clara y consistentemente por el mismo comportamiento, los jugadores aprenderán a evitarlo. Quizás incluso practiquen evitarlo, convirtiéndolo en un elemento de habilidad de tu juego.

En algunos tipos de juegos, donde los bucles están claramente dirigidos y los jugadores tienen que realizar ciertas acciones en cierto orden, esto puede denominarse "aprender muriendo". Hasta que completes el bucle deseado, cualquier acción que hagas fuera de secuencia te matará y reiniciará el estado del juego para que lo intentes de nuevo.

Muchos de los Call of Duty para un jugador usan este tipo de enseñanza, al igual que la popular serie Dark Souls, aunque de una manera muy distinta.

Quizás el ejemplo más claro de "aprender muriendo" está en juegos como Hotline Miami, donde el ritmo es extremadamente rápido y entrarás en una fase, probarás un enfoque, morirás, probarás otro enfoque, y seguirás haciéndolo hasta que tengas éxito. (O abandones.)

### Añade estufas

- **Aturdimientos:** cualquier efecto que te deshabilite temporalmente es, en efecto, un "aturdimiento". Puede ser perder un turno en un juego de mesa, tener que caminar de vuelta hasta tu cadáver en un juego de rol multijugador masivo en línea (MMORPG) para reaparecer, quedar cegado momentáneamente, o que tu arma se sobrecaliente por el uso repetido, etc.
- **Obstaculización:** un obstáculo es un efecto negativo —el inverso de un potenciador— que te causa una molestia duradera hasta que haces lo que se espera que hagas para librarte de él. Moverte más lento, la visión más borrosa, jugar con menos cartas en la mano, tener los controles invertidos, etc.
- **Negación de feature:** consiste en que una de tus *features* estándar sea castigada si la usas. Descartar una carta, recibir algo de daño y caerte; lo que se te ocurra, se activa al usar la *feature* que actualmente te está negada. La *feature* puede seguir funcionando y tener este efecto encima, o puede reemplazarse por completo por el efecto de negación.
- **Pérdida de feature:** la pérdida completa de cierta *feature* es otra manera de quemar a los jugadores en la estufa. Quitar la capacidad de correr porque llevas demasiadas cosas, por ejemplo, o hacer imposible atacar si agotaste toda la resistencia que te quedaba.
- **Inversión:** enséñale al jugador que algo que hace a menudo es algo bueno, y luego castígalo de repente por ello. El clásico mímico de Dungeons & Dragons es quizás el mejor ejemplo de este tipo de inversión. Los aventureros siempre corren hacia los cofres del tesoro en busca de oro, ¡y de pronto un cofre les arranca el brazo de un mordisco! A todo cofre del tesoro futuro se le disparará una flecha antes de abrirlo.

![Ilustración: tres ejemplos de estufas — un arma que hace "clic" (aturdimiento), una carta que obliga a descartar toda la mano (negación) y un cofre que resulta ser un mímico (inversión)](img/game-design-toolbox/p129.png)

> **Texto de la ilustración:**
> - Arriba, dos jugadores de cartas. La de la izquierda, sonriente: "Juego '¡Te agarré!'. Descarta TODAS tus cartas." El de la derecha, angustiado: "Me olvidé de esa carta…". Etiqueta: **NEGACIÓN** — Quitar algo por completo.
> - Abajo a la izquierda, un soldado apunta con un arma que solo hace "¡CLIC!". Etiqueta: **ATURDIMIENTO** — Deshabilitar algo temporalmente.
> - Abajo a la derecha, un cofre cerrado → un cofre abierto lleno de dientes. Etiqueta: **INVERSIÓN** — Los jugadores quieren abrir cofres del tesoro. ¡Pero oh, no! ¡Era un mímico!

## RESUELVE PROBLEMAS (*SOLVE PROBLEMS*)

Disculpas por señalar lo obvio en un capítulo sobre resolución de problemas, pero este es un recordatorio muy importante para no quedar atrapado en minucias.

Si te encuentras en discusiones interminables que parecen no llevar a ningún lado, pregúntate "¿qué problemas estamos resolviendo ahora mismo?". Si no hay una respuesta clara, posterga la discusión y sigue adelante. A esta altura del ciclo de vida de un proyecto, ya no deberías estar haciendo lluvias de ideas libres. Por eso este recordatorio es importante.

Si no estás resolviendo un problema, y ya no estás ideando ni explorando, lo más probable es que tu discusión no valga la pena. Este es un gran riesgo en todo tipo de emprendimiento creativo, y a veces puede sentirse humillante que te digan que la discusión que intentas tener no vale la pena, pero cuanto más rápido puedas llegar a la mentalidad de "¿qué problemas estamos resolviendo ahora mismo?", menos tiempo se desperdiciará.

Hay tres áreas específicas donde esto es especialmente importante.

Los escritores pueden inventar ideas con ramificaciones a gran escala en el tiempo que toma formar un pensamiento y ponerlo en papel. Ya sea cambiando el alcance del proyecto o llevándolo en una dirección inexplorada, estos cambios deben mantenerse bajo control.

Los artistas pueden hacer lo mismo, en particular los bocetistas y los artistas conceptuales, donde una mano rápida puede inventar algo cautivador en cuestión de segundos.

Por último, los diseñadores de juegos; probablemente los infractores más consistentes cuando se trata de idear cosas nuevas que provocan cambios a gran escala. Pero si sigues haciendo esto a esta altura de un proyecto, has decidido quedarte en el Nivel 1. No necesitamos ninguna de las travesuras del diseñador de juegos de Nivel 1 ahora mismo. ¡No para este proyecto! Vuelve a resolver problemas.

### Pregunta "¿Qué problemas estamos resolviendo?" cuando…

- …estás discutiendo algo que no tiene ninguna *feature* tangible ni contenido del juego conectado a ello.
- …estás trabajando en textos o incluso documentos enteros donde nada del material está de cara al jugador.
- …empiezas a discutir cosas que conciernen a la trama, los personajes, los niveles, rediseños fundamentales del tablero u otros elementos del juego que son caros de hacer, demasiado tardíos para considerar, o prácticamente improbables de que realmente ocurran.
- …empiezas a hablar de las cosas geniales del último juego taquillero y de cómo quizás podrías hacer esas cosas también en tu juego.
- …sacas temas que afectarían las cosas drásticamente, y los dueños de dicho trabajo ni siquiera forman parte de la conversación.
- …vuelves a un tema que es importante para alguien personalmente pero que no es de lo que realmente se supone que deberías estar hablando ahora mismo.
- …te enredas demasiado en anécdotas, suposiciones, extrapolaciones arbitrarias u otras desviaciones muy probablemente irrelevantes. Ten en cuenta que cualquier afirmación sobre lo que los jugadores podrían querer, sin evidencia de *playtesting*, es exactamente esto.
- …empiezas a hablar de cosas que quizás quieras o no hacer en el futuro y que no conciernen al juego en el que realmente estás trabajando ahora.

![Ilustración: cuatro miembros del equipo lanzan ideas fuera de lugar mientras otro pregunta en grande qué problemas están resolviendo](img/game-design-toolbox/p131.png)

> **Texto de la ilustración:** cuatro personajes a la izquierda hablan en globos; un personaje a la derecha responde con un globo enorme.
> - "Ha habido un disturbio en las montañas-bosque de los elfoenanos. Hay muchos rumores, pero nadie está del todo seguro de qué pasó, y está lloviendo demasiado para que alguien investigue."
> - "¿Quizás deberíamos cambiarlo para que juegues como roedores en lugar de murciélagos vampiro?"
> - "Creo que necesitamos más armas. Me estoy cansando un poco de las 1.305 armas que ya tenemos."
> - "¡Esta idea para la secuela sería tan increíble! ¡Escúchenme!"
> - Globo grande: "**¿QUÉ PROBLEMAS ESTAMOS RESOLVIENDO AHORA MISMO?**"

## DEJA COSAS ATRÁS (*LEAVE THINGS BEHIND*)

A veces, algo surge como problema una y otra vez. No se siente bien, no es divertido y recibe *feedback* negativo de manera consistente. Está claro que algo anda mal con esta cosa. Pero aun así sientes que es una *feature* clave que tiene que quedarse, porque ha estado contigo desde el principio, o porque en su esencia es una *feature* agradable.

Prueba jugar tu juego sin esta cosa. Si es un subsistema enorme con partes interconectadas, puede ser complicado hacer ese *playtest*, pero asegúrate de hacerlo. Luego juega sin la *feature* durante un tiempo antes de volver a la conversación.

Hay más probabilidades de las que crees de que el sistema o la *feature* simplemente no pertenezca a tu juego y de que el mejor curso de acción sea dejarlo atrás.

Pero hay una razón por la que decimos que lo estás dejando atrás y no simplemente borrándolo.

Cada vez que dejas atrás una *feature*, amplías tu biblioteca de *features* de *gameplay* futuras potencialmente increíbles. Con más tiempo, madurarán, y puede que descubras maneras de resolver los problemas que la *feature* tenía en el pasado. O puede que descubras una nueva solución técnica o una *feature* complementaria que le permita tener más sentido y volverse aún mejor.

Así que, por favor: deja cosas atrás. Hazlo más de lo que crees que deberías. Las ideas solo mejoran con el tiempo.

### Cuándo dejar cosas atrás

- Cuando múltiples *features* cumplen la misma función, puedes dejar una de ellas atrás, a menos que puedas diferenciarla lo suficiente como para hacerla relevante.
- Cuando estás defendiendo una *feature* específica desde tu perspectiva como diseñador, y no por el beneficio del jugador, y no encuentras otras razones para la existencia de la *feature* en el juego actual que tu propia vanidad, definitivamente deberías dejarla atrás. Como diseñador de Nivel 3 o 4, tu intuición bien puede valer la pena escucharla en casos como este. Pero incluso entonces, la vanidad no es una gran razón para conservar *features*.
- Cuando lo que estás defendiendo no encaja con el tema o representa algo que los jugadores no querrán hacer en este juego en particular, puedes dejarlo atrás sin problema. La misión secundaria de cocina en tu juego de ajedrez quizás suene brillante y podría ser todo un juego por derecho propio, pero concentrémonos en el ajedrez por ahora.
- Cuando la *feature* es algo que has mantenido en el juego porque estaba destinada a resolver un problema, pero el problema ya se resolvió de otras maneras, entonces puedes dejar atrás la vieja solución. Antes de tener las alas, añadiste el larguísimo *dash* en el aire. Con las alas en su lugar, quizás el *dash* debería irse.
- Cuando una *feature* está completamente aislada de las demás *features*, sirviendo solo a un único propósito estrecho, puede valer la pena reevaluarla y posiblemente dejarla atrás. Si hay un solo lugar en tu gigantesco juego de mundo abierto donde haces uso de la escalera de cuerda especial impulsada por físicas, puede que no valga la pena el esfuerzo de depuración para conservarla.

![Ilustración: una diseñadora empuja un carrito con cajas de ideas descartadas mientras otro personaje la consuela](img/game-design-toolbox/p133.png)

> **Texto de la ilustración:** una diseñadora empuja un carrito con tres cajas etiquetadas "MOBA en primera persona", "Mecánica de triple dash" y "Múltiples mazos de robo". Otro personaje la mira.
> - "¿Dejando atrás algunas ideas más?"
> - "¡Sí! La verdad es que creo que las voy a extrañar."
> - "No te preocupes. ¡Algún día las volverás a ver!"

---

# Capítulo 6 — Balanceo (*Balancing*)

A esta altura, el juego funciona en lo fundamental, pero todavía no está del todo listo para el mercado masivo. Sin embargo, debería estar listo para tus fans y para los fans de juegos similares. Listo para un escrutinio más cuidadoso.

Aquí es donde puedes hacer pruebas beta o algo parecido. Discute el proyecto en foros, en conferencias o en encuentros de desarrolladores, si tienes el lujo de contar con una comunidad existente.

Después de haber resuelto problemas durante un tiempo, ya conoces todos los deslizadores, variables y detalles de hojas de cálculo con los que tienes que trabajar. Entonces viene el proceso más fino de balancear todo eso hasta formar un todo cohesivo y atractivo.

Sigues jugando y observando a otros jugar, pero lo haces para observar los resultados de tu *balanceo*. Es el equivalente, en diseño de juegos, del pulido visual.

El balanceo cumple varios propósitos:

- Llevar el juego completo a un estado jugable que comunique a todos de qué trata el juego y cómo es jugarlo: ya no solo en teoría.
- Recortar *features* innecesarias.
- Moderar las cosas que son demasiado extremas.
- Intensificar las cosas que no son lo suficientemente extremas.
- Pulir cómo se comunican a los jugadores las sinergias y las features.

## UNA COSA A LA VEZ (*ONE THING AT A TIME*)

Antes de entrar en herramientas más prácticas relacionadas con el balanceo, hay algo importante que requiere mención: el foco. Hay una paradoja en el balanceo que dice algo así: lo más fácil en el balanceo es obtener los resultados que quieres; lo más difícil en el balanceo es entender cómo.

Lo que suele terminar pasando es que cambiamos muchas cosas al mismo tiempo, y se vuelve imposible decir cuál fue el cambio que realmente mejoró las cosas. En particular si hay varias personas intentando producir el mismo cambio de distintas maneras.

Si sentimos que el combate es demasiado rápido, por ejemplo, podemos reducir el daño de las armas, aumentar la salud de los enemigos, cambiar el alcance efectivo de las armas, retocar la cantidad de munición disponible, alterar el multiplicador que se aplica a un impacto en la cabeza del enemigo, y así sucesivamente. Pero lo que ocurre si hacemos todos esos cambios a la vez es que no tenemos idea de cuál cambio hizo realmente que el combate se sintiera mejor. Logramos nuestro resultado, pero no sabemos cómo.

Por eso, debes andar con cuidado con los cambios de balanceo y enfocarte en una cosa a la vez.

### Mantener el foco

Cuando balancees cosas, limítate a hacer un cambio en un área y luego probarlo.

Las siguientes son las áreas que típicamente necesitan balanceo:

- **Datos:** cambia el 1 por un 2, o el color rojo por azul. Los datos suelen ser lo más fácil de cambiar, y un buen pipeline de desarrollo te permitirá hacer cambios en bloque. Por ejemplo, "duplicar el daño de todas las armas" o "reducir a la mitad la salud de todos los enemigos".
- **Sistema:** haz cambios en el flujo de los datos. Dónde se usan como entrada, de dónde salen como salida y cómo generan *feedback* para los jugadores. Sin embargo, es importante separar esto de los datos. Si cambias cómo se usan los datos, no deberías también hacer cambios en los datos. Piensa en el sistema como las reglas que gobiernan tu juego. Si estás cambiando las reglas, estás cambiando el sistema, y entonces no deberías cambiar también los datos.
- **Contenido:** reemplaza cartas o mazos enteros, retoca modelos 3D, haz cambios en el diseño de niveles y realiza otros cambios más extensos que suelen tardar más en hacerse y probarse. También pueden requerir el apoyo de especialistas como artistas o diseñadores de niveles. Al igual que con los otros cambios, si haces cambios en el contenido, no cambies datos ni sistemas al mismo tiempo, a menos que debas hacerlo por cómo están vinculadas las cosas.
- **Eliminación:** cualquier cosa que cambiarías en las áreas anteriores también puedes simplemente eliminarla y probar sin ella. Eliminar sistemas que sabes que funcionan puede ayudarte a estrechar tu foco exactamente a los retoques que marcan la mayor diferencia. Pero también puede hacer que olvides las sutilezas del juego completo, así que debes hacerlo con cuidado.

![Ilustración: dos diseñadores cambian varios valores a la vez y luego no entienden por qué los goblins mueren tan rápido](img/game-design-toolbox/p137.png)

> **Texto de la ilustración:**
> - Arriba a la izquierda (valores iniciales): "JUGADOR — Daño de ataque: 20 — Velocidad de ataque: 1".
> - Arriba a la derecha (valores finales): "JUGADOR — Daño de ataque: 40 — Velocidad de ataque: 10".
> - Globo de diálogo: "¡Los goblins aguantan demasiado daño!"
> - Caja de borde dentado (primer cambio): "Multiplicar la velocidad de ataque por 10 — Duplicar el daño".
> - Tres caras de goblin en el centro: una sonríe con malicia, otra se ve confundida y la tercera está muerta (ojos en X).
> - Caja de borde dentado (segundo cambio): "Reducir a la mitad la salud del goblin — Quitar la armadura del goblin".
> - Globo de diálogo: "¿¡Por qué los goblins están muriendo tan rápido!?"
> - Abajo a la izquierda (valores iniciales): "GOBLIN — Salud: 100 — Armadura: 10".
> - Abajo a la derecha (valores finales): "GOBLIN — Salud: 50 — Armadura: 0".

## HAZ PREGUNTAS ASTUTAS (*ASK SLY QUESTIONS*)

En un proyecto en particular, que era un shooter en primera persona (FPS) cooperativo, teníamos algunas limitaciones estrictas. Estas limitaciones dictaban que no podía haber más de ocho enemigos activos en un momento dado.

Al principio, esto parecía restrictivo. Parecía que los jugadores se aburrirían rápido con tan pocos enemigos con los que interactuar. Pero cuando lo jugamos nosotros mismos, nunca sentimos que fuera un problema. No después de haber hecho que el juego fuera interesante de jugar bajo esas circunstancias.

El diseñador principal ideó una manera de probarlo. En lugar de preguntar lo que queríamos saber —"¿ocho enemigos son demasiado pocos?"—, les preguntó a los testers: "¿contra cuántos enemigos estabas peleando a la vez?".

Con el ritmo rápido del juego (medido como cuántos segundos permanecía vivo el enemigo promedio), las respuestas de los jugadores estaban repartidas por todo el espectro. La mayoría respondía que había alrededor de 12–15 enemigos, pero algunos respondieron hasta 30 (!).

Esto dejó claro que cómo haces una pregunta es sumamente relevante. Nuestro temor de que ocho fueran demasiado pocos simplemente carecía de fundamento, porque los jugadores sentían que había muchos más.

Hacer preguntas de manera que la respuesta te informe sobre cosas aparentemente no relacionadas es un arte, pero uno que necesitarás practicar mucho como diseñador de juegos. En el momento en que empiezas a preguntar de manera explícita, a menudo perderás las respuestas más relevantes.

### Preguntas astutas

- Pregunta a los *playtesters* cómo se sienten las cosas, en lugar de cómo creen que funcionan. Si es posible, vincula estas preguntas directamente con problemas que crees que puedes tener o que han sido reportados por otros playtesters, tal como en el ejemplo del número limitado de enemigos.
- Pregunta a los playtesters adónde iban, en lugar de por qué se perdieron. Insinuar que un playtester hizo algo mal a veces puede afectar el resultado, porque intentará remediar sus "errores" en sus respuestas. Es mejor dejar que describan qué pasó, cómo y por qué, contigo como un indagador neutral.
- Da opciones a los playtesters en lugar de hacerles preguntas abiertas. Mantén las opciones concisas y específicas.
  - Preguntas A/B: "¿Crees que el personaje principal es genial? Sí/No".
  - Comentario: "Sobre el personaje principal, ¿qué te hace sentir así?". Nota aquí: evita "si respondiste que sí, ¿qué te hace sentir así?", por la misma razón de neutralidad mencionada antes.
  - Preguntas graduadas: "En una escala de 1 a 10, ¿cómo calificarías el ritmo de este juego? 1 = Muy lento, 5 = Promedio, 10 = Muy rápido". Lo complicado de las calificaciones con puntos es que los valores más altos implicarán una mejor respuesta, y eso no siempre es deseable. Ten cuidado con lo que implicas con tus calificaciones altas.
  - Últimas reflexiones: "¿Alguna última reflexión sobre el personaje principal que quieras compartir?" debe separarse de "¿Alguna última reflexión sobre el ritmo del juego?". Solo por claridad. Haz este tipo de preguntas únicamente si tienes inquietudes sobre alguna área de tu juego.

![Ilustración: un diseñador con libreta entrevista a un jugador abatido frente a una pantalla que dice "¡Moriste!"](img/game-design-toolbox/p139.png)

> **Texto de la ilustración:**
> - Globo (diseñador, con libreta y lápiz): "¿Cuántas veces crees que has muerto hasta ahora?"
> - Globo (jugador): "Eh, ¿quizás 1.000?"
> - Globo (diseñador): "Cuando mueres así, ¿cómo te hace sentir?"
> - Globo del diseñador, pequeño: "..."
> - Nube de pensamiento (jugador, con la cabeza convertida en un garabato y gotas de sudor, mando en mano): "Me siento vacío por dentro."
> - Pantalla del televisor: "¡MORISTE!"

## EVITA LA DOMINACIÓN (*AVOID DOMINATION*)

A veces verás a los jugadores usar la misma *feature* constantemente, y está bien. Nunca prohibirías robar cartas en un juego de cartas, por ejemplo. Eso sería simplemente absurdo. Pero a veces ocurre porque otras features no son tan buenas o porque esa feature específica es demasiado buena.

Hay dos casos en los que esto es un problema (tomados del concepto de dominancia estratégica de la teoría de juegos):

El primero se llama estrategia dominante, en la que una estrategia siempre lleva a mejores resultados. No hay necesidad de caminar si tienes un sprint ilimitado que puedes usar: junto a caminar, correr se convierte en la estrategia dominante para moverse más rápido.

El segundo es una estrategia dominada, en la que algo es simplemente tanto peor que las otras cosas que nadie lo usa. Quizás no hay necesidad de usar la pistola de un solo disparo una vez que tienes una pistola con cargador, lo que convierte disparar con la pistola de un solo disparo en una estrategia dominada.

Hay casos en los que la dominación puede ser algo que quieres. Si esa primera arma es un arma icónica que define al personaje que la usa, entonces quizás debería ser una opción dominante, porque el jugador la estará usando durante todo el juego.

En Marvel's Spider-Man, balancearse con telarañas es definitivamente una opción dominante comparada con caminar, por ejemplo. Esto es enteramente por diseño. Solo necesitas evitar la dominación cuando hace que tu juego sea menos interesante o no encaja con la premisa del juego.

### Eliminar estrategias dominantes

- **Guárdala para más tarde:** si necesitas mantenerla tal cual por la razón que sea, pospón el acceso a la estrategia dominante a una etapa posterior del juego. Esto no elimina su dominancia, pero la convierte más bien en una recompensa, parecida a un *powerup*.
- **Añade restricciones de reglas:** quizás la estrategia dominante solo se pueda emplear bajo ciertas circunstancias. Una muerte sigilosa en un juego de Hitman, por ejemplo, que solo se puede ejecutar fácilmente cuando el enemigo no es consciente del avatar del jugador, el Agente 47.
- **Añade restricciones de uso:** quizás la estrategia dominante solo se pueda usar una vez, cueste una cantidad significativa de recursos o desencadene una peligrosa avalancha al usarla. Tener que considerar el uso más allá de la ganancia inmediata hará que la estrategia sea menos dominante.

### Eliminar estrategias dominadas

- **Añade una ventaja de recursos:** quizás este tipo de combustible no es genial, pero es abundante. Puedes encontrarlo casi en cualquier lugar, y en grandes cantidades. Hacer que la opción menos favorecida sea más abundante o incluso ilimitada la convierte en un respaldo seguro más que en una opción dominada.
- **Añade protección de nicho:** quizás la pistola de un solo disparo no es tan genial, pero más adelante en el juego resulta que es la única arma que puede dañar a los hombres lobo. De repente es la pistola mata-hombres-lobo de un disparo y su uso ya no es una estrategia dominada.

![Ilustración: un guerrero con una espada enorme (dominante) frente a otro con un cuchillo diminuto (dominado), con las soluciones para cada caso](img/game-design-toolbox/p141.png)

> **Texto de la ilustración:**
> - Arriba a la derecha, título: "DOMINANTE — Espada grande y genial; hace mucho daño y tiene gran alcance."
>   - Guárdala para el final del juego.
>   - Añade restricciones de reglas: ¡los esqueletos enemigos son inmunes!
>   - Añade restricciones de uso: ¡no se puede llevar una espada en la ciudad!
> - Dibujo: a la derecha, un guerrero con casco sostiene una gran espada; a la izquierda, otro guerrero sostiene un cuchillo pequeño; una flecha curva va del guerrero de la espada al del cuchillo.
> - Abajo a la izquierda, título: "DOMINADO — Cuchillo diminuto; casi nada de daño y sin alcance."
>   - Ventaja de recursos: siempre conservas la daga; la durabilidad solo rompe las otras armas.
>   - Protección de nicho: ¡los cuchillos se pueden usar para muertes sigilosas!

## DUPLICA O DIVIDE A LA MITAD (*DOUBLE OR HALVE*)

Tu primer recurso para balancear números debería ser duplicarlos o dividirlos a la mitad. Si tienes demasiadas cartas en tu mazo, prueba usar la mitad. Si tienes muy pocas, prueba con el doble. Esta es una de las formas más rápidas y confiables de abordar muchos problemas de *balanceo* y, en muchos casos, es todo lo que realmente necesitas.

Naturalmente, duplicar y dividir a la mitad una y otra vez no te servirá de mucho; es el equivalente en balanceo de correr en círculos. Pero como primer retoque a algo que necesita balanceo, duplicar o dividir a la mitad es probablemente la mejor herramienta que existe.

### Ejemplos de duplicar o dividir a la mitad

- Duplica o divide a la mitad la duración esperada de una sesión de juego.
- Duplica o divide a la mitad la cantidad de daño de un arma.
- Duplica o divide a la mitad el tiempo permitido para un doble clic en el sistema de entrada.
- Duplica o divide a la mitad cuántos enemigos enfrenta el jugador en un encuentro dado.
- Duplica o divide a la mitad la cantidad de puntos otorgados por recoger una moneda.
- Duplica o divide a la mitad cuántas cartas tiene un jugador en la mano.
- Duplica o divide a la mitad el número total de niveles de tu juego.
- Duplica o divide a la mitad el tamaño de un personaje.
- Duplica o divide a la mitad los precios de la tienda dentro del juego, y revisa los patrones de compra.
- Duplica o divide a la mitad el número de opciones de creación de personaje disponibles.
- Duplica o divide a la mitad la duración del temporizador antes de que el jugador pierda la partida.
- Duplica o divide a la mitad cuántos finales distintos tiene tu historia.
- Duplica o divide a la mitad cuántas acciones obtiene un jugador en cada turno.
- Duplica o divide a la mitad la velocidad de movimiento del jugador.
- Duplica o divide a la mitad el número de puntos necesarios para ganar.
- Duplica o divide a la mitad qué tan grandes son tus componentes físicos.
- Duplica o divide a la mitad el valor de todos los tesoros coleccionables del juego.
- Duplica o divide a la mitad el número de alternativas de diálogo entre las que puede elegir un jugador.
- Duplica o divide a la mitad la longitud y/o la altura del salto del jugador.
- Duplica o divide a la mitad el número de jugadores que pueden jugar al mismo tiempo.
- Duplica o divide a la mitad el número total de cartas del juego.
- Duplica o divide a la mitad cuántas palabras se permiten por bloque de texto dirigido al jugador.

![Ilustración: tres ejemplos de duplicar o dividir a la mitad: el precio de un plato de comida, la distancia de un salto y la cantidad de enemigos](img/game-design-toolbox/p143.png)

> **Texto de la ilustración:**
> - Izquierda: un plato humeante con "$50" y la pregunta "¿Demasiado barato o demasiado caro?"; una flecha lleva a "DUPLICA" (plato con "$100") "O" "DIVIDE A LA MITAD" (plato con "$25").
> - Arriba a la derecha: un personaje saltando entre dos plataformas, con la pregunta "¿Demasiado lejos o demasiado corto?"; una flecha doble lleva a "DUPLICA" (plataformas más separadas) "O" "DIVIDE A LA MITAD" (plataformas más juntas).
> - Abajo a la derecha: cuatro enemigos, con la pregunta "¿Demasiados o muy pocos enemigos?"; una flecha lleva a "DUPLICA" (ocho enemigos) "O" "DIVIDE A LA MITAD" (dos enemigos).

## POR 10 (*BY 10*)

A menudo, cuando retocamos cosas, el instinto es hacerlo solo un poquito. Como diseñadores, tenemos una noción de la diferencia que produce un cambio pequeño porque estamos familiarizados con el juego en el que trabajamos, y a veces confundimos esa sensación de familiaridad con una impresión universal.

Pero esto puede no ser suficiente para causar una impresión en las personas que juegan o prueban el juego. Pueden sentir que sigue comportándose exactamente igual.

Por lo tanto, un principio rector rápido para cuando quieres más impacto de un cambio es hacer las cosas en múltiplos de diez.

Quizás resulte que tu juego de 3 minutos de repente es mucho más interesante cuando dura 30 minutos; o que lo que era una pesadez de 30 minutos se convierte en una ráfaga de 3 minutos.

### Ejemplos de por 10

- Multiplica o divide por 10 la duración de la sesión de juego.
- Multiplica o divide por 10 el número de unidades de tu juego de estrategia.
- Multiplica o divide por 10 la salud del personaje del jugador.
- Multiplica o divide por 10 qué tan alto puede saltar el personaje del jugador.
- Multiplica o divide por 10 el valor monetario de tus billetes de papel.
- Multiplica o divide por 10 cuántos zombis tiene un nigromante.
- Multiplica o divide por 10 el tamaño del nivel o del tablero de juego.
- Multiplica o divide por 10 el número de *props* (objetos de utilería) de tu juego.
- Multiplica o divide por 10 la probabilidad de conseguir los mejores tesoros.
- Multiplica o divide por 10 cuánto daño pueden recibir los enemigos.
- Multiplica o divide por 10 la diferencia de tamaño entre las fichas.
- Multiplica o divide por 10 la duración de la fase inicial del juego.
- Multiplica o divide por 10 el número de puntos de control (*checkpoints*).
- Multiplica o divide por 10 cuántos dados lanzan los jugadores.
- Multiplica o divide por 10 el número de alternativas de diálogo.
- Multiplica o divide por 10 los costos de recursos de tu juego.
- Multiplica o divide por 10 cuántas cartas incluyes.
- Multiplica o divide por 10 la cantidad de coleccionables de tu juego.
- Multiplica o divide por 10 con qué frecuencia ocurren los eventos.
- Multiplica o divide por 10 las acciones del jugador por turno.

![Ilustración: tres ejemplos de multiplicar o dividir por 10: el costo de estamina, las unidades de un juego de estrategia y el número de cartas](img/game-design-toolbox/p145.png)

> **Texto de la ilustración:**
> - Arriba a la izquierda: "¿Los costos de estamina se sienten mal?" — una barra de estamina con "−5 de estamina". Tres flechas salen de ella: "¡Multiplica por 10!" (−50 de estamina); "¡Suma 10!" (−15 de estamina); "¡Divide por 10!" (−0,5 de estamina).
> - Abajo a la izquierda: "¿No hay suficientes unidades en tu juego de estrategia? (2)" — dos soldados. Alternativas: "¡Suma 10! (12)" (doce soldados) y "¡Multiplica por 10! (20)" (veinte soldados).
> - Derecha: "¿Número equivocado de cartas? (10)" — una pila de cartas. Flechas: "¡Multiplica por 10! (100)" (diez pilas de cartas) y "¡Divide por 10! (1)" (una sola carta).

## PRUEBA LOS EXTREMOS (*TEST FOR EXTREMES*)

Un "extremo" en este contexto es el valor más alto o más bajo posible que se puede usar para algo en tu juego. Los puntos de inicio y de fin del deslizador que definen el rango de valores que estás considerando.

Por ejemplo, si descubres que un jefe tiene demasiada salud, estableces el valor actual como su máximo, luego lo reduces y vuelves a probar. Cuando encuentras el valor que es simplemente demasiado bajo, usas ese valor como el extremo inferior. El valor viejo es el máximo; el valor nuevo es el mínimo. Ahí tienes tus extremos.

Una vez que tienes ambos extremos, tienes un espectro dentro del cual puedes mantenerte, y simplemente aumentando el mínimo y reduciendo el máximo podrás encontrar gradualmente el punto justo.

Una buena manera de probar dentro de este rango es usar un número aleatorio en cada *playtest* y alcanzar gradualmente dicho punto justo mediante playtesting prolongado. Algo que es igual de efectivo para juegos digitales que para juegos analógicos.

### Usar extremos altos y bajos

- Encuentra una variable de *gameplay* importante o un número base que sientas que necesita trabajo. Es mejor elegir números que sean tan importantes para el juego que probablemente los retoques continuamente a lo largo del desarrollo.
- Aumenta el número máximo de la variable seleccionada por un margen significativo (por diez, para empezar) y juega tu juego con el número cambiado. Cuando sientas que es demasiado, te quedas ahí: este es tu extremo alto.
- Reduce el número mínimo de la variable seleccionada por un margen igualmente significativo (divide por diez) y juega tu juego usándolo. Cuando sientas que es demasiado bajo, te quedas ahí: este es tu extremo bajo.
- Ahora puedes establecer como Hechos que tu extremo Alto es X y tu extremo Bajo es Y. Nunca volverás a ir más alto que Alto ni más bajo que Bajo.
- Cosas en las que puedes usar esta herramienta:
  - Condiciones de fin del juego: número de puntos necesarios para ganar, salud del jefe, duración hasta completarlo, tamaño del mundo, etc.
  - Números de progresión: salud de los enemigos, valor de los objetos recogibles, experiencia necesaria para subir de nivel, cantidad de munición disponible, número total de cartas robadas en toda una sesión de juego, etc.
  - Niveles de dificultad: el Bajo puede ser el punto de partida del jugador, mientras que el Alto es la dificultad más alta soportada.

![Ilustración: extremos de velocidad de movimiento, desde un perezoso hasta Usain Bolt, con una persona caminando en el medio](img/game-design-toolbox/p147.png)

> **Texto de la ilustración:**
> - Título: "EXTREMOS DE VELOCIDAD DE MOVIMIENTO".
> - Flecha a la izquierda: "Tediosamente lento" — un perezoso: "0,07 m/s (perezoso de tres dedos)".
> - Centro: una persona con sombrero caminando: "1,2 m/s (velocidad promedio de caminata humana)".
> - Flecha a la derecha: "Absurdamente rápido" — un velocista: "10 m/s (Usain Bolt)".

## ELEVA LAS COSAS (*LIFT THINGS UP*)

Digamos que has añadido un arma nueva a tu juego. Es divertidísima de usar y los jugadores están respondiendo bien a ella. Pero sientes que está un poco sobrepotenciada. Parece mucho mejor que las otras armas del juego, o al menos más divertida de usar.

La reacción visceral aquí será "nerfear" el arma nueva y ponerla más a la par con las otras armas de tu juego. Pero antes de hacerlo, prueba elevar las otras. Si los jugadores responden bien al arma nueva, puede que hayan dado con algo, y deberías promover eso con lo que dieron.

Sin embargo, antes de hacerlo hay algo que considerar. El riesgo cuando añades algo nuevo y lo encuentras más disfrutable que lo viejo es que en realidad estés cayendo en el sesgo de novedad. Lo nuevo es más divertido porque es nuevo y se siente mejor porque es nuevo. No es realmente más divertido ni mejor, solo nuevo.

Así que antes de empezar a elevar otras cosas, necesitas determinar si lo nuevo es significativamente diferente en absoluto.

### ¿Elevar o dejar?

1. Primero debes averiguar si la cosa es realmente mejor o si solo estás sufriendo el sesgo de novedad. Usa cualquier métrica que sea común entre las *features* comparadas. Decide de antemano qué tipo de resultados te convencerán de que una u otra es mejor; por ejemplo, daño por segundo, número de cartas robadas o algo más. Tiene que ser medible. "Se siente más rápido/más fuerte" no es suficiente.
2. Si lo nuevo no es demostrablemente mejor en absoluto, entonces no tenías un problema para empezar; simplemente caíste en el sesgo de novedad. Pero si lo nuevo es demostrablemente mejor, considera las dos estrategias siguientes:
   - a. ¿Qué haría falta para que las otras opciones de tu juego produzcan los mismos resultados que lo nuevo?
   - b. ¿Qué haría falta para que esta nueva opción rinda como las otras opciones de tu juego en lugar de destacarse?
3. Implementa el cambio que suene más razonable y que además encaje en tu presupuesto y cronograma.

![Ilustración: un personaje entusiasmado con una mega-capa de +50% de velocidad de vuelo junto a un perchero de capas de +10%](img/game-design-toolbox/p149.png)

> **Texto de la ilustración:**
> - Título: "¡ELÉVALO!" — "Si la capa de +50% de velocidad de vuelo se siente mucho mejor para jugar, ¿quizás hacer que todas las capas sean de +50% de velocidad de vuelo?"
> - Globo (personaje que sostiene una capa grande): "¡Guau! ¡Esta nueva mega-capa es mucho mejor que todas las súper-capas!"
> - Etiqueta sobre un perchero con cinco capas colgadas: "+10% de velocidad de vuelo".
> - Etiqueta junto a la capa que sostiene el personaje: "+50% de velocidad de vuelo".

## USA CONTRAPUNTOS (*USE FOILING*)

El uso de contrapuntos (*foiling*) en la narrativa y en otros ámbitos se inspira en cómo los joyeros montaban una gema preciosa sobre una lámina de estaño (*foil*) para realzar su brillo. En la narrativa, esto suele ser una cuestión de personalidad. Si el protagonista principal es generoso, puedes hacerle "contrapunto" a esta generosidad añadiendo un personaje codicioso o tacaño como compañero, personaje secundario o villano. Esto servirá para contrastar la generosidad del personaje generoso.

El mismo principio de que algo barato realce el "resplandor" visible de algo valioso puede aplicarse en el diseño de juegos.

En cualquier juego con tesoros de rareza variable, por ejemplo, las verdaderas toneladas de objetos comunes inútiles que cargas de un lado a otro sirven de contrapunto a los objetos más raros. La psicología de encontrar el "botín raro" se ve potenciada por tener una fuente inagotable de botín sin valor.

De manera similar, derrotar hordas de enemigos más fáciles sirve tanto para enseñar al jugador a jugar como de contrapunto para cualquier enemigo más duro y complejo.

### Exfoliación

- **Saltos:** los saltos bajos y menos desafiantes te enseñan la mecánica y hacen que se sienta más interesante hacer los saltos más difíciles.
- **Unidades:** construir y controlar muchas unidades pequeñas en un juego de estrategia puede hacer que las grandes se sientan más interesantes y únicas; que "valgan" su inversión.
- **Armas:** un arma más pequeña o más lenta hará que se sienta más interesante encontrar una más grande o más rápida.
- **Velocidad:** después de andar a pie durante un buen rato, las ganancias de usar un caballo o una motocicleta superarán con creces la necesidad de cepillarlo o de recargar combustible.
- **Combos:** después de jugar cartas comunes para preparar tu combo devastador, se sentirá mucho más satisfactorio jugar la carta rara que lo remata.

![Ilustración: un montón de botín basura junto a un cofre hace de contrapunto a una gran espada legendaria](img/game-design-toolbox/p151.png)

> **Texto de la ilustración:**
> - Globo, arriba: "Botín basura..."
> - Dibujo: un cofre abierto, un casco, una maza con púas y una daga corta.
> - Globo, abajo: "¡Hace de contrapunto al botín **LEGENDARIO**!"
> - Al pie: una gran espada de mano y media.

## BALANCEA LA COBERTURA (*BALANCE COVERAGE*)

Si tienes una amplia gama de *features* en tu juego, o simplemente algunas maneras en que ciertas cosas pueden seleccionarse por encima de otras, es bueno mirar más de cerca cómo se equilibran durante el juego.

Digamos que tienes seis acciones distintas que tu jugador puede realizar. Si una de ellas se usa 20 veces por sesión, en promedio, y otra se usa 40 veces, podría ser bueno balancear las seis a alrededor de 10 veces por sesión.

Esta no es una regla estricta, y el propósito de rastrear el uso no es asegurarse de que todo se use siempre por igual, sino comprobar si hay features a las que hay que darles más espacio.

Si nadie salta, porque accidentalmente hiciste que todos los saltos fueran opcionales, entonces probablemente necesites hacerlos menos opcionales o incluso considerar eliminar el salto por completo. Este es el tipo de cosa que una hoja de uso puede decirte.

### Crear una hoja de uso

- Enumera las acciones que quieres rastrear.
- Pon casillas de verificación o círculos junto a cada acción.
- Cada vez que se usa una acción en un *playtest*, o por ti mismo, marcas una casilla.

### Hoja de representación

Una versión alternativa de una hoja de uso es una hoja de representación. Define una manera de medir la representación. Un ejemplo es el Test de Bechdel, donde se requiere "al menos dos mujeres que hablen entre sí sobre algo que no sea un hombre" para pasar la prueba.

Cuando tienes tal definición de la representación que quieres —ya sea cultural, social o de otro tipo—, marcas una casilla cada vez que tu juego la cumple.

### Hoja de gastos

Para juegos con una economía interna de cualquier tipo —desde juegos de mesa con mecánicas de subasta, pasando por juegos de estrategia, hasta juegos de rol con vendedores que compran y venden objetos—, es importante rastrear el flujo de esa economía.

La forma más simple es una hoja donde enumeras Dinero que entra y Dinero que sale: las fuentes y los sumideros de la economía. Es igual que una hoja de uso, pero añades el valor de la moneda virtual como un dato en la hoja. Así que, en lugar de solo marcar una casilla, puede decir +10 de oro, +150 de oro, −12 de oro, etc.

Esto se usa para comprobar la salud de la economía interna del juego y, típicamente, para asegurarse de que haya más sumideros que fuentes, de modo que lo que un jugador hace con su dinero de mentira ganado con esfuerzo se convierta en una elección interesante. En otras palabras: en la mayoría de los tipos de economías de juego, quieres que el balance de fuentes y sumideros sea negativo.

![Ilustración: una hoja de acciones y una hoja de representación con filas de casillas para marcar](img/game-design-toolbox/p153.png)

> **Texto de la ilustración:**
> - Columna izquierda, título "HOJA DE ACCIONES": "Muerte con arma principal", "Muerte con arma secundaria", "Muerte cuerpo a cuerpo", "Muerte sigilosa", "Muerte por diálogo"; cada una con dos filas de diez casillas vacías.
> - Columna derecha, título "REPRESENTACIÓN": "Femenino/no binario", "Africano", "Indonesio", "Asiático", "Nativo americano"; cada una con dos filas de diez casillas vacías.
> - Globo de un personaje, abajo: "¡Usa este tipo de checklists para verificar que tus afirmaciones y esperanzas sean realmente ciertas!"

## SIMPLIFICA TU MATEMÁTICA (*SIMPLIFY YOUR MATH*)

Aunque las matemáticas puedan ser el lenguaje universal de la ciencia, sus complejidades no son ni de cerca tan intuitivas como desearíamos. No importa cuánto creas que ya has simplificado la matemática de tu juego que ve el jugador, lo más probable es que necesite ser aún más simple.

Incluso en juegos donde quieres números visibles y un procesamiento numérico profundo, es importante hacerlo accesible. Aunque algunos juegos pueden simplemente darte una ventana que cubre toda la pantalla con números, o carpetas enteras de tablas y gráficos, decidir hacerlo arriesga alienar a partes de tu base potencial de jugadores.

Hay dos claves para las fórmulas que ve el jugador: mostrar los datos y mostrar comparaciones. Pero siempre puedes trabajar para hacer que tanto los datos como las comparaciones sean más legibles.

Afortunadamente, hay una serie de atajos pedagógicos que puedes tomar.

Algo a tener en cuenta es que el número promedio de elementos en la memoria humana a corto plazo es siete más/menos dos (5–9) (a veces llamado la Ley de Miller). Esto significa que el jugador típico podrá recordar entre cinco y nueve cosas en un momento dado. Para los niños, este número puede ser ligeramente menor. Digamos cinco más/menos dos (3–7).

No es coincidencia que muchos juegos usen tres fases para las peleas contra jefes, tres vidas y otros múltiplos de tres: es una variable que la mayoría de los jugadores, de la mayoría de las edades, pueden mantener en la memoria a corto plazo.

### Checklist de consideraciones matemáticas

- **Usa gráficos:** antes de mostrar cualquier número, considera usar en su lugar comparaciones gráficas de datos: flechas, colores y diagramas.
- **Sé consistente:** establecer reglas estrictas para los datos que ve el jugador, como "los Números Altos Siempre son Buenos" o "los Números Negativos Siempre son Malos", te obliga a ajustarte a un estándar comunicable.
- **Números difusos:** considera usar palabras que expresen los números. "Casi muerto" comunica la salud baja más rápido que "5/100".
- **La suma** es la operación aritmética más rápida. Si quieres que el jugador calcule números mentalmente, que sea una suma.
- **Mayor que** es la comparación más intuitiva, y las comparaciones estáticas son más fáciles que las variables. Si sabes que la dificultad siempre es 20 cuando lanzas los dados, puedes hacer la comparación más rápido.
- **Los múltiplos de cinco** son la multiplicación más rápida e intuitiva.
- **Usa enteros.** En un juego donde quieres sumar +0,25, siempre puedes considerar multiplicar todos los números base por cuatro para poder usar +1 en su lugar. Los números enteros son mucho más fáciles que las fracciones.
- **Usa porcentajes.** Si tu juego todavía necesita fracciones, prueba reemplazar los multiplicadores por porcentajes. x1,1 es menos intuitivo que +10%.
- Si todavía no estás convencido de que puedes prescindir de las fracciones, hazlas de uno o como máximo dos dígitos, e intenta aplicar los otros atajos matemáticos. Es decir, x1,75 se lee mejor que x1,7481139.
- Deja claro si estás sumando los multiplicadores o resolviéndolos de manera acumulativa. Algunos juegos manejan los multiplicadores de forma distinta según qué se esté multiplicando: esto rompe la segunda regla, la de ser consistente.

![Ilustración: ocho burbujas con los atajos matemáticos: gráficos, consistencia, números difusos, suma, mayor que, múltiplos de 5, enteros y porcentajes](img/game-design-toolbox/p155.png)

> **Texto de la ilustración:**
> - Burbuja 1: "1) Usa gráficos" — una flecha hacia arriba con "+", una flecha hacia abajo con "−", un medidor circular y una barra de salud.
> - Burbuja 2: "2) Sé consistente" — una espada: "Daño: 4"; una pistola: "Reducción de salud: −11,31" (tachado) y debajo "Daño: 11".
> - Burbuja 3: "3) Usa números difusos" — "Salud difusa": "Perfectamente bien", "Herido", "Preocupado", "Casi muerto", "Completamente muerto", cada uno con una flecha que apunta a un punto de una barra vertical.
> - Burbuja 4: "4) Suma" — "X + Y".
> - Burbuja 5: "5) Mayor que" — "X > Y".
> - Burbuja 6: "6) Múltiplos de 5" — "5, 10, 15, 20, 25, 30, etc."
> - Burbuja 7: "7) Enteros" — "11,31" (tachado), "¡11!".
> - Burbuja 8: "8) Porcentajes" — "X%".

## INTERPOLA MÁS (*TWEEN MORE*)

En animación, un "intermedio" (*inbetween*) es un dibujo que complementa las poses principales de la acción con dibujos intermedios. El objetivo es generar una curva suave a lo largo del movimiento.

Digamos que un personaje está saltando. Las tres poses principales de esto pueden ser la postura de reposo (*idle*), el impulso en el aire y luego el aterrizaje de superhéroe. Entre esas tres poses, usas intermedios.

El mismo principio aplica al diseño de juegos, y en cierto modo aún más.

Esta sigue siendo una herramienta de *balanceo* simplemente porque a veces marcará la diferencia entre no entender qué está pasando y hacer que tu juego se sienta agradable de jugar.

### Feedback de las acciones

- **Feedback de animación:**
  - Fotogramas de pausa (*stop frames*): detenerse un momento para señalar un cambio de estado.
  - Telegrafiar: mostrar la intención antes de la acción.
  - Retornos: animar la vuelta al reposo desde el final de la acción.
- **Feedback de sonido:**
  - Señales (*cues*): una indicación de audio de que deberías hacer algo.
  - Pistas: sonidos que te informan sobre información del juego.
  - Campanillas (*chimes*): suenan como respuesta directa a una acción o a un cambio de estado.
- **Feedback narrativo:**
  - Cámara: cambiar el foco, el zoom u otras propiedades de la cámara.
  - Voz en off: diálogo grabado.
  - Escritura: mensajes de texto, texto dentro del juego y otras formas de texto.
- **Feedback de efectos:**
  - Partículas: cualquier efecto visual generado por el juego.
  - Resaltados: color, contorno u otros contornos visibles.
- **Feedback de fuerza:**
  - Vibración y hápticos: para indicación o refuerzo de la acción.
  - Sacudida de cámara: para realzar aún más el impacto visual.
- **Feedback de diálogo:**
  - Ladridos (*barks*): líneas sueltas y aisladas que señalan el estado del juego.
  - Refuerzo: líneas dichas en respuesta a la interacción del jugador.
  - Réplicas (*repartee*): comentarios basados en otros diálogos hablados.

![Ilustración: las tres poses de un salto (reposo, salto, aterrizaje) y, debajo, las mismas poses rodeadas de oportunidades de feedback](img/game-design-toolbox/p157.png)

> **Texto de la ilustración:**
> - Título superior: "UN SALTO" — tres figuras unidas por flechas: "Reposo (*idle*)", "Salto", "Aterrizaje".
> - Título inferior: "OPORTUNIDADES DE FEEDBACK" — alrededor de las mismas tres poses:
>   - Reposo: caja "Hápticos del mando"; una figura agachada tomando impulso con la caja "Animación de telegrafiado".
>   - Salto: globo "¡Yeah!"; caja "¡Sonido de silbido!"; caja "¡Desenfoque de movimiento!"; caja "¡Capa ondeante!"; una figura descendiendo con la caja "Animación de descenso".
>   - Aterrizaje: caja "Fotograma de pausa del aterrizaje de superhéroe"; caja "Vibración del mando"; caja "¡Sacudida de cámara!"; caja "¡Partículas de nube de polvo!".

## PON LA PUERTA ANTES QUE LA LLAVE (*PUT THE DOOR BEFORE THE KEY*)

Pueden ser acertijos, enemigos especiales o mecánicas específicas. Algunas situaciones y mecánicas en los juegos requieren que el jugador entienda la solución antes de poder saber qué buscar. Esta solución requerida es la llave.

Puede ser una llave literal y directa, como un objeto de forma extraña que hay que encajar en un hueco para abrir una puerta. Pero también puede ser algo más transitorio, como unas botas que te permiten saltar más alto o una carta que debe jugarse antes de poder abrir el siguiente sobre de tu juego de mesa *legacy*.

Pero las llaves sin contexto son casi completamente inútiles. Encontrar el sobre sellado en la caja de tu juego de mesa que dice "ábrelo cuando ganes tu décima partida" y descubrir la puerta que bloquea tu camino y su ranura de forma extraña: cuando el jugador descubre estas cosas primero, entenderá casi de inmediato lo que necesita hacer.

Como mínimo, sabrá que necesita hacer algo para progresar, y tendrá alguna pista de qué buscar.

### Puertas antes que llaves

- Enemigo con armadura de acero aparentemente inmortal antes que Arma Eléctrica.
- Puerta de color antes que Llave del mismo color.
- Enemigos de colores antes que Proyectiles de arma de colores.
- Ranura de rompecabezas antes que Pieza de rompecabezas. Ranura cuadrada, clavija cuadrada: muchas variaciones.
- Ranura de carta horizontal antes que Carta impresa en orientación apaisada.
- Superficie de madera antes que Antorcha encendida.
- Icono de recurso en el tablero antes que Icono de recurso correspondiente en los dados.
- Símbolo de costo en oro antes que Monedas de oro idénticas al símbolo.
- Puerta normal colocada demasiado alta para el salto normal antes que Botas de doble salto.
- Superficie transitable colocada demasiado abajo antes que Parapente para planear hacia abajo.
- Barra de salud roja o Corazones rojos antes que Objetos de salud rojos.
- Una luz a lo lejos antes que Caminos hacia la luz.
- Mensaje de "No hay suficiente madera" antes de encontrar un árbol y un hacha.

![Ilustración: un grupo de aventureros frente a una puerta cerrada con un símbolo de goblin y, horas después, encontrando la llave con el mismo símbolo](img/game-design-toolbox/p159.png)

> **Texto de la ilustración:**
> - Globo (mago con sombrero puntiagudo y bastón): "Qué símbolo tan extraño. ¡Pícaro! Te ruego que hagas tus cosas de pícaro. ¡Abre la puerta, a toda prisa!"
> - Dibujo: una gran puerta con barrotes y un medallón circular con un símbolo con forma de cabeza de goblin; a la derecha, un pícaro agachado frente a la cerradura.
> - Globo (pícaro): "¡Bah! Me rompió las ganzúas."
> - Globo (mago): "'Busca la llave goblin', dice la inscripción."
> - Rótulo: "HORAS DESPUÉS..."
> - Globo (guerrero con casco sosteniendo una llave brillante con el mismo símbolo de goblin): "¡Mira qué brillante es!"
> - Nube de pensamiento (mago, sudando): "Esto me resulta familiar de algún modo..."

---

# Capítulo 7 — Ajuste (*Tuning*)

Llega un punto en el desarrollo de tu juego en el que ya no puedes seguir escuchando a los fans de tu trabajo ni a los *playtesters*, sino que debes iniciar el proceso de preparar tu juego para el mercado.

Es probable que desde aquí vuelvas al balanceo, o incluso a la resolución de problemas, unas cuantas veces antes de sentirte lo bastante listo, pero eso debería ocurrir solo en casos extremos y para resolver cuestiones aisladas muy específicas. Una vez que empiezas a ajustar, estás en el último tramo del juego antes del lanzamiento. Compáralo con la "postproducción", si te sirve.

El mayor problema de toda esta etapa es que quizá termines teniendo que alejar a algunos de tus verdaderos creyentes, que te ayudaron a balancear el juego. Aun así, pasar de balancear con los fans a ajustar para el mercado es absolutamente esencial. Solo no confundas la palabra "mercado" con cada persona del planeta. Como dice el refrán, si intentas hacer algo para todos, terminarás haciéndolo para nadie.

Cuando termines de ajustar deberías tener lo siguiente:

- Una primera entrega del juego terminado.
- Un plan para el soporte continuado del juego.
- Materiales de marketing.
- Ideas para posibles complementos, secuelas o parches en los que puedas estar listo para empezar a trabajar con poca antelación si tu juego tiene éxito.
- Ideas para dar soporte al juego a largo plazo, en caso de que no tenga éxito.

## REFINA TU AUDIENCIA (*REFINE YOUR AUDIENCE*)

Hay tres peligros de los que debes ser consciente al pasar del balanceo al ajuste. (A decir verdad, hay muchos más peligros además de estos tres, pero concentrémonos solo en estos tres.)

El primero es el sesgo del creador. Pensar que tú lo entiendes, así que los jugadores también lo entenderán. A ti te gusta, así que a los jugadores también les gustará. Poniéndote el sombrero de diseñador de Nivel 4, tienes que dar un paso atrás y mirar el juego sin tener en mente tu autoría. Lo que realmente logra frente a lo que tú quieres que logre.

El segundo es la captura por *grognards* (*Grognard Capture*), un término inventado por Greg Costikyan para explicar cómo muchos juegos terminan atendiendo a su núcleo "más duro" con suficiente tiempo e iteración. La minoría ruidosa se convierte en la gente para la que haces el juego, en lugar de la mayoría silenciosa, y a veces esto aleja a jugadores que podrían haberse convertido en fans si el juego hubiera tenido menos barreras de entrada.

El tercero es el sesgo de confirmación. Puede tomar muchas formas distintas, pero una de las más comunes es mirar la popularidad de juegos parecidos al tuyo, asumir que a la gente también le gustará el tuyo, y luego filtrar todo el *feedback* que llega según esa suposición. En ese estado mental, si crees que los jugadores de Monopoly disfrutarán tu juego, y alguien dice que siempre juega con el zapato en ese juego, vuelves de inmediato a tu juego para agregar el zapato.

Una manera de asegurarte de no caer en ninguna de estas trampas es refinar con más cuidado tu visión del público objetivo. Es un proceso bastante parecido a un *pitch* inicial, salvo que ahora ya sabes cuál es tu producto y puedes usar esa información para aclarar para quién estás haciendo el juego.

### Público objetivo

- Identifica el gancho de tu juego. Esa única oración que convencerá a la gente de jugar (y comprar) tu juego.
- Define tu *pitch* de audiencia: Necesidades, Enfoque, Beneficios, Competencia (NABC, por *Needs, Approach, Benefits, Competition*):
  - Enumera las Necesidades que estás acaparando con tu juego. Los tipos de contenido o experiencias que los jugadores pueden estar buscando.
  - Enumera tu Enfoque para satisfacer dichas necesidades. Aquello en lo que estás trabajando.
  - Enumera los Beneficios que tu enfoque ofrece a tus clientes. Más barato o más rápido. Mayor calidad. Cosas que los competidores no pueden ofrecer en absoluto. Más a largo plazo. Adopción en varios medios. Una marca o propiedad intelectual específica que estás ofreciendo. Todo y cualquier cosa.
  - Enumera los mayores Competidores de tu juego. Otros juegos, pero también otros diseñadores de juegos o compañías de juegos parecidas a la tuya.
- Anota intereses relacionados que se vinculen con tu juego. Marcas que pueden gustarles a los clientes; marcas que pueden desagradarles. Cultura *mainstream*, *fandoms* específicos, lealtad a una plataforma, etcétera.
- Con el gancho, el NABC y las marcas relacionadas en mente, analiza qué tipo de público objetivo te queda y reúne datos de cualquier forma que puedas. Puede que este ejercicio te muestre que hay grupos adicionales de jugadores a los que podrías llegar haciendo cambios en tu gancho.

![Ilustración: tres personajes de palo que ejemplifican los tres sesgos: sesgo del creador, captura por grognards y sesgo de confirmación](img/game-design-toolbox/p163.png)

> **Texto de la ilustración:** tres personajes, cada uno con un globo de diálogo y una etiqueta debajo.
> - Personaje de la izquierda (globo): "¡Esta es la mejor *feature* que diseñé en mi vida! Los testers del grupo focal, los jugadores, los productores, los amigos y demás simplemente ¡NO LO ENTIENDEN!". Etiqueta: **SESGO DEL CREADOR** (*Creator's Bias*).
> - Personaje del centro (globo): "¡Podemos añadir un quinto recurso especial para cuando completes las nuevas raids de jefes, para darles más que hacer a los jugadores del endgame!". Etiqueta: **CAPTURA POR GROGNARDS** (*Grognard Capture*).
> - Personaje de la derecha (globo): "¡Ayer salió otro juego con tres barras de colores en cada carta, así que creo que vamos por buen camino!". Una flecha con la palabra "PRUEBA" señala lo que el personaje sostiene en la mano. Etiqueta: **SESGO DE CONFIRMACIÓN** (*Confirmation Bias*).

## EXTERMINA A TUS FAVORITOS (*EXTERMINATE YOUR DARLINGS*)

"Mata a tus favoritos" (*kill your darlings*) es un modismo que circula en las industrias creativas. Los juegos no son distintos. De hecho, matar favoritos es una forma abreviada muy popular de pedirle a alguien que no sea terco. (Convenientemente, casi siempre se trata de los favoritos de otra persona.)

En realidad hay dos significados distintos detrás de esta violenta exhortación.

El primero, "matar a tus favoritos", suele usarse para referirse a recortar cosas que se han vuelto artefactos importantes para alguien y que se conservan por ninguna otra razón que el apego o la costumbre. Te pide que recortes cosas que ya pasaron su fecha de vencimiento, o al menos que consideres recortarlas. Es lo que ocurre cuando algo se ha dejado dentro durante bastante tiempo, pero las razones para tenerlo han quedado obsoletas.

El otro, "asesinar a tus favoritos" (*murder your darlings*), se relaciona más con recortar cosas que están ahí para beneficio del autor y no del lector, en la escritura. Se aplica igual entre desarrolladores y jugadores. Lo formuló por primera vez el autor Arthur Quiller-Couch, al decir: "Cada vez que sientas el impulso de perpetrar un fragmento de escritura excepcionalmente fina, obedécelo —de todo corazón— y bórralo antes de enviar tu manuscrito a imprenta. Asesina a tus favoritos".

Asesinar a tus favoritos también es personal, pero se trata más de sacarte las cosas del sistema y seguir adelante de inmediato. No se trata de recortar cosas que se han vuelto cómodas, sino de entender desde el principio que no son necesarias.

Herramientas parecidas pero distintas. Ambas son increíblemente útiles. Cuantos más favoritos asesines, menos tendrás que matar.

### Matar features favoritas

Has tenido esta *feature* de doble *sprint* en el juego desde el principio, pero nunca ha terminado de funcionar. Los jugadores se atascan en la geometría del nivel, corren demasiado rápido para que los enemigos les disparen, y todo queda un poco desprolijo.

La razón principal por la que sigue ahí es que el programador que la hizo insiste en que va a funcionar más adelante y se ofrece a hacer horas extra para terminarla. Pero sigue sin estar terminada. Es el favorito del programador, claro, pero en realidad no le aporta nada al juego.

Un favorito así debería ser matado.

### Asesinar features favoritas

Es la misma *feature* de doble *sprint*, pero ahora rebobinamos la cinta hasta su concepción: hasta los antiguos días de la ideación y la exploración.

Te sientes terriblemente ingenioso por añadirla, ya que el *sprint* normal parece un poco lento. Pero te das cuenta en el momento en que empiezas a explorar de que no vale la pena, porque moverse tan rápido podría introducir problemas más amplios en el juego. Juegas con ella un rato breve durante la exploración, luego la recortas y sigues adelante.

Acabas de asesinar a tu favorito.

![Ilustración: dos escenas con personajes de palo y una espada de tres manos, sobre matar y asesinar favoritos](img/game-design-toolbox/p165.png)

> **Texto de la ilustración:** dos escenas, una arriba y otra abajo.
> - Escena superior: dibujo de una espada con una empuñadura extralarga con tres agarres. Personaje de la izquierda (globo): "Entonces, ¿nadie está usando la espada de tres manos?". Personaje de la derecha (globos): "No, pero los elfoenanos de Megafar la forjaron para la batalla final, y…" / "¡Será divertida cuando estemos más cerca del lanzamiento!". Cartel: **UN FAVORITO QUE (PROBABLEMENTE) DEBERÍAS MATAR**.
> - Escena inferior: un personaje sonriente con dos globos: "¿Conoces las espadas de una mano, no? ¿Y las de dos manos?" / (globo dentado, exaltado) "¡¿Pero qué hay de las espadas de tres manos?!". Cartel: **¡SI ASESINAS A ESTE FAVORITO, NO TENDRÁS QUE MATARLO DESPUÉS!**

## PON LO GENIAL PRIMERO (*PUT THE COOL THING FIRST*)

Los datos sobre las tasas de finalización de los juegos de un solo jugador son sombríos. La mayoría de los jugadores que empiezan a jugar juegos de un jugador nunca los terminan, y solo alrededor del 25 %–30 % de los que empiezan a jugar llegarán alguna vez al final (mirando las tasas de logros de Steam para una variedad de juegos de un jugador).

Lo mismo ocurre con muchos tipos de juegos, en los que los jugadores se atascan en las complejidades de la interfaz, sienten que hay demasiados componentes o reglas demasiado densas, etcétera. Muchos en la comunidad de Advanced Squad Leader bromean con que nadie ha terminado jamás una sesión completa de sus enormes escenarios históricos, porque suele ser evidente bastante pronto quién va a ganar, y nadie quiere seguir la rutina solo porque técnicamente debería hacerlo. En cambio, el bando perdedor se rinde a mitad de la partida.

Con un número creciente de plataformas que ofrecen juegos gratuitos, el compromiso inicial del jugador también se vuelve más pequeño, y la ventana de oportunidad para que un juego convenza a alguien de jugarlo se reduce en consecuencia.

Esto hace que sea importante que tu juego llegue rápido a sus partes más geniales. Lo difícil es saber cuáles son las partes más geniales, y admitir ante ti mismo que a las partes que no son las más geniales se les debería prestar menos atención.

### ¿Qué es lo genial?

- No es el aviso modal: avisos a pantalla completa que no se pueden saltar, que están cronometrados o que requieren que el jugador lea más de una sola oración de texto.
- No es el reglamento: tener que leer un buen trozo del reglamento antes de llegar al juego es un gran desincentivo para muchos jugadores. Ofrecer videos de "cómo jugar", reglas de inicio rápido, guías visuales y otros medios para entrar al juego más rápido ayudará al atractivo del juego.
- No es la exposición: es muy poco probable que al jugador le importe algo más allá del contexto y las llamadas a la acción al empezar un juego nuevo. Si pasas demasiado tiempo explicándoles todo a los jugadores de forma demasiado obvia, corres el riesgo de perder a algunos. Dosifica la narrativa y el contexto, y deja que los jugadores hagan cosas.
- No es el tutorial: si tutorializas todo, lo más probable es que aburras a tus jugadores. Si están jugando un shooter en primera persona, probablemente no necesites explicarles cómo se mueven o apuntan. Lo mismo se observa con el uso básico de las cartas y el barajado. Haz que cualquier tutorial extenso sea opcional de activar (*opt-in*) en lugar de opcional de desactivar (*opt-out*).
- No es el porqué. A diferencia de gran parte de la ficción popular, el porqué rara vez es tan importante para los jugadores. Donde un personaje de película quizá tenga que perder a su hijo o a su pareja para entrar en modo acción, los jugadores empezarán en modo acción con solo iniciar el juego. Si quieres ofrecer un porqué sólido, hazlo después de que el jugador haya tenido la oportunidad de probar las cosas geniales que va a poder hacer, no antes.
- No son los anuncios. Si tu juego tiene anuncios de cualquier tipo —en particular de los que pausan el juego—, debes tener cuidado de dejar que tus jugadores jueguen antes de mostrarles cualquier anuncio. Descargar y lanzar un juego solo para ser recibido por un anuncio que no se puede saltar es un desincentivo garantizado (y posiblemente una desinstalación).

![Ilustración: tabla de retención estimada de jugadores y dos personajes de palo conversando](img/game-design-toolbox/p167.png)

> **Texto de la ilustración:**
> - Título: **¡PON LO GENIAL PRIMERO!**
> - Personaje de la izquierda (globo): "¿Entonces me estás diciendo que el 10 % de la gente que compra un juego nunca llega a jugarlo?!".
> - Tabla titulada **RETENCIÓN ESTIMADA DE JUGADORES\***:
>   - 100 % — Momento de la compra
>   - 90 % — Desempaquetado / pantalla de menú
>   - 80 % — Inicio del juego / fase de aprendizaje
>   - 70 % — Fase posterior al aprendizaje
>   - 60 % — Mitad del juego
>   - 50 % — Juego tardío
>   - 40 % — Fase final
>   - 30 % — Final del juego
>   - 20 % — Endgame temprano / recogiendo
>   - 10 % — Mitad del endgame
>   - <10 % — Endgame tardío
> - Personaje de la derecha (globo): "No. Te estoy diciendo que esto probablemente es una estimación GENEROSA…".
> - Nota al pie: "\*Basado en datos de logros de Steam de una muestra de alrededor de 250 juegos de un solo jugador."

## ELIMINA LAS DECISIONES DESINFORMADAS (*REMOVE UNINFORMED CHOICES*)

Una decisión desinformada es una decisión en la que el jugador todavía no conoce la diferencia entre las opciones disponibles. Los juegos que usan alguna forma de creación de personaje o que te hacen elegir una facción al principio del juego son algunos ejemplos de decisiones que serán desinformadas cuando alguien juega el juego por primera vez.

Una vez que te acostumbras al juego y a cómo funciona, esta decisión será importante, y podrás tomarla de forma informada, afectando a cómo juegas. Pero la primera vez que juegas no tienes manera de saber qué significa siquiera +15 % de Ciencia o una carta de recurso extra.

Eliminar decisiones como estas del inicio del juego permite que los jugadores tomen decisiones más informadas más adelante, y que entren más rápido en el inicio del juego. No tienes que eliminar por completo la creación de personaje ni las habilidades especiales de las cartas: solo muévelas a una etapa del juego en la que las opciones requieran menos explicación.

De aquí también vienen muchos de los tropos clásicos del diseño de juegos. Si puedes elegir una de tres clases de personaje establecidas que son iguales en este juego que en muchos otros, esto aparentemente ofrece un atajo. Pero también hace que sea un requisito estar inmerso en la cultura general de los juegos, donde esas decisiones significan algo. Para cualquiera que no esté familiarizado con los tropos, la decisión será tan desinformada como cualquier otra decisión desinformada.

### Identificar decisiones desinformadas

Si la respuesta a cualquiera de las siguientes preguntas de la lista de verificación es "no", lo más probable es que le estés pidiendo al jugador que tome una decisión desinformada:

- ¿La decisión hará solo una diferencia cosmética? (Elegir una *skin*, escoger un color, etc.)
- ¿El jugador ha interactuado con todas las *features* afectadas por la decisión antes de que se tome la decisión?
- ¿Las consecuencias potenciales de cada opción disponible son conocidas por el jugador antes de que se tome la decisión?
- ¿La decisión tendrá un resultado significativo y perceptible para el jugador?
- ¿Las consecuencias de la decisión son inmediatas?
- Si las consecuencias no son inmediatas, ¿habrá una referencia clara a la decisión cuando las consecuencias finalmente ocurran?
- Si el jugador no ha interactuado con las *features*, ¿hay una forma abreviada efectiva que puedas usar para introducir las opciones de todos modos? (Piensa en roles, clases de personaje y otros estereotipos que puedan aplicarse a tu juego.)
- ¿La forma abreviada de la pregunta anterior es algo que se puede esperar que el jugador conozca intuitivamente, sin tener que estar inmerso en ninguna cultura, pasatiempo o lanzamiento de juego previo específico?
- Si hay un costo de oportunidad —por ejemplo un costo en recursos o la pérdida de opciones futuras en una decisión distinta—, ¿el significado de ese costo queda claro para el jugador antes de que tenga que tomar la decisión?

![Ilustración: tres cartas de selección de personaje con poderes desconocidos y dos personajes de palo discutiendo la elección](img/game-design-toolbox/p169.png)

> **Texto de la ilustración:** tres cartas de personaje en la parte superior, y dos personajes conversando abajo.
> - Carta 1: "PODER DE MORDIDA" — (dibujo de una cara con un colmillo) — "TOOTHGRIN, DEL PLANETA DENTISTA".
> - Carta 2: "PODER CEREBRAL" — (dibujo de una cara alienígena) — "McALIENFACE, DEL PLANETA EXO".
> - Carta 3: "PODER DE SOMBRERO" — (dibujo de una cara con fez y sonrisa ladeada) — "SMIRK, DEL PLANETA FEZ".
> - Personaje de la izquierda (globo): "¡Solo elige un PERSONAJE! Todos te estamos esperando."
> - Personaje de la derecha (tres globos): "Pero… ¿no sé qué hacen los poderes?" / "¿Ni los planetas?" / "¡¿Ni las imágenes?!".

## PERMITE LA PERSONALIZACIÓN (*ALLOW CUSTOMIZATION*)

Jugar un juego a su manera siempre ha sido una parte importante de la identidad de muchos jugadores, y hoy más que nunca.

Cuando la gente empezó a jugar Quake a mediados de los años noventa, la mayoría de los jugadores jugaba solo con el teclado. El esquema de control en primera persona establecido por el juego anterior de id Software —Doom— era que usabas las teclas de flecha para moverte y girar, la tecla control (CTRL) para disparar tu arma y la barra espaciadora para abrir puertas. Pero Doom también tenía un consejo en su manual: "Cuando te sientas cómodo jugando, prueba usar el teclado y el ratón simultáneamente". Sabiendo cómo se juegan hoy los shooters en primera persona en PC, esto es más que un poco nostálgico, pero la discusión entre los jugadores de la época era si te aferrabas a la forma antigua o adoptabas "usar el teclado y el ratón simultáneamente".

Pero la personalización va mucho más allá de la elección entre aferrarse a lo probado y conocido o intentar la forma nueva. Con opciones de personalización sólidas puedes convertir a personas que de otro modo serían completamente incapaces de jugar tu juego en jugadores potenciales. A veces los cambios que necesitas implementar son triviales; otras veces los cambios pueden requerir mucho trabajo técnico, o incluso que tengas que reconstruir tu juego, añadir contenido extra o reimprimir componentes.

Piensa en la personalización llevada a su extremo lógico: si alguien quiere jugar tu shooter en primera persona con una sola mano, o usando un periférico con forma de tabla de surf, en el mejor de los mundos sería posible acomodarlo.

### Ejemplos de personalización

- Posibilidad de saltarse segmentos particularmente difíciles o abrumadores.
- Permitir que los jugadores deshagan/rehagan acciones antes de confirmarlas.
- Personalización de las reglas del juego (gravedad, cantidad de intentos, etc.) y de los datos del juego (velocidades de movimiento, cantidad de cartas, etc.).
- Configuraciones base del mando para zurdos y diestros.
- Opciones de configuración del mando para una sola mano.
- Automatización de acciones repetitivas.
- Personalización detallada de la disposición de los botones, incluido el soporte para mandos de hardware personalizados.
- Cambiar las interacciones entre Pulsar, Mantener y Alternar.
- Cambiar durante cuánto tiempo debe mantenerse pulsado un botón, si debe mantenerse.
- Selección de tamaño, color y fuente del texto.
- Ubicación del texto en pantalla.
- Limitar cuánto texto aparece en un momento dado.
- Subtitulado; para los diálogos, pero también avisos para personas con discapacidad auditiva.
- Opciones de color para todos los elementos visibles.
- Donde se puedan elegir colores, hacer posible elegir patrones.
- Hacer posible encargar cartas impresas en braille.
- Resaltados opcionales, con elección de colores.
- Activar o desactivar las animaciones.
- Activar/desactivar el contenido potencialmente desencadenante o traumatizante.

![Ilustración: un grupo de jugadores de palo con globos de diálogo que expresan distintas necesidades de personalización y accesibilidad](img/game-design-toolbox/p171.png)

> **Texto de la ilustración:** múltiples globos de diálogo sobre un grupo de personajes de palo, en orden de lectura:
> - "Más de dos o tres tareas en pantalla al mismo tiempo me abruman."
> - "Me dan ataques de ansiedad con los ruidos fuertes."
> - "Este juego es tan oscuro que no puedo ver qué está pasando."
> - "Rara vez puedo jugar más de cinco minutos seguidos."
> - "No puedo jugar el nivel de las arañas, por aracnofobia severa."
> - "¡Preferiría poder saltarme los segmentos de combate y solo vivir la historia!"
> - "¡El juego se cuelga si conecto mi periférico de tabla de surf!"
> - "¡Ojalá pudiera saltar automáticamente toda la tediosa cháchara de la historia!"
> - "Estas cartas se vuelven ilegibles cuando las abre en abanico un jugador zurdo."
> - "Si no tuviera que mantener la tecla pulsada, podría jugar sin dolores crónicos."

## OFENDE A PROPÓSITO (*OFFEND ON PURPOSE*)

A veces la historia que quieres contar o la *feature* que quieres incluir es ofensiva. Puede ser de naturaleza violenta, sexual, religiosa o políticamente controvertida. Puede ser inhumana u horrible: muchísimos juegos retratan violencia gráfica, por ejemplo.

Cuando haces un juego, y decides tener contenido ofensivo en ese juego, serás responsable de tomar esa decisión y de cualquier indignación o controversia que pueda causar.

Pero lo cierto es que también puedes tener algo en tu juego que resulte extremadamente ofensivo para alguien de un trasfondo particular o con alguna convicción particular, y ni siquiera saber que es ofensivo. Simplemente pensaste que era algo "genial" para tener y nunca lo pensaste dos veces.

El problema es que debes saberlo. Es tu trabajo saberlo. Debes presentar tu juego a personas que puedan tener algo que decir al respecto, sin importar cómo te parezcan sus opiniones a ti o a tu sensibilidad creativa.

Si ofendes a alguien, debes estar haciéndolo a propósito y asegurarte de estar lo bastante informado para responder por ello. Debes tener buenas razones, que no sean solo alguna variante de hacer lo que te place porque puedes, o de ofender por accidente porque no sabías más. Nada de eso es suficiente.

A veces ser ofensivo es todo el punto. Solo asegúrate de saber si tu juego es ofensivo antes de que ofenda a alguien, y prepárate para defender tus decisiones cuando lo haga. Respeta también que no todo el mundo estará de acuerdo con tu decisión.

### Localización

Traducir un juego a un idioma nuevo se conoce como localización. En la superficie, esto significa cambiar palabras escritas por las palabras de otro idioma. Pero el significado de una palabra o una oración no siempre se traduce bien.

A veces el lenguaje se usa más como decoración o construcción de mundo —por ejemplo, la señalización del mundo del juego—, pero esto debe localizarse igual que cualquier otro lenguaje que se use en tu juego.

Si localizas tu juego, asegúrate de que cada traducción soportada sea revisada a fondo por hablantes nativos del idioma en cuestión.

### Culturalización

Analizar un juego a través de una lente cultural se conoce a veces como culturalización. Esto es mucho más difícil que la localización y requiere que tengas acceso a personas que puedan informarte sobre lo que deberías estar haciendo. Hay expertos pagos que ofrecen ese tipo de servicios, pero incluso con solo preguntarle a alguien que conozcas que entienda mejor la cultura en cuestión estarás más informado.

Algunos países tendrán reglas sobre lo que se te permite representar. La violencia gráfica puede causar restricciones sobre dónde puedes poner a la venta tu juego, por ejemplo.

Otros países pueden tener limitaciones culturales o religiosas, o pueden querer que elimines ciertos estereotipos de tu juego.

Otros símbolos culturales pueden ser tan sagrados o culturalmente específicos que su representación se considera apropiación si se incluyen. Debes ser consciente de ellos.

![Ilustración: un personaje de palo insulta a una aspiradora, que le responde con indiferencia](img/game-design-toolbox/p173.png)

> **Texto de la ilustración:**
> - Título: **SI OFENDES, HAZLO A PROPÓSITO.**
> - Personaje de la izquierda, señalando (globo): "¡Apestas!" [en el original, *You suck!*, juego de palabras con "succionar"].
> - Aspiradora de la derecha (globos): "¡Lo que sea!" / "No es como si fuera la primera vez que alguien hace ese chiste…".

## PONLO EN OTRO LADO (*PUT IT ELSEWHERE*)

Considera cómo funcionaría tu juego en un smartphone, en consolas de videojuegos, como juego de mesa, juego de cartas, cosplay, novela o película. Este ejercicio te ayuda a identificar el núcleo con más facilidad y te ayuda a entender qué hace que una marca funcione, en contraposición a solo un juego.

Puede parecer que esto es dominio del marketing y no del diseño de juegos, pero es importante que tú, como diseñador de juegos, seas consciente de más cosas que las *features* y el *gameplay*, y que tomes decisiones que ayuden a facilitar el marketing.

Algunas decisiones tendrán que tomarse antes. No puedes hacer que un personaje complejo sea más apto para peluche una vez que llegas al ajuste, por ejemplo. Pero pensar en tu juego como un producto, y en cómo podría verse más como un fenómeno *mainstream* y menos como "solo un juego", es un gran ejercicio en esta etapa.

Si tu juego tiene éxito, puede que la gente quiera involucrarse con tus ideas de más maneras que jugando el juego. Si ya lo has puesto en otro lado en tu cabeza, estarás mejor preparado.

### Moverlo a otro lado

- Cercano (*relatable*): los superhéroes serán superhéroes, pero no es casualidad que algunos de los más populares sean adolescentes con problemas de adolescentes mientras salvan el mundo. Se cruza con la audiencia para la que escribían los autores. Acercar la temática del juego a su audiencia, de modo que uno pueda identificarse emocionalmente con las luchas y los conflictos, lo hace cercano.
- Agradable (*agreeable*): asegurarse de que cualquier sangre, vísceras, desnudez y otras instancias de contenido potencialmente menos agradable estén contrastadas y no dominen todo el producto. Algunos juegos, por supuesto, prosperan con lo contrario, pero muchas franquicias de juegos de gran éxito son fundamentalmente agradables.
- Apto para peluche (*plushable*): hacer que los personajes, vehículos y otros objetos centrales tengan rasgos y esquemas de color que sean distinguibles y que puedan caricaturizarse hasta el punto de poder hacer peluches con ellos y aun así reconocerlos por lo que son.
- Tatuable (*tattooable*): hacer que tu iconografía sea fácil de dibujar con líneas simples y en blanco y negro, haciéndola atractiva como tatuaje, pegatina u otro símbolo abreviado.
- Memeable (*memeable*): escribir lenguaje y presentar animaciones que puedan repetirse con facilidad y aporten significado contextual sin más explicación. Puede incluir incluso bugs o *features* orientadas al desarrollador, si tienes acceso a una comunidad que disfrute compartiendo ese tipo de cosas.
- Cosplayable (*cosplayable*): hacer siluetas de vestuario que sean llamativas y reconocibles, pero considerando también qué tipos de materiales y patrones incluyes, de modo que cualquier disfraz potencial no sea demasiado exótico o difícil de producir para un cosplayer.

![Ilustración: seis viñetas que ejemplifican las cualidades cercano, agradable, apto para peluche, tatuable, memeable y cosplayable](img/game-design-toolbox/p175.png)

> **Texto de la ilustración:** seis viñetas con etiqueta.
> - Personaje de palo señalándose (globo): "¡Mira! Tiene una cabeza, ¡igual que yo!". Etiqueta: **CERCANO** (*Relatable*).
> - Caja de juego tachada con una gran X, con el título "MURDER & KILL 9 — KILLING SIMULATOR" [Asesinar y Matar 9 — Simulador de matanza]. Etiqueta: **AGRADABLE** (*Agreeable*).
> - Silueta negra de un muñeco redondeado con ojos. Etiqueta: **APTO PARA PELUCHE** (*Plushable*).
> - Logotipo estilizado con la palabra "LAZERDUDE" y una pluma o rayo encima. Etiqueta: **TATUABLE** (*Tattooable*).
> - Personaje con sombrero (globo): "¡El sombrero es una mentira!". Etiqueta: **MEMEABLE** (*Memeable*).
> - Personaje con sombrero y pistola (globo): "Hice la pistola de poliestireno. Compré el sombrero. ¡Soy 'LAZERGAL'!". Etiqueta: **COSPLAYABLE** (*Cosplayable*).

## HAZ QUE SEA DIVERTIDO DE VER (*MAKE IT FUN TO WATCH*)

No todos los juegos son interesantes de ver. Algunos juegos tienen animaciones demasiado rápidas o demasiado nerviosas como para resultar satisfactorios de mirar, mientras que otros juegos son demasiado lentos o esotéricos. Convertir un juego que es divertido de jugar en entretenimiento para espectadores es complicado, pero hay algunas cosas que puedes considerar.

Imagina ser un guionista que tiene 5 minutos entre anuncios para contar una historia y sabe que algunos espectadores pueden entrar o salir entre esos anuncios para echar un vistazo a tu programa. El programa tiene que ser entretenido tanto para el fanático acérrimo que lo ve de forma continua como para el espectador casual que resulta encender la televisión en un momento específico.

La misma dinámica existe en Twitch, YouTube y las muchas otras formas actuales en que la gente puede interactuar con contenido en video.

Quieres que esos *streamers* jueguen tu juego y se lo muestren a jugadores potenciales en el proceso. Para que esto ocurra, debes hacer que tu juego sea divertido de ver.

### Hacer que algo sea divertido de ver

- Comunica los objetivos: los espectadores deben poder entender qué está pasando, si le está yendo bien o no a la persona que juega, y a qué prestar atención.
- Movimiento fluido: gran parte de nuestra intuición en el diseño de juegos se basa en cómo se siente algo, en particular en el espacio digital. Por desgracia, muchos de los cortes rápidos y abruptos que hacemos como formas abreviadas de animación se ven nerviosos y chocantes cuando miras jugar a otra persona. Para que un juego sea divertido de ver, esto puede necesitar ser más fluido.
- Comunica lo que está pasando: usar fotogramas detenidos, explicaciones, avisos en pantalla y otra información para contar a los espectadores lo que está pasando de manera visual es extremadamente importante. Donde un jugador puede captar señales visuales discretas y la háptica del mando, un espectador solo tendrá lo que está en la pantalla y en sus oídos para guiarse.
- Empodera al *influencer*: si quieres que tu juego se juegue, no solo debes hacerlo divertido de ver, sino que también debes hacer que la persona que juega tu juego se vea bien. No están ahí para promocionar tu juego, sino para entretener a sus fans. Encuentra *influencers* que jueguen juegos como el que estás haciendo y pregúntales qué hace que un juego sea particularmente entretenido para su audiencia. Ellos son los expertos.
- Nombra el juego: muestra el logotipo del juego repetidamente. En los menús de pausa, en las pantallas de recompensa, en las pantallas de progresión, en cualquier lugar que puedas. Si alguien llegó por casualidad, no debería tener que preguntarse qué juego es.
- Usa la repetición: igual que con el nombre, necesitas recordarles a los jugadores quiénes son los personajes, cuáles son los objetivos, etcétera, dentro del juego.
- Integra la participación: si tienes los recursos, haz posible que los espectadores del *stream* personalicen contenido, sugieran soluciones o interactúen de otro modo directamente con el juego mientras lo juega un *influencer*.
- Da soporte al *streaming*: ofrece interruptores para desactivar la música potencialmente sujeta a derechos de autor. Haz posible jugar el juego en modo ventana sin bordes. Asegúrate de que el tablero del juego no sea demasiado brillante, causando reflejos en la cámara. Hay muchas cosas que puedes hacer para facilitar la "streameabilidad" de tu juego.

![Ilustración: dos personajes de palo jugando a las cartas y hablando en una jerga inventada e incomprensible](img/game-design-toolbox/p177.png)

> **Texto de la ilustración:**
> - Título: **CÓMO PUEDEN SONAR LOS JUEGOS PARA LOS DE AFUERA**
> - Subtítulo: "¡Y con lo que debes lidiar para hacerlo divertido de ver!"
> - Personaje de la izquierda, con una carta en la mano (globo): "¡Entonces yo squibleo tu squuble, y eso inflige quince squabuz por squack!"
> - Personaje de la derecha, con una carta en la mano (globo): "¡No, no lo hace! Porque mi squort squapea tu squible, ¡y debes squashear dos squicks de tu squemp!" [jerga inventada en el original: *squeeble, squooble, squabooze, squack, squort, squaps, squash, squicks, squemp*].

## PIENSA COMO UN JUGADOR (*THINK LIKE A PLAYER*)

A esta altura de un proyecto de juego, estás tan metido en el funcionamiento interno de tu juego que puede ser difícil ver el juego como lo verán tus jugadores cuando lo vean por primera vez.

La diferencia de perspectiva entre un desarrollador y un jugador puede verse como una división de tres cosas que ya mencionamos: Mecánicas, Dinámicas y Estéticas.

Como diseñador de juegos, diseñas las mecánicas con la esperanza de generar dinámicas interesantes, y las estéticas son entonces la representación de cara al jugador de lo que has hecho.

Los jugadores lo abordarán exactamente de la manera opuesta. Primero se acercarán a las estéticas, luego se involucrarán con las dinámicas del juego, y finalmente puede que aprendan sobre las mecánicas detrás de todo si le dedican suficiente tiempo.

Usaremos al personaje Indiana Jones como paralelo. Independientemente de si te gustan las películas o el personaje o no, la mayoría de ustedes estará familiarizada con el arqueólogo del sombrero fedora. Si se anuncia una película nueva, presumirá de este héroe pulp de inmediato: oye, mira, es ese héroe que conoces y amas; ¡ven a ver la nueva película!

Pero para la primera película, Raiders of the Lost Ark, eso no era posible. Nadie estaba familiarizado todavía con las "Mecánicas" del personaje, ni siquiera con el nombre Indiana Jones. En cambio, el tráiler se centró en el misterio del Arca de la Alianza —el artefacto buscado en la película— y no te vende el personaje en absoluto, salvo mostrando acción y misterio. El tráiler se centró en la "Estética" de Indiana Jones.

Esto es exactamente lo que significa pensar como un jugador. Encontrar la estética —el misterio— que hará que tus jugadores quieran jugar tu juego.

### Misterio y actividades

Haz que los *playtesters* y otras partes externas miren los *assets* de tu juego y se concentren en si hay un misterio que los atraiga y qué actividades esperan.

- Material de marketing: incluso antes de que la gente participe en el juego real, es probable que vea material de marketing. Empieza por ahí y observa el efecto de qué personaje eliges mostrar y qué arte clave publicas primero. Distintos misterios; distintas promesas. Anota qué es lo que captan.
- El título del juego, incluidos los subtítulos: el nombre es muy importante para lo que la gente llegará a esperar. Si es una secuela o un producto vinculado a una marca, esto será distinto de tu propio título original, pero aun así importa.
- El género del juego: si explicas el juego en términos de géneros de juegos —juego de rol de acción, shooter en primera persona, colocación de trabajadores, etc.—, necesitas preguntar por las implicaciones y por cómo interpretan estos términos los distintos testers. Es bastante común que lo que un diseñador de juegos cree que significa sea distinto de lo que los jugadores realmente esperan.
- El arte de la caja: si tu juego tiene una caja —física o virtual—, el arte que presenta a menudo llegará a representar el juego entero.
- Páginas de publicación y tiendas: si miras más allá de los componentes narrativos que quizá conozcas, considera qué acciones están implícitas en ese arte.
- Inicio del juego: cuando arrancas el juego hasta su primerísima pantalla, o desempaquetas los componentes, esto puede reforzar las promesas hechas o puede no hacerlo.
- *Gameplay*: una vez que el jugador ha pasado por todo el circo de conocer y comprar tu juego, la gran pregunta es si considera que las promesas se cumplieron. Si no, has fallado en pensar lo suficiente como un jugador.

![Ilustración: un desarrollador y un jugador se acercan al juego desde extremos opuestos de la cadena Mecánicas → Dinámicas → Estéticas](img/game-design-toolbox/p179.png)

> **Texto de la ilustración:**
> - Título: **¡RECUERDA QUE VIENEN DE PERSPECTIVAS DISTINTAS!**
> - Arriba a la izquierda, un personaje etiquetado **DESARROLLADOR** (globo): "¡Esta economía de estamina es tan ingeniosa que creo que a los jugadores les va a encantar!". Una flecha va del desarrollador hacia la primera caja.
> - Tres cajas en diagonal descendente: **MECÁNICAS** → **DINÁMICAS** → **ESTÉTICAS**.
> - Abajo a la derecha, un personaje etiquetado **JUGADOR** (globo): "¡Guau! ¡Eso es genial! Me pregunto cómo se jugará…". Una flecha va del jugador hacia la caja de Estéticas.

## SATISFACE LAS INTENCIONES DEL JUGADOR (*MEET PLAYER INTENTIONS*)

Cuando alguien empieza a jugar tu juego, llegará con expectativas que a su vez llevarán a intenciones de su parte. Si el juego entonces no logra corresponder a dichas intenciones, esto puede causar frustración.

Aunque los fanáticos de cualquier género en el que estés haciendo tu juego quizá entiendan de inmediato lo que estás haciendo, trabajar activamente para que la intención del jugador coincida con las expectativas de todos los jugadores es fundamental para cualquier producto de juego exitoso.

Piensa en la pregunta clásica con la que puedes engañar a los niños: ¿qué pesa más, un kilo de plomo o un kilo de plumas? Pesan lo mismo, por supuesto, pero eso no es lo que nuestra intuición intentará decirnos.

En el diseño de juegos, a menudo es buena idea seguir nuestra intuición. El acero se hunde en el agua. La madera arde. Saltar este hueco me permite llegar al otro lado. Apagar mi motor a reacción hará que caiga.

En una simulación realista, algunos de estos ejemplos no serían para nada deterministas. Una fuerza lo bastante alta o una masa lo bastante pequeña significa que seguirás subiendo durante un tiempo incluso después de apagar tu motor a reacción. De manera similar, un tronco aparentemente inflamable puede estar invisiblemente húmedo y no prenderse fuego.

De esto se trata satisfacer la intención del jugador: descubrir qué está intentando lograr el jugador y dejar que lo logre.

Si tienes casos en tu juego en los que esto simplemente no es factible, entonces deberías ser tan explícito con esas excepciones como te sea posible. O si de verdad estás haciendo una simulación, entonces tienes objetivos distintos de apelar a la intención.

### Acomodar la intención

- Acción frente a intención: a veces, especialmente mientras aprendemos un juego, podemos hacer algo que en realidad no pretendíamos. Quizá saltar cuando debíamos agacharnos, o jugar la carta equivocada de nuestra mano cuando en realidad no podíamos permitirnos jugarla. En casos como estos, el juego puede necesitar permitir volver al estado anterior, deshacer lo que acabamos de hacer, o dar suficiente margen para que unos pocos errores estén bien sin arruinar la experiencia.
- Sensibilidad al contexto: una manera de aclarar dónde tus intenciones coinciden con tus opciones es hacerlo sensible al contexto. Cuando estás junto a la cornisa, aparece en pantalla un aviso de botón que dice "Trepar", o quizá hay una mancha de pintura amarilla claramente visible donde puedes trepar.
- Diseño de "lo bastante cerca": muchos juegos ofrecen funciones de asistencia para que te sientas genial jugando incluso cuando la simulación detallada sabe que en realidad fallaste. Ejemplos son agarrarse a una cornisa aunque hayas fallado por una corta distancia, seguir suavemente al objetivo al que apuntas en tu shooter en primera persona, o registrar la entrada de Salto del jugador incluso unos pocos fotogramas después de que tu personaje visual haya caminado más allá de una cornisa (un "salto de coyote", por la tendencia de Wile E. Coyote a correr más allá de los precipicios antes de darse cuenta de que debería caer).
- Paredes invisibles: añadir restricciones artificiales, como paredes invisibles que impiden a los jugadores entrar en cierta zona, es algo que conviene evitar. Puede que tenga que ser tu solución de último recurso, pero deberías probar cualquier otra solución imaginable antes de añadir esa pared invisible. Si no hay una manera intuitiva de entender que tu intención de explorar será bloqueada, la frustración está casi garantizada.

![Ilustración: comparación entre un juego que frustra al jugador y uno que satisface su intención, con un salto de coyote y un golpe "lo bastante cerca"](img/game-design-toolbox/p181.png)

> **Texto de la ilustración:** dos mitades.
> - Título superior: **COMPARA ESTO:**
>   - Un personaje cae en un hueco entre dos plataformas gritando "AAAAAAAH". Globo dentado: "¡No! Ya intenté saltar este hueco cincuenta y ocho veces…".
>   - Un personaje con hacha frente a un zombi. Globo dentado: "¡Maldición! El juego tiene lag. ¡Sé que le di a ese zombi!".
> - Título inferior: **CON SATISFACER LA INTENCIÓN DEL JUGADOR:**
>   - Un personaje salta desde el borde de una plataforma con una flecha curva; etiqueta: "SALTO DE COYOTE" (*coyote jump*).
>   - Un personaje colgado del borde de la plataforma opuesta; etiqueta: "Agarrarse a la cornisa cuando fallaste por muy poco".
>   - Un hacha impacta a un zombi con líneas de golpe; textos: "¡+50 PUNTOS!" y "'LO BASTANTE CERCA' cuenta como golpe".

---

# Referencias (*References*)

- Costikyan, G. 2013. *Uncertainty in Games*. Cambridge, MA: The MIT Press.
- Dille, F. and Zuur Platten, J. 2007. *The Ultimate Guide to Video Game Writing and Design*. Hollywood, CA: Lone Eagle.
- Hecker, C. 2006. "Advanced Prototyping," Game Developers Conference, 2006. Disponible en: https://www.chrishecker.com/Advanced_Prototyping.
- Hunicke, R., LeBlanc, M., and Zubeck, R. 2004. *MDA: A Formal Approach to Game Design and Game Research*. Disponible en: https://users.cs.northwestern.edu/~hunicke/MDA.pdf.
- Lovell, N. 2019. *The Pyramid of Game Design*. Boca Raton, FL: CRC Press.
- Quiller-Couch, A. 2006. *On the Art of Writing*. Disponible en el dominio público en: https://www.gutenberg.org/ebooks/17470.
- Romero, B. and Schreiber, I. 2017. *Challenges for Game Designers*.
- Sellers, M. 2018. *Advanced Game Design: A Systems Approach*. Boston, MA: Pearson Addison-Wesley.
- Skinner, B.F. 1953. *Science and Human Behavior*. Glencoe, IL: The Free Press.
- Sorkin, A. 2016. "Aaron Sorkin Teaches Screenwriting." Disponible en: https://www.masterclass.com/classes/aaron-sorkin-teaches-screenwriting.
- Swift, K. and Wolpaw, E. 2008. "Integrating Narrative into Game Design: A Portal Post-Mortem," Game Developers Conference, 2008. Disponible en: https://www.youtube.com/watch?v=c2YRVWZupwo.
- Valve, política de devoluciones de Steam, 2023. "Valve emitirá, previa solicitud a través de help.steampowered.com, un reembolso por cualquier título que se solicite dentro de los 14 días posteriores a la compra y que se haya jugado menos de 2 horas (esto incluye el tiempo de juego en línea, sin conexión y de biblioteca compartida)." Disponible en: https://help.steampowered.com/en/faqs/view/5FDE-BA65-ACCE-A411.
- Wolpaw, E. 2000. "Crate Review System." Disponible en: https://www.oldmanmurray.com/features/39.html.

## Ludografía (*Ludography*)

- Blizzard Entertainment. 1998. *StarCraft*. Videojuego. Blizzard Entertainment.
- Bohemia Interactive. 2013. *Arma 3*. Videojuego. Bohemia Interactive.
- Bungie. 2017. *Destiny 2*. Videojuego. Activision and Bungie.
- Chvátil, V. 2011. *Mage Knight Board Game*. Juego de mesa. WizKids, Asmodee, etc.
- Darrow, C. and Magie, L. 1935. *Monopoly*. Juego de mesa. Hasbro, Parker Brothers, etc.
- Dennaton Games. 2012. *Hotline Miami*. Videojuego. Devolver Digital.
- DICE. 2018. *Battlefield V*. Videojuego. Electronic Arts.
- Epic Games. 2018. *Fortnite Creative*. Videojuego. Epic Games.
- Firaxis Games. 2016. *Civilization VI*. Videojuego. 2K and Aspyr Media.
- FromSoftware. 2011. *Dark Souls*. Videojuego. Bandai Namco Entertainment and FromSoftware.
- Garfield, R. 1993. *Magic: The Gathering*. Juego de cartas. Wizards of the Coast.
- Greenwood, D. 1985. *Advanced Squad Leader*. Juego de mesa. Avalon Hill and Multi-Man Publishing.
- Gygax, G. and Arneson, D. 1974. *Dungeons & Dragons*. Juego de rol. TSR, Wizards of the Coast.
- id Software. 1993. *DOOM*. Videojuego. id Software.
- id Software. 1996. *Quake*. Videojuego. GT Interactive, Activision, Electronic Arts, etc.
- Infinity Ward. 2003. *Call of Duty*. Videojuego. Activision.
- Insomniac Games. 2018. *Marvel's Spider-Man*. Videojuego. Sony Interactive Entertainment.
- IO Interactive. 2000. *Hitman: Codename 47*. Videojuego. Eidos Interactive.
- King. 2012. *Candy Crush Saga*. Videojuego. King.
- Looking Glass Studios. 1998. *Thief: The Dark Project*. Videojuego. Eidos Interactive.
- Vaccarino, D. 2008. *Dominion*. Juego de cartas. Rio Grande Games.
- Valve. 2008. *Portal*. Videojuego. Valve and Microsoft Game Studios.

# Índice (*Index*)

*Los números de página corresponden a la edición impresa original en inglés (CRC Press, 2024), no a esta traducción. Las entradas se conservan en el orden alfabético inglés del original.*

- preguntas A/B (*a/b questions*) — 130
- habilidades (*abilities*) — 61, 160
- abstracto (a <-> B <-> A) (*abstract (a <-> B <-> A)*) — 71
- accesibilidad (*accessibility*) — 90, 99
- acción (*action*) — 28
- checklists de acciones (*action checklists*) — 110
- acción vs. intención (*action vs. intent*) — 172
- acciones (*actions*) — 15, 114
- actores (*actors*) — 15
- añade un costo (*add a cost*) — 116
- añade una ganancia (*add a gain*) — 116
- añade una ventaja de recursos (*add a resource advantage*) — 133
- añade desafío (*add challenge*) — 68
- añade opciones (*add choices*) — 117
- añade protección de nicho (*add niche protection*) — 133
- añade asperezas (*add rough edges*) — 68
- añade restricciones de reglas (*add rules restrictions*) — 132
- añade estufas (*add stoves*) — 120
- añade trampas (*add traps*) — 68
- añade tesoros (*add treasure*) — 69
- añade incertidumbre (*add uncertainty*) — 62
- añade restricciones de uso (*add usage restrictions*) — 132
- suma (*addition*) — 146
- Advanced Squad Leader — 158
- estéticas (*aesthetics*) — 13, 170
- agradable (*agreeable*) — 166
- permite la personalización (*allow customization*) — 162
- permite remates (*allow finishing moves*) — 117
- permite la retirada (*allow retreat*) — 117
- complejidad analítica (*analytic complexity*) — 62
- feedback de animación (*animation feedback*) — 148
- llegada (*arrival*) — 80
- recursos ascendentes (*ascending resources*) — 58
- haz menos preguntas (*ask fewer questions*) — 22
- haz preguntas astutas (*ask sly questions*) — 130
- asume menos (*assume less*) — 40
- verificaciones de suposiciones (*assumption checks*) — 40
- en la reunión (*at the meeting*) — 47
- atraer (a+a = disparador) (*attract (a+a = trigger)*) — 70
- atributos (*attributes*) — 67
- evita la dominación (*avoid domination*) — 132
- balancea la cobertura (*balance coverage*) — 144
- balanceo (*balancing*) — 12, 94, 127
- *barks* (líneas de voz breves) — 149
- línea base (*baseline*) — 66, 138
- Battlefield V — 18
- sé consistente (*be consistent*) — 146
- test de Bechdel (*Bechdel Test*) — 144
- antes de la reunión (*before the meeting*) — 46
- potenciación (*boosting*) — 118
- arte de la caja (*box art*) — 171
- haz lluvia de ideas en papel (*brainstorm on paper*) — 24
- dejar migas de pan (*breadcrumbing*) — 114
- amplio (*broad*) — 86
- construye un parque de diversiones (*build an amusement park*) — 80
- arma grupos de trabajo (*build task forces*) — 74
- quémalos en la estufa (*burn them on the stove*) — 120
- pero… (*but...*) — 72
- por 10 (*by 10*) — 136
- Call of Duty — 120
- cámara (*camera*) — 148
- sacudida de cámara (*camera shake*) — 148
- Candy Crush Saga — 18
- desafía el juego con la trama (*challenge play with plot*) — 72
- métricas de personaje (*character metrics*) — 94
- personajes (*characters*) — 34, 38, 60, 166
- verifícalo (*check it*) — 98
- campanillas (*chimes*) — 148
- Civilization — 16
- diseño suficientemente cercano (*close enough design*) — 172
- matriz de combinaciones (*combination matrix*) — 89
- comentario (*commentary*) — 131
- compromiso (*commitment*) — 11
- comunica los objetivos (*communicate goals*) — 168
- comunica lo que está pasando (*communicate what's happening*) — 168
- comunidad (*community*) — 17
- premios por completar (*completion awards*) — 118
- métricas de componentes (*component metrics*) — 94
- componentes (*components*) — 28, 53, 94
- bucle de compulsión (*compulsion loop*) — 16
- sesgo de confirmación (*confirmation bias*) — 154
- conflicto (*conflict*) — 34, 61, 88
- premios de consolación (*consolation prizes*) — 118
- contenido (*content*) — 17, 128
- sensibilidad al contexto (*context sensitivity*) — 172
- cambios de control (*control changes*) — 97
- mando (*controller*) — 28, 162
- comodidades (*conveniences*) — 80
- convertidor (*converter*) — 58
- apto para cosplay (*cosplayable*) — 167
- Costikyan, Greg — 62, 154
- Sistema de Revisión de Cajas (*Crate Review System*) — 112
- sesgo del creador (*creator's bias*) — 106, 154
- interdisciplinario (*cross-disciplinary*) — 5, 74
- matriz cruzada (*cross-matrix*) — 88
- cruza todo en una matriz (*cross-matrix everything*) — 88
- señales (*cues*) — 148
- culturalización (*culturalization*) — 164
- Dark Souls — 18, 120
- datos (*data*) — 56, 128
- guiado por datos (*data-driven*) — 66
- decide a quién juega el jugador (*decide who the player plays*) — 38
- decisor (*decider*) — 58
- define las features (*define the features*) — 84
- partida (*departure*) — 80
- recursos descendentes (*descending resources*) — 58
- tablero de diseño (*design board*) — 93
- diseña en capas (*design in layers*) — 56
- pilares de diseño (*design pillars*) — 86, 88
- Destiny 2 — 17
- anticipación del desarrollo (*development anticipation*) — 62
- feedback de diálogo (*dialogue feedback*) — 149
- dificultad (*difficulty*) — 44, 139, 146
- Dille, Flint — 96
- muéstralo (*display it*) — 96
- el hacedor (*the doer*) — 38
- estrategia dominante (*dominant strategy*) — 132
- estrategia dominada (*dominated strategy*) — 132
- Dominion — 40
- no expliques (*don't explain*) — 68
- Doom — 162
- duplica o divide a la mitad (*double or halve*) — 134
- dibuja un mapa de estrategias (*draw a strategy map*) — 108
- Dungeons & Dragons — 121
- dinámicas (*dynamics*) — 13, 36, 170
- feedback de efectos (*effect feedback*) — 148
- abrazar la subjetividad (*embracing subjectivity*) — 18
- emergente (*emergent*) — 68
- empodera al influencer (*empower the influencer*) — 168
- el enemigo (*the enemy*) — 39
- *engagement* — 17, 169
- eventos (*events*) — 15, 84
- exfoliación (*exfoliation*) — 142
- exploración (*exploration*) — 11
- exposición (*exposition*) — 158
- cinemáticas de exposición (*exposition cutscenes*) — 96
- extermina a tus favoritos (*exterminate your darlings*) — 156
- el facilitador (*the facilitator*) — 38
- hecho (*fact*) — 90, 92
- convierte en hechos (*factualize*) — 90
- expansión descontrolada de features (*feature creep*) — 50
- negación de features (*feature denial*) — 120
- pérdida de features (*feature loss*) — 121
- prejuicio de features (*feature prejudice*) — 19
- redundancia de features (*feature redundancy*) — 50
- recursos de features (*feature resources*) — 59
- *features* — 50, 84, 88
- *feedback* — 70, 84
- recursos finitos (*finite resources*) — 58
- seguir tendencias (*following trends*) — 51
- feedback de fuerza (*force feedback*) — 148
- Fortnite — 40
- diversión (*fun*) — 18, 118, 140, 168
- funciones (*functions*) — 67
- números difusos (*fuzzy numbers*) — 146
- documento de diseño de juego (GDD) (*game design document (GDD)*) — 92
- diseñador de juegos (*game designer*) — 5
- condiciones de fin de juego (*game end conditions*) — 139
- bucle de gameplay (*gameplay loop*) — 15
- métricas de gameplay (*gameplay metrics*) — 94
- género (*genre*) — 35, 171
- dales zanahorias (*give them carrots*) — 118
- bueno o malo (*good or bad*) — 19
- preguntas graduadas (*graded questions*) — 131
- captura del grognard (*grognard capture*) — 154
- tiene-un (*has-a*) — 66
- Hecker, Chris — 8
- información oculta (*hidden information*) — 62
- mayor que (*higher than*) — 146
- resaltados (*highlights*) — 148
- obstaculización (*hindering*) — 120
- pistas (*hints*) — 148
- haz reuniones estructuradas (*hold structured meetings*) — 46
- gancho (*hook*) — 154
- Hotline Miami — 120
- Hunicke, Robin — 13
- id Software — 162
- ideación (*ideation*) — 11
- identificar decisiones desinformadas (*identifying uninformed choices*) — 160
- intercalado (*inbetween*) — 148
- incentivos (*incentives*) — 114
- Indiana Jones — 170
- entrada (*input*) — 56
- entrada, salida, grito (*input, output, scream*) — 70
- entradas (*inputs*) — 70
- el instrumento (*the instrument*) — 39
- integra el engagement (*integrate engagement*) — 169
- inventa una mecánica (*invent a mechanic*) — 36
- paredes invisibles (*invisible walls*) — 173
- es-un (*is-a*) — 66
- solo un juego (*just a game*) — 166
- mata a tus favoritos (*kill your darlings*) — 156
- matar features favoritas (*killing darling features*) — 156
- últimas reflexiones (*last thoughts*) — 131
- deja un rastro (*lay a trail*) — 114
- aprender muriendo (*learning by dying*) — 120
- deja cosas atrás (*leave things behind*) — 124
- LeBlanc, Marc — 13
- juego de mesa legacy (*legacy board game*) — 150
- nivel 0: no diseñador (*level 0: non-designer*) — 6
- nivel 1: diseñador con opiniones (*level 1: opinionated designer*) — 6
- nivel 2: diseñador probado (*level 2: proven designer*) — 7
- nivel 3: diseñador experimentado (*level 3: experienced designer*) — 9
- nivel 4: diseñador holístico (*level 4: holistic designer*) — 9
- métricas de nivel (*level metrics*) — 94
- ¿Elevar o dejar? (*Lift or Leave?*) — 140
- eleva las cosas (*lift things up*) — 140
- elementos literarios (*literary elements*) — 34
- localización (*localization*) — 164
- cierra la puerta con llave (*lock the door*) — 68
- mira, no toques (*look, don't touch*) — 69
- bucles y aros (*loops and hoops*) — 15
- botín (*loot*) — 142
- Lovell, Nicholas — 8, 17
- MacGuffin — 42
- macro bucle (*macro loop*) — 16
- Mage Knight — 18
- ¡hazlo mágico! (*magic it!*) — 64
- Magic: The Gathering — 17, 64
- haz prototipos analógicos (*make analogue prototypes*) — 52
- haz prototipos con diagramas de flujo (*make flowchart prototypes*) — 58
- haz que escale (*make it escalate*) — 116
- haz que sea divertido de ver (*make it fun to watch*) — 168
- hazlo escalable (*make it scale*) — 116
- crea player personas (*make player personas*) — 102
- hacer un juego (rápido) (*making a (quick) game*) — 52
- hacer una hoja de uso (*making a usage sheet*) — 144
- material de marketing (*marketing material*) — 170
- Marvel's Spider-Man — 132
- mecánicas (*mechanics*) — 13, 36, 88, 170
- mecánicas, dinámicas, estéticas (MDA) (*mechanics, dynamics, aesthetics (MDA)*) — 12, 170
- satisface las intenciones del jugador (*meet player intentions*) — 172
- memeable (*memeable*) — 166
- meta bucle (*meta loop*) — 16
- meta recursos (*meta resources*) — 59
- micro bucle (*micro loop*) — 16
- ley de Miller (*Miller's Law*) — 146
- aviso modal (*modal prompt*) — 158
- modificadores (*modifiers*) — 67
- Dinero que entra, dinero que sale (MIMO) (*Money In, Money Out (MIMO)*) — 144
- Monopoly — 18, 154
- múltiplos de cinco (*multiples of five*) — 146
- asesina a tus favoritos (*murder your darlings*) — 156
- asesinar features favoritas (*murdering darling features*) — 156
- misterio (*mystery*) — 170
- nombra el juego (*name the game*) — 169
- anticipación narrativa (*narrative anticipation*) — 62
- feedback narrativo (*narrative feedback*) — 148
- tema narrativo (*narrative theme*) — 34
- necesidades, enfoque, beneficios, competencia (NABC) (*needs, approach, benefits, competition (NABC)*) — 154
- *nerf* (debilitar) — 140
- NewZoo — 102
- orientado a objetos (*object-oriented*) — 66
- objetos (*objects*) — 15
- observa y analiza (*observe and analyze*) — 104
- rampa de salida (*off-ramp*) — 17
- ofende a propósito (*offend on purpose*) — 164
- Old Man Murray — 112
- rampa de entrada (*on-ramp*) — 17
- *one-pager* — 92
- una cosa a la vez (*one thing at a time*) — 128
- salidas (*outputs*) — 70
- superpuestos (*overlapping*) — 86
- ritmo (*pace*) — 35
- premios por participación (*participation awards*) — 118
- partículas (*particles*) — 148
- lápiz y papel (*pen and paper*) — 8
- incertidumbre de percepción (*perception uncertainty*) — 63
- incertidumbre de desempeño (*performance uncertainty*) — 62
- persona contra la naturaleza (*person against nature*) — 42
- persona contra persona (*person against person*) — 42
- persona contra sí misma (*person against self*) — 42
- persona contra la sociedad (*person against society*) — 42
- persona contra la tecnología (*person against technology*) — 43
- persona contra lo sobrenatural (*person against the supernatural*) — 43
- *persona* (arquetipo de jugador) — 102
- perspectiva (*perspective*) — 35
- juega, no muestres (*play, don't show*) — 96
- juégalo (*play it*) — 96
- de cara al jugador (*player-facing*) — 84
- historia del jugador (*player story*) — 72
- rotación de jugadores (*player turnover*) — 113
- imprevisibilidad del jugador (*player unpredictability*) — 62
- trama (*plot*) — 34
- apto para peluche (*plushable*) — 166
- Portal — 16
- finge que juegas (*pretend to play*) — 44
- resolución de problemas (*problem solving*) — 12
- progresión (*progression*) — 17, 114, 139
- prototipo (*prototype*) — 9, 52, 58
- ponlo en otro lado (*put it elsewhere*) — 166
- pon lo genial primero (*put the cool thing first*) — 158
- pon la puerta antes que la llave (*put the door before the key*) — 150
- Quake — 162
- preguntas que (quizá) conviene evitar en la ideación (*questions to (maybe) avoid in ideation*) — 22
- preguntas para hacer a menudo en la ideación (*questions to ask often in ideation*) — 23
- Quiller-Couch, Arthur — 156
- Raiders of the Lost Ark — 170
- recompensas aleatorias (*random rewards*) — 119
- aleatoriedad (*randomness*) — 62
- rareza (*rarity*) — 142
- clasificaciones (*ratings*) — 98
- refina tu audiencia (*refine your audience*) — 154
- regiones (*regions*) — 57
- refuerzo (*reinforcement*) — 149
- verificaciones de refuerzo (*reinforcement checks*) — 109
- identificable (*relatable*) — 166
- eliminación (*removal*) — 129
- elimina las decisiones desinformadas (*remove uninformed choices*) — 160
- réplicas ingeniosas (*repartee*) — 149
- hoja de representación (*representation sheet*) — 144
- repeler (a-a = disparador) (*repulse (a-a = trigger)*) — 71
- prototipo de capa de retención (*retention layer prototype*) — 8
- bucle de retención (*retention loop*) — 17
- llamada de retorno (*return call*) — 17
- retornos (*returns*) — 148
- reversión (*reversal*) — 121
- atracciones (*rides*) — 80
- haz juego de rol con tu diseño (*role play your design*) — 60
- Romero, Brenda — 52
- reglas (*rules*) — 61
- dirigir una sesión simulada (*running a pretend session*) — 44
- guárdalo para después (*save it for later*) — 132
- dilo (*say it*) — 96
- dilo de nuevo (*say it again*) — 82
- di "sí, y…" (*say "yes, and..."*) — 30
- dirección de escena (*scene direction*) — 96
- narración de escena (*scene narration*) — 97
- incertidumbre de cronograma (*schedule uncertainty*) — 62
- Schreiber, Ian — 52
- segundos por muerte (*seconds per kill*) — 112
- segundos hasta la caja (*seconds to crate*) — 112
- segundos hasta matar (*seconds to kill*) — 112
- Sellers, Michael — 70
- duración de la sesión (*session length*) — 106, 112
- establece un tema (*set a theme*) — 34
- establece métricas (*set metrics*) — 94
- ambientación (*setting*) — 34
- muestra, no cuentes (*show, don't tell*) — 96
- muestra los datos, muestra comparaciones (*show the data, show comparisons*) — 146
- simplifica tu matemática (*simplify your math*) — 146
- prototipo simulado (*simulated prototype*) — 8
- sumidero (*sink*) — 58
- situaciones (*situations*) — 61
- Skinner, B.F. — 119
- movimiento suave (*smooth motion*) — 168
- suavizado (*smoothing*) — 56
- resuelve problemas (*solve problems*) — 122
- incertidumbre del solucionador (*solver's uncertainty*) — 62
- Sorkin, Aaron — 42
- feedback sonoro (*sound feedback*) — 148
- fuente (*source*) — 58
- aparición de entidades (*spawning*) — 56
- específico (*specific*) — 86
- Específico, Medible, Alcanzable, Relevante, Temporal (SMART) (*Specific, Measurable, Achievable, Relevant, Timed (SMART)*) — 46
- hoja de gasto (*spend sheet*) — 144
- detecta el pastel de salchichas (*spot the sausage cake*) — 50
- específico de hoja de cálculo (*spreadsheet specific*) — 70
- escenario (*stage*) — 61
- etapas del diseño de un juego (*stages of a game's design*) — 10
- complacedores de *stakeholders* (*stakeholder pleasers*) — 50
- párate sobre pilares (*stand on pillars*) — 86
- empieza desde el conflicto (*start from conflict*) — 42
- ¡roba! (*steal!*) — 8
- reserva (*stock*) — 58
- fotogramas detenidos (*stop frames*) — 148
- historia (*story*) — 34
- aptitud para el streaming (*streamability*) — 169
- aturdimientos (*stuns*) — 120
- estilo (*style*) — 35
- apoya el streaming (*support streaming*) — 169
- Swift, Kim — 16
- sistema (*system*) — 128
- quita cosas (*take things away*) — 68
- tatuable (*tattooable*) — 166
- enseñanza (*teaching*) — 106
- métricas técnicas (*technical metrics*) — 95
- telegrafiar (*telegraphing*) — 148
- cuenta una historia (*tell a story*) — 78
- testea a ciegas (*test blind*) — 106
- prueba los extremos (*test for extremes*) — 138
- tema (*theme*) — 34, 88
- entonces… (*then...*) — 72
- por lo tanto… (*therefore...*) — 72
- Thief: The Dark Project — 70
- piensa como un jugador (*think like a player*) — 170
- piensa en los datos (*think of the data*) — 66
- recursos temporizados (*timed resources*) — 59
- título (*title*) — 171
- tono (*tone*) — 35
- las herramientas (*the tools*) — 20
- toca, no pruebes (*touch, don't taste*) — 69
- marcas registradas (*trademarks*) — 98
- transferible (*transferable*) — 86
- advertencias de contenido (*trigger warnings*) — 99
- disparadores (*triggers*) — 99
- pruébalo (*try it*) — 32
- ajuste (*tuning*) — 12
- cantidad de turnos (*turn count*) — 113
- duración del turno (*turn length*) — 113
- tutorial (*tutorial*) — 158
- interpola más (*tween more*) — 148
- Twitch — 168
- prueba de las dos horas (*two-hour test*) — 113
- único (*unique*) — 87
- usa contrapuntos (*use foiling*) — 142
- usa gráficos (*use graphics*) — 146
- usa enteros (*use integers*) — 147
- usa porcentajes (*use percentages*) — 147
- usa la repetición (*use repetition*) — 169
- usa timeboxes (*use timeboxes*) — 54
- usar hechos (*using facts*) — 91
- valida tus pilares (*validate your pillars*) — 112
- features de vanidad (*vanity features*) — 51
- indicaciones verbales o escritas (*verbal or written directions*) — 97
- verbaliza (*verbalize*) — 28
- verbos (*verbs*) — 15, 25, 28, 84
- verifica con checklists (*verify with checklists*) — 110
- vibración y hápticos (*vibration and haptics*) — 148
- indicaciones visuales (*visual directions*) — 97
- elementos visuales (*visuals*) — 57
- voz en off (*voice-over*) — 148
- formas de derivar mecánicas (*ways to derive mechanics*) — 36
- quién, qué, dónde, por qué, cuándo y cómo (5W+H) (*who, what, where, why, when, and how (5W+H)*) — 60, 78
- Wolpaw, Erik — 16
- escribe one-pagers (*write one-pagers*) — 92
- escritura (*writing*) — 148
- escribir un hecho (*writing a fact*) — 90
- YouTube — 168
- suma cero (*zero-sum*) — 116
- acerca y aleja el zoom (*zoom in, zoom out*) — 26
- Zubek, Robert — 13
- Zuur Platten, John — 96
