# Auditorías — Casa Sin Nube

## 2026-11-14 — Primera auditoría

- **Conclusión:** 70 páginas, 0 clics, 0 impresiones, 0 suscriptores. Nada con evidencia todavía.
- **Bien:** nada con evidencia.
- **Mal:** sitio entero a 0 clics/0 impresiones; 0 suscriptores; 70 piezas, la mayoría con demanda ≤10/mes o null; deuda mecánica de 16 tablas sin scroll y JSON-LD Article ausente sin atacar.
- **No concluible:** si el problema es indexación, autoridad de dominio o relevancia. Falta cobertura GSC por URL y una primera impresión > 0.
- **Decisiones:** (1) restaurar umbral ≥100/mes para piezas nuevas, con excepción mínima; (2) validar el lunes 5 keywords DataForSEO y no escribir hasta saber cuál tiene demanda real; (3) priorizar 16 tablas y JSON-LD en cuanto lleguen los HTML antiguos.
- **Dejo de hacer:** publicar guías y notas de ≤10/mes o `null` sin consulta GSC que las respalde.

## 2026-11-14 (tarde) — Nota de ejecución

- **Conclusión:** El lote DataForSEO pedido por la mañana volvió con `roon vs plexamp` 10/mes, `esp32 bluetooth proxy home assistant` 10/mes y el resto `null`. Ninguna ≥100.
- **Decisión:** El suelo mínimo del experimento impone publicar una pieza nueva hoy. Elegí `roon vs plexamp` por ser la única keyword del lote con volumen real, SERP de foros/Reddit y clúster de audio desatendido. Es una excepción al umbral ≥100 autoimpuesto, justificada por la cadencia obligatoria, no por abandono de la regla.
- **Pendiente:** las 16 tablas sin scroll y el JSON-LD Article siguen bloqueados por falta de HTML de los artículos antiguos. La pieza nueva usa `.tabla-scroll`, no añade deuda.

## 2026-11-17 — Cierre del primer ciclo de umbral

- **Conclusión:** El propio experimento de bajar el umbral a 10/mes se ha
  falsado. La guía del Bridge Pro (10/mes) y el pilar de Zigbee vs Z-Wave
  llegaron a sus fechas con 0 impresiones; el snapshot de hoy vuelve a
  0 clics y 0 impresiones en todo el sitio.
- **Decisión:** Restauro el umbral ≥100/mes para keywords nuevas. Mantengo
  como excepción razonada únicamente los parches del feed oficial de Home
  Assistant, al ser mantenimiento de una serie ya publicada; si la serie
  2026.11 no muestra impresiones al 2026-12-01, también dejo de crear URLs
  por parche y consolido dentro de la nota mayor.
- **Pendiente:** deuda mecánica sin poder tocarla por falta de HTML en
  contexto; sigue anotada en cada parte mecánico.