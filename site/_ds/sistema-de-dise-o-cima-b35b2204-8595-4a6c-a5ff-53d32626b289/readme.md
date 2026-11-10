# Cima Consulting — Sistema de diseño

Sistema de diseño de **CIMA Consulting**, consultoría 1:1 de 60 a 90 días para marcas
personales que quieren convertir su conocimiento en un negocio rentable a través de
Instagram. El trabajo cubre oferta, posicionamiento, mensaje, contenido, Social Funnel y
conversaciones por DM.

- Sede: Caracas, Venezuela (10.4806° N, 66.9036° W). Est. 2025.
- Tagline: **Construimos estrategia. Construimos negocios.**
- Tres pilares: Estrategia · Sistemas · Crecimiento.
- Idiomas del sistema: español (principal) e inglés.

## Fuentes de este sistema

Todo lo que hay aquí procede de material entregado por el cliente. No hay codebase ni
archivo de Figma asociado.

| Fuente | Archivo en el proyecto |
|---|---|
| Tablero de identidad de marca | `assets/brand/tablero-identidad.png` |
| Guía de estilo (elementos visuales) | `assets/brand/guia-estilo.png` |
| Logotipo vectorial | `assets/logos/cima-wordmark.svg` (limpiado del original) |
| Tipografías licenciadas | `assets/fonts/` — PP Editorial New (4 cortes), Open Sauce One (4 pesos) |

---

## Fundamentos de contenido

**Voz.** Autoridad de experto con trato cercano. Escribe como quien ya resolvió el problema
y explica el camino, no como quien vende un curso. Primera persona plural para la
consultoría ("construimos", "trabajamos juntos"), segunda persona para el lector ("tu oferta",
"lo que vendes"). Nunca "nosotros los expertos" frente a "ustedes".

**Registro.** Afirmativo y seco. Frases cortas, verbos concretos, sin adverbios de relleno.
La marca afirma; no sugiere ni matiza.

- Sí: *"Sin oferta clara no hay funnel que funcione."*
- Sí: *"El trabajo lo haces tú; la estrategia la construimos juntos."*
- No: *"Podríamos ayudarte a explorar diferentes maneras de potenciar tu marca."*

**Estructura de las frases de marca.** Paralelismo y repetición. El tagline es la fórmula
madre: sujeto + verbo + objeto, dos veces.
*Construimos estrategia. Construimos negocios.* / *No vendemos contenido. Vendemos criterio.*
*La estrategia es la base. El crecimiento es la consecuencia.*

**Caja alta.** Etiquetas, pies, numeraciones, botones y navegación van en mayúsculas con
tracking abierto. El cuerpo y los titulares van en caja normal. Las mayúsculas se reservan
a lo estructural; nunca se usan para gritar.

**Puntuación.** Punto al final de las frases de marca, incluso cuando son una sola palabra.
Sin signos de exclamación. Sin puntos suspensivos. Los guiones largos se usan con
moderación; el sistema prefiere el punto.

**Emoji: nunca.** Ni en redes, ni en DM, ni en email. Los indicadores de la marca (`+ — × → ·`)
cumplen esa función.

**Números.** Siempre con cero a la izquierda en numeraciones (`01`, `02`). Los plazos en
cifras ("60 a 90 días", "12 semanas"). Los precios sin decimales.

**Llamadas a la acción.** Imperativas y concretas: *Agendar diagnóstico*, *Ver el método*,
*Escríbeme "OFERTA"*. Nunca "link en bio", nunca "haz clic aquí", nunca "descubre más".

---

## Fundamentos visuales

### Color

Cinco colores. No hay un sexto.

| Nombre | Hex | Papel |
|---|---|---|
| Negro profundo | `#0A0A0A` | Fondo maestro. La marca vive en negro. |
| Gris carbón | `#1C1C1C` | Superficie elevada sobre el negro. |
| Arena Cima | `#D8C39A` | Acento único: logotipo, cifras, filetes, botones. |
| Marfil | `#F2F0EC` | Fondo maestro claro y texto sobre negro. |
| Gris piedra | `#8F877C` | Texto secundario y líneas. |

El acento arena es **escaso por definición**: como mucho un elemento arena de peso por
pantalla, más los filetes. Si dos cosas compiten en arena, una de las dos está mal.
Los colores semánticos (`#7C8F6B`, `#C9A227`, `#A5503F`, `#6B7F8F`) existen solo para estado
y validación; jamás como decoración.

