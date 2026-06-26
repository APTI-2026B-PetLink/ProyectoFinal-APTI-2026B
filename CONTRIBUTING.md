# Guía de Contribución — PetLink

## Convención de Ramas

| Prefijo | Uso |
|---------|-----|
| `feature/` | Nueva funcionalidad o tarea administrativa |
| `fix/` | Corrección de errores |
| `docs/` | Actualizaciones de documentación |
| `hotfix/` | Corrección urgente en producción |

**Formato:** `feature/descripcion-corta-en-kebab-case`

## Mensajes de Commit

Formato obligatorio:
```
tipo(alcance): descripción breve en imperativo

[cuerpo opcional]
```

**Tipos válidos:** `feat`, `fix`, `docs`, `chore`, `refactor`, `test`

**Ejemplos:**
```
docs(estructura): agregar árbol de directorios oficial del proyecto
feat(auth): implementar módulo de registro de usuarios
chore(config): agregar archivo de variables de entorno
```

## Pull Requests

- Todo cambio debe realizarse en una rama `feature/`
- El PR debe incluir descripción del cambio y capturas si aplica
- Requiere revisión de al menos un miembro antes de merge a `develop`

## Tablero Kanban (Trello)

Columnas del sprint:
1. **Por Hacer / Ready** — Tareas definidas y listas para iniciar
2. **En Proceso** — Tarea activa en desarrollo
3. **En Revisión** — Esperando revisión de compañero
4. **Terminado / Done** — Tarea completada y mergeada
