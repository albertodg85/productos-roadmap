# 🔄 Flujo de Trabajo de Trimestre

## Planificación Inicial (Primera semana del trimestre)

### Día 1-2: Revisión de Objetivos
1. **Lee** la documentación del trimestre (`docs/Q#-2026.md`)
2. **Revisa** los productos afectados
3. **Identifica** cambios de prioridad desde último trimestre
4. **Participa** en Discussion de planificación

### Día 3-4: Creación de Issues
1. **Crea** un issue por cada feature/tarea
2. **Estima** complejidad y tiempo (1-5 puntos, 1d-2w)
3. **Conecta** issues bloqueadas
4. **Asigna** a desarrolladores

### Día 5: Kick-off
1. **Reúnete** con el equipo
2. **Presenta** roadmap del trimestre
3. **Aclara** dudas y dependencias
4. **Comienza** trabajo en issues

---

## Ejecución (Semanas 2-11)

### Daily Standup
```bash
# Cada día, revisar:
1. Issues asignadas a ti que están "In Progress"
2. Issues "Blocked" que necesitan ayuda
3. Issues "Ready" que puedas empezar
```

### Actualizaciones Diarias
- Mueve issues a través del Kanban según progreso
- Comenta en issues con actualizaciones
- Reporta bloqueadores inmediatamente

### Reuniones Regulares
- **Weekly Sync** (Lunes): Status general del trimestre
- **Mid-Trimestre Review** (Semana 6): Ajustes de prioridad
- **Demo** (Último viernes): Mostrar progreso

---

## Cierre de Trimestre (Última semana)

### Finalizando Trabajo
1. **Completa** todas las tareas posibles
2. **Documenta** work-in-progress
3. **Crea** pull requests para code review
4. **Prepara** releases/deployment

### Documentación
1. **Actualiza** README de productos
2. **Cierra** issues completados
3. **Documenta** issues no terminadas (con notas para próximo trimestre)
4. **Crea** GitHub Release con resumen

### Retrospectiva
1. **Abre** Discussion de retrospectiva
2. **Analiza**: Qué salió bien, qué mejorar
3. **Recopila** feedback de usuarios
4. **Planifica** ajustes para próximo trimestre

### Transición
1. **Review** prioridades con PM
2. **Comienza** planificación de próximo trimestre
3. **Archiva** issues de trimestre completado (add label "completed")

---

## Vistas Recomendadas por Rol

### Developer View
```
Project > Board
Filters: 
  - Assignee: Tu nombre
  - Status: In Progress
SortBy: Priority DESC, Created ASC
```

### PM View
```
Project > Roadmap
Filters:
  - Trimestre: Q3-2026 (actual)
ShowBy: Timeline
```

### Manager View
```
Project > Table
Group By: Product
Filters: Trimestre actual
Metrics: Issues completados, En progreso, Bloqueados
```

---

## Checkpoints Recomendados

### Weekly Checkpoint (Viernes)
- [ ] Todos los issues en Kanban actualizados
- [ ] PRs sin revisar minados
- [ ] Bloqueadores reportados
- [ ] Métricas de completitud verificadas

### Bi-Weekly Checkpoint (Cada 2 semanas)
- [ ] Reunión de sync completada
- [ ] Prioridades ajustadas si es necesario
- [ ] Riesgos identificados y mitigados
- [ ] Stakeholders informados de progreso

### Mid-Trimestre Checkpoint (Semana 6)
- [ ] 50% del trabajo completado
- [ ] Identificar tasks en riesgo
- [ ] Ajustar prioridades para segundo half
- [ ] Comunicar cambios al equipo

### End-Trimestre Checkpoint (Última semana)
- [ ] 90%+ del trabajo completado
- [ ] Code review finalizados
- [ ] Testing completado
- [ ] Documentación actualizada
- [ ] Releases preparadas

---

## Métricas a Trackear

| Métrica | Objetivo | Frecuencia |
|---------|----------|------------|
| Issues Completados | 100% de planned | Diaria |
| Issues Bloqueados | <5% | Diaria |
| Code Review Cycle Time | <24h | Semanal |
| Test Coverage | >80% | Semanal |
| Deployment Frequency | 2+ por semana | Semanal |
| Mean Time to Production | <1d | Semanal |
| User Satisfaction (NPS) | >50 | Mensual |
| Bug Escape Rate | <2% | Semanal |

---

## Plantilla de Status Report

```markdown
## Status Report - Semana [X]

### Completado esta semana
- [ ] Task 1 (#123)
- [ ] Task 2 (#124)

### En progreso
- [ ] Task 3 (#125) - 60% completado
- [ ] Task 4 (#126) - 30% completado

### Bloqueados
- [ ] Task 5 (#127) - Bloqueado por #999

### Riesgos
- Risk 1: [Descripción] - Impacto: [High/Medium/Low]
- Risk 2: [Descripción] - Impacto: [High/Medium/Low]

### Siguiente semana
- [ ] Task 6
- [ ] Task 7

### Notas
- Nota importante 1
- Nota importante 2
```
