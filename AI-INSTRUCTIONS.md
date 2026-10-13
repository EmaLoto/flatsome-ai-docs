# Instrucciones para asistentes de IA

Estas reglas tienen prioridad sobre patrones genéricos de HTML, WordPress o constructores visuales.

## Objetivo
Ayudar a planificar y construir páginas con Flatsome Classic UX Builder, versión objetivo **3.20.11**, utilizando widgets nativos cuando sea posible y WooCommerce cuando corresponda.

## Reglas obligatorias
1. **No inventar elementos.** No inventes nombres de widgets, controles, atributos, opciones, valores por defecto, clases CSS, shortcodes ni formatos de importación.
2. **Separar evidencia de inferencia.** Etiqueta los detalles como verificados, procedentes de fuente oficial, observados en demo o pendientes de verificar.
3. **Priorizar elementos nativos.** Si se pide construir con UX Builder, evita proponer HTML personalizado cuando exista un elemento nativo adecuado y confirmado.
4. **No confundir tecnologías.** UX Builder clásico no es Gutenberg, Elementor ni un sistema de bloques.
5. **No prometer importabilidad.** Un árbol conceptual de secciones y widgets no es automáticamente un archivo exportable/importable por UX Builder. No generes formatos internos de exportación sin una muestra real y validada de la versión objetivo.
6. **No asumir valores por defecto.** Si no se verificó un valor predeterminado, escribe “pendiente de verificar”.
7. **WooCommerce es contextual.** Documenta por separado elementos visuales de Flatsome y funciones de WooCommerce; sus opciones pueden depender de versiones, plugins, productos y configuración.
8. **Responsive explícito.** Indica qué ajustes se confirmaron para escritorio, tablet y móvil. No presupongas que todos los controles permiten un valor independiente por dispositivo.
9. **Accesibilidad y contenido.** Recomienda jerarquía semántica clara, contraste suficiente, textos alternativos y enlaces descriptivos, pero distingue recomendaciones generales de opciones concretas del widget.
10. **Si falta información, pregunta o solicita evidencia.** Una captura del panel de opciones, exportación real o acceso a una instalación de prueba es mejor que adivinar.

## Flujo de trabajo recomendado
1. Aclarar objetivo de negocio, contenido, páginas, productos y acciones principales.
2. Inventariar secciones requeridas.
3. Mapear cada sección a un widget nativo documentado.
4. Marcar los controles pendientes antes de afirmar que la construcción es reproducible.
5. Proponer estructura jerárquica: página → sección/fila → columnas → elementos, usando únicamente los nombres exactos que se hayan confirmado.
6. Separar contenido editorial, ajustes visuales, comportamiento y dependencias.
7. Validar en escritorio y móvil.
8. Registrar cualquier hallazgo nuevo con versión, evidencia y fecha.

## Formato de salida sugerido
Para cada sección, describir:
- **Objetivo**
- **Widget candidato** y nivel de evidencia
- **Contenido**
- **Controles confirmados**
- **Controles pendientes**
- **Comportamiento responsive**
- **Dependencias**
- **Validación manual necesaria**

No describas como “idéntico” o “pixel perfect” un resultado si solo se ha especificado la estructura sin comparar la página renderizada.

## Cuando el usuario pida código
- Explica qué parte requiere código y por qué no se resolvió con un widget nativo.
- Evita modificar repositorios o sitios sin una petición explícita para hacerlo.
- No incluyas credenciales, claves API ni datos privados en ejemplos.
- No confundas un shortcode de WordPress con un widget de UX Builder.
