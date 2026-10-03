---
layout: default
title: Consultar Mis Fichajes
parent: Empleado
grand_parent: Guías por Rol
nav_order: 2
---

# Consultar Mis Fichajes
{: .no_toc }

Cómo consultar tu historial de fichajes, entender los estados de cada día y verificar tus horas trabajadas.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Acceder a Mis Fichajes

1. Ve al menú lateral **"Mi Trabajo"**
2. Selecciona **"Mis Fichajes"**

En la parte superior verás los botones de **"Cierre Mensual"** (cuando estás dentro del plazo de cierre) y **"Mis Cierres"**.

---

## Qué verás en la pantalla

### Tarjetas de resumen

En la parte superior encontrarás **4 tarjetas** con las estadísticas del periodo filtrado:

| Tarjeta | Qué muestra |
|---------|-------------|
| **Total días** | Número de días incluidos en el filtro |
| **Horas totales** | Suma de horas entre el primer y último fichaje de cada día |
| **Correcto** | Días con la jornada completa y sin incidencias |
| **Incidencias** | Días con algún problema (fichajes impares, falta de salida...) |

### Filtros

- **Fecha inicio / Fecha fin**: rango a consultar
- **Estado**: Todos los estados / Solo correctos / Solo incidencias
- Botones rápidos: **"Esta semana"**, **"Semana pasada"**, **"Este mes"**, **"Mes pasado"**

### Panel "Resumen semanal"

Debajo de los filtros tienes un resumen de tu semana con navegación **"Semana anterior / Semana actual / Semana siguiente"**.

---

## Entender el estado de cada día

Cada día del listado muestra un estado:

| Estado | Icono | Significado |
|--------|-------|-------------|
| **Correcto** | ✅ check-circle (verde) | Jornada completa, fichajes pares (todas las entradas con su salida) |
| **Incidencia** | ⚠️ alert-circle (ámbar) | Algo no cuadra: fichajes impares (falta salida), fuera de horario... Incluye botón **"Solucionar"** |
| **Ausencia** | 📅 calendar-check | Día con ausencia aprobada (vacaciones, baja...). Muestra el tipo y, si cubre la jornada, la etiqueta "Efectivo" |
| **Sin fichajes** | ❌ x-circle (rojo) | No hay ningún fichaje ese día laborable. Incluye botón **"Solucionar"** |

### Los fichajes del día

Al desplegar un día verás cada fichaje con:

- 🕐 La **hora** registrada
- 🟢🔴 El **tipo** (entrada/salida) según su posición en la jornada
- 🏷️ El **método de acceso** (Web, Móvil, PIN, Terminal...)

### Horas totales vs horas efectivas

- **Horas totales**: desde el primer fichaje hasta el último
- Si fichaste salida a comer y vuelta de comer, el tiempo de pausa resta de las horas efectivas

---

## Solicitar un cambio de fichaje

Junto a cada fichaje verás el **icono del lápiz** ✏️ (*"Solicitar cambio"*) para corregir su hora. Ver la guía completa:

👉 [¿Olvidé Fichar?](/guias-por-rol/empleado/olvide-fichar/)

Si el día está **"Sin fichajes"** o con **"Incidencia"**, usa el botón **"Solucionar"**.

---

## Estados de una solicitud de cambio

Cuando solicitas un cambio de hora, la solicitud pasa por estos estados:

| Estado | Qué significa |
|--------|---------------|
| **Pendiente** | Esperando que un Validador o Administrador la revise. El fichaje mantiene su hora original y no puedes solicitar otro cambio sobre él |
| **Aceptada** | La hora del fichaje se ha actualizado con la solicitada |
| **Rechazada** | La hora original se mantiene. Puedes enviar una nueva solicitud mejor justificada |

Toda la trazabilidad del cambio (quién lo aprobó y cuándo) queda registrada en el sistema y es visible en los reportes de tu empresa.

---

## Cierre mensual

Desde esta pantalla accedes al **Cierre Mensual** cuando estás en plazo: confirma tus fichajes del mes anterior y firma digitalmente.

👉 [Ver guía: Cierre Mensual](/guias-por-rol/empleado/cierres-mensuales/)

---

## Preguntas frecuentes

### ¿Por qué un día aparece con incidencia si fichué?

Las causas más habituales:

- **Fichajes impares**: fichaste la entrada pero no la salida (o viceversa)
- **Fuera de horario**: el fichaje está fuera de la ventana flexible de tu horario
- **Falta una pausa**: tu horario requiere fichar la salida y vuelta de comer

Pulsa **"Solucionar"** para corregirlo.

### ¿Puedo exportar mis fichajes?

Sí, la tabla de fichajes incluye las opciones de exportación de DataTables (impresión y exportación a los formatos disponibles).

### ¿Quién puede ver mis fichajes?

- **Tú**: todos los tuyos
- **Tu Manager**: vía reportes de su equipo
- **Validadores y Administradores**: según su ámbito
- **SuperAdmin**: todas las empresas

### ¿Puedo ver la ubicación GPS de cada fichaje?

La ubicación se registra en el sistema cuando tu empresa tiene el control por GPS activado, y se usa para validar que fichas dentro del área autorizada. La vista de empleado muestra la hora y el método de acceso de cada fichaje.

### ¿Por qué no aparece el lápiz en un fichaje?

Porque ya tiene una **solicitud de cambio pendiente**. Espera a que se resuelva.

---

## ¿Necesitas ayuda?

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [¿Olvidé Fichar?](/guias-por-rol/empleado/olvide-fichar/)
- 👉 [Cierre Mensual](/guias-por-rol/empleado/cierres-mensuales/)
- 👉 [Primer Fichaje](/primeros-pasos/primer-fichaje/)
- 👉 [Módulo de Fichajes](/modulos/fichajes/)
