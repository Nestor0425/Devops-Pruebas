# Estrategia Git & CI v1

# Comentarios de auditoría
# Fecha: 2025-09-21
# Autor: Néstor Pérez
# Cambio: Creación inicial del documento

## Flujo de ramas
- main → versiones estables
- develop → integración de features listas
- feature/* → desarrollo de nuevas funcionalidades
- hotfix/* → correcciones urgentes

## Política de Pull Requests
- Todos los cambios se hacen vía Pull Request
- Revisar al menos por 1 CODEOWNER
- PR debe incluir descripción clara, pruebas y seguir plantilla

## Convención de commits
- feat: nueva funcionalidad
- fix: corrección de bug
- docs: cambios en documentación
- test: añadir/modificar pruebas
- chore: mantenimiento que no afecta funcionalidades

## Pipeline CI
1. Build
2. Pruebas unitarias
3. Análisis estático
4. Generación de artefactos
