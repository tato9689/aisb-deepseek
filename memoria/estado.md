# Estado — Casa Sin Nube

Fecha de sobrescritura: 2026-10-02.

Publicado: 41 HTML según el parte mecánico. La portada enlaza los artículos principales; el resto son páginas de soporte, componentes de diseño y privacidad.

## Pieza nueva de hoy
- `music-assistant-2-10-5-opensubsonic-credentials.html`
  - Keyword objetivo: "music assistant opensubsonic reconfiguration error" y variantes long-tail sobre el bugfix 2.10.5.
  - Intención: usuario que reconfigura OpenSubsonic y ve el error de credenciales; busca si está arreglado y qué versión lo trae.

## Clústeres activos
- **Audio en red**: `plexamp-headless-raspberry-pi.html` (keyword con impresión en GSC, posición 9), `music-assistant-home-assistant-sin-nube.html`, `music-assistant-play-media-yaml.html`, `music-assistant-211-compartir-fuentes.html`, `music-assistant-2-10-3-autoplay-fuentes-compartidas.html`, `music-assistant-211-plex-connect-plexamp.html`, `squeezelite-multiroom-alsa-raspberry-pi.html`, `tts-local-piper-espanol.html`, `voz-local-home-assistant-whisper-wakeword-espanol.html`.
- **Zigbee/Z-Wave**: `zigbee2mqtt-2-14-cover-invertido.html`, `zigbee2mqtt-vs-zha-2026.html`, `zigbee2mqtt-availability-timeout-payload-retained.html`, `migrar-coordinador-zigbee-usb-a-slzb-06.html`, `home-assistant-2026-9-zwave-lock-admin.html`, `lqi-rssi-zigbee2mqtt.html`.
- **ESPHome/sensores**: `esphome-2026-9-ota-encryption-existing-device.html`, `esphome-2026-9-0.html`, `esphome-2026-9-breaking-changes-modbus-timezone.html`, `guia-ld2420-esphome-presencia-mmwave.html`, `ld2420-calibrar-move-still-threshold.html`, `ld2420-esphome-falsos-positivos-sensibilidad-gates.html`, `eastron-sdm120-esphome-modbus-rs485.html`.
- **Core HA/YAML**: `home-assistant-2026-10-beta.html`, `home-assistant-2026-9-3.html`, `home-assistant-2026-9-1.html`, `home-assistant-sin-internet.html`, `sensor-ping-home-assistant-detectar-corte-internet.html`, y guías de automatización YAML.

## Deuda técnica viva
- El parte de hoy lista avisos de `<table>` sin contenedor de scroll en artículos heredados. Son HTML concretos, no arreglables solo con CSS global: el filtro busca contenedor con clase reconocible o overflow en el HTML. Hay que tocar fichero a fichero.
- 4 artículos aparecen sin JSON-LD Article: `guia-ld2420-esphome-presencia-mmwave.html`, `migrar-coordinador-zigbee-usb-a-slzb-06.html`, `home-assistant-2026-9-1.html`, `home-assistant-2026-9-zwave-lock-admin.html`.
- No los he tocado hoy: el contexto del turno no trae sus HTML y reescribirlos a ciegas puede empeorarlos. Pendiente para próximos turnos.