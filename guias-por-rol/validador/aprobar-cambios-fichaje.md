---
layout: default
title: Aprobar Cambios de Fichaje
parent: Validador
grand_parent: Guías por Rol
nav_order: 1
---

# Aprobar Cambios de Fichaje
{: .no_toc }

Aprende a validar las solicitudes de cambio de fichaje cuando un empleado olvidó fichar o necesita corregir la hora de un registro. Como Validador, eres responsable de verificar que las correcciones sean legítimas antes de aprobarlas.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué son los cambios de fichaje?

Los **cambios de fichaje** son solicitudes que los empleados envían cuando:

- ❌ **Olvidaron fichar** la entrada o la salida
- ❌ **Ficharon a una hora incorrecta** (por error)
- ❌ **Necesitan corregir** la hora de un fichaje ya registrado

{: .important }
> **Solo se modifica la hora**: El empleado solicita una **nueva hora para el mismo día** del fichaje. No puede cambiar la fecha ni añadir o eliminar fichajes desde la solicitud. Si falta un fichaje completo por añadir o hay que eliminar uno erróneo, se hace desde la gestión de fichajes del Administrador (o con el botón "Solucionar" del propio empleado, que genera un cambio auto-aprobado).

Como Validador, tu trabajo es:

- ✅ **Revisar** la solicitud y el motivo
- ✅ **Verificar** que la corrección es legítima
- ✅ **Aprobar** si está justificada (el fichaje se actualiza automáticamente)
- ✅ **Rechazar** si no es válida o creíble

{: .important }
> **Responsabilidad legal**: Los cambios de fichaje deben estar **justificados y documentados**. Según el RD 8/2019, las modificaciones del registro de jornada deben tener una razón válida y quedar registradas con su aprobador.

---

## Acceder a las solicitudes de cambio

### Desde el menú

1. Inicia sesión con tu usuario **Validador** (o Administrador)
2. Ve al menú lateral → **"Validaciones"** → **"Cambios de Fichajes"**
3. Verás junto al menú un **badge** con el número de solicitudes pendientes
4. Se abrirá el listado **"Solicitudes de cambio pendientes"**

### Desde las notificaciones

Cuando un empleado solicita un cambio de fichaje, los Validadores reciben una **notificación por email y push** con un enlace directo al listado de validación.

---

## Listado de solicitudes pendientes

### Columnas de la tabla

| Columna | Descripción |
|---------|-------------|
| ☑️ | Casilla para selección múltiple (acción masiva) |
| **Acciones** | Aprobar (✓) o Denegar (✗) individual |
| **Usuario** | Empleado solicitante |
| **Fecha fichaje original** | Fecha y hora registradas actualmente |
| **Nueva fecha** | La misma fecha con la **nueva hora** solicitada |
| **Observaciones** | Motivo indicado por el empleado |

### Filtros

- **Selector de empleado**: elige **"Todos los empleados"** o un empleado concreto
- Botón **"Filtrar"**

{: .tip }
> El listado solo muestra solicitudes **pendientes**. Una vez aprobada o denegada, la solicitud desaparece del listado y el resultado queda registrado en la trazabilidad del fichaje.

---

## Aprobar o rechazar

### Aprobación individual

1. Localiza la solicitud en la tabla
2. Pulsa el icono **✓ (Aprobar)** o **✗ (Denegar)** de la fila

### Aprobación masiva

1. Marca las casillas de las solicitudes (o la casilla de selección total)
2. Pulsa **"Aprobar"** o **"Denegar"** (mostrarán el contador de seleccionadas)
3. Se abre un diálogo de confirmación: *"¿Deseas confirmar los cambios de fichaje seleccionados?"*
4. Marca o desmarca **"Notificar al empleado por email"** (activada por defecto)
5. Confirma con **"Sí, Aprobar"** / **"Sí, Denegar"**

{: .note }
> Al aprobar o denegar individualmente no se pide comentario. Si necesitas explicar el rechazo al empleado, comunícalo por los canales habituales o usa la validación masiva para asegurarte de que recibe el email de notificación.

### Qué ocurre al aprobar

- El fichaje **se actualiza automáticamente** con la nueva hora solicitada
- Queda registrada la **trazabilidad**: quién aprobó y con qué fecha
- El empleado recibe una **notificación** del cambio de estado
- Si tu empresa usa el **banco de horas extras**, el saldo del empleado se recalcula con la nueva hora

### Qué ocurre al rechazar

- El estado pasa a **Rechazado** y el fichaje **no se modifica**
- El empleado recibe una notificación y puede enviar una nueva solicitud con mejor justificación

---

## Verificar la legitimidad del cambio

Antes de aprobar, hazte estas preguntas:

### 1. ¿El motivo es razonable?

✅ **Motivos legítimos:**
- "Olvidé fichar al salir con prisa"
- "Tuve un problema con la app móvil"
- "El sistema no registró mi fichaje por error de red"

❌ **Motivos sospechosos:**
- "Quiero cambiar la hora porque llegué tarde" (no es válido)
- "Olvidé fichar" (sin más explicación, muy vago)
- Sin motivo

### 2. ¿La hora propuesta coincide con su horario?

Verifica que la hora solicitada:
- Esté dentro de su horario habitual
- Sea coherente con sus patrones de fichaje normales
- No sea sospechosamente exacta (ej: 09:00:00 cuando siempre ficha 09:03, 09:05...)

### 3. ¿La solicitud es reciente?

