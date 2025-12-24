---
layout: default
title: Aprobar Imputaciones
parent: Guía del Manager
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
> **Módulo opcional**: Esta funcionalidad solo está disponible si tu empresa tiene el módulo de **Imputaciones** (también llamado "Proyectos") activado. Si no lo ves en tu menú, contacta con el Administrador o SuperAdmin.

---

## ¿Qué son las imputaciones?

Las **imputaciones** son el registro de las horas que un empleado dedica a diferentes proyectos, clientes o tareas. Ejemplos típicos:

- 💼 **Proyectos de clientes**: Horas trabajadas para Cliente A, Cliente B, etc.
- 📋 **Tareas internas**: Formación, reuniones, administración
- 🔧 **Mantenimiento**: Tareas de soporte o mantenimiento de sistemas
- 📊 **Desarrollo**: Horas en desarrollo de nuevas funcionalidades

Como Manager, tu trabajo es:

- ✅ **Revisar** las horas imputadas por cada empleado
- ✅ **Verificar** que las horas son razonables y coherentes
- ✅ **Comprobar** que suman correctamente
- ✅ **Aprobar** si todo está correcto
- ✅ **Rechazar** si hay errores o inconsistencias

{: .important }
> **Importancia de la precisión**: Las imputaciones se usan para facturar a clientes, calcular rentabilidad de proyectos y analizar productividad. Es crucial que sean precisas.

---

## Acceder a las imputaciones pendientes

### Opción 1: Desde Notificaciones

Cuando un empleado imputa horas, recibirás una **notificación por email** (configurable):

```
Asunto: Imputaciones pendientes de validar - Semana 3/2025

Tienes 5 empleados con imputaciones pendientes de aprobar:
- Juan Pérez: 40h imputadas
- María García: 38h imputadas
- ...

Haz clic aquí para revisar las imputaciones.
```

### Opción 2: Desde el menú

1. Inicia sesión como **Manager**
2. Ve al menú lateral → **"Mis Imputaciones"** o **"Proyectos"**
3. Pestaña **"Pendientes de aprobar"**
4. Verás todas las imputaciones de tu(s) departamento(s)

![Menú imputaciones manager](/assets/images/placeholder-menu-imputaciones-manager.png)

### Opción 3: Desde el Dashboard

En tu dashboard verás:
- Número de empleados con imputaciones pendientes
- Total de horas pendientes de validar
- Acceso directo al listado

---

## Listado de imputaciones pendientes

Generalmente se revisan **por semana completa**:

### Vista por empleado

| Columna | Descripción |
|---------|-------------|
| **Empleado** | Nombre del empleado + departamento |
| **Semana** | Semana de trabajo (ej: Semana 3, del 15 al 21 ene) |
| **Horas Trabajadas** | Total de horas fichadas esa semana |
| **Horas Imputadas** | Total de horas que ha imputado |
| **Diferencia** | Desviación entre fichadas e imputadas |
| **Proyectos** | Número de proyectos a los que imputó |
| **Estado** | Pendiente, Aprobado, Rechazado |
| **Acciones** | Botones para revisar/aprobar/rechazar |

![Listado imputaciones](/assets/images/placeholder-listado-imputaciones.png)

### Filtros disponibles

- **Semana**: Filtrar por semana específica
- **Empleado**: Ver solo un empleado
- **Estado**: Pendientes, Aprobadas, Rechazadas
- **Proyecto**: Ver solo imputaciones a un proyecto específico

{: .tip }
> **Consejo**: Revisa semanalmente (cada lunes) las imputaciones de la semana anterior para no acumular trabajo.

---

## Revisar las imputaciones de un empleado

### Paso 1: Abrir el detalle

1. Haz clic en **"Ver Detalle"** o en el nombre del empleado
2. Se abrirá una vista con todas las imputaciones de esa semana

### Información que verás

**Resumen de la semana:**
- 👤 **Empleado**: Nombre completo, departamento
- 📅 **Semana**: Rango de fechas (lunes a domingo)
- ⏰ **Horas fichadas**: Total de horas trabajadas según fichajes
- 📊 **Horas imputadas**: Total de horas registradas en proyectos
- ⚖️ **Diferencia**: Desviación (debería ser 0 o muy pequeña)

**Desglose por proyecto:**

| Proyecto | Lunes | Martes | Miércoles | Jueves | Viernes | Total |
|----------|-------|--------|-----------|--------|---------|-------|
| Cliente A | 4h | 6h | 8h | 5h | 3h | **26h** |
| Cliente B | 2h | 2h | 0h | 3h | 4h | **11h** |
| Interno | 2h | 0h | 0h | 0h | 1h | **3h** |
| **Total** | **8h** | **8h** | **8h** | **8h** | **8h** | **40h** |

![Detalle imputaciones](/assets/images/placeholder-detalle-imputaciones.png)

