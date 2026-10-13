# Fuentes oficiales y límites de evidencia

Este documento separa las fuentes públicas que sirven para documentar Flatsome Classic / UX Builder de la evidencia que requiere inspección de una instalación real.

## Alcance de versión

- Versión objetivo del proyecto: **Flatsome 3.20.11**.
- La API pública de UX Themes muestra actualmente la versión **v3.20.11**, release **v292**: https://api.uxthemes.com/
- Esta comprobación confirma la versión que informa ese endpoint en la fecha de consulta; no demuestra que cada opción descrita en una demo coincida exactamente con una instalación local.

## Fuentes oficiales útiles

| Fuente | Uso recomendado | Qué no demuestra por sí sola |
|---|---|---|
| [UX Themes Docs](https://docs.uxthemes.com/) | Guías oficiales de Flatsome Classic, UX Builder, shortcodes, WooCommerce y desarrollo. | Que una guía cubra todas las opciones de un widget en 3.20.11. |
| [Colección Flatsome de UX Themes Docs](https://docs.uxthemes.com/collection/1-flatsome) | Índice de artículos y categorías oficiales. | Que todos los artículos estén actualizados para cada versión. |
| [Demo oficial: Elements](https://demos.flatsome.com/elements/) | Identificar nombres y familias de elementos expuestos en la demo pública. | Opciones completas del panel, valores predeterminados, sintaxis exacta o disponibilidad idéntica en la versión objetivo. |
| [Demo oficial: Elements Overview](https://demos.flatsome.com/features/elements-overview/) | Contrastar la lista pública de elementos. | Inventario exhaustivo del editor. |
| [Demo oficial: Sections](https://demos.flatsome.com/elements/sections/) | Observar ejemplos visuales de secciones y algunos patrones de composición. | Todos los controles disponibles para Section. |
| [Demo oficial: Sliders](https://demos.flatsome.com/elements/sliders/) | Observar estilos y ejemplos de sliders. | Que cada estilo visible sea una opción del mismo control o tenga el mismo nombre en el panel. |
| [Demo oficial: Product Categories](https://demos.flatsome.com/elements/product-categories/) | Observar estilos visuales de categorías de producto. | Todas las opciones o filtros disponibles del elemento. |
| [Demo oficial: documentación de características](https://demos.flatsome.com/features/documentation/) | Localizar la documentación y tutoriales oficiales. | Referencia técnica exhaustiva. |

## Nota importante sobre Classic y el nuevo Builder

La documentación actual de Flatsome puede incluir material del sistema nuevo basado en bloques. Este repositorio documenta **Flatsome Classic con UX Builder clásico**, versión objetivo 3.20.11. No se deben trasladar opciones, nombres de bloques ni instrucciones de migración al inventario Classic sin verificar su equivalencia.

La página oficial [From Flatsome Classic](https://flatsome.com/docs/from-flatsome-classic) describe la migración al sistema nuevo y menciona familias de elementos compatibles con la migración. Es útil como fuente complementaria para descubrir nombres, pero **no** debe tomarse como referencia única de sintaxis ni como prueba de los controles del UX Builder clásico.

## Política de citación

Cada afirmación técnica en una ficha de widget debe enlazar la fuente que realmente la respalda. Usar las etiquetas definidas en `validation/EVIDENCE-LEVELS.md`. Si la fuente solo muestra el resultado visual, documentar únicamente el resultado observado y marcar los controles como pendientes.
