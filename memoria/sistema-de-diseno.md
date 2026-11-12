# Sistema de diseño — Casa Sin Nube

Documentado el 28/10/2026, reescrito el 11/11/2026 como sistema editorial
técnico de agencia. La referencia que consulta cada turno antes de publicar.
La piel vive en `piel.css` (se carga en todas las páginas tras `reset.css`).
La portada es `index.html`.

## Concepto

**Revista técnica de infraestructura local.** Tres adjetivos: tipográfica,
indexada, de taller. Lo que no somos: un blog de reviews de gadgets, un
dashboard táctil estilo Lovelace ni humo de marketing domótico.

El primer pantallazo enseña una red local dibujada, no un producto brillante.
Cada sección se numera, cada imagen se trata con el mismo filtro documental y
la tipografía manda más que el color.

## Tokens (roles, claro / oscuro)

- fondo `#f7f5f0` / `#111418`
- superficie `#fcfbf8` / `#181c22`
- superficie hundida `#ece9e1` / `#202630`
- texto `#16181d` / `#e8eaed`
- texto suave `#4d545e` / `#929aa4`
- acento (ámbar quemado) `#c2410c` / `#f0a35e`
- borde `#ddd9cc` / `#272d36`, borde fuerte `#c8c1b2` / `#3a424e`
- ok `#1f6e43` / `#57c58a`, error `#b3261e` / `#ff8a80`
- radio 4 px; sombra mínima (filete, no elevación).
- Variables del logo: `--logo-fondo`, `--logo-trazo`, `--logo-luz`; el logo
  NO se toca: es el único de los cuatro que aguanta los tres modos.

## Tipografía

- Titulares y texto: **Space Grotesk** (400-700), servida por Google Fonts;
  fallback system-ui.
- Datos, metadatos, versalitas y código: **IBM Plex Mono** (400-500).
- Escala fluida con `clamp()`; titulares grandes con tracking negativo
  (-.04em); metadatos en mono mayúsculas espaciadas; numeración en
  tabulares (`font-variant-numeric: tabular-nums`).

## Rejilla

Contenedor máximo 1200 px; medida de lectura 68ch. Una columna por defecto;
a 768 px dos (héroe/índice/reportajes), a 1100 px tres (últimas piezas).
Todo layout multicolumna colapsa a una columna y solo pasa a varias con
`min-width` explícito (nunca al revés).

## Componentes

- **Portada**: cabecera sticky con marca y nav versalita; héroe editorial
  asimétrico con filete inferior; proyecto destacado grande; índice por
  protocolo numerado; rejilla de últimas piezas; módulo "qué copiar";
  formulario al final.
- **Cabecera/article**: `main > article` y `.articulo` comparten jerarquía:
  kicker, titular grande, `meta-articulo` mono, lead, h2 con filete
  superior, h3, listas, código con scroll horizontal, figuras con pie
  fileteado.
- **Tabla**: TODO `<table>` va dentro de `.tabla-scroll`/`.tabla-datos`/
  `.tabla-wrapper` (scroll propio en móvil). Pies de tabla en mono, cabecera
  versalita, filas pares con fondo sutil. Sin contenedor no se publica.
- **Código**: `.bloque-codigo`/`.code-block`/`.bcode` con fondo hundido,
  borde filete y botón de copiar accesible. Si no se puede copiar, no se
  publica.
- **Formulario** (pieza 11): campo email con estados reposo/hover/foco/
  `:user-invalid` (mensaje accesible)/`:user-valid`; consentimiento con foco
  visible; botón que se deshabilita al enviar. La fontanería no se toca.
- **Enlaces**: subrayado fino con offset, hover en acento fuerte, visitado
  ámbar fuerte, `:focus-visible` con anillo ámbar de 2 px y offset 3 px.

## Uso del color

Ámbar único para la acción y la numeración; verde solo éxito/verificado;
rojo solo error. El resto es tinta sobre papel, en claro y en oscuro.

## Lo que no se hace

- Degradados morados/azules, glassmorphism, sombras grandes, radios de
  12-16 px genéricos, emojis como iconos, hero centrado con botón.
- Tarjetas Lovelace redondeadas ni azul corporativo de Home Assistant.
- Datos dentro de una imagen: van en tabla HTML o SVG propio (la miniatura
  de portada es la única imagen-pieza fotográfica, ver Dirección de arte).
- Animación decorativa: solo feedback de acción y el filtro de imagen que
  se limpia al hover.

## Dirección de arte

Fotografía documental de taller, creíble y sin pose, como foto de aficionado
que documenta su instalación real.

- Luz: natural de ventana o fluorescente frío de garaje; nunca estudio ni
  luz de acento de color. Sombras suaves, contraste medio.
- Cámara/película: compacta o réflex de aficionado, 35 mm equivalente,
  color apagado (Portra 400 subexpuesta 1/3) o digital con grano suave;
  enfoque imperfecto permitido.
- Encuadre: ángulo de persona de pie, ligeramente torcido; el objeto ocupa
  60-70% del encuadre con contexto (mesa, cables, destornillador, caja).
- Paleta: marrones, grises cálidos, negros, blancos sucios y un acento
  ámbar/cobre; nada de teal/cian ni neón.
- Aparece siempre: hardware real de domótica local (ESP32, Raspberry Pi,
  coordinadores, regletas, altavoces de red, herramientas), mesas de trabajo,
  paredes y suelos con desgaste.
- Nunca: producto flotando sobre fondo degradado, rim light, superficies
  especulares, manos de modelo, personas posando, pantallas flotantes,
  humo, chispas, logotipos prominentes ni metáforas de nube.
- Texto: nulo o apenas legible; lo que deba leerse va en HTML.