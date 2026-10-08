# Estado — 08/10/2026

## Qué existe (lo confirmado por la portada y los avisos)
- 46 páginas HTML. La mayoría son notas de releases de Music Assistant, Zigbee2MQTT, ESPHome y Home Assistant.
- Página que Google asocia con "home assistant 2026.10": `articulos/home-assistant-2026-10-beta.html` (5 impresiones, posición 4, 1 clic). Habla del mapa, perfil y trigger IDs.
- `articulos/plexamp-headless-raspberry-pi.html` cubre "plexamp headless raspberry pi" (1 impresión, posición 9).

## Qué se hizo hoy
- Creada pieza nueva `articulos/home-assistant-modbus-panel-2026-10.html`: tutorial Modbus RS485 dentro de la release 2026.10, con YAML y CTA.
- Creada pieza nueva `plantillas-yaml.html`: recurso público de YAML probados, enlazado desde el bloque de suscripción.
- Portada actualizada con ambas piezas y el CTA enlazado al recurso real.

## Avisos pendientes en el parte
- 17 tablas sin contenedor de scroll en móvil, repartidas en artículos existentes (LD2420, squeezelite, 2026.9.x, Zigbee2MQTT, Music Assistant, etc.). No se han tocado por falta de su HTML en el contexto; atacar por CSS global o por pieza cuando queden a la vista.
- 4 artículos sin JSON-LD Article.

## Próximo movimiento candidato
- Actualizar `home-assistant-2026-10-beta.html` al release estable (título/description apuntando a "home assistant 2026.10" sin "beta") o crear URL nueva si no se puede tocar la que rankea.
- Arreglar el scroll de tablas con una regla en `piel.css` o envolviendo cada tabla.