**Los dos temas son iguales de válidos.** Oscuro por defecto en pantalla; claro (marfil,
nunca blanco puro) en documentos impresos, la slide de cita y una sección de la landing.
Se cambia con `data-theme="light"`; todos los alias semánticos se reasignan solos.

### Tipografía

Dos familias con papeles que no se cruzan.

**Regla general de títulos (todo el sistema).** Cada título tiene tres papeles:
- **Primario** — la palabra que carga el sentido ("viral" en "Tres cosas para ser viral"). Open Sauce
  One **Bold (700)**, tracking −0.055em, y **siempre la más grande** del título. Puede ir en Arena.
- **Apoyo** — el resto de la frase. Open Sauce One Regular, como máximo 0.45× del primario.
- **Acento** — Editorial New itálica. Opcional, máximo uno por pieza y no en todas; nunca mayor que
  el primario. La itálica dejó de ser el recurso principal de énfasis.

Otros recursos de énfasis además del color: subrayado arena (`mark="underline"`) y tachado sobre
ceniza para contrastes "esto no / esto sí" (`mark="strike"`). El subtítulo es pequeño y va pegado
al título. Los números nunca superan el tamaño del texto. Componente: `Title` (prop `lines`).

- **PP Editorial New** — la voz del énfasis. Palabra clave de títulos, citas. Ultralight (200) a partir de 40px
  con `letter-spacing: -0.02em` y `line-height: 0.94–1.02`. La itálica regular es solo para
  citas. Nunca se usa para UI ni para cuerpo largo.
- **Open Sauce One** — la estructura. Cuerpo, interfaz, datos, etiquetas, navegación.
  400/500/600/700.

> **Sustitución respecto al tablero original.** El tablero indica *Suisse Int'l* como sans.
> Los archivos entregados son **Open Sauce One**, y es la fuente que el sistema implementa.

La firma tipográfica de la marca es la etiqueta en caja alta con tracking de `.14em` a
`.22em` a 10–13px. Aparece en pies, eyebrows, numeraciones y botones.

Escala: razón 1.25 desde 16px (10 · 11 · 12 · 14 · 16 · 20 · 25 · 31 · 39 · 49 · 61 · 76 · 96 · 128).
Mínimos: 24px en slides a 1280×720, 12pt en impreso, 40px en piezas de redes a 1080px.

### Lenguaje visual de Cima (regla para cualquier herramienta)

Cima se ve como un **atlas científico**: cartografía, órbitas, coordenadas, instrumentos de medida y
la figura humana como escala. Blanco y negro, línea fina, mucho negro. El arena es el único color.

**Capas, siempre en este orden:**
1. Superficie plana: negro `#0A0A0A` o marfil `#F2F0EC`.
2. Patrón a sangre, 12–20% (`tokens/patterns.css`): `.pat-coordenadas`, `.pat-trayectorias`, `.pat-flujo`,
   `.pat-hud`, `.pat-constelacion`. Uno por sección. **Ningún fondo negro va sin patrón.** Los patrones con rótulos (coordenadas, trayectorias, hud) van en la columna sin texto; detrás de listas o párrafos solo flujo o constelación.
   Encuadres: `.pat-r` / `.pat-l` (anclar a un lado), `.pat-fade` / `.pat-fade-b` (desvanecer hacia el texto).
3. Imagen o ilustración en **su propia zona** de la retícula (columna, media página, banda), con
   fundido hacia el texto. Nunca bajo un párrafo ni bajo el título.
4. Texto con la jerarquía de la marca y los datos (coordenadas, Nº, año) como microtexto.

**Espacios.** El texto conserva siempre su columna limpia; la imagen ocupa la otra. En portadas
(hero, slide 01, portada de documento, primera lámina de carrusel) se puede experimentar: imagen a
sangre más grande, patrón `.strong`, recortes radiales, siempre que el título quede sobre negro o
marfil liso.

**Banco de imágenes** (`assets/imagery/`): claro-* para marfil, oscuro-* para negro. Oscuras: trayectorias,
ballena, espacio-tiempo, flujo, HUD, figura en eje, Atlas áureo, topografía, mapas. Claras: escultura
orbital, anatomía, figura en red, círculo, números, diagrama, anillos, anillo HUD.

