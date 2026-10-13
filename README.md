# Flatsome AI Docs

Documentación técnica en español para construir páginas con **Flatsome Classic UX Builder 3.20.11** y WooCommerce, orientada a asistentes de IA y desarrolladores.

> **Estado del proyecto:** base documental inicial. No debe interpretarse como inventario exhaustivo ni como confirmación de todos los controles disponibles en la versión indicada. Los detalles de cada widget deben contrastarse con una instalación real de Flatsome 3.20.11.

## Objetivos

- Identificar widgets nativos y su propósito.
- Documentar controles, opciones, estructura, responsive y dependencias con evidencia.
- Crear patrones reutilizables para páginas institucionales, landing pages y tiendas WooCommerce.
- Evitar que una IA invente widgets, propiedades, valores por defecto o shortcodes.
- Separar información verificada, documentación oficial y observaciones pendientes de prueba.

## Alcance

- **Builder:** UX Builder clásico de Flatsome; no Gutenberg ni un sistema nuevo de bloques.
- **Versión objetivo:** 3.20.11.
- **Idioma principal:** español.
- **Comercio:** WooCommerce, con diferencias de versión documentadas cuando corresponda.
- **Formato:** Markdown legible por humanos y modelos de lenguaje.

## Cómo usar esta documentación

1. Leer [AI-INSTRUCTIONS.md](AI-INSTRUCTIONS.md) antes de generar layouts.
2. Consultar [VERSION-SCOPE.md](VERSION-SCOPE.md) para entender límites y convenciones.
3. Revisar [MASTER-INDEX.md](MASTER-INDEX.md) para navegar por los temas.
4. Verificar las fichas de widgets y patrones antes de reutilizarlos.
5. Si falta evidencia, marcar el dato como **Pendiente de verificación** en lugar de adivinar.

## Estado de verificación

Cada afirmación técnica debe etiquetarse según [validation/EVIDENCE-LEVELS.md](validation/EVIDENCE-LEVELS.md):

- **Verificado en 3.20.11:** comprobado en una instalación de esa versión.
- **Fuente oficial:** descrito por la documentación oficial, sin prueba local registrada.
- **Observado en demo:** visible en una demo pública; no garantiza que todos los controles coincidan con la versión objetivo.
- **Pendiente:** no hay evidencia suficiente.
- **No compatible/no confirmado:** no se debe usar como instrucción de implementación.

## Fuentes de referencia

- [Demo oficial: Elements](https://demos.flatsome.com/elements/)
- [Demo oficial: Products](https://demos.flatsome.com/elements/products/)
- [Demo oficial: Product Categories](https://demos.flatsome.com/elements/product-categories/)
- [Demo oficial: WooCommerce](https://demos.flatsome.com/features/woocommerce/)
- [Documentación de UX Themes](https://docs.uxthemes.com/)
- [Colección Flatsome](https://docs.uxthemes.com/collection/1-flatsome)
- [WooCommerce Documentation](https://woocommerce.com/documentation/)

Las demos y documentación web pueden cambiar con el tiempo. Para afirmaciones específicas de la versión 3.20.11, registrar evidencia y fecha en las fichas correspondientes.

## Contribuciones

Al documentar un widget, incluir nombre exacto de la interfaz, propósito, controles confirmados, restricciones, comportamiento responsive, ejemplo y nivel de evidencia. No completar campos desconocidos mediante suposiciones.
