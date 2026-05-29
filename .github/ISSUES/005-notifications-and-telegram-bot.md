# Notificaciones y bot de Telegram

## Descripción
Integración con Telegram para notificaciones (nuevas actividades, inscripciones, moderación) y bot de help-desk.

## Motivo
Facilita comunicaciones en tiempo real y automatiza flujos de moderación/soporte.

## Criterios de aceptación
- Bot que envía notificaciones a administradores.
- Webhook/handler para interacciones entrantes.

## Implementación sugerida
- Usar `python-telegram-bot` o `aiogram` y configurar `TELEGRAM_TOKEN` en env.
- Plantillas de mensajes y tests de integración básicos.

## Etiquetas
`feature` `integrations` `telegram`
