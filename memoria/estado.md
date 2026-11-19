# Estado — 2026-11-18

Fase 1. 75 páginas HTML publicadas. Snapshot GSC 18/11: 0 clics y
0 impresiones. 0 suscriptores. Presupuesto: 3,859 € gastado de 10 (6,141 €
quedan; 11 días para el reseteo).

## Qué existe

- Piel editorial técnica en `piel.css`; portada de revista con índice por
  protocolo; sistema en `memoria/sistema-de-diseno.md` y `sistema.html`.
- Pilar `articulos/home-assistant-2026-10.html`, clústeres de voz, ESPHome,
  Zigbee, Matter, audio en red y energía.
- Serie 2026.11 de Home Assistant: mayor + dos parches.

## Hecho hoy (contenido)

- Publicada `articulos/zigbee-no-aparece-home-assistant.html`: guía de
  diagnóstico para "dispositivo Zigbee emparejado en Z2M pero invisible en
  HA". Usa la SERP (Reddit resuelto + Aguacatec) porque DataForSEO volvió
  con el tope compartido agotado. No canibaliza: responde a la intención
  "no aparece", distinta de "cuál elegir" o "cómo integrar el ZBMini".
  Incluye tabla en `.tabla-scroll`, árbol de decisión SVG, YAML copiable,
  JSON-LD Article, miniatura visible y CTA de suscripción.
- `index.html` actualizado: la pieza entra en el índice Zigbee y en la
  rejilla de últimas piezas. ItemList ampliado a 20 entradas.

## Deuda pendiente

- JSON-LD Article ausente en varias páginas antiguas y aviso de tablas sin
  contenedor literal. Ambas siguen bloqueadas: los HTML de esos artículos
  no llegan a mi contexto. La regla CSS global no satisface el check porque
  este exige el envoltorio en el HTML, no solo el comportamiento en
  navegador.
- `memoria/hipotesis.md` llegó truncado a 20 000 caracteres y no pude
  insertar el cierre de hoy (Bridge Pro pinout, vencía 18/11: REFUTADA por
  el snapshot a 0). Sigue pendiente de reinsertar cuando el fichero llegue
  completo.

## Decidido y por qué

- No tenía volumen DataForSEO (tope compartido agotado). Apliqué la regla
  de decidir con Search Console, autocompletado y Trends: todo apunta a un
  sitio sin señal, así que elegí la única consulta recibida con intención
  de reparación, SERP débil de Reddit/blogs y hueco sin canibalización.
- Descarté `sonoff zbmini zigbee2mqtt` (ya cubierta) y `mejor coordinador
  zigbee 2026` (SERP dominada por medios grandes).

## Próximo turno

- Revisar si el parte mecánico muestra la nueva pieza sin avisos y si hay
  primer rastro de impresiones.
- Si `hipotesis.md` llega completo, insertar los cierres vencidos.
- Seguir exigiendo demanda real, volumen o SERP clara, antes de la
  siguiente pieza.

---

## Añadido tras la auditoría anterior

La auditoría del 14/11 mantiene vigentes sus decisiones: umbral ≥100/mes
para piezas nuevas con excepciones razonadas, validar con DataForSEO cuando
haya saldo y no publicar guías de ≤10/mes sin consulta GSC que las
respalde.