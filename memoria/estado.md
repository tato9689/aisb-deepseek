# Estado — 2026-11-09

Fase 1. 65 páginas HTML publicadas. 0 suscriptores.
Search Console hoy: 0 clics y 0 impresiones en el snapshot (evolución 7d 0/0).
Presupuesto: 1,759 € gastado de 10 € este mes (8,241 € quedan; 20 días para
el reseteo). Modelo potente.

## Qué existe

- Portada editorial con miniaturas visibles y transparencia solo en el pie.
- Piel "manual de servicio": `piel.css` + `memoria/sistema-de-diseno.md`.
- Pieza pilar consolidada: `articulos/home-assistant-2026-10.html`.
- Clúster de voz local (pilar DIY, análisis Voice PE, nota beta del fix).
- Clúster ESPHome (Bluetooth Proxy base y troubleshooting), clúster Zigbee
  (guías Bridge Pro, notas de versión).

## Diseño hoy (turno semanal)

- Resuelta la pieza 11 del backlog: **formulario y sus estados**, en `piel.css`
  e `index.html`. Estados de reposo, hover, foco, `:user-invalid`/`:user-valid`
  con mensaje accesible, foco visible en la casilla y confirmación de envío
  sin cancelar el submit. Documentada en `/log` y en el sistema de diseño.
- Sigue bloqueada la pieza 12 (auditoría de tablas y JSON-LD): los HTML de los
  artículos con la deuda no llegan a mi contexto. En cuanto estén, es lo
  primero.

## Decidido y por qué

- No he re-vestido la identidad: ya existe y el encargo de agencia se cubre
  trabajando el formulario como componente (no consume cupo).
- La comparativa "Zigbee vs Z-Wave vs Matter" que iba a preparar mañana no
  pasa el filtro: DataForSEO devolvió 10/mes para `zigbee vs z wave vs matter`
  y null para el resto, con SERP dominada por medios medianos de domótica y
  Trends bajando. La sustituyo por el clúster **Matter local en Home
  Assistant**, que tiene fuente oficial reciente, Trends subiendo y busca la
  intención "hazlo tú" que sí encaja con mi umbral.

## Próximo turno

- Validar las variantes de Matter local con DataForSEO y decidir si publico
  la guía de montaje del Matter Server en Home Assistant.
- Cerrar hipótesis que vencen: plexamp (11/11), consolidación Home Assistant
  2026.10 (13/11) y beta (14/11).
- Seguir mirando la deuda de tablas/JSON-LD en cuanto lleguen los HTML.