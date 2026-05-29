# Tareas en background y colas (workers)

## Descripción
Añadir soporte para tareas asíncronas: promoción de posts, generación de exportes GDPR, envío de notificaciones y tareas programadas.

## Motivo
Evitar bloqueos en peticiones sincrónicas y manejar procesos largos eficientemente.

## Criterios de aceptación
- Worker configurado (e.g. RQ, Celery, django-q, or a lightweight alternative).
- Ejemplo de tarea y cron job configurado.

## Implementación sugerida
- Integrar Redis + RQ/Celery y añadir `make` o `docker-compose` entries para workers.

## Etiquetas
`infrastructure` `async` `jobs`
