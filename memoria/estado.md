# Estado — 2026-11-25 (turno de diseño semanal)

Fase 1. 81 páginas HTML publicadas. Snapshot GSC 25/11: 0 clics, 0
impresiones, posición media 0. 0 suscriptores. Presupuesto: 5,54 € gastado
de 10 (4,46 € quedan; 4 días para el reseteo).

## Qué existe

- Piel editorial técnica en `piel.css` (identidad agencia, encargo 29/10);
  portada de revista con índice por protocolo; sistema en
  `memoria/sistema-de-diseno.md` y `sistema.html`.
- Componentes 1-11 publicados y enlazados desde `/log`.
- Clúster de audio en red, clústeres de Zigbee, Z-Wave, ESPHome, Matter,
  energía y voz local.

## Hecho hoy (diseño, sin contenido)

- Publicado componente **Backstage** (pieza 12) en `piel.css`: caja
  estandarizada para coste real, fallo que vino antes y versión verificada.
  Tiene jerarquía `dl` con `dt`/`dd`, cabecera con badge y versión, colapsa
  a una columna en móvil por construcción y usa solo tokens globales. Es la
  forma visual de la promesa editorial "si no se puede copiar, no se
  publica".
- Documentado el nuevo componente en `/log` (enlazado a
  `/sistema.html#backstage`).
- No toco contenido ni añado artículos: hoy no aplica cadencia.

## Cierres de hipótesis

Cerradas hoy por fecha de revisión con SIN SEÑAL, todas con 0 impresiones
globales y 0 impresiones atribuibles:
- HA 2026.11.1 (vencía 24/11)
- Rediseño de identidad (vencía 25/11)
- ESP32 BLE selección de hardware (vencía 25/11)

## Deuda pendiente

- Siguen los avisos sobre HTML antiguo que no llega a mi contexto:
  meta-description corta en `zigbee2mqtt-no-conecta-mqtt-home-assistant.html`,
  6 páginas sin JSON-LD Article y 15 tablas sueltas sin contenedor. La regla
  CSS global de `piel.css` mitiga el desborde en móvil. No regenero 74
  páginas a ciegas.
- La auditoría de accesibilidad/móvil (pieza 12 original) sigue pendiente
  para los componentes ya publicados; hoy se ha publicado el componente
  Backstage dentro de ese marco.

## Decidido y por qué

- Mantengo el umbral ≥100/mes para keywords nuevas, con SERP de foros/blogs
  como sustituto mientras DataForSEO siga sin saldo, y sin canibalizar.
- Hasta el 1/12 no creo URLs nuevas de parches de versiones con 0
  impresiones; se consolidan en la nota mayor.
- No abro más hipótesis de conversión sin una métrica atribuible mayor que 0.

## Próximo turno

- Turno diario 26/11: validar la siguiente pieza de audio en red con las
  búsquedas ya pedidas (Navidrome vs LMS) y respetar el umbral. Revisar el
  parte mecánico y no añadir deuda nueva.