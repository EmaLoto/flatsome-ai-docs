# Procedimiento para completar el inventario de UX Builder

## Objetivo

Construir una referencia útil para una IA que tenga que diseñar páginas con **Flatsome Classic UX Builder 3.20.11**, minimizando las opciones inventadas y permitiendo distinguir lo confirmado de lo inferido.

## Unidad de documentación

No asumir que cada nombre visible es un widget único. Una ficha debe identificar, cuando sea posible:

- Nombre visible en el selector del UX Builder.
- Nombre interno o shortcode, solo si se ha comprobado.
- Tipo: estructura, contenido, diseño, navegación, WooCommerce, integración o utilidad.
- Contexto en el que puede insertarse: página, bloque UX, plantilla de producto u otro.
- Controles y opciones del panel, usando los rótulos reales.
- Valores predeterminados, solo si se observaron.
- Contenido hijo permitido y reglas de anidación.
- Comportamiento responsivo y controles por dispositivo.
- Salida serializada o shortcode exacto, si se obtuvo de forma reproducible.
- Dependencias (WooCommerce, plugin, integración o módulo activado).
- Limitaciones y errores conocidos.
- Evidencia, versión y fecha de comprobación.

## Niveles de evidencia

Consultar `validation/EVIDENCE-LEVELS.md`. No elevar la evidencia de una captura de la demo a “Verificado en 3.20.11”.

## Flujo recomendado por elemento

1. **Descubrir:** identificar el nombre en la demo oficial, la documentación o el selector del editor.
2. **Localizar fuente:** buscar primero en UX Themes Docs; usar la demo oficial para ejemplos visuales.
3. **Inspeccionar Classic:** en una instalación 3.20.11, insertar el elemento en una página de prueba y abrir sus controles.
4. **Registrar literalmente:** transcribir etiquetas y opciones como aparecen. Registrar valores iniciales únicamente después de crear un elemento nuevo sin modificarlo.
5. **Probar interacciones:** guardar, recargar, previsualizar y comprobar qué cambios produce cada control.
6. **Inspeccionar serialización:** si es necesario, examinar el contenido guardado/shortcode generado por UX Builder. No inferir atributos de memoria ni de versiones anteriores.
7. **Probar responsive:** comprobar escritorio, tablet y móvil; registrar qué controles son globales y cuáles por dispositivo.
8. **Validar dependencias:** probar el elemento con y sin WooCommerce o módulos opcionales solo cuando corresponda.
9. **Documentar límites:** registrar comportamientos no confirmados y casos que requieren plugin o código adicional.
10. **Revisar por otra pasada:** comprobar que cada campo afirmado tenga evidencia y que no se mezclen opciones de otros elementos.

## Criterios de aceptación de una ficha

Una ficha se considera lista para uso de IA cuando:

- El nombre está identificado y el estado de evidencia es explícito.
- Los controles están separados entre confirmados, parciales y pendientes.
- No hay valores por defecto inventados.
- Los ejemplos de sintaxis se han copiado de una salida generada o fuente técnica verificable.
- Se explica cuándo usar el elemento y qué alternativas nativas considerar.
- Los campos específicos de WooCommerce no se mezclan con elementos de contenido general.
- Se incluyen referencias y una nota de versión.

## Prioridad sugerida

1. Estructura y composición: Section, Row/Columns, Stack/Gap/Divider (si aparecen en el selector de la versión objetivo).
2. Elementos usados con frecuencia en landing pages: Text, Title, Button, Image, Banner, Icon Box, Image Box, Accordion, Tabs, Forms y UX Block.
3. Contenido editorial: Blog Posts, Gallery, Video, Testimonials, Map y Portfolio.
4. Tienda: Products, Product Categories y elementos de plantilla de producto individual.
5. Elementos complementarios: Search, Share/Follow, Countdown, Hotspot, Price Table, Instagram Feed y Flip Book.
6. Integraciones y componentes que dependan de plugins.

Esta priorización es una propuesta de trabajo, no una afirmación de que todos los nombres de la lista existan como elementos separados en 3.20.11.

## Registro de comprobación

Añadir a cada ficha una tabla o bloque con:

- Versión de Flatsome.
- WordPress y WooCommerce probados, si corresponde.
- Fuente.
- Fecha de comprobación.
- Persona/procedimiento de comprobación.
- Resultado y límites.

## Si no se dispone de instalación 3.20.11

Se puede continuar documentando fuentes oficiales y ejemplos públicos, pero los controles deben marcarse como “pendiente de verificación”. Para cerrar ese pendiente se necesitará una captura del panel o acceso a una instalación de la versión objetivo. No declarar la documentación “completa” solo por haber listado la demo.
