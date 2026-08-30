# 📋 Guía de Uso del Roadmap

## Objetivo
Esta guía te explica cómo usar el sistema de roadmap centralizado para gestionar los 4 productos.

---

## 🎯 Para Desarrolladores

### 1. Encontrar tareas asignadas
```
1. Ve a https://github.com/albertodg85/productos-roadmap/projects
2. Selecciona el project del producto que desarrollas
3. Filtra por tu nombre en "Assignees"
4. Ordena por "Priority" para ver las tareas más urgentes
```

### 2. Empezar a trabajar en una tarea
```
1. Abre el Issue de la tarea
2. Cambia el status a "In Progress" (arrastra en Kanban o edita en vista de tabla)
3. Crea una rama en tu repo: git checkout -b feature/issue-name
4. Trabaja normalmente en el código
5. Cuando termines, crea un PR referenciando el issue
```

### 3. Actualizar el status
- **Backlog → Ready**: Cuando está lista para iniciar
- **Ready → In Progress**: Cuando empiezas a trabajar
- **In Progress → In Review**: Cuando creas el PR
- **In Review → Done**: Cuando se hace merge

### 4. Labels importantes
- `priority:critical` - Hazlo YA
- `priority:high` - Este mes/trimestre
- `blocking` - Bloquea otras tareas
- `needs-review` - Necesita revisión

---

## 📊 Para Product Managers

### 1. Ver el roadmap completo
```
1. Ve a https://github.com/albertodg85/productos-roadmap/projects
2. Usa la vista de "Roadmap" para ver timeline visual
3. Filtra por trimestre usando labels (Q3-2026, Q4-2026, etc.)
```

### 2. Agregar nuevas features
```
1. Crea un nuevo Issue en el repo
2. Título: Descripción clara de la feature
3. Descripción: Contexto, requisitos, aceptación
4. Labels: producto, trimestre, mes, tipo, prioridad
5. Milestone: El trimestre correspondiente
```

### 3. Priorizar trabajo
```
1. Usa labels de prioridad: critical, high, medium, low
2. Draggea issues en el Kanban para cambiar orden
3. Usa Discussions para decisiones de roadmap
```

### 4. Seguimiento de progreso
```
1. Project > View as Table
2. Group by: Status o Product
3. Filtra por trimestre actual
4. Revisa % completado en cada columna
```

---

## 💬 Para Todos - Discussions

### Usar Discussions para:
- 🎯 Estrategia de producto
- 🤔 Decidir entre alternativas
- 💡 Feedback de usuarios
- 📈 Retrospectivas de trimestre
- 🔄 Cambios de prioridades

### Crear una Discussion
```
1. Ve a Discussions > New Discussion
2. Selecciona categoría (Decision, Idea, Q&A, etc.)
3. Abre el debate
4. Referencia issues relevantes con #numero
```

---

## 📅 Flujo de Trabajo Típico

### Inicio de Trimestre
1. Revisar documentación del trimestre en `/docs/Q#-2026.md`
2. Crear Issues para cada feature
3. Estimar complejidad
4. Asignar a desarrolladores

### Durante el Trimestre
1. Daily standup usando Issues con label de mes actual
2. Actualizar status de issues regularmente
3. Mover bloqueados a "Blocked" label
4. Ajustar prioridades según cambios

### Fin de Trimestre
1. Cerrar issues completados
2. Mover work-in-progress al siguiente trimestre
3. Crear Discussion de retrospectiva
4. Planificar siguiente trimestre

---

## 🏷️ Estructura de Labels Recomendada

### SIEMPRE usar:
```
- producto:goSail, producto:ProAgencyDeploy, producto:lack, producto:seaPilot
- Q1-2026, Q2-2026, Q3-2026, Q4-2026
- enero, febrero, marzo... (el mes específico)
- priority:critical, priority:high, priority:medium, priority:low
- status:backlog, status:ready, status:in-progress, status:review, status:done
```

### OPCIONALMENTE usar:
```
- feature, bug, improvement, documentation, infrastructure, performance, security
- phase:mvp, phase:v1.0, phase:v1.1, phase:enterprise, phase:monetization
- breaking-change, external-dependency, needs-design, needs-pm-review
- blocked, blocking, help-wanted
```

---

## 🔗 Enlaces Rápidos

| Recurso | Link |
|---------|------|
| **Project Board** | https://github.com/albertodg85/productos-roadmap/projects |
| **Issues** | https://github.com/albertodg85/productos-roadmap/issues |
| **Discussions** | https://github.com/albertodg85/productos-roadmap/discussions |
| **Milestones** | https://github.com/albertodg85/productos-roadmap/milestones |
| **Q1 Roadmap** | [docs/Q1-2026.md](../docs/Q1-2026.md) |
| **Q2 Roadmap** | [docs/Q2-2026.md](../docs/Q2-2026.md) |
| **Q3 Roadmap** | [docs/Q3-2026.md](../docs/Q3-2026.md) |
| **Q4 Roadmap** | [docs/Q4-2026.md](../docs/Q4-2026.md) |

---

## ❓ FAQs

### ¿Cómo asignarme una tarea?
Clic en el issue → Assignees → Selecciona tu nombre

### ¿Puedo cambiar la prioridad de una tarea?
Solo PMs pueden cambiar prioridades. Abre una Discussion si desacuerdas.

### ¿Qué pasa si me quedo bloqueado?
Agrega label `blocked` y comenta en el issue qué te bloquea. Un PM puede ayudar.

### ¿Cómo reporto un bug encontrado?
Crea un nuevo Issue con label `bug` y `priority:high`

### ¿Puedo posponer una tarea al siguiente trimestre?
Sí, pero requiere aprobación de PM. Abre una Discussion.

---

## 📚 Más Información

- [Documentación de cada producto](../productos/)
- [Labels disponibles](../LABELS.md)
- [GitHub Projects Guide](https://docs.github.com/en/issues/planning-and-tracking-with-projects)
