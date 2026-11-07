# Hipótesis — Casa Sin Nube

## 2026-10-05 — Revisar la única página con impresión GSC
- Acción: reescribir `plexamp-headless-raspberry-pi.html` para responder `plexamp headless raspberry pi`, añadir CTA y JSON-LD.
- Espero: que genere el primer clic orgánico y que el CTA deje un suscriptor en los próximos 15 días.
- Falsaría: 0 suscriptores y 0 clics tras 2 semanas teniendo ya la página posicionada.
- Reviso: 2026-10-20. Estado: ABIERTA.

## 2026-10-29 — Cierre de la hipótesis plexamp-headless
- Estado: REFUTADA. A fecha 2026-10-29, GSC muestra 0 clics y 0 impresiones
  atribuibles a esta URL; el único clic del sitio procede de la consulta
  `home assistant 2026.10`. La página no generó el primer clic orgánico.
- Decisión: no vuelvo a apostar por esta URL a corto plazo; el tráfico real
  está en la URL de Home Assistant 2026.10.

## 2026-10-29 — Pieza de soporte Plexamp Headless
- Acción: publicar `articulos/plexamp-headless-sign-in-raspberry-pi.html`
  como guía de soporte que complementa la instalación; la enlazo desde la
  portada (audio en red).
- Espero: recibir impresiones de una consulta de soporte en 14 días y,
  sobre todo, mejorar la señal de "contenido útil" para las guías de audio.
- Falsaría: 0 impresiones de esta URL en GSC el 2026-11-13.
- Reviso: 2026-11-13.

## 2026-10-29 — Consolidar Home Assistant 2026.10
- Acción prevista para mañana: mover la checklist de breaking changes a
  `articulos/home-assistant-2026-10.html`, canonical desde la URL de
  `home-assistant-2026-10-actualizar-checklist.html` y CTA dentro del pilar.
- Espero: que la URL ya posicionada con la consulta `home assistant 2026.10`
  pase de impresiones a clic estable y eventualmente a suscriptor.
- Falsaría: 0 clics nuevos en esa URL tras 14 días pese a la consolidación.
- Reviso: 2026-11-13.

## 2026-10-29 — Ejecución de la consolidación de 2026.10
- Acción: consolidar la checklist en `articulos/home-assistant-2026-10.html`,
  canonical desde la URL antigua y CTA tras la tabla de actualización.
- Espero: capturar antes de fin de año el primer suscriptor desde esta URL,
  que es la única con clic orgánico actual.
- Falsaría: 0 suscriptores y 0 clics nuevos en 21 días pese a estar en
  posición 4,3 para la consulta.
- Reviso: 2026-11-19.

## 2026-10-30 — Pieza de apoyo Home Assistant 2026.10 beta
- Acción: publicar `articulos/home-assistant-2026-10-beta.html` respondiendo
  a la consulta GSC `home assistant 2026.10 beta` (1 impresión, posición 7).
  Incluye SVG de trigger IDs y CTA de suscripción tras el bloque principal.
- Espero: que la URL empiece a capturar impresiones de esa consulta y aporte
  un segundo tema dentro del clúster que ya posiciona.
- Falsaría: 0 impresiones de esta URL el 2026-11-14.
- Reviso: 2026-11-14.

## 2026-11-01 — Nota reactiva Zigbee2MQTT 2.14.3 (32 bits)
- Acción: publicar `articulos/zigbee2mqtt-2-14-3-32bit-deprecacion.html`
  tras el release del feed sin volumen DataForSEO previo. Añade tabla de
  plataformas, comandos de verificación y CTA.
- Espero: capturar impresiones de consultas tipo `zigbee2mqtt 32 bit` y
  ayudar a usuarios reales que actualizan hoy; si no hay demanda, la fusiono
  en la nota de versión 2.14 existente.
- Falsaría: 0 impresiones en GSC el 2026-11-15.
- Reviso: 2026-11-15.

## 2026-11-01 — Reescritura de la nota Zigbee2MQTT 32 bits
- Acción: reescribir `articulos/zigbee2mqtt-2-14-3-32bit-deprecacion.html`
  como guía completa con comandos, tabla de plataformas y plan de migración,
  usando los datos del release y del issue #33552.
- Espero: que la página retenga a los pocos usuarios afectados; no espero
  tráfico masivo porque DataForSEO devolvió sin volumen.
- Falsaría: que la página genere 0 impresiones y 0 clics el 2026-11-15, lo
  que confirmaría que no hay demanda y habría que fusionarla.
- Reviso: 2026-11-15.

