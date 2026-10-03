---
layout: default
title: Aprobar Imputaciones
parent: Manager
grand_parent: Guías por Rol
nav_order: 4
---

# Aprobar Imputaciones
{: .no_toc }

Aprende a validar las horas que tus empleados imputan a diferentes proyectos. Asegura que las imputaciones sean precisas, estén justificadas y reflejen el trabajo real realizado.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{: .note }
> **Módulo opcional**: Esta funcionalidad solo está disponible si tu empresa tiene el módulo de **Imputaciones** (también llamado "Proyectos") activado. Si no lo ves en tu menú, contacta con el Administrador.

---

## ¿Qué son las imputaciones?

Las **imputaciones** son el registro de las horas que un empleado dedica a diferentes proyectos, clientes o tareas. Ejemplos típicos:

- 💼 **Proyectos de clientes**: Horas trabajadas para Cliente A, Cliente B...
- 📋 **Tareas internas**: Formación, reuniones, administración
- 🔧 **Mantenimiento y soporte**

El empleado las registra en su **hoja semanal** (matriz de proyectos × días) desde **"Mi Trabajo" → "Mis imputaciones"**.

Como Manager, tu trabajo es:

- ✅ **Revisar** las horas imputadas por cada empleado
- ✅ **Verificar** que son razonables y coherentes con sus fichajes
- ✅ **Aprobar** si todo está correcto
- ✅ **Rechazar** si hay errores o inconsistencias

{: .important }
> **Importancia de la precisión**: Las imputaciones se usan para facturar a clientes, calcular rentabilidad de proyectos y analizar productividad. Es crucial que sean precisas.

---

## Acceder a las imputaciones pendientes

### Desde el menú

1. Inicia sesión como **Manager** (o Administrador)
2. Ve al menú lateral → **"Validaciones"** → **"Imputaciones Pendientes"**
3. Verás las imputaciones pendientes de tu ámbito

![Menú imputaciones manager](/assets/images/placeholder-menu-imputaciones-manager.png)

### Filtros

- **Trabajador**: filtrar por un empleado concreto (o todos)
- Botón **"Filtrar"**

---

## Listado de imputaciones pendientes

La validación se hace **imputación a imputación** (cada registro de horas de un día y proyecto):

| Columna | Descripción |
|---------|-------------|
| **Acciones** | Aprobar (✓) / Denegar (✗) |
| **Trabajador** | Empleado solicitante |
| **Fecha** | Día imputado |
| **Tiempo usado** | Horas/minutos imputados |
| **Proyecto** | Proyecto (código + nombre) |
| **Observaciones** | Comentarios del empleado |

![Listado imputaciones](/assets/images/placeholder-listado-imputaciones.png)

{: .tip }
> Para ver el contexto completo de un empleado (todas sus horas de la semana por proyecto), consulta su hoja semanal desde **"Equipo" → "Imputaciones equipo"** o el **"Resumen por Proyectos"** del menú Reportes.

---

## Verificaciones antes de aprobar

### 1. ¿Las horas imputadas coinciden con las fichadas?

**Fórmula ideal**: `Horas Imputadas = Horas Fichadas` (en el día)

- ✅ Diferencia de 0h: perfecto
- ⚠️ Diferencias grandes: revisar con el empleado (consulta el resumen diario de fichajes del empleado)

### 2. ¿Los proyectos tienen sentido?

Verifica que el empleado esté **asignado a esos proyectos**:

- ✅ El empleado trabaja en Cliente A → Puede imputar a Cliente A
- ❌ El empleado NO trabaja en Cliente B → No debería imputar ahí

### 3. ¿La distribución es razonable?

- ✅ **Normal**: ~8h al día repartidas entre 1-3 proyectos
- ⚠️ **Sospechoso**: 12h en un día (imposible si fichó 8h)
- ❌ **Erróneo**: horas en días de ausencia aprobada

