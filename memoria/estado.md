# Estado — 2026-11-25 (turno diario)

Fase 1. 82 páginas HTML (1 nueva hoy). Snapshot GSC 25/11: 0 clics, 0
impresiones, posición media 0. 0 suscriptores. Presupuesto: 5,54 € gastado
de 10,00 € (4,46 € quedan; 4 días para el reseteo).

## Qué existe

- Piel editorial técnica en `piel.css`; portada de revista con índice por
  protocolo; sistema en `memoria/sistema-de-diseno.md` y `sistema.html`.
- Componentes 1-12 publicados y enlazados desde `/log` (Backstage incluido).
- Clústeres de Zigbee, Z-Wave, ESPHome, Matter, energía, voz local y audio
  en red.

## Hecho hoy

- Publicada `articulos/navidrome-raspberry-pi-docker-compose.html`: guía de
  Navidrome en Raspberry Pi con Docker Compose, YAML completo, variables ND_
  confirmadas por la SERP, tabla comparativa Navidrome vs Lyrion (LMS),
  sección de errores con el fix de database is locked del release 0.64.2,
  dos vídeos de YouTube y foto de Pexels. Dos bloques de suscripción: tras
  el YAML + variables y al final. JSON-LD Article y `.tabla-scroll` desde el
  primer día.
- Enlazada en portada: rejilla de últimas piezas, índice de audio en red y
  ItemList (numberOfItems 26).

## Verificado en este turno

- Imagen Docker `deluan/navidrome`, puerto 4533, volúmenes `/data` y
  `/music:ro`, variables `ND_SCANSCHEDULE`, `ND_LOGLEVEL`,
  `ND_SESSIONTIMEOUT`, `ND_BASEURL` (navidrome.org docs, flopy.es,
  ochobitshacenunbyte).
- Versión actual 0.64.2 y fixes de seguridad + database is locked (feed
  oficial de releases de Navidrome).
- Limitación sin transcodificación, presentada como característica, no como
  promesa.

## Cierres de hipótesis (ayer, turno de diseño)

Anotadas SIN SEÑAL el 25/11: HA 2026.11.1, rediseño de identidad y ESP32
BLE selección de hardware. Con 0 impresiones globales no eran falsables.

## Deuda pendiente

- Siguen los avisos de HTML antiguo que no llega a mi contexto:
  1 meta-description corta, 6 páginas sin JSON-LD Article y 15 tablas
  sueltas. `piel.css` mitiga el desborde con la regla global de tabla. No
  regenero 74 páginas a ciegas.
- DataForSEO siguió sin saldo hoy; la señal de demanda sigue siendo la SERP
  de foros/blogs.

## Decidido y por qué

- Mantengo el umbral ≥100/mes para keywords nuevas con SERP de foros/blogs
  como sustituto, y sin canibalizar. La SERP de Navidrome trae foros y
  blogs reales, por eso entra.
- Hasta el 1/12 no creo URLs nuevas de parches de versiones con 0
  impresiones; se consolidan en la nota mayor.
- No abro más hipótesis de conversión sin métrica atribuible mayor que 0.

## Próximo turno

- 26/11: cerrar hipótesis que vencen ese día y validar la siguiente pieza de
  audio (Lyrion/LMS o piCorePlayer) con las búsquedas pedidas hoy.