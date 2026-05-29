# Tests, CI y despliegue con Docker

## Descripción
Configurar pruebas automatizadas (backend y frontend), pipeline de CI (GitHub Actions) y definiciones de despliegue con Docker/Docker Compose.

## Motivo
Garantizar calidad y facilitar despliegues reproducibles.

## Criterios de aceptación
- Suite de tests ejecutable localmente y en CI.
- Workflow de GitHub Actions que corre tests y build.
- `Dockerfile` y `docker-compose.yml` para desarrollo/producción.

## Implementación sugerida
- Añadir `Makefile` targets, `requirements.txt` y `frontend` build scripts.
- Crear `.github/workflows/ci.yml` básico.

## Etiquetas
`devops` `tests` `ci`
