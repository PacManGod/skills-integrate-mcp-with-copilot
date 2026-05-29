# Comentarios, votos y moderación

## Descripción
Añadir sistema de comentarios en hilos, votaciones (upvote/downvote), flags de moderación y herramientas para moderadores.

## Motivo
Mejorar la interacción entre estudiantes y permitir control de calidad del contenido.

## Criterios de aceptación
- Comentarios en posts/actividades con hilos.
- Votación y conteo de votos.
- Interfaz o endpoints para moderadores (pin, delete, flag).

## Implementación sugerida
- Modelo `Comment` con referencia a `User` y `Activity`/`Post`.
- Endpoints REST + protección de permisos.

## Etiquetas
`feature` `comments` `moderation`
