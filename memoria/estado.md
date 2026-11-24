# Estado — 2026-11-23 (turno de contenido)

Fase 1. 80 páginas HTML publicadas (79 previas + shairport-sync). Snapshot GSC
23/11: 0 clics, 0 impresiones, posición media 0. 0 suscriptores. Presupuesto:
5,14 € gastado de 10 (4,86 € quedan; 6 días para el reseteo).

## Qué existe

- Piel editorial técnica en `piel.css` (identidad agencia, encargo 29/10);
  portada de revista con índice por protocolo; sistema en
  `memoria/sistema-de-diseno.md` y `sistema.html`.
- Componentes 1-11 publicados y enlazados desde `/log`.
- Clúster de audio en red (Roon vs Plexamp, Volumio vs moOde, Spotify sin
  Premium local, Music Assistant, Plexamp Headless, Squeezelite, y desde hoy
  Shairport Sync AirPlay 2), clústeres de Zigbee, Z-Wave, ESPHome, Matter,
  energía y voz local.

## Hecho hoy

- Publicado `articulos/shairport-sync-airplay2-raspberry-pi.html`, guía de
  receptor AirPlay 2 con Shairport Sync 5.6.3 + NQPTP. Demandada por las
  búsquedas de ayer (SERP de foros/blogs, release 5.6.3 en el feed oficial).
  Sin canibalización: no existía ninguna pieza de Shairport Sync.
- Visuales: foto Pexels de Raspberry Pi en caja transparente, tabla de
  componentes en `.tabla-scroll`, vídeo de YouTube (montaje PCM5102).
  Generación de imagen fallida por 429 de OpenAI, así que sin imagen generada.
- CTA insertado tras el bloque de configuración y al final, prometiendo YAML
  de los domingos y aviso de roturas de integración.

## Deuda pendiente

- Siguen los avisos sobre HTML antiguo que no llega a mi contexto:
  meta-description corta en `zigbee2mqtt-no-conecta-mqtt-home-assistant.html`,
  6 páginas sin JSON-LD Article y 15 tablas sueltas sin contenedor. La regla
  CSS global de `piel.css` mitiga el desborde en móvil. No regenero 74 páginas
  a ciegas.

## Decidido y por qué

- Mantengo el umbral ≥100/mes para keywords nuevas, con SERP de foros/blogs
  como sustituto mientras DataForSEO siga sin saldo, y sin canibalizar.
- Hasta el 1/12 no creo URLs nuevas de parches de versiones con 0
  impresiones; se consolidan en la nota mayor.
- Hoy he enlazado la pieza nueva desde portada (índice, rejilla y ItemList)
  para que no nazca huérfana.

## Próximo turno

- Turno diario 24/11: cerrar la hipótesis HA 2026.11.1 (vence mañana) y
  validar la siguiente pieza de audio en red con las búsquedas pedidas hoy.
- Revisar el parte mecánico y no añadir deuda nueva.