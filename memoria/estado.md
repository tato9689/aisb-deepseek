# Estado — 2026-11-12

Fase 1. 69 páginas HTML publicadas. 0 suscriptores.
GSC snapshot del 12/11: 0 clics y 0 impresiones (evolución 7d 0/0).
Presupuesto: 2,488 € gastado de 10 € (7,512 € quedan; 17 días para el
reseteo). Modelo potente en curso.

## Qué existe

- Piel reescrita por completo (encargo del propietario del 29/10): sistema
  de revista técnica de infraestructura local en `piel.css`. Portada
  actualizada con la misma estructura editorial. Documento del sistema en
  `memoria/sistema-de-diseno.md`.
- Logo intacto: el único de los cuatro que aguanta claro, oscuro y alto
  contraste.
- Pieza pilar consolidada `articulos/home-assistant-2026-10.html`.
- Clúster de voz local, clúster ESPHome, clúster Zigbee, clúster Matter.
- **Nueva hoy**: `articulos/zigbee-vs-zwave-vs-matter-2026.html`, pilar de
  decisión de protocolo. Responde a `zigbee vs zwave vs matter`, la única
  keyword con volumen real del lote DataForSEO de hoy (10/mes, dificultad
  null), y enlaza los clústeres Zigbee, Z-Wave y Matter. Incluye tabla,
  SVG de arquitecturas, YAML y dos CTAs. Enlazada desde portada (índice,
  últimas piezas y ItemList a 16).

## Deuda pendiente

- 16 tablas sin contenedor de scroll y JSON-LD ausente en ~5 páginas.
  Sigo sin poder tocarlas: los HTML de esos artículos no llegan a mi
  contexto. Las piezas nuevas usan `.tabla-scroll`, así que no añaden deuda.

## Decidido y por qué

- Publicar solo sobre la keyword con volumen validado hoy (10/mes), con la
  misma excepción ya aplicada al Bridge Pro: intención de decisión clara y
  pilar que conecta clústeres. No escribo sobre las variantes ESP32 porque
  todas vinieron con volumen null en DataForSEO.
- No toco la piel ni añado CSS global: no tengo el contenido actual de
  `piel.css` y no quiero romper el sistema de diseño.

## Próximo turno

- Revisar los resultados de búsqueda/DataForSEO que pido hoy para afinar
  esta pieza o atacar la siguiente intención con demanda real.
- Cerrar hipótesis vencidas: consolidación (13/11) y beta (14/11).