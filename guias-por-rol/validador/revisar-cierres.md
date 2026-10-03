---
layout: default
title: Revisar Cierres Mensuales
parent: Validador
grand_parent: Guías por Rol
nav_order: 2
---

# Revisar Cierres Mensuales
{: .no_toc }

Consulta el estado de los cierres mensuales de los empleados: quién ha cerrado y firmado su mes, y qué hacer cuando hay que reabrir un cierre.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué es el cierre mensual?

El **cierre mensual** permite al empleado revisar y confirmar todos sus fichajes del mes anterior y **firmar digitalmente** su registro de jornada. Al cerrar:

- Cada fichaje queda **confirmado** (con fecha de confirmación)
- Se genera un **registro de cierre** con la firma del trabajador
- El mes queda **bloqueado**: el empleado no puede solicitar cambios de fichaje de ese mes
- El trabajador puede descargar un **PDF** del cierre con sus fichajes y su firma

Ver la guía completa del proceso desde el punto de vista del empleado: [Cierre Mensual (empleado)](/guias-por-rol/empleado/cierres-mensuales/).

---

## Consultar los cierres

1. Inicia sesión con tu usuario **Validador** (o Administrador)
2. Ve al menú lateral → **"Validaciones"** → **"Cierres Mensuales"**
3. Verás el listado de cierres de los empleados de tu ámbito de validación

### Columnas del listado

| Columna | Descripción |
|---------|-------------|
| **Acciones** | Descargar PDF / Reabrir (solo Admin) |
| **Empleado** | Nombre del trabajador |
| **Mes** | Mes cerrado |
| **Fecha de cierre** | Cuándo se realizó el cierre |
| **Estado** | 🟢 **Cerrado** / 🟡 **Reabierto** |

### Descargar el PDF del cierre

Pulsa el icono de descarga en la fila del cierre: se genera un PDF con los datos del empleado, el periodo, el detalle de fichajes por día, festivos, ausencias aprobadas, la fecha de cierre, los comentarios y la **firma** del trabajador. Ideal para archivar como justificante del registro de jornada.

---

## Estados de un cierre

| Estado | Significado |
|--------|-------------|
| 🟢 **Cerrado** | El empleado confirmó sus fichajes y firmó. El mes está bloqueado para cambios. |
| 🟡 **Reabierto** | Un Administrador reabrió el cierre. Los fichajes vuelven a estar sin confirmar y el empleado puede modificar y volver a cerrar el mes. |

---

## Reabrir un cierre (solo Administradores)

Si un mes cerrado necesita una corrección (por ejemplo, un cambio de fichaje sobrevenido), un **Administrador** puede reabrir el cierre:

1. Ve a **"Validaciones"** → **"Cierres Mensuales"**
2. Localiza el cierre en estado **Cerrado**
3. Pulsa el icono **Reabrir** (candado abierto)
4. En el diálogo **"Reabrir Cierre"**:
   - Confirma la acción (el texto avisa: *"El empleado podrá modificar sus fichajes de ese mes"*)
   - Indica el **motivo de la reapertura** (queda registrado)
5. Pulsa **"Reabrir"**

### Efectos de la reapertura

- El estado pasa a **Reabierto** y se registra **quién, cuándo y por qué** se reabrió
- Los fichajes confirmados del mes vuelven a estar **sin confirmar**
- El empleado **ya puede solicitar cambios de fichaje** de ese mes y volver a realizar el cierre con firma
- El historial de la reapertura se conserva en el registro del cierre

{: .important }
> **Trazabilidad**: La reapertura queda registrada con el usuario que la realizó, la fecha y el motivo indicado. Úsala solo cuando sea estrictamente necesario y documenta siempre el motivo.

{: .note }
> El rol **Validador** puede consultar cierres y descargar PDFs, pero **solo los roles Administrador y SuperAdmin pueden reabrir** un cierre.

---

## Buenas prácticas

✅ **Revisa periódicamente** el listado para hacer seguimiento de quién no cierra su mes

✅ **Archiva los PDF** de los cierres como parte del registro de jornada (conservación legal de 4 años)

✅ **Reabre solo si es necesario** y con motivo documentado

❌ **Evita** dejar meses sin cerrar durante mucho tiempo: cuanto más tardía la corrección, más difícil verificarla

---

## Preguntas frecuentes

### ¿Puedo ver qué empleados NO han cerrado el mes?

El listado muestra los cierres realizados. Para hacer seguimiento de pendientes, consulta a los empleados o usa los reportes de fichajes del Administrador.

### ¿Un empleado puede volver a cerrar un mes reabierto?

Sí. Tras la reapertura, el empleado puede solicitar sus cambios de fichaje, confirmar los fichajes y volver a firmar el cierre (dentro del plazo disponible o cuando el Administrador lo indique).

### ¿Los fichajes confirmados cuentan para el informe de inspección?

Sí: los fichajes confirmados con cierre aportan más fiabilidad al registro, pero todo el histórico de fichajes (confirmados o no) está disponible para los informes de inspección.

---

## ¿Necesitas ayuda?

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Cierre Mensual (Empleado)](/guias-por-rol/empleado/cierres-mensuales/)
- 👉 [Aprobar Cambios de Fichaje](/guias-por-rol/validador/aprobar-cambios-fichaje/)
- 👉 [Informe para Inspección de Trabajo](/reportes/informe-inspeccion-trabajo/)
- 👉 [Guía del Validador](/guias-por-rol/validador/)
