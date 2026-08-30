# 🎯 Plantilla de Issue

Usa esta plantilla para crear nuevos issues en el roadmap.

## Información General
- **Producto**: [goSail | ProAgencyDeploy | lack | seaPilot]
- **Trimestre**: [Q1-2026 | Q2-2026 | Q3-2026 | Q4-2026]
- **Mes**: [enero-diciembre]
- **Prioridad**: [critical | high | medium | low]
- **Tipo**: [feature | bug | improvement | documentation | infrastructure | performance | security]

## Descripción

### ¿Qué es?
Descripción clara de la feature o fix.

### ¿Por qué es importante?
Contexto de negocio. ¿Por qué debemos hacerlo?

### Criterios de Aceptación
- [ ] Criterio 1
- [ ] Criterio 2
- [ ] Criterio 3

## Detalles Técnicos

### Cambios Requeridos
- Frontend: [describe cambios]
- Backend: [describe cambios]
- Base de datos: [describe cambios]
- Infraestructura: [describe cambios]

### Estimación
- **Complejidad**: [1-5 puntos]
- **Tiempo estimado**: [Xd/Xw/Xm]
- **Dependencias**: Referencia a otros issues con #numero

### Consideraciones
- [ ] Requiere design review
- [ ] Requiere security review
- [ ] Breaking change
- [ ] Requiere documentación
- [ ] Requiere testing especial

## Testing

### Plan de Testing
- [ ] Unit tests
- [ ] Integration tests
- [ ] E2E tests
- [ ] Manual testing

### Casos de Prueba
1. Caso normal: [describe]
2. Casos edge: [describe]
3. Casos error: [describe]

## Documentación

### Documentación Requerida
- [ ] README actualizado
- [ ] API docs actualizada
- [ ] User guide actualizada
- [ ] Code comments

## Labels

Agregar labels relevantes:
- Producto: `producto:goSail`, etc.
- Trimestre: `Q3-2026`, etc.
- Mes: `agosto`, etc.
- Tipo: `feature`, `bug`, etc.
- Prioridad: `priority:high`, etc.
- Fase: `phase:v1.0`, etc.

## Milestone

Asignar al milestone del trimestre correspondiente (Q3-2026, etc.)

## Assignees

Asignar a los desarrolladores responsables.

---

## Ejemplo Completado

**Título**: Agregar autenticación con OAuth a goSail

**Descripción**:

### ¿Qué es?
Implementar login con Google y GitHub en goSail para mejorar experiencia de usuarios.

### ¿Por qué es importante?
Reducir fricción en registro. Industry standard. Aumentar conversión.

### Criterios de Aceptación
- [ ] Login con Google funcional
- [ ] Login con GitHub funcional
- [ ] Logout funcional
- [ ] Refresh tokens automático
- [ ] Tests pasando al 100%

### Cambios Requeridos
- Frontend: Nueva página de login con botones OAuth
- Backend: Endpoints de OAuth callback
- Base de datos: Nuevo schema para OAuth tokens

### Estimación
- Complejidad: 3 puntos
- Tiempo: 3-4 días
- Dependencias: #12 (Setup de autenticación base)

### Labels
- `producto:goSail`
- `Q1-2026`
- `enero`
- `feature`
- `priority:high`
- `phase:mvp`