- ✅ Solicitud de ayer o anteayer: Normal
- ⚠️ Solicitud de hace 1 semana: Revisar con más cuidado
- ❌ Solicitud de hace 1 mes: Sospechoso, requiere verificación extra

{: .warning }
> **Importante**: Si las solicitudes son muy antiguas o frecuentes del mismo empleado, puede indicar un problema de disciplina o intento de manipulación.

### 4. ¿Puedes confirmar que estuvo trabajando?

Si tienes dudas, verifica:
- ¿Estuvo en reuniones ese día? (calendario, emails)
- ¿Compañeros lo vieron trabajando?
- ¿Hay evidencia de trabajo realizado?

---

## Cambios que no llegan a validación

No todas las modificaciones de fichaje pasan por tu listado. Existen **cambios auto-aprobados** que se registran directamente con estado "Aceptada":

- **Salida teórica**: si el horario del empleado lo permite, al fichar la salida después de su hora teórica puede elegir entre "Hora actual" o "Hora teórica". Si elige la teórica, se crea un cambio auto-aprobado con la observación *"Auto-aprobado: fichaje fuera de horario teórico"*.
- **Resolución de incidencias**: cuando el empleado usa el botón **"Solucionar"** en un día sin fichajes o con incidencia, los fichajes de corrección se registran como cambios auto-aprobados.

Estos cambios igualmente quedan registrados con su trazabilidad y son visibles en reportes e informes de inspección.

---

## Casos especiales

### Mes cerrado con cierre mensual

Si el mes del fichaje ya fue cerrado por el empleado (cierre mensual firmado), **no se pueden solicitar cambios** de ese mes. Si la corrección es necesaria, un **Administrador** debe **reabrir el cierre** primero (la reapertura queda registrada con su motivo).

### Empleado olvidó fichar entrada y salida del mismo día

Si falta un fichaje completo (no hay nada que "corregir la hora"), la solicitud de cambio no aplica: el empleado debe usar **"Solucionar"** desde Mis Fichajes o el Administrador debe crear los fichajes desde la gestión de fichajes.

### Empleado quiere cambiar la hora porque llegó tarde

1. **Rechaza siempre** este tipo de solicitudes
2. Comunícalo al empleado: los retrasos deben quedar registrados como tal

{: .important }
> **Principio clave**: Los fichajes deben reflejar la realidad. No se pueden modificar para "maquillar" retrasos o ausencias.

### Fichaje duplicado por error

Los fichajes duplicados muy seguidos suelen estar bloqueados por el sistema (ventana anti-duplicado). Si aun así existe un fichaje erróneo que deba eliminarse, lo gestiona el Administrador desde la gestión de fichajes.

---

## Detección de patrones sospechosos

Como Validador, debes estar atento a:

### 🚩 Señales de alerta

- 🚩 **Olvidos frecuentes**: El mismo empleado olvida fichar cada semana
- 🚩 **Solicitudes tardías**: Siempre solicita modificaciones después de varios días
- 🚩 **Horas sospechosas**: Siempre propone horas "perfectas" (09:00:00, 18:00:00)
- 🚩 **Solo días específicos**: Solo olvida los lunes o viernes

### Qué hacer si detectas un patrón

1. **Documenta**: guarda registro de todas las solicitudes del empleado
2. **Habla con él o con su Manager**: reunión privada para entender qué está pasando
3. **Establece expectativas**: explica la importancia de fichar correctamente
4. **Escala a RRHH**: si no mejora, informa con la documentación

---

## Preguntas frecuentes

### ¿Qué pasa si no reviso una solicitud?

La solicitud permanece **pendiente**: el fichaje no se modifica y al empleado se le mantiene la hora original. En la pantalla de **Cierre Mensual** del empleado verá el aviso de "Solicitudes pendientes" hasta que se resuelva.

### ¿Puedo aprobar un cambio de hace 1 mes?

Técnicamente sí (si el mes no está cerrado), pero **no es recomendable**: es muy difícil verificar la legitimidad de cambios tan antiguos. Establece una política clara (ej: máximo 7-10 días).

### ¿Los empleados pueden modificar fichajes sin aprobación?

No. Los empleados **nunca** modifican sus fichajes directamente: siempre pasan por solicitud y aprobación (Validador o Administrador), salvo los cambios auto-aprobados (salida teórica y resolución de incidencias) que igualmente quedan registrados y trazados.

### ¿Los cambios aprobados aparecen en el Informe de Inspección?

Sí. Las observaciones de los cambios (pendientes, aprobadas y rechazadas) se incluyen en los informes de fichajes e inspección, con la trazabilidad de quién aprobó. Esto cumple la transparencia requerida por el RD 8/2019.

### ¿Puedo aprobar mis propios cambios de fichaje?

Un Administrador podría técnicamente, pero **no es recomendable** por conflicto de interés. Lo habitual es que tus propios cambios los apruebe otro Validador o el Administrador.

---

## ¿Necesitas ayuda?

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [¿Olvidé Fichar? (Empleado)](/guias-por-rol/empleado/olvide-fichar/)
- 👉 [Revisar Cierres Mensuales](/guias-por-rol/validador/revisar-cierres/)
- 👉 [Reporte de Impuntualidades](/reportes/reporte-impuntualidades/)
- 👉 [Informe para Inspección de Trabajo](/reportes/informe-inspeccion-trabajo/)
- 👉 [Guía del Validador](/guias-por-rol/validador/)