{: .note }
> **Vista matricial**: Verás una tabla con los días de la semana en columnas y los proyectos en filas, mostrando las horas dedicadas a cada combinación.

---

## Verificaciones antes de aprobar

Antes de aprobar, comprueba:

### 1. ¿Las horas imputadas coinciden con las fichadas?

**Fórmula ideal**: `Horas Imputadas = Horas Fichadas`

- ✅ **Diferencia de 0h**: Perfecto
- ✅ **Diferencia de ±0,5h**: Aceptable (redondeos)
- ⚠️ **Diferencia de ±2h**: Revisar con el empleado
- ❌ **Diferencia de ±5h o más**: Rechazar y pedir corrección

**Ejemplo:**
- Horas fichadas: 40h
- Horas imputadas: 40h
- Diferencia: 0h → ✅ **Aprobar**

**Ejemplo con problema:**
- Horas fichadas: 40h
- Horas imputadas: 30h
- Diferencia: -10h → ❌ **Rechazar** (faltan 10 horas por imputar)

### 2. ¿Los proyectos tienen sentido?

Verifica que el empleado esté **asignado a esos proyectos**:

- ✅ El empleado trabaja en Cliente A → Puede imputar a Cliente A
- ❌ El empleado NO trabaja en Cliente B → No debería imputar ahí

### 3. ¿La distribución de horas es razonable?

Comprueba que no haya días con distribuciones extrañas:

- ✅ **Distribución normal**: 8h en un día repartidas entre 2-3 proyectos
- ⚠️ **Distribución sospechosa**: 12h en un día (imposible si fichó 8h)
- ❌ **Distribución errónea**: 0h en todos los proyectos varios días

### 4. ¿Hay comentarios o notas?

Si el empleado añadió observaciones, léelas:

- Pueden explicar desviaciones
- Pueden justificar horas extras
- Pueden aclarar cambios de proyecto

---

## Aprobar imputaciones

Si todo está correcto:

### Paso 1: Hacer clic en "Aprobar"

1. En la vista de imputaciones del empleado, haz clic en **"Aprobar Semana"**
2. (Opcional) Añade un comentario
3. Haz clic en **"Confirmar"**

![Aprobar imputaciones](/assets/images/placeholder-aprobar-imputaciones.png)

### Paso 2: Confirmación

- El estado cambiará a **"Aprobado"** (badge verde)
- El empleado recibirá una **notificación** de aprobación
- Las horas quedarán **cerradas** y no se podrán modificar
- Las imputaciones se usarán para facturación y reportes

{: .tip }
> **Comentario positivo**: "Aprobado. Gracias por imputar correctamente toda la semana."

---

## Rechazar imputaciones

Si hay errores o inconsistencias:

### Paso 1: Hacer clic en "Rechazar"

1. En la vista de imputaciones, haz clic en **"Rechazar Semana"**
2. **OBLIGATORIO**: Añade un comentario explicando qué está mal
3. Haz clic en **"Confirmar"**

![Rechazar imputaciones](/assets/images/placeholder-rechazar-imputaciones.png)

### Paso 2: Justificar el rechazo

**Ejemplos de comentarios apropiados:**

✅ **Buenos comentarios:**
- "Faltan 5 horas por imputar. Total imputado: 35h, pero fichaste 40h. Por favor, revisa."
- "El martes imputaste 12h pero solo fichaste 8h. Corrige las horas del martes."
- "No puedes imputar al Cliente B, no estás asignado a ese proyecto. Cambia a Cliente A."
- "El viernes no fichaste pero imputaste 8h. Revisa ese día."

❌ **Malos comentarios (evitar):**
- "Mal" (sin explicación)
- "No cuadra" (poco específico)
- "Revisa tú mismo" (poco profesional)

### Paso 3: Confirmación

- El estado cambiará a **"Rechazado"** (badge rojo)
- El empleado recibirá una **notificación** con tu comentario
- El empleado deberá **corregir y volver a enviar**
- Las horas permanecen editables para el empleado

---

## Solicitar correcciones

Si solo necesitas pequeñas correcciones:

### Opción: Comentar sin decidir aún

1. Usa el campo **"Añadir comentario"**
2. Explica qué debe corregir
3. No apruebes ni rechaces aún, espera la corrección
4. El empleado recibirá notificación y podrá editar

**Ejemplo de comentario:**
"El jueves faltan 2 horas por imputar. Por favor, revisa ese día y vuelve a enviar."

---

## Casos especiales

### Empleado con horas extras

**Situación**: El empleado trabajó 45h pero su jornada es de 40h.

**Acción:**
1. Verifica que las horas extras estaban **autorizadas**
2. Si sí, aprueba las 45h imputadas
3. Comenta: "Aprobado incluyendo 5h extras autorizadas."
4. Si no, rechaza las horas extras
5. Comenta: "Solo puedo aprobar las 40h contratadas. Las 5h extras no fueron autorizadas."

### Empleado con ausencias

