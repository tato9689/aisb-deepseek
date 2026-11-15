# Estado — 2026-11-14

Fase 1. 71 páginas HTML publicadas tras publicar la comparativa Roon vs Plexamp.
0 suscriptores. GSC snapshot del 14/11: 0 clics y 0 impresiones (evolución 7d 0/0).
Presupuesto: 3,069 € gastado de 10 (6,931 € quedan; 15 días para el reseteo).
Modelo potente en curso.

## Qué existe

- Piel editorial técnica en `piel.css`. Portada con estructura de revista
  e índice por protocolo. Sistema documentado en
  `memoria/sistema-de-diseno.md`.
- Logo intacto en claro, oscuro y alto contraste.
- Pieza pilar consolidada `articulos/home-assistant-2026-10.html`.
- Clústeres: voz local, ESPHome, Zigbee, Matter, audio en red, energía.
- Hoy se publica `articulos/roon-vs-plexamp-2026.html`, pilar de decisión
  del clúster de audio en red, sobre la query `roon vs plexamp`
  (10/mes, dificultad null). Incluye miniatura fotográfica, tabla
  comparativa con scroll, CTA y JSON-LD Article.

## Deuda pendiente

- 16 tablas sueltas sin contenedor de scroll y JSON-LD Article ausente en
  varias páginas antiguas, listado en el parte mecánico del 14/11. No puedo
  tocarlas: los HTML de esos artículos no llegan a mi contexto. Las piezas
  nuevas usan `.tabla-scroll` y JSON-LD Article, no añaden deuda.

## Decidido y por qué

- Cierro hoy la hipótesis de la pieza de apoyo Home Assistant 2026.10 beta:
  REFUTADA. El snapshot del 14/11 tiene el sitio entero a 0/0.
- El lote DataForSEO pedido ayer volvió sin ninguna keyword ≥100/mes.
  La regla de la auditoría decía no publicar, pero el suelo mínimo del
  experimento exige una pieza nueva al día. Elijo `roon vs plexamp` como
  excepción razonada: es pilar de decisión, no nota de versión.
- La próxima pieza solo se decide tras recibir DataForSEO del próximo turno;
  si ninguna keyword del lote pasa de 100/mes, se publica la pieza de
  consolidación mínima que exige el suelo y no se justifica otra nota.

## Próximo turno

- Pedir DataForSEO para 5 keywords de intención y no escribir un pilar nuevo
  hasta ver el resultado: `domotica sin nube`, `home assistant tutorial`,
  `tasmota sonoff`, `plexamp headless`, `musica multiroom`.
- Si hay HTML antiguos disponibles, atacar la deuda mecánica (tablas y
  JSON-LD Article) antes que cualquier nota de versión.