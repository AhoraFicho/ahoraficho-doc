---
layout: default
title: Aprobar Gastos
parent: Guía del Manager
grand_parent: Guías por Rol
nav_order: 3
---

# Aprobar Gastos
{: .no_toc }

Aprende a revisar, aprobar o rechazar los gastos presentados por los empleados de tu departamento. Asegura que los gastos sean legítimos, estén correctamente documentados y cumplan con la política de empresa.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{: .note }
> **Módulo opcional**: Esta funcionalidad solo está disponible si tu empresa tiene el módulo de **Gastos** activado. Si no lo ves en tu menú, contacta con el Administrador o SuperAdmin.

---

## ¿Qué son los gastos en AhoraFicho?

Los **gastos** son desembolsos que los empleados realizan por cuenta de la empresa y que posteriormente solicitan reembolsar. Ejemplos típicos:

- 🚗 **Kilometraje**: Uso de vehículo personal para trabajo
- 🍽️ **Comidas de cliente**: Restaurantes con clientes o proveedores
- 🏨 **Alojamiento**: Hoteles en viajes de trabajo
- 🚆 **Transporte**: Billetes de tren, avión, taxi
- 📦 **Material**: Compras pequeñas de material de oficina
- 🅿️ **Parking**: Aparcamiento en visitas a clientes

Como Manager, tu trabajo es:

- ✅ **Revisar** el gasto y su justificación
- ✅ **Verificar** que hay ticket/factura adjunta
- ✅ **Comprobar** que cumple la política de gastos de empresa
- ✅ **Aprobar** si todo está correcto
- ✅ **Rechazar** si falta información o no cumple

{: .important }
> **Responsabilidad fiscal**: Los gastos aprobados se usarán para reembolsar al empleado y para deducir en impuestos. Es importante que sean legítimos y estén bien documentados.

---

## Acceder a las solicitudes de gastos

### Opción 1: Desde Notificaciones

Cuando un empleado sube un gasto, recibirás una **notificación por email**:

```
Asunto: Nuevo gasto pendiente de aprobación - Juan Pérez

Juan Pérez ha presentado un gasto:
- Concepto: Comida con cliente
- Importe: 45,50 €
- Fecha: 15/01/2025
- Categoría: Restauración

Haz clic aquí para revisar el gasto.
```

### Opción 2: Desde el menú

1. Inicia sesión como **Manager**
2. Ve al menú lateral → **"Mis Gastos"** o **"Gastos"**
3. Pestaña **"Pendientes de aprobar"**
4. Verás todos los gastos de tu(s) departamento(s) que esperan validación

![Menú gastos manager](/assets/images/placeholder-menu-gastos-manager.png)

### Opción 3: Desde el Dashboard

En tu dashboard verás:
- Número de gastos pendientes de aprobación
- Importe total pendiente de validar
- Acceso directo al listado

---

## Listado de gastos pendientes

Al acceder verás una tabla con todos los gastos:

### Columnas de la tabla

| Columna | Descripción |
|---------|-------------|
| **Empleado** | Nombre del solicitante + departamento |
| **Fecha** | Día en que se realizó el gasto |
| **Concepto** | Descripción del gasto |
| **Categoría** | Tipo (Transporte, Restauración, Alojamiento, etc.) |
| **Importe** | Cantidad en euros |
| **Ticket** | Icono indicando si hay justificante adjunto |
| **Estado** | Pendiente, Aprobado, Rechazado |
| **Fecha Subida** | Cuándo se registró el gasto |
| **Acciones** | Botones para revisar/aprobar/rechazar |

![Listado gastos](/assets/images/placeholder-listado-gastos.png)

### Filtros disponibles

- **Estado**: Pendientes, Aprobados, Rechazados, Todos
- **Empleado**: Filtrar por un empleado específico
- **Categoría**: Transporte, Restauración, Alojamiento, etc.
- **Fecha**: Rango de fechas del gasto
- **Importe**: Rango de importes (ej: más de 100€)