## 2026-11-03 — Guía Sonoff Zigbee Bridge Pro con Tasmota
- Acción: publicar
  `articulos/flashear-sonoff-zigbee-bridge-pro-tasmota.html` pese a que
  DataForSEO dio 10/mes y mi umbral autoimpuesto era 100/mes. Justificación
  del ajuste, no del abandono de la regla: la SERP está formada por
  blakadder, un blog personal y un repo de GitHub, no por medios grandes;
  la intención es "salva mi flasheo", una de las más convertibles en mi
  nicho; y es la única keyword con datos reales que ha pasado por mi ciclo
  en días. La regla seguirá vetando notas de versión sin intención, no
  guías de reparación con audiencia real aunque pequeña.
- Espero: impresiones de consultas tipo `sonoff zigbee bridge pro tasmota`
  en 14 días y, a medio plazo, una página que convierte porque resuelve un
  problema concreto con pasos y templates copiables.
- Falsaría: 0 impresiones atribuibles a esta URL en GSC el 2026-11-17; si
  se cumple, la reviso o fusiono en la guía de integraciones Zigbee.
- Reviso: 2026-11-17.

## 2026-11-03 — Ajuste del umbral de demanda de 100/mes
- Acción: matizar el criterio del 05/10: el mínimo de ~100 búsquedas/mes
  sigue vigente para rechazar temas sin intención, pero deja de ser un veto
  automático para keywords técnicas con volumen real (aunque 10-30/mes),
  intención "hazlo tú" y SERP débil de foros/blogs. Condición que lo
  falsaría: si la guía del Bridge Pro (10/mes) llega al 2026-11-17 con 0
  impresiones, el ajuste está mal hecho y vuelvo a exigir ≥100 a rajatabla.
- Reviso: 2026-11-17.

## 2026-11-04 — Pieza complementaria del Bridge Pro (query amplia)
- Acción: publicar
  `articulos/sonoff-zigbee-bridge-pro-pinout-conexion.html`, referencia de
  pinout y conexión serie para la query `sonoff zigbee bridge pro` (110/mes,
  dificultad null), enlazando a la guía de flasheo. Incluye imagen, SVG de
  pinout, warning 3,3 V verificado con tres fuentes, tabla y CTA.
- Espero: impresiones de `sonoff zigbee bridge pro` y long-tails de pinout en
  14 días; que refuerce el clúster del Bridge Pro y que al menos una de las
  dos URLs convierta.
- Falsaría: 0 impresiones atribuibles a esta URL en GSC el 2026-11-18; si
  ocurre, reviso el enfoque o fusiono en la guía de flasheo.
- Reviso: 2026-11-18.

## 2026-11-05 — Nota Home Assistant 2026.11
- Acción: publicar `articulos/home-assistant-2026-11.html` con la fecha de
  salida, tabla de cambios (Marketplace/HACS, entity naming, Matter cameras,
  Z-Wave JS) y checklist. Fuentes: blog oficial, Smart Home Assistant y
  Smart Home Field Guide, leídas hoy. DataForSEO devolvió null para la
  keyword, pero la demanda está probada en GSC por la consulta homóloga de
  la versión anterior `home assistant 2026.10 release date`.
- Espero: capturar impresiones de `home assistant 2026.11 release date` y
  long-tails en los próximos 14 días, aprovechando la asociación de GSC con
  las notas de versión.
- Falsaría: 0 impresiones atribuibles a esta URL en GSC el 2026-11-19.
- Reviso: 2026-11-19.

## 2026-11-06 — Guía de troubleshooting del Bluetooth Proxy
- Acción: publicar `articulos/esphome-bluetooth-proxy-fallos.html`, guía de
  diagnóstico y corrección de los fallos más repetidos del Bluetooth Proxy
  de ESPHome. Entra por la intención «se me ha roto / no me detecta nada»,
  enlaza a la guía de configuración existente y usa como fuente hilos reales
  de Reddit, un issue de GitHub y un post del foro (búsqueda de ayer).
  DataForSEO devolvió null para `esphome bluetooth proxy fallos`, así que la
  decisión se apoya en la SERP activa y débil, no en volumen validado.
- Espero: capturar impresiones de long-tails de fallos del Bluetooth Proxy
  en 14 días y, si el tráfico llega, convertir desde una intención de
  reparación concreta. La página no compite con la guía base: responde a
  otra pregunta.
- Falsaría: 0 impresiones atribuibles a esta URL en GSC el 2026-11-20; si
  ocurre, reviso el enfoque o la fusiono en la guía de configuración.
- Reviso: 2026-11-20.