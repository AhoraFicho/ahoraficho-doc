---
layout: default
title: Banco de horas extras
nav_order: 10
has_children: false
permalink: /modulos/banco-horas/
---

# Módulo de Banco de horas extras
{: .no_toc }

Los empleados acumulan las horas trabajadas de más y pueden compensarlas con días libres o compensación económica.
{: .fs-6 .fw-300 }

{: .note }
> **Módulo opcional**: Solo disponible si tu empresa tiene el módulo de **Banco de horas extras** activado.

---

## ¿Qué es el banco de horas extras?

El **banco de horas extras** (también "bolsa de horas") registra automáticamente las horas que cada empleado trabaja por encima de su horario (y también los débitos, si se trabaja de menos). Esas horas se acumulan con una **caducidad** y se pueden compensar de dos formas:

- 🗓️ **Día compensatorio**: tomarte un día (o unas horas) libres gastando horas del banco
- 💶 **Compensación económica**: solicitar el pago de las horas acumuladas

Según la configuración de la empresa, puede permitir ambas opciones, solo días o solo compensación económica.

---

## Para el empleado: "Mi bolsa de horas"

Ve a **"Mi Trabajo" → "Mi bolsa de horas"**. Verás:

### Tu saldo

- **Acumuladas**: horas extras registradas
- **Disfrutadas**: horas ya compensadas con días
- **Pagadas**: horas ya compensadas económicamente
- **Horas debidas**: saldo negativo (horas debidas a la empresa)
- **Caducidad**: fecha límite de las horas acumuladas
- **Multiplicador de compensación** (si aplica): el coste en horas de un día compensatorio puede ser mayor que 1 (ej: x1,5)

### Solicitar día compensatorio

1. Pulsa **"Solicitar día compensatorio"**
2. Indica la **fecha** del día libre (fecha futura)
3. Indica **cuántas horas quieres usar** (0 = día completo de tu horario)
4. Verás el **coste del día** según el multiplicador
5. Añade un motivo (opcional) y envía

Validaciones: no puedes solicitarlo sobre un día con ausencia ya registrada ni en un **festivo**, y necesitas saldo suficiente.

{: .important }
> La solicitud crea una ausencia de tipo **"Compensatorio"** que sigue el **flujo normal de aprobación** de ausencias: la aprueba tu responsable. Al aprobarse, las horas se descuentan del banco automáticamente.

### Solicitar compensación económica

1. Pulsa **"Solicitar compensación económica"**
2. Indica los **minutos a compensar** (máximo: tu saldo disponible)
3. Envía la solicitud

La solicitud queda **pendiente** y será aprobada o rechazada por un **Administrador**. Las horas solo se descuentan cuando se aprueba. Verás el estado (y el motivo del rechazo, si lo hay) en la sección **"Mis solicitudes económicas"**.

### Historial de movimientos

Cada movimiento del banco (acumulación, compensación, pago, ajuste) queda registrado con fecha, tipo, minutos y observaciones.

---

## Para el Manager/Administrador: "Bolsa horas extras"

Menú **"Reportes" → "Bolsa horas extras"** (Administradores y SuperAdmin):

- **Tarjetas de equipo**: horas disponibles, horas debidas, saldo neto y solicitudes económicas pendientes
- **Solicitudes económicas**: aprobar (✓) o rechazar (✗) con motivo
- **Tabla por empleado**: acumuladas / disfrutadas / pagadas / debidas / saldo neto / caducidad
- **Acciones por empleado**: crear día compensatorio, **reconciliar** el saldo con los fichajes reales, **marcar horas como pagadas** (parcial o totalmente)
- **Registro manual**: añadir ajustes manuales de minutos
- Filtros por departamento, trabajador y año

---

## Cómo se acumulan las horas

- El sistema compara cada día los **fichajes reales** con el **horario** del empleado
- Las horas por encima del horario se acumulan como horas extras (con el multiplicador y umbrales configurados)
- Los cambios de fichaje aprobados **recalculan** el banco del día afectado
- Crear, editar o **eliminar fichajes desde la gestión de fichajes** también recalcula automáticamente la bolsa del día, de forma que la bolsa nunca se queda descuadrada
- La acumulación puede incluir ajustes automáticos (reconciliación) para corregir desviaciones

---

## Corregir movimientos: anular o eliminar

Desde el detalle de una bolsa (**"Reportes" → "Bolsa horas extras" → detalle de un trabajador**), cada movimiento muestra acciones en la primera columna:

### Anular movimiento (Administradores y SuperAdmin)

- El botón de **anular** (flecha de vuelta) crea un movimiento inverso que compensa el original y pide indicar un **motivo**
- El movimiento original pasa a estado **"Anulada"** y deja de contar, pero se conserva para auditoría
- Es la opción recomendada para corregir pagos, consumos o acumulaciones dejando traza

### Eliminar movimiento (solo SuperAdmin autorizado)

- El botón de **eliminar** (papelera) borra el movimiento **definitivamente**, junto con sus anulaciones asociadas si las tiene, y recalcula los totales de la bolsa al momento
- Pide indicar un **motivo**, que queda registrado en la auditoría
- No está disponible para movimientos de **día compensatorio** (se corrigen eliminando la ausencia correspondiente) ni para movimientos que ya tienen consumos o pagos vinculados
- Úsalo solo para limpiar registros erróneos sin recorrido (por ejemplo, acumulaciones generadas por fichajes que luego se borraron)

{: .warning }
> Eliminar un movimiento **no se puede deshacer**. Si necesitas conservar la traza del error, usa **anular** en su lugar.

### Reconciliar

- El botón **"Reconciliar"** comprueba que los totales de la bolsa coinciden con sus movimientos y corrige cualquier discrepancia
- Si el problema son acumulaciones ligadas a fichajes ya eliminados, gestiona los fichajes o elimina el movimiento directamente: reconciliar solo aritmética de totales, no recalcula días

---

## Preguntas frecuentes

### ¿Las horas extras caducan?

Sí, cada bolsa tiene fecha de caducidad (visible en tu saldo). Úsalas antes de que venzan.

### ¿Un día compensatorio cuesta lo mismo que las horas que tengo?

Depende del **multiplicador** configurado por tu empresa (ej: con x1,5, un día de 8h cuesta 12h de banco). El coste exacto se muestra antes de enviar la solicitud.

### ¿Quién aprueba cada tipo de solicitud?

- **Días compensatorios**: tu responsable, por el flujo normal de ausencias
- **Compensación económica**: un Administrador

### ¿Puedo solicitar medio día compensatorio?

Sí: indica las horas concretas a usar (0 = día completo). El sistema validará que te alcancen para el horario del día elegido.

### Se eliminaron fichajes de un día y la bolsa quedó con horas de más, ¿qué hago?

Desde la versión actual, crear, editar o eliminar fichajes desde la gestión de fichajes recalcula la bolsa del día automáticamente. Si tienes movimientos antiguos que quedaron huérfanos por fichajes ya borrados, un **SuperAdmin** puede **eliminarlos directamente** desde el detalle de la bolsa (o anularlos), y la bolsa quedará cuadrada.

---

## ¿Necesitas ayuda?

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Solicitar Vacaciones (tipo Compensatorio)](/guias-por-rol/empleado/solicitar-vacaciones/)
- 👉 [Módulo de Fichajes](/modulos/fichajes/)
- 👉 [Reporte de Impuntualidades](/reportes/reporte-impuntualidades/)