{: .tip }
> **Consejo**: Ordena por importe descendente para revisar primero los gastos más altos.

---

## Revisar un gasto

### Paso 1: Abrir el detalle

1. Haz clic en **"Ver Detalle"** o en el concepto del gasto
2. Se abrirá una ventana con toda la información

### Información que verás

**Datos del gasto:**
- 👤 **Empleado**: Nombre completo, departamento
- 📅 **Fecha del gasto**: Cuándo se realizó
- 💰 **Importe**: Cantidad exacta (con IVA incluido normalmente)
- 🏷️ **Categoría**: Tipo de gasto
- 📝 **Concepto**: Descripción detallada
- 🧾 **Ticket/Factura**: Imagen o PDF adjunto
- 💬 **Observaciones**: Comentarios del empleado
- 🏢 **Proyecto**: Si está asignado a un proyecto específico (opcional)

![Detalle gasto](/assets/images/placeholder-detalle-gasto.png)

### Ver el ticket/factura

1. Haz clic en el icono 📎 **"Ver Ticket"**
2. Se abrirá el documento en una nueva pestaña o visor
3. Verifica que:
   - La imagen sea legible
   - Coincida con el importe declarado
   - Tenga fecha válida
   - Sea un documento oficial (no una foto borrosa)

---

## Verificaciones antes de aprobar

Antes de aprobar, comprueba los siguientes puntos:

### 1. ¿El gasto es legítimo?

✅ **Gastos legítimos:**
- Comida con cliente confirmado (verifica en calendario si hubo reunión)
- Transporte necesario para trabajo (verifica desplazamiento ese día)
- Material solicitado y necesario para la operativa
- Hotel en viaje de trabajo autorizado

❌ **Gastos NO legítimos:**
- Comida personal sin cliente/compañero
- Compras personales
- Gastos no relacionados con el trabajo
- Lujos innecesarios (restaurante muy caro sin justificación)

### 2. ¿Hay ticket/factura adjunta?

{: .important }
> **Obligatorio**: Para reembolsar y deducir fiscalmente, **debe haber ticket o factura** adjunta. Sin justificante, no puedes aprobar.

- ✅ Ticket claro y legible
- ✅ Factura oficial con NIF de la empresa
- ❌ Foto borrosa o ilegible
- ❌ Documento no oficial
- ❌ Sin justificante

### 3. ¿El importe coincide con el ticket?

- Verifica que el importe declarado **coincida exactamente** con el del ticket
- Revisa que no haya errores de decimal (45,50 € no es lo mismo que 4,50 €)
- Comprueba la moneda si es gasto internacional

### 4. ¿Cumple la política de gastos de empresa?

Verifica que cumple las normas de tu empresa, por ejemplo:

| Categoría | Límite típico | Requiere autorización previa |
|-----------|---------------|------------------------------|
| **Comida cliente** | 30-50 € por persona | No |
| **Hotel** | 80-120 € por noche | Sí |
| **Kilometraje** | 0,19 € por km | No |
| **Material oficina** | Hasta 100 € | No |
| **Parking** | Ticket real | No |

{: .note }
> Cada empresa tiene su propia política. Asegúrate de conocer los límites y reglas de la tuya.

### 5. ¿El gasto es reciente?

- ✅ Gastos de esta semana o semana pasada: Normal
- ⚠️ Gastos de hace 1 mes: Revisar, recordar al empleado que debe subirlos antes
- ❌ Gastos de hace 3+ meses: Generalmente fuera de plazo

---

## Aprobar un gasto

Si el gasto cumple todos los requisitos:

### Paso 1: Hacer clic en "Aprobar"

1. En el detalle del gasto, haz clic en **"Aprobar"**
2. (Opcional) Añade un comentario interno
3. Haz clic en **"Confirmar"**

![Aprobar gasto](/assets/images/placeholder-aprobar-gasto.png)

### Paso 2: Confirmación

