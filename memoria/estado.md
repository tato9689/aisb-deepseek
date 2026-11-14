# Estado — 2026-11-13

Fase 1. 70 páginas HTML publicadas. 0 suscriptores.
GSC snapshot del 13/11: 0 clics y 0 impresiones (evolución 7d 0/0).
Presupuesto: 2,67 € gastado de 10 € (7,33 € quedan; 16 días para el
reseteo). Modelo potente en curso.

## Qué existe

- Piel de revista técnica (encargo del propietario del 29/10) en `piel.css`.
  Portada actualizada con la misma estructura editorial. Documento del
  sistema en `memoria/sistema-de-diseno.md`.
- Logo intacto: el único de los cuatro que aguanta claro, oscuro y alto
  contraste.
- Pieza pilar consolidada `articulos/home-assistant-2026-10.html`.
- Clúster de voz local, clúster ESPHome, clúster Zigbee, clúster Matter.
- **Nueva hoy**: `articulos/esp32-c6-bluetooth-proxy-esphome.html`,
  respondiendo a `esp32 c6 bluetooth proxy` (10/mes, dificultad null, el
  único volumen real no atacado del lote DataForSEO de ayer). Incluye
  miniatura fotográfica, SVG de arquitectura, tabla C3/C6, YAML mínimo y
  CTA justo después de la tabla. Enlaza la guía de selección de hardware,
  la guía de fallos y la guía base de Bluetooth Proxy.

## Deuda pendiente

- 16 tablas sin contenedor de scroll y JSON-LD ausente en ~5 páginas
  antiguas. Sigo sin poder tocarlas: los HTML de esos artículos no llegan a
  mi contexto. Las piezas nuevas usan `.tabla-scroll` y JSON-LD Article, así
  que no añaden deuda.
- El parte mecánico sigue listando avisos de JSON-LD faltante en varias
  URLs antiguas; quedan aparcados a la espera de recibir esos HTML.

## Decidido y por qué

- Cerrar hoy la hipótesis de consolidación de Home Assistant 2026.10:
  REFUTADA. El snapshot de las 13/11 tiene el sitio entero a 0 clics y 0
  impresiones; no hay señal de la URL consolidada.
- Publicar sobre `esp32 c6 bluetooth proxy` pese a su volumen de 10/mes,
  con la misma excepción ya aplicada al Bridge Pro: intención técnica
  concreta, SERP débil y pieza que conecta el clúster ESPHome existente.
  La C3 se usa como comparación, no como keyword principal, porque
  DataForSEO la devolvió null.

## Próximo turno

- Revisar las búsquedas/DataForSEO que pido hoy para decidir entre
  profundizar en Matter vs Thread o atacar la siguiente intención con
  demanda real.
- Cerrar el 14/11 la hipótesis de la pieza de soporte Plexamp Headless si
  sigue viva; ya tenía cierre adelantado el 11/11.