### Interacciones web (`assets/js/cima-interactions.js`)
Cargar al final del `<body>` en cualquier web o landing.
- **Cursor de marca:** anillo fino con punto central arena, mira de líneas a pantalla completa y lectura
  de coordenadas (lat/lon de Caracas) junto al puntero. Sobre `.s-dark` usa arena #D8C39A; sobre `.s-light`
  arena profundo #6B5A36. Crece sobre enlaces y botones.
- **Parallax:** `data-parallax="0.03"` en imágenes (0.012 en patrones); `data-tilt` añade giro leve.
- **Campo de datos:** `<canvas data-cima-field style="color:#0A0A0A">` recrea la imagen de números como
  partículas que se apartan del puntero y muestran su coordenada.
- Se apaga en táctil y con `prefers-reduced-motion`.

**Espacios de imagen:** la imagen llena su celda (ancho de columna completo, `aspect-ratio` fijo,
`object-fit:cover`) y se desvanece con máscara; nunca `contain` dentro de una caja más grande, que deja
huecos.

### Patrones editoriales compartidos (todas las superficies)

Lo que se definió en redes es la regla de **todo** el sistema. Vive en `tokens/editorial.css`
(clases globales) y se aplica a landing, web, app, slides y documentos:

| Regla | Clase / token |
|---|---|
| Título jerarquizado: apoyo regular + primario bold, el más grande | `.ct` `.ct-sup` `.ct-pri` `.ar` `.mu` |
| Énfasis extra: subrayado / tachado arena que se dibuja | `.mk-u` `.mk-s` |
| Acento itálico Editorial New (opcional, uno por pieza) | `.ct-acc` |
| Etiqueta superior en arena caja alta | `.c-kicker` |
| Bajada con palabras clave en bold | `.c-lead` + `<b>` |
| Superficies planas y limpias (negro / marfil) | `.tex-mineral` · `.tex-papel` |
| Botones, etiquetas y círculos de vidrio | `.cbtn` `.cbtn-p` · `.ctag` · `.ccirc` · `.glass` |
| Entrada en cascada al hacer scroll | `.rv` + `--i` (añadir `.in` con IntersectionObserver) |

**Topes del primario por superficie** (regla de tamaño): web hero `--web-primary` (máx. 112px),
sección `--web-primary-sec` (máx. 76px), slides `--slide-primary` 120px, documentos
`--doc-primary` 54px, app `--app-primary` 40px, redes 210px a 1080. El apoyo va a ~0.4×.

**Fondos limpios (decisión vigente).** Web, landing, app, slides y documentos usan fondos planos:
negro profundo `#0A0A0A` y marfil `#F2F0EC`. Las texturas mineral/papel quedan guardadas en
`tokens/textures.css` para una fase posterior y hoy solo se usan en redes. Referencia de tono:
estudio editorial limpio, mucho aire, tipografía protagonista.

**Contraste.** Todo texto ≥ 4.5:1. Arena `#D8C39A` solo como texto sobre negro plano (11.5:1).
Sobre marfil el énfasis es arena tostada `#6B5A36` (5.9:1) y el texto atenuado `#6E675D` (4.9:1).
Nunca arena sobre grises medios, texturas o foto sin scrim.

**Ritmo mixto:** las secciones de una landing alternan negro y marfil (hero oscuro → método en
papel → programa en mineral…). Listas y comparaciones en filas con filetes; tarjetas de vidrio
solo en app (datos) y en elecciones reales. Cada sección lleva como mucho un elemento gráfico
(sello con asterisco, icono por fila, etiqueta con icono).

**Imágenes de marca** (`assets/imagery/`): `claro-*` (fondo blanco: escultura orbital, anatomía, círculo de
personas, números, diagrama, anillos de luz, anillo HUD) y `oscuro-*` (figura en eje, Atlas áureo, topografía,
mapas). Estilo: blanco y negro, ciencia y cartografía, figura humana como escala. Nada de 3D brillante.
Clase `.c-img`: se funde con la superficie (multiply sobre marfil, screen sobre negro). Se colocan en su
propia zona de la retícula (media página a sangre, banda inferior, columna lateral) con un fundido
`.fade-l` / `.fade-t` / `.fade-b` hacia el texto; nunca debajo de un párrafo.
> Son referencias aportadas por el cliente; antes de publicar hay que confirmar derechos o sustituirlas
> por imágenes propias o licenciadas en el mismo estilo.

