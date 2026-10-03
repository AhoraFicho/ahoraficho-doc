---
layout: default
title: Asignar Horarios
parent: Administrador
grand_parent: Guías por Rol
nav_order: 4
---

# Asignar Horarios
{: .no_toc }

Cómo asignar horarios a empleados de forma individual o masiva, con cambios permanentes o temporales (con fecha de inicio y fin).
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Antes de empezar

### Prerequisitos

Antes de asignar horarios, asegúrate de:

- ✅ Tener [horarios creados](/guias-por-rol/administrador/crear-horarios/)
- ✅ Tener empleados dados de alta
- ✅ Conocer qué horario corresponde a cada empleado

---

## Métodos de asignación

Existen **dos formas** de asignar horarios:

### 1. Asignación individual
Al dar de alta o editar un empleado (cambio inmediato).

### 2. Asignación masiva
Asignar el mismo horario a múltiples empleados a la vez, de forma **permanente** o **temporal** (con fecha de inicio y fecha de fin y vuelta automática al horario habitual).

---

## Asignación Individual

### Durante el alta de empleado

Cuando [das de alta un empleado](/guias-por-rol/administrador/dar-alta-empleados/):

1. En el formulario de alta, sección **"Configuración Laboral"**
2. Campo **"Horario"**
3. Selecciona el horario del desplegable
4. Guarda el empleado

### Para empleado existente

1. Ve a **"Configuraciones"** → **"Trabajadores"**
2. Busca el empleado
3. Haz clic en **"Editar"** ✏️
4. Cambia el horario en el desplegable
5. Haz clic en **"Guardar"**

{: .note }
> Este método cambia el horario **inmediatamente**. Para cambios programados o temporales, usa la asignación masiva.

---

## Asignación Masiva de Horarios

### Cuándo usar asignación masiva

- 📅 Cambio de horario de verano (muchos empleados)
- 🔄 Horarios cambiantes por periodos (mañana/tarde/noche por semanas o meses)
- 🏢 Nuevo departamento con mismo horario
- 📊 Ajustes por departamento

### Acceder

1. Ve a **"Configuraciones"** → **"Horarios"**
2. Pulsa el botón de **"Asignación Masiva de Horarios"**

La pantalla tiene **dos pestañas**: **"Cambio Permanente"** y **"Cambio Temporal (Verano/Invierno)"**.

---

## Pestaña: Cambio Permanente

El empleado queda con el nuevo horario de forma indefinida a partir de la fecha indicada.

### Pasos

1. **Seleccionar Horario**: elige el horario a asignar
2. **Fecha de Inicio**:
   - Si seleccionas hoy o una fecha pasada, se aplica **inmediatamente**
   - Si seleccionas una fecha futura, el cambio queda **programado**
3. **Descripción (opcional)**: documenta el motivo (ej: "Cambio de horario por nueva jornada laboral")
4. **Seleccionar Empleados**:
   - Filtra por departamento con el desplegable **"-- Todos los Departamentos --"**
   - Usa **"Seleccionar Todos"** / **"Deseleccionar Todos"**
   - Verás la lista con el **horario actual** de cada empleado antes de aplicar
5. Pulsa **"Aplicar Cambios"**

### Resultado

- Fecha actual o pasada → mensaje *"Horario asignado correctamente a X empleado(s)"*
- Fecha futura → mensaje *"Cambio programado para X empleado(s) el [fecha]"*

---

## Pestaña: Cambio Temporal (Verano/Invierno)

Programa un cambio de horario **con fecha de inicio y fecha de fin**, con **vuelta automática** al horario actual al terminar. Es la herramienta ideal para horarios estacionales o rotaciones de horario por periodos.

### Pasos

1. **Horario Temporal**: elige el horario que se aplicará durante el periodo
2. **Fecha Inicio**: primer día del horario temporal
3. **Fecha Fin**: último día (la fecha de fin debe ser posterior a la de inicio)
4. **Descripción (opcional)**: ej: "Horario de verano 2025"
5. **Seleccionar Empleados**: igual que en el cambio permanente
6. Pulsa **"Programar Cambio Temporal"**

### Resultado

Mensaje: *"Cambio temporal programado para X empleado(s): desde [inicio] hasta [fin]"*

{: .important }
> **Vuelta automática**: Al llegar la fecha de fin, los empleados vuelven solos a su horario anterior. No hace falta programar la vuelta manualmente.

{: .tip }
> **Sustituye a los turnos rotativos**: Para equipos con horarios que cambian por semanas o meses (mañanas un mes, tardes al siguiente), programa cambios temporales encadenados con sus fechas de inicio y fin.

---

## Ver cambios programados

### Cambios pendientes

Para ver cambios de horario programados que aún no se han aplicado:

1. Ve a **"Configuraciones"** → **"Horarios"**
2. Entra en **"Cambios de Horario Programados"**

