---
layout: default
title: Vacaciones y Ausencias
nav_order: 7
has_children: true
permalink: /modulos/vacaciones/
---

# Módulo de Vacaciones y Ausencias
{: .no_toc }

Gestiona las solicitudes de vacaciones, permisos y ausencias de tu empresa de forma digital, cumpliendo con la normativa laboral española.
{: .fs-6 .fw-300 }

---

## ¿Qué es el módulo de Vacaciones y Ausencias?

El **módulo de Vacaciones y Ausencias** permite a los empleados solicitar días libres y a los Managers aprobar o rechazar estas solicitudes de forma digital y trazable.

{: .important }
> **Siempre activo**: Este módulo está siempre activado (no se puede desactivar) porque es fundamental para el cumplimiento del Estatuto de los Trabajadores.

### Funcionalidades principales

- 📅 **Solicitar vacaciones**: Los empleados piden sus días libres
- ✅ **Aprobar/Rechazar**: Los Managers validan las solicitudes
- 📊 **Control de días**: Días disponibles vs consumidos
- 📧 **Notificaciones**: Alertas automáticas
- 📑 **Reportes**: Informes de ausencias

---

## Tipos de ausencias

| Tipo | Descuenta vacaciones | Requiere aprobación | Retribuida |
|------|---------------------|---------------------|------------|
| **Vacaciones** | ✅ Sí | ✅ Sí | ✅ Sí |
| **Permiso retribuido** | ❌ No | ✅ Sí | ✅ Sí |
| **Baja médica** | ❌ No | ❌ No | ⚠️ Parcial |
| **Asuntos propios** | ❌ No | ✅ Sí | ❌ No |
| **Permiso no retribuido** | ❌ No | ✅ Sí | ❌ No |

### Vacaciones anuales

- Días establecidos por convenio (generalmente 22-30 días/año)
- Se acumulan proporcionalmente cada mes trabajado
- Pueden tener fecha de caducidad (ej: 31 diciembre)
- Deben ser aprobadas por el Manager

👉 [Ver guía: Solicitar Vacaciones](/guias-por-rol/empleado/solicitar-vacaciones/) | 👉 [Ver guía: Aprobar Vacaciones](/guias-por-rol/manager/aprobar-vacaciones/)

### Permisos retribuidos

Días libres pagados por situaciones específicas:
- Matrimonio (15 días)
- Nacimiento de hijo (6 semanas)
- Fallecimiento familiar (2-4 días según parentesco)
- Mudanza (1 día)
- Asuntos médicos propios o familiares

{: .note }
> Los permisos retribuidos **no descuentan** del saldo de vacaciones anuales.

### Bajas médicas

- No requieren aprobación del Manager (solo informativa)
- El empleado debe presentar parte médico a RRHH
- No descuentan vacaciones
- Los días de baja interrumpen las vacaciones si coinciden

### Asuntos propios

Días libres por motivos personales sin especificar:
- Política varía según empresa
- Generalmente 2-6 días/año
- Algunos son retribuidos, otros no
- Requieren aprobación del Manager

---

## Flujo de solicitud

### Para Empleados

1. **Solicitar** → Selecciona fechas y tipo de ausencia
2. **Esperar** → El Manager revisa la solicitud
3. **Notificación** → Recibes email con la decisión
4. **Disfrutar** → Si se aprueba, los días quedan bloqueados

### Para Managers

1. **Recibir** → Notificación de nueva solicitud
2. **Revisar** → Verificar cobertura y saldo disponible
3. **Decidir** → Aprobar o rechazar con justificación
4. **Notificar** → El empleado recibe la respuesta

👉 [Ver guía: Aprobar Vacaciones (Manager)](/guias-por-rol/manager/aprobar-vacaciones/)

---

## Consultar saldo de vacaciones

Los empleados pueden ver su saldo en cualquier momento:

**Saldo mostrado:**
- **Días totales**: Días anuales asignados
- **Días consumidos**: Ya disfrutados
- **Días pendientes**: Solicitudes sin aprobar
- **Días disponibles**: Restantes para solicitar

**Ejemplo:**
```
Saldo de vacaciones 2025:
Total asignado: 22 días
Consumidos: 8 días
Pendientes: 3 días (esperando aprobación)
Disponibles: 11 días
```

