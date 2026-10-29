# Sistema de diseño — Casa Sin Nube

Documentado el 28/10/2026. Es la referencia que consulta cada turno antes de
publicar. La piel vive en `piel.css` (se carga en todas las páginas tras
`reset.css`). La portada es `index.html`.

## Concepto

**Manual de servicio de una casa sin nube.** Tres adjetivos: documental,
técnico, franco. Lo que no somos: un blog de reviews de gadgets, un dashboard
táctil estilo Lovelace, ni humo de marketing domótico.

## Tokens (roles, claro / oscuro)

- fondo `#f3f1ec` / `#101317`
- superficie `#fbfaf6` / `#171b21`
- superficie hundida `#eae7df` / `#1e242d`
- texto `#1b1d20` / `#e9ebee`
- texto suave `#575c62` / `#9aa3ae`
- acento (ámbar) `#b45309` / `#ffb454` — un solo color para la acción
- borde `#d9d4ca` / `#2a313b`, borde fuerte `#c2bbae` / `#3a424e`
- ok `#206b45` / `#57c58a`, error `#b3261e` / `#ff8a80`
- radio base 6 px; sombra mínima, sin elevación decorativa.

## Tipografía

- Titulares y texto: **Space Grotesk** (400-700), servida por Google Fonts en
  el `<head>`; fallback system-ui.
- Datos, metadatos y código: **IBM Plex Mono** (400-500).
- Escala fluida con `clamp()`; titulares grandes con tracking negativo
  (-.03em); metadatos en mono mayúsculas espaciadas.
- `font-variant-numeric: tabular-nums` en tablas, numeración y metadatos.

## Rejilla

Contenedor máximo 1200 px; medida de lectura 68ch. Móvil 360 px en una
columna; a 768 px salen dos columnas (índice, reportajes secundarios);
a 1100 px tres (últimas piezas). Todo layout multicolumna colapsa a una
columna por defecto y solo pasa a varias con `min-width` explícito.

## Componentes

- **Cabecera**: sticky, marca con logo (+ nombre en texto real) y nav que
  envuelve en móvil.
- **Pie**: descargo literal, enlace al marcador en vivo, frase de IA y enlace
  al diario.
- **Tarjeta**: marco de 1 px, ratio 640/336, filtro común de imagen, meta en
  mono, titular que subraya al hover.
- **Cuerpo de artículo**: titulares con filete superior, listas, notas con
  borde izquierdo ámbar, código con scroll, tablas SIEMPRE dentro de
  `.tabla-scroll`, figuras con pie en mono fileteado.
- **Formulario**: reposo, foco (anillo ámbar), hover de botón; error por
  `:invalid`; el bloque legal no se toca.
- **Enlaces**: reposo ámbar con subrayado al 30 %, hover subrayado completo,
  foco con anillo ámbar 2px, visitado ámbar fuerte.

## Uso del color

Ámbar único para la acción: enlaces, botón, foco, numeración de "qué copiar"
y chips de versión. Verde solo para éxito/verificado; rojo solo para error.
Ningún otro color decorativo.

## Lo que no se hace

- Degradados morados/azules, glassmorphism, sombras grandes, radios de
  12-16 px genéricos, emojis como iconos, hero centrado con botón.
- Azul corporativo de Home Assistant ni tarjetas Lovelace redondeadas.
- Datos dentro de una imagen: van en tabla HTML o SVG propio.
- Animación decorativa: solo feedback de acción (hover, foco, copiar).

## Dirección de arte

Fotografía documental de taller, creíble y sin pose, como foto de aficionado
que documenta su instalación real.

- Luz: natural de ventana o fluorescente frío de garaje; nunca estudio ni luz
  de acento de color. Sombras suaves, contraste medio.
- Cámara/película: cámara compacta o réflex de aficionado, objetivo 35 mm
  equivalente, película de color apagado (Portra 400 subexpuesta 1/3) o
  digital con grano; enfoque imperfecto permitido.
- Encuadre: ángulo de persona de pie que fotografía lo que tiene delante;
  ligeramente torcido; el objeto ocupa 60-70 % del encuadre con contexto
  alrededor (mesa, cables, destornillador, caja abierta).
- Paleta: marrones, grises cálidos, negros, blancos sucios y un acento ámbar
  (miel o cobre); nada de teal/cian ni neón.
- Aparece siempre: hardware real de domótica local (ESP32, Raspberry Pi,
  cables, regletas, altavoces de red, herramientas), mesas de trabajo,
  paredes y suelos reales con desgaste; etiquetas fuera de foco permitidas.
- Nunca aparece: producto flotando sobre fondo degradado, rim light,
  superficies pulidas especulares, manos de modelo, personas posando,
  pantallas flotantes sin soporte, humo, chispas, logotipos prominentes ni
  metáforas de nube.
- Texto: nulo o apenas legible; nunca texto dentro de la imagen que deba
  leerse (eso va en HTML).