- El estado cambiará a **"Aprobado"** (badge verde)
- El empleado recibirá una **notificación** de aprobación
- El gasto pasará al departamento de **Administración/RRHH** para el reembolso
- Quedará registrado con tu nombre como aprobador

{: .tip }
> **Añade un comentario positivo**: "Aprobado. Gracias por adjuntar el ticket completo."

---

## Rechazar un gasto

Si el gasto no cumple los requisitos:

### Paso 1: Hacer clic en "Rechazar"

1. En el detalle del gasto, haz clic en **"Rechazar"**
2. **OBLIGATORIO**: Añade un comentario explicando el motivo del rechazo
3. Haz clic en **"Confirmar"**

![Rechazar gasto](/assets/images/placeholder-rechazar-gasto.png)

### Paso 2: Justificar el rechazo

**Ejemplos de comentarios apropiados:**

✅ **Buenos comentarios:**
- "Falta adjuntar el ticket. Por favor, súbelo y vuelve a solicitar."
- "El importe del ticket (35 €) no coincide con lo declarado (45 €). Por favor, corrige."
- "Comidas personales no son reembolsables. Solo se aprueban comidas con clientes."
- "Este gasto supera el límite de 50 € por comida. Rechazado."
- "El ticket es ilegible. Por favor, sube una foto más clara."

❌ **Malos comentarios (evitar):**
- "No" (sin explicación)
- "Muy caro" (poco específico)
- "No me gusta" (subjetivo)

### Paso 3: Confirmación

- El estado cambiará a **"Rechazado"** (badge rojo)
- El empleado recibirá una **notificación** con tu comentario
- El gasto **NO se reembolsará**
- El empleado puede corregir y volver a subirlo si es posible

---

## Solicitar más información

Si el gasto necesita aclaración pero podría ser aprobable:

### Opción: Añadir comentario sin decidir aún

1. En el detalle del gasto, usa el campo **"Comentarios"**
2. Pregunta lo que necesites aclarar
3. El empleado recibirá notificación con tu pregunta
4. Cuando responda, revisa de nuevo y aprueba/rechaza

**Ejemplo de comentario:**
"¿Quién fue el cliente con el que comiste? Por favor, añade su nombre en observaciones para poder aprobar."

---

## Casos especiales

### Gasto sin ticket porque se perdió

**Situación**: El empleado dice que perdió el ticket.

**Acción:**
1. Si es un gasto pequeño (<10 €) y el empleado es de confianza, puedes aprobar excepcionalmente
2. Si es un gasto mayor, rechaza
3. Comenta: "Sin ticket no puedo aprobar gastos mayores. En el futuro, pide siempre factura con email."

{: .warning }
> **Límite**: No apruebes gastos sin ticket de forma recurrente. Establece que es excepcional.

### Gasto compartido entre varios empleados

**Situación**: Comida de equipo, uno pagó por todos.

**Acción:**
1. Verifica que todos los participantes están en tu equipo
2. Divide el importe entre el número de personas
3. Aprueba solo la parte proporcional a cada uno
4. Comenta: "Aprobado 15 € (45 € / 3 personas)."

### Gasto en moneda extranjera

**Situación**: Viaje internacional, gastos en dólares, libras, etc.

**Acción:**
1. Verifica el cambio aplicado (puede ser el del banco del empleado)
2. Si es razonable según el tipo de cambio oficial de esa fecha, aprueba
3. Comenta: "Aprobado al tipo de cambio del día."

### Propina incluida en el ticket

**Situación**: El empleado añadió propina en el restaurante.

**Acción:**
- Si la propina es razonable (5-10%), aprueba el total
- Si la propina es excesiva (20%+), aprueba solo el importe base sin propina
- Comenta: "Aprobado importe base. La propina excesiva corre a tu cuenta."

### Kilometraje

**Situación**: El empleado usa su coche personal para visitas.

**Acción:**
1. Verifica que hubo desplazamiento ese día (revisando agenda, reportes, etc.)
2. Comprueba que los km declarados son razonables (Google Maps)
3. Verifica el precio por km según política de empresa (ej: 0,19 €/km)
4. Aprueba si todo cuadra

