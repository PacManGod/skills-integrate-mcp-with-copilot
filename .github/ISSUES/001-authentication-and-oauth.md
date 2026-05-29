# Autenticación avanzada y OAuth/OpenID

## Descripción
Añadir soporte de autenticación avanzado: cuentas de usuario, login por email, y proveedor OAuth/OpenID para que aplicaciones externas puedan integrarse (creación/gestión de apps, `service_token`).

## Motivo
Permite integraciones seguras con bots y aplicaciones externas y evita uso sin autenticación.

## Criterios de aceptación
- Login de usuarios con email (código o contraseña).
- Endpoint para crear/gestionar apps OAuth (Client ID/Secret).
- Soporte para `service_token` en peticiones API.

## Implementación sugerida
- Añadir `users` y `authn` módulos.
- Integrar `oauthlib` o Django social/OAuth si se migra a Django; para FastAPI usar `Authlib`.
- Añadir tests para flujo de autorización y uso de `service_token`.

## Etiquetas
`feature` `auth` `security`