**Situación**: El empleado tuvo 1 día de vacaciones, solo trabajó 32h.

**Acción:**
1. Verifica que solo imputó las horas realmente trabajadas (32h)
2. Aprueba si las 32h están correctamente distribuidas
3. No debe imputar las 8h del día de vacaciones

### Empleado cambió de proyecto a mitad de semana

**Situación**: Trabajó 3 días en Cliente A y 2 días en Cliente B.

**Acción:**
1. Verifica que tiene asignación a ambos proyectos
2. Comprueba que la distribución coincida con los días reales
3. Si todo cuadra, aprueba

### Empleado olvidó imputar

**Situación**: El empleado no ha enviado sus imputaciones de la semana.

**Acción:**
1. Envíale un recordatorio por email o chat
2. Si no responde en 2-3 días, contacta directamente
3. No puedes aprobar si no ha imputado nada

{: .warning }
> **Deadline**: Establece un plazo claro (ej: "Imputaciones deben enviarse antes del lunes siguiente").

### Diferencia pequeña por redondeos

**Situación**: Horas fichadas: 40h, Horas imputadas: 39,5h (diferencia de 0,5h).

**Acción:**
1. Si es menos de 1 hora de diferencia, es aceptable
2. Aprueba con comentario: "Aprobado. Diferencia mínima por redondeo."

---

## Reportes y análisis de imputaciones

### Consultar imputaciones aprobadas

1. Ve a **"Imputaciones"** → **"Reportes"**
2. Filtra por período (semana, mes, trimestre)
3. Filtra por proyecto o empleado

### Estadísticas útiles

- **Horas por proyecto**: Cuántas horas se dedicaron a cada cliente/proyecto
- **Horas por empleado**: Quién trabajó más en cada proyecto
- **Rentabilidad**: Si las horas facturables cubren los costes
- **Tendencias**: ¿Aumentan o disminuyen las horas en cada proyecto?

### Exportar para facturación

Al final de mes:
1. Exporta las **horas aprobadas por proyecto**
2. Envía el reporte al departamento de Facturación
3. Se usará para facturar a los clientes según las horas trabajadas

---

## Buenas prácticas

### Para Managers

✅ **Revisa semanalmente**: No dejes acumular varias semanas
✅ **Establece plazos claros**: Ej: "Imputaciones antes del lunes a las 10h"
✅ **Sé consistente**: Aplica los mismos criterios a todos
✅ **Comunica expectativas**: Explica a tu equipo cómo deben imputar
✅ **Da feedback**: Si alguien imputa mal, enséñale cómo hacerlo bien

### Para comunicar al equipo

💬 **Mensaje recomendado:**

```
Hola equipo,

Recordatorio sobre imputaciones:
- Imputad todas las horas trabajadas cada día
- Verificad que el total coincida con vuestras horas fichadas
- Enviadlas antes del lunes a las 10h de la semana siguiente
- Si tenéis dudas sobre a qué proyecto imputar, preguntadme

Gracias por vuestra colaboración.
```

---

## Preguntas frecuentes

### ¿Qué pasa si no apruebo las imputaciones?

Quedan en estado "Pendiente" indefinidamente. No se podrán usar para facturación hasta que las apruebes.

### ¿Puedo aprobar imputaciones parcialmente?

No, se aprueban o rechazan por **semana completa**. Si un día está mal, rechaza toda la semana y pide corrección.

### ¿Los empleados pueden editar imputaciones aprobadas?

No, una vez aprobadas están **cerradas**. Si hay un error, debes **cancelar la aprobación** primero (si es posible según configuración).

### ¿Qué hago si un empleado imputa sistemáticamente mal?

1. Documenta los errores
2. Agenda reunión individual
3. Explica cómo debe imputar correctamente
4. Monitorea las siguientes semanas
5. Si no mejora, eleva a RRHH

### ¿Puedo aprobar mis propias imputaciones?

Generalmente **no**. Tus imputaciones deberían ser aprobadas por tu superior para evitar conflictos de interés.

### ¿Las horas imputadas afectan a la nómina?

Depende de cómo esté configurado en tu empresa. Normalmente las imputaciones son para **facturación a clientes**, no para calcular el salario (eso va por fichajes). Pero en algunos casos sí pueden afectar (ej: bonus por productividad).

---

## ¿Necesitas ayuda?

Si tienes dudas sobre cómo aprobar imputaciones:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)
- 👤 Contacta con el Administrador de tu empresa

---

## Guías relacionadas

- 👉 [Aprobar Vacaciones](/guias-por-rol/manager/aprobar-vacaciones/)
- 👉 [Aprobar Cambios de Fichaje](/guias-por-rol/manager/aprobar-cambios-fichaje/)
- 👉 [Aprobar Gastos](/guias-por-rol/manager/aprobar-gastos/)
- 👉 [Reporte Mensual](/reportes/reporte-mensual/)
- 👉 [Guía del Manager](/guias-por-rol/manager/)