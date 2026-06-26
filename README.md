# PetLink — Nuevo Hogar 🐾

Sistema web para la gestión de adopción y vinculación de mascotas, desarrollado bajo el estándar **ISO/IEC 29110** por el equipo IDGS91.

## Equipo de Desarrollo

| Rol | Nombre |
|-----|--------|
| Project Manager / Documentación | Roy Eduardo Sandoval Rosales |
| Backend (PHP + PostgreSQL) | Saul Gamaliel Cruz López |
| Frontend (Angular) | Gustavo Caleb Escobedo Jiménez |

## Stack Tecnológico

| Capa | Tecnología |
|------|-----------|
| Frontend | Angular |
| Backend | PHP (MVC) |
| Base de Datos | PostgreSQL |
| Control de Versiones | Git / GitHub |
| Gestión de Proyecto | Trello (Kanban) |

## Estructura del Repositorio

```
petlink/
├── docs/
│   ├── requisitos/       # Especificaciones y casos de uso
│   ├── diagramas/        # Diagramas UML, ER y arquitectura
│   └── actas/            # Actas de reunión y minutas
├── src/
│   ├── frontend/         # Aplicación Angular
│   ├── backend/          # API REST en PHP
│   └── database/         # Scripts SQL y migraciones
├── config/               # Archivos de configuración del entorno
├── .github/
│   └── ISSUE_TEMPLATE/   # Plantillas de issues y PRs
└── README.md
```

## Estándares de Calidad (ISO/IEC 29110)

1. **Kanban estructurado** en Trello: columnas Por Hacer → En Proceso → Revisión → Terminado
2. **Control de ramas** en GitHub: toda funcionalidad en rama `feature/` con Pull Request obligatorio
3. **Carpeta `/docs`** con documentación técnica y administrativa actualizada

## Flujo de Trabajo Git

```
main
└── develop
    ├── feature/estructura-proyecto     ← rama de esta sesión
    ├── feature/frontend-[módulo]
    └── feature/backend-[módulo]
```

## Estado del Proyecto

| Fase | Estado |
|------|--------|
| Definición de estándares de calidad | ✅ Completado |
| Estructura del repositorio | 🔄 En proceso |
| Desarrollo de módulos | ⏳ Pendiente |
