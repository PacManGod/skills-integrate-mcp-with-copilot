# Membresías y pagos (Stripe / Yookassa)

## Descripción
Sistema de membresías de pago, gestión de suscripciones, webhooks de pago, páginas de compra y renovación, y opciones de regalo/links promocionales.

## Motivo
Monetizar el servicio y controlar accesos a contenido privado.

## Criterios de aceptación
- Página de compra/checkout funcional.
- Webhooks seguros para actualizar estado de membresía.
- Gestión de expiración y renovación automática.

## Implementación sugerida
- Integrar Stripe (recomendado) y/o Yookassa.
- Modelar `Membership` y `Subscription` en la base de datos.
- Añadir pruebas de webhook y flujo de pago.

## Etiquetas
`feature` `payments` `billing`