Verás una tabla:

| Empleado | Horario | Fecha Aplicación | Descripción | Creado Por | Estado | Acciones |
|:---------|:--------|:-----------------|:------------|:-----------|:-------|:---------|
| Juan Pérez | Intensivo Verano | 01/06/2026 | Horario de verano | Admin | Pendiente | Cancelar |

### Cancelar cambio programado

1. Localiza el cambio en "Cambios de Horario Programados"
2. Haz clic en **"Cancelar Cambio"**
3. Confirma la cancelación

{: .warning }
> Solo puedes cancelar cambios **pendientes**. Los ya aplicados no se deshacen (pero puedes crear otro cambio).

---

## Historial de cambios de horario

### Historial de un empleado

1. Ve a **"Configuraciones"** → **"Trabajadores"**
2. Abre el **histórico de horarios** del empleado

Verás el **horario actual** y todos sus horarios anteriores con:

| Horario | Fecha Inicio | Fecha Fin | Estado | Descripción | Creado Por |
|:--------|:-------------|:----------|:-------|:------------|:-----------|
| Intensivo Verano | 01/06/2026 | 30/09/2026 | Vigente | Horario de verano | Admin |
| Jornada Partida | 01/01/2026 | — | Anterior | — | Admin |

---

## Casos de uso comunes

### Caso 1: Horario de verano con vuelta automática

**Situación:** 50 empleados pasan a jornada intensiva del 1 de junio al 30 de septiembre.

1. Asignación masiva → pestaña **"Cambio Temporal"**
2. Horario temporal: "Jornada Intensiva Verano"
3. Fecha Inicio: 01/06 · Fecha Fin: 30/09
4. Selecciona los 50 empleados
5. Programar → el 1 de octubre vuelven solos a su horario habitual

### Caso 2: Rotación de horarios por meses (mañana/tarde)

**Situación:** Un equipo alterna un mes en mañanas y otro en tardes.

1. Programa un cambio temporal a "Horario de Mañanas" (01/01 → 31/01)
2. Programa otro cambio temporal a "Horario de Tardes" (01/02 → 28/02)
3. Repite según el plan de rotación

### Caso 3: Nuevo departamento completo

1. Crea el horario "Atención Cliente 10-19h"
2. Asignación masiva (Cambio Permanente)
3. Filtra por departamento: "Atención al Cliente"
4. Selecciona todos y **"Aplicar Cambios"**

### Caso 4: Empleados de campo con horario flexible

1. Crea un horario "Flexible Comerciales" (Lun-Vie 00:00-23:59, flexibilidad total)
2. Asignación masiva permanente a los comerciales

---

## Notificaciones a empleados

La asignación de horarios **no envía por sí misma un aviso** a los empleados. Ten en cuenta:

- El botón de fichaje del empleado se adapta automáticamente a su horario vigente
- Si el horario tiene configurados los **minutos de notificación de inicio y fin**, el empleado recibirá **recordatorios de entrada y salida** (email y push) según esos tiempos
- Se recomienda comunicar los cambios de horario por los canales habituales de la empresa

---

## Verificar asignaciones

Después de asignar horarios:

1. Ve al listado de **"Trabajadores"**
2. Verifica la columna de horario
3. Comprueba que todos tienen el horario correcto

---

## Solución de problemas

### No veo la opción de asignación masiva

- Verifica que tienes permisos de Administrador

### El cambio programado no se aplicó

1. ¿La fecha ya pasó?
2. ¿El cambio sigue en "Pendiente"?
3. Si sigue pendiente, cancélalo y vuelve a crearlo; si persiste, contacta con soporte

### Empleado no aparece en la selección

- Comprueba que el empleado está **activo** (no desactivado)
- Quita los filtros y busca por nombre

---

## Preguntas frecuentes

### ¿Puedo asignar diferentes horarios a empleados del mismo departamento?

Sí, cada empleado puede tener un horario diferente independientemente de su departamento.

### ¿Qué pasa si cambio el horario de un empleado a mitad de mes?

El sistema calculará cada día con el horario vigente en esa fecha, y los reportes lo reflejarán correctamente.

### ¿Puedo ver qué horario tenía un empleado en una fecha pasada?

Sí, en el **histórico de horarios** del empleado puedes ver todos sus horarios con fechas de inicio y fin.

### ¿Los cambios de horario afectan a fichajes anteriores?

No, los fichajes pasados se mantienen con el horario que tenían en ese momento. Solo afecta a fichajes futuros.

### ¿Puedo programar múltiples cambios de horario?

Sí, puedes programar varios cambios permanentes y temporales para diferentes fechas.

---

## ¿Necesitas ayuda?

Si tienes problemas al asignar horarios:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Crear Horarios](/guias-por-rol/administrador/crear-horarios/)
- 👉 [Dar de alta empleados](/guias-por-rol/administrador/dar-alta-empleados/)
