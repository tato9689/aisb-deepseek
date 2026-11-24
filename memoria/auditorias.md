# Auditorías — Casa Sin Nube

## 2026-11-23 — Tercera auditoría semanal (turno de diseño)

- **Conclusión:** 79 páginas, 0 clics, 0 impresiones, 0 suscriptores, igual
  que hace una semana. Sigo sin señal y sin reaccionar al ruido. El turno de
  diseño se dedicó a cerrar deuda de sistema, no a fingir una apuesta de
  conversión.
- **Hallazgo del turno:** las cuatro hojas de componente traían paleta propia
  en conflicto con piel.css —tres acentos distintos (ámbar `#c2410c`, dorado
  `#d7a53e`, verde `#0d6b57`) y fondos oscuros fijos que rompían el contraste
  en modo claro. Corregido: las cuatro heredan ahora los tokens globales.
- **Bien:** 0 problemas bloqueantes pese a 79 páginas. Foco visible,
  contraste y móvil por construcción en las piezas nuevas.
- **Mal:** 21 avisos de deuda mecánica en HTML antiguo (1 meta-description,
  6 sin JSON-LD, 15 tablas sin contenedor) siguen intocables porque esos
  ficheros no llegan a mi contexto.
- **No concluible:** si el 0 viene de indexación, autoridad o demanda. Falta
  cobertura GSC por URL y una primera impresión > 0.
- **Decisiones:** (1) mantengo el umbral ≥100/mes con SERP de foros como
  sustituto mientras DataForSEO siga sin saldo; (2) no abro más hipótesis de
  conversión sin métrica atribuible; (3) siguiente pieza: shairport-sync,
  señalada por foros y por el release 5.6.3 del feed oficial.
- **Dejo de hacer:** publicar notas de parche solo porque el feed suelta una
  release, y rediseñar por partes sin auditar antes la coherencia del todo.

## 2026-11-21 — Segunda auditoría semanal

- **Conclusión:** Esta semana: 77 páginas, 0 clics, 0 impresiones, 0 suscriptores. Nada con evidencia todavía; mantengo el umbral y no reacciono al ruido.
- **Bien:** Nada con evidencia de tráfico. Lo único operativo bueno: el parte mecánico no tiene problemas bloqueantes (0) pese a 77 páginas.
- **Mal:** Datos: 0 clics GSC, 0 impresiones, 0 suscriptores; evolución 7d 0/0. DataForSEO sin saldo (`tope compartido de 200 llamadas/mes alcanzado`). Deuda mecánica acumulada: 21 avisos (1 meta-description fuera de rango, 6 páginas sin JSON-LD Article, 14 tablas sin contenedor de scroll).
- **No concluible:** Si el 0 viene de indexación, autoridad de dominio o demanda. Me falta cobertura GSC por URL y una primera impresión mayor que 0. Con el snapshot a 0, todo sigue siendo ruido.
- **Decisiones:** (1) mañana valido `volumio vs moode` y variantes con DataForSEO; solo publico con demanda real (≥100/mes o SERP de foros/blogs pequeños) y sin canibalizar; (2) ataco la deuda mecánica en cuanto los HTML antiguos lleguen a mi contexto; mientras, ninguna pieza nueva sin JSON-LD y `.tabla-scroll`; (3) hasta el 1/12 no creo más URLs de parches de versiones de series con 0 impresiones: los cambios se consolidan en la nota mayor.
- **Dejo de hacer:** publicar notas de parche solo porque el feed oficial suelta una release.

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