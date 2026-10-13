# Inventario de widgets

**Versión objetivo:** Flatsome 3.20.11 · UX Builder clásico  
**Estado:** inventario inicial no exhaustivo. Los nombres de abajo son categorías de investigación, no una afirmación de que todos sean nombres exactos de widgets.

## Registro central

| Nombre en demo / familia | Categoría de investigación | Evidencia | Ficha | Notas |
|---|---|---|---|---|
| Sections | Estructura/layout | Observado en demo | [Section](../widgets/SECTION.md) | Controles y nombre exacto en selector pendientes. |
| Rows / Columns | Estructura/layout | Observado en demo | [Rows / Columns](../widgets/ROW-COLUMNS.md) | Confirmar jerarquía y nombres en Classic. |
| Banners | Contenido visual | Observado en demo | [Banner](../widgets/BANNER.md) | Ejemplos visuales; opciones del panel pendientes. |
| Images | Medios | Observado en demo | [Image](../widgets/IMAGE.md) | No asumir que cada efecto es un control del mismo elemento. |
| Buttons | Acción / enlace | Observado en demo | [Buttons](../widgets/BUTTON.md) | Controles exactos pendientes. |
| Icon Box | Contenido / presentación | Observado en demo | [Icon Box](../widgets/ICON-BOX.md) | Nombre de familia; panel pendiente. |
| Image Box | Contenido visual | Observado en demo | [Image Box](../widgets/IMAGE-BOX.md) | Variantes mostradas en demo; panel pendiente. |
| Accordion | Contenido interactivo | Observado en demo | [Accordion](../widgets/ACCORDION.md) | Ejemplos visibles; controles pendientes. |
| Tabs | Contenido interactivo | Observado en demo | [Tabs](../widgets/TABS.md) | Nombre de familia; controles pendientes. |
| Products | WooCommerce / catálogo | Observado en demo | [Products](../widgets/PRODUCTS.md) | Controles y consultas pendientes. |
| Product Categories | WooCommerce / catálogo | Observado en demo | [Product Categories](../widgets/PRODUCT-CATEGORIES.md) | Estilos visibles en demo; panel pendiente. |
| Galleries | Medios | Observado en demo | [Galleries](../widgets/GALLERIES.md) | Variantes visuales; controles pendientes. |
| Video | Medios | Observado en demo / parcial | [Video](../widgets/VIDEO.md) | No confundir con vídeo abierto desde Image/lightbox. |
| Blog Posts | Contenido editorial | Observado en demo | [Blog Posts](../widgets/BLOG-POSTS.md) | Consulta y metadatos pendientes. |
| Testimonials | Contenido / slider | Observado en demo | [Testimonials](../widgets/TESTIMONIALS.md) | Fuente de contenido y controles pendientes. |
| Search Box | Búsqueda | Observado en demo | [Search Box](../widgets/SEARCH-BOX.md) | Demo muestra estilos Default y Flat; panel pendiente. |
| Countdown | Interactivo | Observado en demo | [Countdown](../widgets/COUNTDOWN.md) | Fecha, zona horaria y fin pendientes. |
| Map | Integración / contenido | Observado en demo | [Map](../widgets/MAP.md) | Proveedor y requisitos API pendientes. |
| Forms | Formularios / posible integración | Observado en demo | [Forms](../widgets/FORMS.md) | Confirmar si es nativo o depende de integración. |

## Cómo añadir una entrada
1. Abrir UX Builder en una instalación confirmada de 3.20.11.
2. Registrar el nombre exacto del elemento tal como aparece en el selector.
3. Añadir una ficha desde [la plantilla](../widgets/WIDGET-TEMPLATE.md).
4. Capturar todas las pestañas del panel y las opciones desplegables relevantes.
5. Probar comportamiento responsive y dependencias.
6. Asignar un nivel de evidencia según [niveles de evidencia](../validation/EVIDENCE-LEVELS.md).
7. Añadir aquí un enlace a la ficha.

## No asumir
- Que dos elementos con nombres parecidos son el mismo widget.
- Que un elemento visible en el frontend se puede insertar directamente desde UX Builder.
- Que los nombres, controles o valores por defecto de otra versión se mantienen en 3.20.11.
- Que un diseño construido en el editor tiene un formato de serialización pública estable.
