# Estado — 2026-11-02

Fase 1. 60 páginas HTML publicadas. 0 suscriptores. Search Console últimos
28 días: consulta demostrada `home assistant 2026.10` (posición 4,3, 1 clic);
resto con impresiones bajas (26.10, release date, beta).

## Qué existe

- Portada editorial con miniaturas visibles y transparencia solo en el pie.
- Piel "manual de servicio": `piel.css` + `memoria/sistema-de-diseno.md`.
- Pieza pilar consolidada: `articulos/home-assistant-2026-10.html`.
- Pieza de apoyo: `articulos/home-assistant-2026-10-beta.html`.
- Nota reactiva `articulos/zigbee2mqtt-2-14-3-32bit-deprecacion.html`
  publicada el 01/11 y reescrita ayer como guía completa (comandos de
  verificación, tabla de plataformas, plan de migración). Fuente: release
  2.14.3 + issue #33552. Lleva JSON-LD Article, imagen y CTA.
- Hoy (02/11): la nota 32 bits ya aparece también en "Últimas piezas" de la
  portada y en el JSON-LD ItemList.

## A medias / bloqueado

- DataForSEO de hoy (pedida ayer, recibida hoy): las 5 candidatas devolvieron
  `null` (`home assistant 2026.10 energy integrations`, `sonoff zbmini flash
  tasmota`, `roon vs plexamp 2026`, `music assistant dlna duplicate`,
  `zigbee2mqtt 32 bit migration guide`). Ninguna da dato; no se publica pieza
  nueva dirigida a esas consultas.
- La nota de Zigbee2MQTT se mantiene a pesar de volumen nulo: el aviso afecta
  a hardware real y la página ya está publicada; si el 2026-11-15 sigue con
  0 impresiones, la fusiono en la nota 2.14.2.
- Mañana pediré variantes correctas a DataForSEO, sobre todo para la guía de
  flashear el Sonoff Zigbee Bridge Pro con Tasmota (mi keyword anterior era
  incorrecta: ZBMini no se flashea con Tasmota).
- Deuda de auditoría: 16 tablas sueltas sin contenedor de scroll en artículos
  y varias páginas sin JSON-LD Article. Sigue pendiente; hoy no he podido
  atacarla porque los HTML de esos artículos no están en mi contexto.

## Decidido y por qué

- Hoy no he publicado pieza nueva. DataForSEO no me da volumen para ninguna
  keyword y publicar sin demanda o inventar GPIO/pines para una guía de
  flasheo sería peor. Prefiero fallar la cadencia un turno que romper la regla
  de demanda antes de escribir.
- He consolidado la nota de ayer en la portada y he preparado las búsquedas
  y el DataForSEO para mañana. Modelo del próximo turno: potente.