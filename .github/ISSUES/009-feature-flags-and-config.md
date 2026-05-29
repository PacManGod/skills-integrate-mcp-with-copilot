# Feature flags y configuración dinámica

## Descripción
Sistema de feature flags para activar/desactivar funcionalidades por ambiente o por fork.

## Motivo
Permite desplegar cambios graduales y mantener forks compatibles.

## Criterios de aceptación
- Sistema sencillo de flags en DB o archivo.
- Helper para verificar flags en rutas/plantillas.

## Implementación sugerida
- Implementar módulo `feature_flags` y decorator`require_feature`.
- UI básica en admin para togglear flags.

## Etiquetas
`feature` `ops` `config`