👉 [Ver guía: Consultar Saldo (Empleado)](/guias-por-rol/empleado/solicitar-vacaciones/)

---

## Calendario de equipo

Los Managers pueden ver un calendario con todas las ausencias:

- 🟢 **Verde**: Ausencias aprobadas
- 🟡 **Amarillo**: Ausencias pendientes
- 🔴 **Rojo**: Ausencias rechazadas
- ⚪ **Azul**: Festivos

Permite detectar solapamientos y planificar mejor la cobertura.

---

## Políticas de vacaciones

### Antelación mínima

Cada empresa puede establecer:
- Días de antelación para solicitar (ej: 15 días)
- Excepciones para emergencias
- Períodos bloqueados (ej: cierre de trimestre)

### Caducidad de vacaciones

Según convenio, las vacaciones pueden:
- **Caducar** el 31 de diciembre (no se arrastran)
- **Arrastrarse** al año siguiente (hasta marzo/junio)
- **Pagarse** si no se disfrutan (excepcional)

👉 [Ver guía: Asignar Vacaciones (Admin)](/guias-por-rol/administrador/asignar-vacaciones/)

### Períodos restringidos

Los Managers pueden:
- Bloquear fechas específicas (ej: Black Friday en retail)
- Limitar el número de personas de vacaciones simultáneamente
- Establecer turnos rotativos para períodos populares

---

## Notificaciones

### Para Empleados

- 📧 Solicitud enviada correctamente
- 📧 Vacaciones aprobadas
- 📧 Vacaciones rechazadas (con motivo)
- 📧 Recordatorio: vacaciones próximas (7 días antes)
- 📧 Alerta: vacaciones por caducar

### Para Managers

- 📧 Nueva solicitud pendiente
- 📧 Recordatorio: solicitudes sin revisar (24h)
- 📧 Alerta: vacaciones que generan problemas de cobertura

<!-- ---

## Reportes de ausencias

### Para Managers

- **Resumen mensual**: Ausencias del mes por empleado
- **Saldo del equipo**: Días pendientes de cada uno
- **Planificación**: Ausencias futuras ya aprobadas

### Para Administradores

- **Informe anual**: Total de días de vacaciones consumidos
- **Costes**: Días retribuidos vs no retribuidos
- **Cumplimiento**: % de vacaciones disfrutadas

👉 [Ver guía: Reportes](/reportes/) -->

---

## Integración con fichajes

Las ausencias afectan a los fichajes:

- ❌ Días de vacaciones: No se espera fichaje
- ❌ Días festivos: No se espera fichaje
- ✅ Días laborables: Se espera fichaje completo

Si un empleado está de vacaciones, no aparecerá como "falta de fichaje" en los reportes.

---

## Cumplimiento normativo

El módulo cumple con:

- ✅ **Estatuto de los Trabajadores**: Derecho a vacaciones anuales
- ✅ **Convenios colectivos**: Días según sector
- ✅ **LOPD**: Protección de datos en solicitudes
- ✅ **Trazabilidad**: Registro de solicitudes y aprobaciones

---

## Preguntas frecuentes

### ¿Puedo solicitar vacaciones con menos antelación?

Depende de la política de tu empresa. En casos excepcionales, habla con tu Manager.

### ¿Qué pasa si rechazan mis vacaciones?

El Manager debe explicar el motivo. Puedes solicitar fechas alternativas.

### ¿Puedo cancelar vacaciones aprobadas?

Sí, antes de que empiecen. Después del inicio, depende de tu empresa.

### ¿Los festivos descuentan de mis vacaciones?

No, los festivos **no** se descuentan del saldo de vacaciones.

### ¿Puedo transferir vacaciones a otro año?

Depende del convenio colectivo. Consulta con RRHH.

---

## ¿Necesitas ayuda?

Si tienes dudas sobre vacaciones y ausencias:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Solicitar Vacaciones (Empleado)](/guias-por-rol/empleado/solicitar-vacaciones/)
- 👉 [Aprobar Vacaciones (Manager)](/guias-por-rol/manager/aprobar-vacaciones/)
- 👉 [Asignar Vacaciones (Admin)](/guias-por-rol/administrador/asignar-vacaciones/)
- 👉 [Días Festivos](/guias-por-rol/administrador/dias-festivos/)