{: .note }
> **Precio por km**: En España es habitual 0,19 €/km según Hacienda, pero cada empresa puede tener su propia tarifa.

---

## Límites y autorizaciones previas

### Gastos que requieren autorización previa

Algunos gastos deben estar **autorizados antes** de realizarse:

- 🏨 **Hoteles** (generalmente)
- ✈️ **Viajes** internacionales
- 🎓 **Formación** o cursos
- 💻 **Compras grandes** (ordenadores, móviles)

**Si un empleado sube uno de estos gastos sin autorización previa:**
1. Verifica si debía haber pedido permiso antes
2. Si sí, rechaza: "Los hoteles requieren autorización previa. La próxima vez solicítalo antes de reservar."
3. Si fue una emergencia justificada, aprueba excepcionalmente

### Límites por categoría

Establece límites claros para tu equipo:

**Ejemplo de política clara:**
```
Política de Gastos - Departamento de Ventas

Comidas con clientes:
- Máximo: 50 € por persona
- Requiere: Ticket + Nombre del cliente en observaciones

Kilometraje:
- Tarifa: 0,19 € por km
- Requiere: Origen y destino en observaciones

Parking:
- Aprobado: Solo en visitas a clientes
- Requiere: Ticket

Material oficina:
- Hasta 100 €: Aprobar directamente
- Más de 100 €: Consultar antes con manager
```

---

## Reportes y análisis de gastos

### Consultar gastos aprobados del mes

1. Ve a **"Gastos"** → **"Reportes"**
2. Filtra por mes actual
3. Filtra por **"Aprobados"**
4. Verás el total de gastos aprobados y el importe total

### Estadísticas útiles

- **Gasto medio** por empleado
- **Categorías más utilizadas**
- **Tendencias**: ¿Aumentan o disminuyen los gastos?
- **Empleados con más gastos**: ¿Es normal según su rol?

### Exportar para Administración

Al final de mes, puedes exportar:
1. **Listado de gastos aprobados** en Excel
2. Envíalo a Administración/RRHH para que procesen los reembolsos
3. Incluye: Empleado, concepto, importe, fecha, ticket

---

## Preguntas frecuentes

### ¿Qué pasa si apruebo un gasto por error?

Puedes **cancelar la aprobación** si aún no ha sido reembolsado por Administración. Contacta con ellos rápidamente.

### ¿Puedo aprobar mis propios gastos?

Generalmente **no**. Tus gastos deberían ser aprobados por tu superior o por Administración para evitar conflictos de interés.

### ¿Los empleados pueden editar gastos rechazados?

Depende de la configuración, pero normalmente deben crear un **nuevo gasto** corrigiendo los errores.

### ¿Cuánto tiempo tienen los empleados para presentar gastos?

Varía por empresa, pero lo habitual es **30-60 días** desde la fecha del gasto. Pasado ese plazo, pueden no ser reembolsables.

### ¿Qué hago si un empleado abusa del sistema?

1. Documenta todos los casos
2. Rechaza los gastos no legítimos
3. Habla con el empleado en privado
4. Si continúa, eleva a RRHH con evidencias

### ¿Los gastos aprobados se reembolsan automáticamente?

No, normalmente pasan a **Administración/RRHH** que procesa los reembolsos (transferencia o nómina).

---

## ¿Necesitas ayuda?

Si tienes dudas sobre cómo aprobar gastos:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)
- 👤 Contacta con Administración de tu empresa

---

## Guías relacionadas

- 👉 [Aprobar Vacaciones](/guias-por-rol/manager/aprobar-vacaciones/)
- 👉 [Aprobar Cambios de Fichaje](/guias-por-rol/manager/aprobar-cambios-fichaje/)
- 👉 [Aprobar Imputaciones](/guias-por-rol/manager/aprobar-imputaciones/)
- 👉 [Guía del Manager](/guias-por-rol/manager/)