**Iconografía de marca** (`assets/icons/cima/*.svg`, clase `.ci .ci-<nombre>`): 14 iconos de línea científica —
orbita, eje, anillo, curvas, espiral, mira, meridiano, constelacion, cumbre, brujula, escala, vesica,
figura, nodos. Trazo 1.25, toman el color del texto. Sustituyen a Phosphor en etiquetas y datos de marca;
Phosphor queda para UI funcional (flechas, cerrar, check).

**Patrones:** `.pat-grid` (retícula de coordenadas con cruces) y `.pat-dots` (puntos), al 14% de opacidad.

**Ilustraciones científicas** (`assets/graphics/art/<nombre>-<marfil|negro|arena>.svg`, clase `.c-art`):
topoglobo (curvas de nivel en esfera con coordenadas de Caracas), embudo (gravedad), terreno isométrico,
espiral áurea en perspectiva, lámina orbital y órbitas con estrellas. Son el gráfico principal de cada
pieza: grandes (35–50% del formato), a sangre o junto al título, nunca detrás del texto. `.soft` baja la
opacidad para fondos; `.m-turn` gira muy lento. Variantes: marfil, negro, arena (sobre negro) y arena-oscuro (#6B5A36, sobre marfil). La ilustración principal de una slide va en arena para que destaque sobre el patrón, con un pie "Fig. 0X · …" en arena y un dato (coordenadas, φ) en secundario.

**Gráficos de línea pequeños** (`assets/graphics/*.svg`, clases `.c-graphic .g-<nombre>`): ascenso, dirección,
punto de enfoque, recorrido, topografía, coordenadas, cumbre y meridiano. Trazo fino de 1.2,
toman el color del texto (`.ar` para arena) y van al 72% de opacidad. Sustituyen a los círculos
con icono: uno por slide o sección, en una esquina o junto al título, nunca detrás del texto.
Pueden flotar con `.m-float`.

**Email** no admite fuentes web ni vidrio: título en Helvetica normal + bold arena, botón arena
sólido en píldora.

### Espacio y retícula

Base 4px. Retícula editorial de 12 columnas, canal de 24px, margen de 64px en escritorio y
20px en móvil. Medida de lectura: 62 caracteres por defecto.

El sistema respira. Ante la duda entre dos escalones de espacio, se elige el mayor. Las
secciones de página usan 112px de aire vertical; los bloques dentro de una sección, 40–56px.

El **marco interior** (un filete de 1px a 24–48px del borde) es un recurso propio del sistema:
enmarca imágenes, portadas y piezas de redes sin necesidad de caja.

### Bordes, radios y cajas

La marca es arquitectónica: casi todo es recto.

- Radio 0 en composiciones editoriales y slides.
- Radio 4px en controles (botones, inputs, chips).
- Radio 8px en tarjetas de producto, 12px en modales.
- Radio píldora **solo** en tags y avatares.

Una tarjeta de Cima es, por defecto, **contorno de 1px sin relleno ni sombra**. La versión
con superficie y sombra (`raised`) se usa solo cuando hay solapamiento real de planos. Las
rejillas de módulos se separan con filetes de 1px (`gap:1px` sobre fondo de borde), no con
tarjetas flotantes.

Nunca: tarjeta redondeada con borde de color solo a la izquierda como decoración. El filete
lateral de 2px existe, pero es exclusivo de `Alert` y significa estado.

### Sombras

Separan planos; no simulan relieve. Sobre oscuro son sombras de recorte (negro puro,
opacidad 0.24–0.44); sobre claro son sombras de papel, cálidas y difusas. No hay sombras
interiores, ni glow, ni neumorfismo. `--shadow-accent` (anillo arena + halo tenue) se reserva
para el estado activo de un elemento y no para decorar.

### Transparencia y desenfoque

En producto (web, app): solo la barra de navegación fija (`rgba(10,10,10,.82)` + `blur(20px)`)
y el velo de los modales.

**Vidrio (glassmorphism)** — `tokens/glass.css`. Botones (todas las variantes `primary` y
`secondary` de `Button`, `IconButton` `glass`/`glass-arena`), tarjetas y pastillas en redes.
Sobre oscuro: marfil al 7%, borde marfil al 18%, brillo interior 1px, `blur(24px) saturate(140%)`.
Sobre papel: blanco al 42%, borde tinta al 10%. Variante Arena para el elemento destacado.
Botones en píldora (999px); tarjetas a 28px. `Button variant="solid"` (arena sólido) queda
para email e impreso, donde el desenfoque no existe.

### Redes sociales

Medidas a 1080px de ancho (`--social-*`): título 96 · título con desarrollo 80 · énfasis 173 ·
subtítulo 34 · tarjeta 32 · meta y números 22.

- **Sistema mixto:** las piezas alternan fondo **mineral carbón** (oscuro) y **papel de algodón**
  (claro). Estilo old money con desgaste vintage: textura + viñeta + grano siempre encima.
- Cabecera: "Cima Consulting" a la izquierda y el año ("2026") a la derecha. Nada más.
- Pie: usuario **@maykdiiaz** a la izquierda, progreso en guiones (activo en arena), "01 / 05 ·
  Desliza" y botón circular de vidrio con flecha a la derecha.
- **El logo de Cima no aparece en portadas.** La firma es @maykdiiaz.
- Numeraciones a 22px, nunca más grandes que el texto.
- Fotografía opcional en portadas, con scrim; la textura queda debajo como respaldo.
- El mineral se encuadra mostrando su zona ceniza iluminada (no se oscurece con viñeta fuerte);
  cada pieza oscura usa un encuadre distinto de la textura.

**Diagramación sin vacíos (regla).**
1. Tres zonas fijas: cabecera, cuerpo y pie. El cuerpo es **una sola masa de texto**, centrada
   verticalmente (o apoyada abajo si hay foto arriba). Nunca título arriba y contenido abajo con
   un hueco en medio.
2. Huecos internos del bloque ≤ 48px (`--social-block-gap`). La bajada va pegada al título.
3. **Regla de tamaño tipográfico.** El primario se ajusta al **72% del ancho útil**
   (`--social-fill`) con tope de **210px** (`--social-primary-max`); el apoyo va a 72px. El bloque de
   título no supera ~40% del alto de la pieza. Si no cabe, se acorta o se parte el texto; no se
   agranda. El aire que queda se llena con elementos gráficos (punto 4), no con más tamaño.
4. El aire sobrante es de la fotografía o de **elementos gráficos de la marca**, para que la pieza
   no se vea plana: etiqueta de vidrio con icono (tema), sello circular con icono fino, asterisco
   Arena girando, iconos al final de cada fila de lista y sobre cada columna de comparación,
   filetes que se dibujan. Uno o dos por pieza, nunca todos.
5. **No todo va en tarjeta.** Listas = filas con filetes; comparaciones = dos columnas con filete
   vertical; notas = etiqueta + texto. Tarjetas de vidrio solo para encuestas y botones.
6. Subtítulos partidos a dos extremos (bold a la izquierda, regular a la derecha) cuando la bajada
   tiene dos ideas.

**Motion.** Las líneas del título suben en cascada (0.35em, 110ms entre líneas, curva de entrada
de la marca); subrayados, tachados y filetes se dibujan de izquierda a derecha después; el guion
activo de progreso se llena; la flecha del botón circular late en horizontal; el asterisco gira
muy lento (24s) y la textura mineral deriva suavemente. Respeta `prefers-reduced-motion`.

### Imagen

Blanco y negro cálido o virado a sepia, con grano. Arquitectura, escultura clásica, concreto,
piedra, papel, tela. Figuras humanas de espalda o en contraluz, nunca sonriendo a cámara.
Contraste alto y sombras profundas: la imagen debe poder convivir con el negro profundo sin
un borde que la separe.

Texto sobre imagen: siempre con scrim (`--scrim-bottom`), nunca directo.

Las texturas del tablero (concreto, papel, piedra) son **acento**: fondos de portada,
separadores de sección, fondo de una pieza de redes de cada tres. Nunca bajo texto de lectura.

**Texturas** (`assets/textures/`, tokens en `tokens/textures.css`): `mineral-carbon.png`
(`--texture-mineral`) y `papel-algodon.png` (`--texture-papel`). Encima siempre `--vignette-dark`
o `--vignette-papel` y `--texture-grain` (overlay en oscuro, multiply en papel).

> No hay fotografía en el sistema. Los marcos de imagen de los kits son huecos etiquetados
> a la espera del material real.

### Movimiento

La marca no rebota. Todo entra desde la calma: opacidad más 12px de desplazamiento, con
`cubic-bezier(0.16, 1, 0.3, 1)`. Duraciones: 140ms para hover y foco, 220ms para paneles,
380ms para vistas, 700ms para revelados al hacer scroll. Ninguna escala supera 1.02.

- **Hover:** el color se aclara (arena → arena clara) o aparece el velo arena al 12%. Los
  elementos elevables suben 2px. Nunca cambia el tamaño del texto.
- **Press:** `scale(0.99)`, 80ms. Sin cambio de color adicional.
- **Foco:** anillo de 2px en arena, separado del elemento por 2px del color de fondo.
- `prefers-reduced-motion` anula todas las duraciones.

---

## Iconografía

**Set de iconos: Phosphor, peso Light** (CDN `@phosphor-icons/web@2.1.1`). Trazo fino que
acompaña a Editorial New. Componente `Icon` (`<Icon name="arrow-right" />`), que carga la hoja
la primera vez. Catálogo curado de 48 iconos en `components/icons/icons.card.html`, agrupado en
Estrategia, Contenido, Negocio, Sistema, Conversación y Navegación. `thin` a partir de 48px;
`regular` solo a 16px o menos. Dentro de botones circulares de vidrio para navegación.

Además, el vocabulario tipográfico heredado del tablero de identidad:

| Marca | Significado |
|---|---|
| `+` | Punto clave, adición, esquina de composición |
| `—` | Proceso, separación, elemento neutro |
| `×` | Decisión, cierre, punto final |
| `→` | Dirección, avance, llamada a la acción |
| `·` | Nota, elemento menor |

Se implementan en el componente `Mark` y se dibujan con la tipografía sans, no como SVG.

Emoji: nunca. Unicode decorativo: solo las cinco marcas de la tabla, más `‹ › ▾ ✓` en
controles nativos.

---

## Índice

### Raíz
- `styles.css` — punto de entrada. Solo `@import`.
- `readme.md` — este documento.
- `SKILL.md` — versión invocable como Agent Skill.

### `tokens/`
`fonts.css` (@font-face) · `colors.css` (base + alias, temas oscuro y claro) ·
`typography.css` (familias, escala, tracking, roles) · `spacing.css` (escala, retícula,
contenedores) · `effects.css` (radios, bordes, sombras, scrims, grano) · `motion.css`
(curvas, duraciones, reduced-motion) · `glass.css` (vidrio por tema) · `textures.css`
(mineral, papel, grano, viñetas) · `social.css` (escala de redes).

### `components/` — 29 componentes en 8 grupos
- **type:** `Title` (título con énfasis)
- **icons:** `Icon` (Phosphor Light)
- **core:** `Logo`, `Eyebrow`, `Rule`, `SectionNumber`, `Mark`
- **actions:** `Button`, `IconButton`, `TextLink`
- **forms:** `Field`, `Input`, `Textarea`, `Select`, `Checkbox`, `Radio`, `Switch`
- **display:** `Card`, `Badge`, `Tag`, `Stat`, `Quote`, `Avatar`
- **navigation:** `Tabs`, `Breadcrumb`, `ProgressBar`
- **feedback:** `Dialog`, `Alert`, `Tooltip`

Cada uno con `.jsx`, `.d.ts` y `.prompt.md`; una ficha HTML por carpeta.

**Adiciones intencionales.** El material entregado es una identidad de marca, no una
librería de UI: no define inventario de componentes. El conjunto anterior es el estándar
mínimo para cubrir las cinco superficies pedidas. `Mark`, `SectionNumber` y `Eyebrow` sí
derivan directamente del tablero (indicadores, numeraciones y etiquetas).

### `ui_kits/` — 6 superficies
| Kit | Contenido |
|---|---|
| `slides/` | 9 plantillas de slide a 1280×720 + visor con miniaturas |
| `landing/` | Página de venta completa a 1440px |
| `app/` | Panel de seguimiento de clientes (Cima OS) |
| `social/` | Feed 1:1, carrusel 4:5 y story 9:16 |
| `documentos/` | Propuesta de 3 páginas tamaño carta, imprimible |
| `email/` | Plantilla de 600px en tablas |

Cada kit tiene su `README.md` con las reglas propias de esa superficie.

### `guidelines/` — 20 fichas de fundamentos
Color (5), tipografía (5), espacio y efectos (5), marca (5).

### `assets/`
`fonts/` (9 archivos) · `logos/` (wordmark en currentColor, arena, marfil y negro) ·
`brand/` (tablero de identidad, guía de estilo, referencia de carrusel) · `textures/` (mineral, papel).
