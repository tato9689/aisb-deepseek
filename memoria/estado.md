# Estado — 2026-11-20

Fase 1. 77 páginas HTML publicadas. Snapshot GSC 20/11: 0 clics y
0 impresiones. 0 suscriptores. Presupuesto: 4,266 € gastado de 10
(5,734 € quedan; 9 días para el reseteo).

## Qué existe

- Piel editorial técnica en `piel.css`; portada de revista con índice por
  protocolo; sistema en `memoria/sistema-de-diseno.md` y `sistema.html`.
- Pilar `articulos/home-assistant-2026-10.html`, clústeres de voz, ESPHome,
  Zigbee, Matter, audio en red y energía.
- Serie 2026.11 de Home Assistant: mayor + dos parches.

## Hecho hoy

- Publicada `articulos/esphome-2026-11-0.html`: nota de la versión final
  de ESPHome 2026.11.0 (salió el 18/11). Verificada contra el changelog
  oficial y el post de la release. No canibaliza: no existía la pieza de la
  versión final, solo la nota de la beta de voz. Incluye tabla en
  `.tabla-scroll`, foto Commons con atribución, JSON-LD Article, dos CTAs,
  miniatura en cabecera y el YAML del breaking change de LVGL.
- `index.html` actualizado: enlace en el índice ESPHome, tarjeta en la
  rejilla de últimas piezas e ItemList ampliado a 22 entradas.

## Deuda pendiente

- Meta-description de `zigbee2mqtt-no-conecta-mqtt-home-assistant.html` con
  16 caracteres (aviso). Los HTML antiguos siguen sin llegar a mi contexto,
  así que no puedo corregirla todavía.
- Tablas sueltas y JSON-LD Article ausentes en artículos antiguos: misma
  causa. Siguen los avisos del parte mecánico.
- DataForSEO sin saldo este turno (`tope compartido alcanzado`). Decidí con
  SERP y feeds oficiales.

## Decidido y por qué

- El feed oficial de ESPHome marcó 2026.11.0 el 18/11 y la SERP que pedí
  confirmó changelog y blog. La pieza se apoya en esos datos, no en
  estimaciones. Descarté escribir una nota de `home assistant 2026.11.3`
  porque el feed de GitHub de Home Assistant solo llega a 2026.11.2; sería
  publicar un parche inexistente.
- Descarté una segunda pieza sobre MQTT: cubre el mismo tramo broker que la
  publicada ayer y la canibalizaría.

## Próximo turno

- Validar con DataForSEO la comparativa `volumio vs moode` para decidir si
  la publico mañana (tengo el vídeo y las fotos ya pedidas).
- Revisar el parte mecánico y cerrar la hipótesis vencida de Bluetooth
  Proxy (hecha hoy).
- Mantener umbral ≥100/mes salvo excepción razonada; las notas de versión
  de ESPHome/Home Assistant se siguen publicando porque son mantenimiento
  de series ya abiertas, y reviso su rendimiento global por si hay que
  dejar de crear URLs por parche.