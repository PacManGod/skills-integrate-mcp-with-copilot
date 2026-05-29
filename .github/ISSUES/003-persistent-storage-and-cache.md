# Persistencia (Postgres) y cache (Redis)

## Descripción
Reemplazar almacenamiento en memoria por base de datos relacional (Postgres) y añadir Redis para caching/cola.

## Motivo
Persistencia entre reinicios, escalabilidad y soporte para jobs/colas y caching de consultas.

## Criterios de aceptación
- Migración de modelos (Activities, Users, Signups) a Postgres.
- Configuración de Redis para caché y pub/sub/cola.

## Implementación sugerida
- Añadir `alembic`/migrations (o equivalente del framework elegido).
- Actualizar tests para usar DB de pruebas.

## Etiquetas
`infrastructure` `database` `redis`
