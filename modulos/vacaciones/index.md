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

- 📅 **Solicitar ausencias**: Los empleados piden vacaciones, permisos y bajas desde su calendario
- ✅ **Aprobar/Rechazar**: Los Managers (y Administradores) validan las solicitudes, individual o masivamente
- 🔁 **Doble aprobación opcional**: Flujo Responsable 1 → Responsable 2 con estado "Pendiente Segunda Aprobación"
- 🌗 **Media jornada**: Vacaciones de medio día (mañana/tarde) para días sueltos
- 📊 **Control de días por año**: Saldo por año administrativo con caducidad
- 🚫 **Bloqueos de vacaciones**: Fechas bloqueadas por edificio (campañas, cierres)
- 📆 **Calendarios**: De equipo, de empresa y general
- 📧 **Notificaciones**: Email y push en cada cambio de estado
- 🗓️ **Sincronización con Google Calendar**: Las vacaciones aprobadas se copian en un calendario de Google

---

## Tipos de ausencias

Los tipos son **configurables por empresa** (Configuraciones → "Tipos de Ausencias"). Los habituales:

| Tipo | Descuenta vacaciones | Adjunto | Duración |
|------|---------------------|---------|----------|
| **Vacaciones** | ✅ Sí | No | Día completo o media jornada |
| **Baja** | ❌ No | Sí (parte médico) | — |
| **Teletrabajo** | ❌ No | Opcional | Opcional |
| **Asuntos propios** | ❌ No | Opcional | Opcional |
| **Otras ausencias justificadas** | ❌ No | Opcional | Opcional |
| **Compensatorio** (banco de horas) | ❌ No (consume horas del banco) | No | — |

👉 [Ver todos los tipos en detalle](/modulos/vacaciones/tipos-ausencias/)

### Vacaciones anuales

- Días establecidos por convenio (generalmente 22-30 días/año)
- Al dar de alta a un empleado se genera el **prorrateo** del año en curso (por meses devengados) más la bolsa del año siguiente
- Cada bolsa tiene **fecha de caducidad** (habitualmente 31 de diciembre)
- Se aprueban por el Responsable (Manager) y, si está activa la doble aprobación, también por el segundo responsable

👉 [Ver guía: Solicitar Vacaciones](/guias-por-rol/empleado/solicitar-vacaciones/) | 👉 [Ver guía: Aprobar Vacaciones](/guias-por-rol/manager/aprobar-vacaciones/)

### Permisos retribuidos

Días libres pagados por situaciones específicas (según Estatuto y convenio):
- Matrimonio (15 días)
- Nacimiento de hijo (6 semanas)
- Fallecimiento familiar (2-4 días según parentesco)
- Mudanza (1 día)
- Asuntos médicos propios o familiares

{: .note }
> Los permisos retribuidos **no descuentan** del saldo de vacaciones anuales.

### Bajas médicas

- El empleado adjunta el **parte médico** en la solicitud
- No descuentan vacaciones
- Los días de baja interrumpen las vacaciones si coinciden (gestión manual por RRHH)

### Asuntos propios

Días libres por motivos personales:
- Política varía según empresa (generalmente con duración configurable)
- Requieren aprobación del Responsable

---

## Flujo de solicitud

### Para Empleados

1. **Solicitar** → Selecciona el rango en tu calendario y completa el formulario (tipo, año administrativo, media jornada, motivo, adjunto)
2. **Esperar** → El Responsable (Manager) revisa la solicitud; con doble aprobación, pasa después al segundo responsable
3. **Notificación** → Recibes email y push con la decisión
4. **Disfrutar** → Si se acepta, los días quedan registrados y descontados del saldo

### Para Managers

1. **Recibir** → Notificación de nuevas solicitudes pendientes
2. **Revisar** → Verificar saldo, cobertura y calendario del equipo
3. **Decidir** → Aprobar o denegar (individual o masivamente, con motivo en el rechazo)
4. **Notificar** → El empleado recibe la respuesta

👉 [Ver guía: Aprobar Vacaciones (Manager)](/guias-por-rol/manager/aprobar-vacaciones/)

---

## Consultar saldo de vacaciones

Los empleados ven su saldo por **año administrativo** en "Mis ausencias" (tarjetas del año anterior, actual y siguiente):

- **Aceptada**: días aprobados
- **Pendiente**: solicitudes sin resolver
- **Rechazada**: días denegados
- **No usadas**: días aún disponibles

Con avisos de **caducidad** (días perdidos / disponibles / alerta de próximas caducidades).

👉 [Ver guía: Solicitar Vacaciones (Empleado)](/guias-por-rol/empleado/solicitar-vacaciones/)

---

## Calendarios de ausencias

- **"Equipo" → "Calendario del equipo"**: ausencias del equipo de tu responsable
- **"Equipo" → "Calendario General"** (si está habilitado): todas las ausencias visibles de la empresa
- **"Empresa" → "Calendario de la empresa"** (Admin): todas las ausencias de la empresa

Permite detectar solapamientos y planificar la cobertura.

---

## Políticas de vacaciones

### Caducidad de vacaciones

Cada bolsa anual puede tener **fecha de caducidad** (habitualmente 31 de diciembre). El empleado recibe avisos de las caducidades próximas y ve los días perdidos/disponibles reales.

👉 [Ver guía: Asignar Vacaciones (Admin)](/guias-por-rol/administrador/asignar-vacaciones/)

### Bloqueos de vacaciones

El Administrador puede definir **rangos de fechas bloqueadas por edificio** (Configuraciones → "Bloqueos de vacaciones"): en esas fechas los empleados no podrán solicitar vacaciones y verán el error correspondiente (ideal para campañas, cierres de empresa o picos de actividad).

---

## Notificaciones

Las notificaciones se envían por **email y push**, y cada empleado puede configurar qué recibe desde **"Mi Perfil" → "Notificaciones"**:

### Para Empleados

- 📧 Cambio de estado de sus ausencias (aceptada / rechazada / pendiente 2ª aprobación)
- 📧 Resúmenes de ausencias próximas a caducar (visible en pantalla)

### Para Managers y Admins

- 📧 Ausencias pendientes de validación (aviso diario o resumen semanal, según configuración)

👉 [Ver guía: Notificaciones](/guias-por-rol/empleado/notificaciones/)

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
- 👉 [Sincronización con Google Calendar](/modulos/vacaciones/sincronizacion-google-calendar/)