### 4. ¿Hay observaciones?

Si el empleado añadió observaciones, léelas: pueden explicar desviaciones o cambios de proyecto.

---

## Aprobar o rechazar imputaciones

### Individual

- Pulsa el icono **✓ (Aprobar)** o **✗ (Denegar)** en la fila de cada imputación

### Qué ocurre al aprobar

- El estado pasa a **"Aceptada"**
- La imputación queda **bloqueada**: el empleado ya no puede modificarla (verá el candado 🔒 *"Esta imputación ya está aprobada y no se puede modificar"*)
- Se usará para facturación y reportes

### Qué ocurre al rechazar

- El estado pasa a **"Rechazado"**
- El empleado puede **modificar la imputación** y volver a someterla a validación

{: .important }
> **Comunica las correcciones**: la pantalla de validación no incluye campo de comentarios. Explica al empleado qué debe corregir por los canales habituales (ej: "Faltan 5 horas por imputar el martes", "No puedes imputar al Cliente B").

{: .note }
> **Auto-aceptación**: Si tu empresa tiene activada la auto-aceptación de imputaciones, las imputaciones se crean directamente **aprobadas** y no pasan por validación. Consulta con tu Administrador si es tu caso.

---

## Casos especiales

### Empleado con horas extras

**Situación**: El empleado trabajó 45h pero su jornada es de 40h.

**Acción**: Verifica que las horas extras estaban autorizadas. Si tu empresa usa el [banco de horas extras](/modulos/banco-horas/), esas horas se acumularán automáticamente en la bolsa del empleado.

### Empleado con ausencias

**Situación**: El empleado tuvo 1 día de vacaciones.

**Acción**: No debe haber imputaciones en el día de ausencia aprobada (solo las horas realmente trabajadas).

### Empleado cambió de proyecto a mitad de semana

**Acción**: Verifica que tiene asignación a ambos proyectos y que la distribución coincide con los días reales.

### Empleado olvidó imputar

**Acción**: Recuérdaselo. Establece un plazo claro (ej: "imputaciones antes del lunes siguiente").

---

## Reportes y análisis de imputaciones

- **"Reportes" → "Resumen por Proyectos"**: horas por proyecto y empleado
- **"Equipo" → "Imputaciones equipo"**: calendario de imputaciones del equipo
- **"Empresa" → "Imputaciones empresa"** (Admin): visión completa
- Las tablas incluyen opciones de **exportación** para facturación

---

## Buenas prácticas

✅ **Revisa semanalmente**: no dejes acumular varias semanas
✅ **Establece plazos claros**: ej: "imputaciones antes del lunes a las 10h"
✅ **Sé consistente**: aplica los mismos criterios a todos
✅ **Da feedback**: si alguien imputa mal, enséñale cómo hacerlo bien

---

## Preguntas frecuentes

### ¿Qué pasa si no apruebo las imputaciones?

Quedan en estado "Pendiente" indefinidamente. No se usarán para facturación hasta que las apruebes.

### ¿Puedo aprobar imputaciones parcialmente?

La validación es imputación a imputación: puedes aprobar las correctas y rechazar las erróneas. El empleado corregirá solo las rechazadas.

### ¿Los empleados pueden editar imputaciones aprobadas?

No: una vez aprobadas quedan **cerradas** (candado). Si hay un error, contacta con el Administrador para gestionarlo.

### ¿Puedo aprobar mis propias imputaciones?

Generalmente **no**. Tus imputaciones deberían ser aprobadas por tu superior para evitar conflictos de interés.

---

## ¿Necesitas ayuda?

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Aprobar Vacaciones](/guias-por-rol/manager/aprobar-vacaciones/)
- 👉 [Aprobar Gastos](/guias-por-rol/manager/aprobar-gastos/)
- 👉 [Módulo de Imputaciones](/modulos/imputaciones/)
- 👉 [Guía del Manager](/guias-por-rol/manager/)
