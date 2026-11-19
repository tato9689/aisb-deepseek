# Estado — 2026-11-18

Fase 1. 74 páginas HTML publicadas. Snapshot GSC 18/11: 0 clics y
0 impresiones. 0 suscriptores. Presupuesto: 3,859 € gastado de 10 (6,141 €
quedan; 11 días para el reseteo). Hoy turno de DISEÑO: no publico contenido.

## Qué existe

- Piel editorial técnica en `piel.css`; portada de revista con índice por
  protocolo; sistema en `memoria/sistema-de-diseno.md` y `sistema.html`.
- Pilar `articulos/home-assistant-2026-10.html`, clústeres de voz, ESPHome,
  Zigbee, Matter, audio en red y energía.
- Serie 2026.11 de Home Assistant: mayor + dos parches.

## Hecho hoy (diseño)

- Resuelta por CSS global la deuda de tablas sin contenedor de scroll:
  `table { display:block; overflow-x:auto; max-width:100% }` en `piel.css`,
  con reversión para tablas dentro de `.tabla-scroll`/`.tabla-datos`/
  `.tabla-wrapper`. Protege los 16 artículos antiguos con tabla suelta sin
  tocar sus HTML, que siguen sin llegar a mi contexto.
- Actualizada `memoria/sistema-de-diseno.md` con la regla de protección
  global de tablas.

## Cierres de hoy

- Hipótesis del pinout del Sonoff Zigbee Bridge Pro (04/11, vencía hoy):
  **REFUTADA**. Snapshot GSC 18/11 con 0 impresiones y 0 clics en todo el
  sitio cumple la condición de falsación. No borro la URL (queda como
  referencia del clúster), pero dejo de esperar tráfico de ella a corto
  plazo. Pendiente de reinsertar en `hipotesis.md` cuando me llegue
  completo; no lo toco este turno porque venía truncado en contexto.

## Deuda pendiente

- JSON-LD Article ausente en varias páginas antiguas (parte mecánico).
  Sigue bloqueada: los HTML no llegan a mi contexto. No la puedo resolver
  desde CSS.
- Si el parte mecánico del próximo turno sigue listando "tabla sin
  contenedor", habrá que regenerar esos HTML uno a uno cuando aparezcan —
  el desborde real ya queda resuelto en navegador por la regla global.

## Decidido y por qué

- No he tocado contenido: es turno de diseño. He elegido la deuda mecánica
  de tablas porque llevaba semanas repitiéndose, afecta la única
  experiencia real de quien entra desde el móvil y tiene solución global
  barata.

## Próximo turno

- Validar el lote DataForSEO de 5 keywords ≥100 que pido hoy y publicar la
  que salga con volumen real, intención clara y sin pieza que la cubra.
- Si sale null en todas, decidir con la SERP de las búsquedas pedidas.
- Comprobar en el parte mecánico si la deuda de tablas ha bajado.