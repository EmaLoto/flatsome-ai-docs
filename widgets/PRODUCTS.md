# Products

- **Nombre en demo:** Products
- **Nombre exacto en selector de UX Builder:** Pendiente de verificar
- **Versión probada:** Ninguna instalación local; versión objetivo 3.20.11
- **Categoría:** WooCommerce / catálogo
- **Nivel de evidencia:** Observado en demo (familia); controles pendientes
- **Fuente:** [Demo oficial de Elements](https://demos.flatsome.com/elements/) y [documentación oficial de UX Themes](https://docs.uxthemes.com/)

## Propósito observado
La demo pública identifica Products como familia de elementos de Flatsome. La consulta real del catálogo y los datos de productos dependen de WooCommerce y de los productos disponibles en el sitio. No se han confirmado los controles de consulta, orden ni presentación de esta familia en 3.20.11.

## Separación de responsabilidades
- **Flatsome:** presentación del listado y controles propios del elemento, según evidencia.
- **WooCommerce:** catálogo, productos, precios, stock y datos de tienda.
- **Plugins externos:** filtros, swatches u otras funciones solo si se confirma su dependencia.

## Controles
| Control | Estado |
|---|---|
| Fuente o selección de productos | Pendiente de verificar |
| Categorías, etiquetas o IDs | Pendiente de verificar |
| Cantidad y columnas | Pendiente de verificar |
| Orden y paginación | Pendiente de verificar |
| Precio, rating, etiquetas y botones | Pendiente de verificar |
| Diseño responsive | Pendiente de verificar |

## Requisitos y límites
Requiere comprobar que WooCommerce está activo y que existen productos publicables. No asumir que el elemento funciona como el shortcode estándar de WooCommerce ni que comparte sus argumentos.

## Ejemplo validado
No disponible. No inventar atributos de shortcode.

## Limitaciones y pendientes
- Verificar el panel en una instalación de Flatsome 3.20.11 con WooCommerce instalado.
- Probar productos simples y variables, agotados y sin imagen.
- Registrar las opciones de consulta y el HTML resultante.
