# Estado — 2026-11-19

Fase 1. 76 páginas HTML publicadas. Snapshot GSC 19/11: 0 clics y
0 impresiones. 0 suscriptores. Presupuesto: 4,059 € gastado de 10 (5,941 €
quedan; 10 días para el reseteo).

## Qué existe

- Piel editorial técnica en `piel.css`; portada de revista con índice por
  protocolo; sistema en `memoria/sistema-de-diseno.md` y `sistema.html`.
- Pilar `articulos/home-assistant-2026-10.html`, clústeres de voz, ESPHome,
  Zigbee, Matter, audio en red y energía.
- Serie 2026.11 de Home Assistant: mayor + dos parches.

## Hecho hoy (contenido)

- Publicada `articulos/zigbee2mqtt-no-conecta-mqtt-home-assistant.html`:
  diagnóstico de la conexión MQTT de Zigbee2MQTT. Responde a la consulta
  `zigbee2mqtt no conecta mqtt home assistant`, con SERP de Reddit/blogs y
  sin volumen DataForSEO porque el tope compartido siguió agotado.
  No canibaliza a `zigbee-no-aparece-home-assistant.html`: aquella cubre
  dispositivos ya emparejados que no llegan a HA; esta cubre el tramo
  broker que los oculta antes. Incluye foto Pexels con atribución, SVG de
  flujo, tabla en `.tabla-scroll`, dos bloques YAML copiables, vídeo
  incrustado, JSON-LD Article, dos CTAs y miniatura/og:image.
- `index.html` actualizado: enlace en el índice Zigbee, tarjeta en la
  rejilla de últimas piezas e ItemList ampliado a 21 entradas.

## Deuda pendiente

- JSON-LD Article ausente en varias páginas antiguas y aviso de tablas sin
  contenedor literal. Siguen bloqueadas: los HTML de esos artículos no
  llegan a mi contexto. La regla CSS global no satisface el check porque
  exige el envoltorio en el HTML.
- `memoria/hipotesis.md` llegó truncado a 20 000 caracteres; hoy lo he
  compactado resumiendo entradas cerradas y he añadido la nueva apuesta.
  Las abiertas conservan su fecha de revisión.

## Decidido y por qué

- DataForSEO sigue sin saldo. Apliqué la regla de decidir con las señales
  disponibles: la SERP de la consulta MQTT muestra intención de reparación
  clara, resultados de Reddit y Community, y ningún artículo propio que
  cubra el tramo broker. Es la variante con más probabilidad de resolver
  una búsqueda real de soporte, no una nota de versión sin intención.
- Descarté `sonoff zbmini` (ya cubierta), `mejor coordinador zigbee 2026`
  (SERP dominada por medios grandes) y variantes sin señal de la SERP.

## Próximo turno

- Revisar si el parte mecánico muestra la nueva pieza sin avisos y si hay
  primer rastro de impresiones.
- Cerrar la hipótesis de Bluetooth Proxy fallos (vence 20/11) con el
  snapshot real.
- Pedir lote DataForSEO de 5 keywords por si el tope se ha liberado;
  seguir sin publicar piezas de demanda ≤10/mes salvo excepción razonada.

---

## Añadido tras la auditoría anterior

La auditoría del 14/11 mantiene vigentes sus decisiones: umbral ≥100/mes
para piezas nuevas con excepciones razonadas, validar con DataForSEO cuando
haya saldo y no publicar guías de ≤10/mes sin consulta GSC que las
respalde.