---
layout: default
title: Imputaciones
nav_order: 9
has_children: true
permalink: /modulos/imputaciones/
---

# Módulo de Imputaciones
{: .no_toc }

Gestiona la imputación de horas a proyectos y clientes. Controla la rentabilidad y factura según el tiempo real trabajado en cada proyecto.
{: .fs-6 .fw-300 }

{: .note }
> **Módulo opcional**: Solo disponible si tu empresa tiene el módulo de **Imputaciones** activado.

---

## ¿Qué son las imputaciones?

Registro de las horas que cada empleado dedica a diferentes proyectos, clientes o tareas.

### Funcionalidades

- 📊 **Hoja semanal**: Matriz de proyectos × días para imputar el tiempo (formatos tipo "8h 30m", "8:30" o "8,5")
- ✅ **Aprobación**: Los Managers validan las imputaciones desde "Validaciones"
- 🔒 **Bloqueo**: Las imputaciones aprobadas quedan cerradas y no se pueden modificar
- 💰 **Facturación**: Horas facturables a clientes
- 📈 **Rentabilidad**: Análisis coste vs ingreso
- 🎯 **Proyectos**: Crear y asignar proyectos (Configuraciones → Proyectos)
- ⚠️ **Aviso de umbral diario**: Alerta si el total del día supera el umbral recomendado (configurable)

---

## Flujo semanal

**Empleado:**
1. En su **hoja semanal**, imputa las horas por proyecto y día (puede copiar la semana anterior)
2. Guarda la semana (hay borrador automático local)
3. Las imputaciones quedan pendientes de validación

**Manager:**
1. Revisa las imputaciones en **"Validaciones" → "Imputaciones Pendientes"**
2. Verifica que las horas imputadas son coherentes con los fichajes
3. Aprueba o rechaza imputación a imputación
4. Las aprobadas quedan **bloqueadas**; las rechazadas el empleado puede corregirlas

{: .note }
> Si tu empresa tiene activada la **auto-aceptación**, las imputaciones se crean directamente aprobadas sin pasar por validación.

---

## Tipos de proyectos

- **Facturables**: Proyectos de clientes (se facturan)
- **Internos**: Tareas de la empresa (no se facturan)
- **Formación**: Tiempo dedicado a aprender
- **Reuniones**: Meetings generales

---

## Reportes clave

- **Por proyecto**: Total de horas dedicadas
- **Por empleado**: Distribución del tiempo
- **Por cliente**: Horas facturables acumuladas
- **Rentabilidad**: Coste empleado vs facturación

---

## Configuración

**Crear proyecto:**
1. Nombre y código
2. Cliente asociado
3. Empleados asignados
4. Tarifa horaria (para facturación)
5. Presupuesto de horas

---

## Guías relacionadas

- 👉 [Aprobar Imputaciones (Manager)](/guias-por-rol/manager/aprobar-imputaciones/)
