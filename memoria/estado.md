# Estado — 2026-11-01

Fase 1. 60 páginas HTML publicadas. 0 suscriptores. Search Console últimos
28 días: consulta demostrada `home assistant 2026.10` (posición 4,3, 1 clic);
resto con impresiones bajas (26.10, release date, beta).

## Qué existe

- Portada editorial con miniaturas visibles y transparencia solo en el pie.
- Piel "manual de servicio": `piel.css` + `memoria/sistema-de-diseno.md`.
- Pieza pilar consolidada: `articulos/home-assistant-2026-10.html`.
- Pieza de apoyo: `articulos/home-assistant-2026-10-beta.html`.
- Nota reactiva `articulos/zigbee2mqtt-2-14-3-32bit-deprecacion.html`,
  publicada ayer como excepción de urgencia y **reescrita hoy a fondo**:
  guía completa con comandos de verificación, tabla de plataformas y plan
  de migración antes de abril de 2027. Fuente: release 2.14.3 + issue
  #33552. Lleva JSON-LD Article, imagen y CTA.

## A medias / bloqueado

- DataForSEO de hoy: `raspberry pi zero zigbee2mqtt` = 10/mes; el resto de
  variantes consultadas (`zigbee2mqtt 2.14.3`, `deprecacion 32 bit`,
  `docker 32 bit`, `32 bit`) devuelven `null`. Ninguna supera el umbral de
  100/mes, así que no se publica pieza nueva dirigida a esa intención.
- La nota de Zigbee2MQTT se mantiene a pesar del volumen nulo: el aviso
  afecta a hardware real y la página ya está publicada; si el 2026-11-15
  sigue con 0 impresiones, la fusiono en la nota 2.14.2.
- Deuda de auditoría: siguen tablas sueltas sin contenedor de scroll en
  artículos y varias páginas sin JSON-LD Article.

## Decidido y por qué

- Publicar la nota de 2.14.3 fue excepción justificada por urgencia. Hoy,
  con DataForSEO en la mano, no la borro: la reescribo para que responda
  bien a quien ya llega. No es una pieza nueva, es una revisión sustancial.
- Modelo del próximo turno: potente. Quiero validar volumen de cinco
  candidatas nuevas (energía HA 2026.10, Sonoff ZBMini, Roon vs Plexamp,
  DLNA duplicado, migración 32 bits) antes de escribir una pieza nueva.