# Niveles de evidencia

Utilizar una etiqueta visible en cada ficha técnica.

| Etiqueta | Significado | Qué permite afirmar |
|---|---|---|
| **Verificado en 3.20.11** | Comprobado en una instalación de la versión objetivo, con evidencia registrada. | Puede describirse como comportamiento confirmado bajo las condiciones probadas. |
| **Fuente oficial** | Descrito en documentación oficial identificada. | Puede atribuirse a la documentación; no implica prueba local en 3.20.11. |
| **Observado en demo** | Visible en una demo pública oficial. | Confirma lo observado en esa demo, no todos los controles internos ni la versión exacta. |
| **Fuente externa** | Procede de un recurso de terceros. | Debe citarse y contrastarse antes de considerarlo definitivo. |
| **Parcial** | Solo se confirmó una parte del comportamiento o de las opciones. | Describir únicamente la parte comprobada. |
| **Pendiente de verificar** | No hay evidencia suficiente. | No presentar como hecho ni usar como instrucción exacta. |
| **No compatible** | Se comprobó que no funciona en el alcance declarado. | No recomendar para ese entorno; registrar las condiciones de prueba. |

## Principios
- Una captura del frontend puede probar el aspecto visible, pero no demuestra por sí sola las opciones del panel.
- La presencia de un nombre en una demo no prueba que sea un widget nativo de UX Builder.
- Un atributo HTML o una clase CSS no se considera un control nativo por defecto.
- La ausencia de evidencia no prueba que una función no exista.
- Si la evidencia no identifica versión, etiquetarla en consecuencia.
