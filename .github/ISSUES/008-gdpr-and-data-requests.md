# GDPR y solicitudes de datos (export/forget)

## Descripción
Soporte para solicitudes GDPR: exportación de datos (archive) y eliminación (forget), con tiempo y procesos asincrónicos.

## Motivo
Cumplimiento legal y confianza del usuario.

## Criterios de aceptación
- Endpoint para solicitar export/delete.
- Tareas en background para generar/limpiar datos.

## Implementación sugerida
- Modelo `DataRequest` y proceso batch para generar archivos.
- Guardar y servir archivos temporalmente con caducidad.

## Etiquetas
`feature` `legal` `gdpr`
