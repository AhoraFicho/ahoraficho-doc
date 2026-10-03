---
layout: default
title: Gestionar Solicitudes
parent: Vacaciones y Ausencias
nav_order: 2
---

# Gestionar Solicitudes de Ausencias
{: .no_toc }

Guía para Administradores sobre cómo gestionar todas las solicitudes de vacaciones y ausencias de la empresa.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Vista global de solicitudes

Como **Administrador**, puedes ver y resolver las solicitudes de toda la empresa (los Managers solo ven las de su ámbito).

### Acceder a solicitudes

1. Ve a **"Validaciones"** → **"Ausencias Pendientes"**
2. Verás las solicitudes pendientes con:
   - **Pestañas "Pendientes"** y **"Validadas"** (histórico con selector de año)
   - **Filtro por trabajador** + botón **"Filtrar"**
   - Casillas para **selección múltiple**

Como Administrador puedes resolver **cualquier** solicitud, incluidas las de empleados sin responsable asignado y las de segunda aprobación pendientes.

---

## Aprobar o rechazar

### Acciones individuales

- Pulsa **✓ (Aprobar)** o **✗ (Denegar)** en cada fila
- Al denegar se te pedirá el **"Motivo del rechazo (opcional)"**, que queda registrado y visible para el empleado

### Acción masiva

1. Selecciona múltiples solicitudes (checkbox o seleccionar todas)
2. Pulsa **"Aprobar"** o **"Denegar"**
3. En el diálogo de confirmación, marca **"Notificar al empleado por email"** (activada por defecto)
4. Confirma

**Cuándo usar la acción masiva:**
- Final de mes para resolver las pendientes válidas
- Períodos de cierre de empresa (Navidad)
- Solicitudes sencillas sin conflictos

{: .note }
> Si tu empresa usa la **doble aprobación** (EnableTwoLevelAbsenceApproval), el flujo Resp. 1 → Resp. 2 se respeta: el sistema impedirá resolver en el orden incorrecto con el aviso *"La ausencia debe aprobarse/rechazarse por el responsable correspondiente en el orden establecido."* Como Administrador puedes resolver en cualquier momento las que estén a la espera.

---

## Gestionar bajas médicas

Según la configuración del tipo **"Baja"** en tu empresa:

1. Verifica que el empleado ha adjuntado el **parte oficial** (el formulario lo solicita)
2. Revisa y resuelve la solicitud como cualquier otra
3. Archiva la documentación (obligación legal)
4. Registra las prórrogas: el empleado puede subir partes de confirmación desde sus ausencias

---

## Configuración relacionada

### Saldo de vacaciones por empleado

**Desde**: Configuraciones → **Trabajadores** → Editar trabajador → campo **"Max Ausencias"** y su caducidad. Ver [Asignar Vacaciones](/guias-por-rol/administrador/asignar-vacaciones/).

### Bloqueos de vacaciones por edificio

Si necesitas impedir solicitudes en ciertas fechas (campañas, cierres de empresa): Configuraciones → **"Bloqueos de vacaciones"**. Los empleados verán el error correspondiente al intentar solicitar en esas fechas.

### Tipos de ausencia

Configuraciones → **"Tipos de Ausencias"**: crea, edita o desactiva los tipos que los empleados pueden solicitar, con su color en el calendario.

---

## Reportes de ausencias

- **"Validaciones" → "Ausencias Pendientes" → pestaña "Validadas"**: histórico por año
- Menú **"Empresa" → "Calendario de la empresa"**: visión de todas las ausencias aprobadas
- Menú **"Reportes" → "Resumen Ausencias"**: visión general de la empresa (contadores por tipo y año)

---

## Preguntas frecuentes

### ¿Puedo modificar una solicitud ya aprobada?

Puedes gestionarla desde la **"Gestión de Ausencias"** del menú Empresa (eliminar días futuros o ajustar). Siempre explica el motivo al empleado.

### ¿Qué hago con solicitudes muy antiguas pendientes?

Contacta con el Manager responsable para que las revise, o resuélvelas tú directamente. Si ya pasó la fecha, recházalas.

### ¿Puedo crear una ausencia en nombre de un empleado?

Sí, desde **"Empresa" → "Gestión de Ausencias"** puedes crear ausencias para cualquier empleado (útil para registrar bajas comunicadas por teléfono).

---

## Guías relacionadas

- 👉 [Aprobar Vacaciones (Manager)](/guias-por-rol/manager/aprobar-vacaciones/)
- 👉 [Asignar Vacaciones](/guias-por-rol/administrador/asignar-vacaciones/)
- 👉 [Solicitar Vacaciones (Empleado)](/guias-por-rol/empleado/solicitar-vacaciones/)
- 👉 [Módulo de Vacaciones](/modulos/vacaciones/)
