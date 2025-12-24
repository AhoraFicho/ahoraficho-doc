---
layout: default
title: Asignar Vacaciones
parent: Guía del Administrador
grand_parent: Guías por Rol
nav_order: 7
---

# Asignar Vacaciones
{: .no_toc }

Aprende a configurar y asignar los días de vacaciones disponibles para cada empleado, establecer fechas de caducidad y gestionar el saldo anual.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué son las vacaciones en AhoraFicho?

Las vacaciones son días de ausencia retribuida que los empleados pueden solicitar y que deben ser aprobadas por un responsable. Como administrador, puedes:

- ✅ Configurar los días de vacaciones anuales por empleado
- ✅ Establecer fechas de caducidad del saldo
- ✅ Asignar días adicionales o extraordinarios
- ✅ Consultar el saldo disponible y consumido
- ✅ Modificar vacaciones ya asignadas

{: .important }
> El módulo de **Vacaciones y Ausencias** está siempre activo en AhoraFicho y no puede desactivarse, ya que es obligatorio para el cumplimiento del RD 8/2019.

---

## Asignar vacaciones anuales a un empleado

### Paso 1: Acceder a la gestión de empleados

1. Inicia sesión como **Administrador**
2. Ve al menú lateral y haz clic en **"Empleados"**
3. Busca al empleado al que quieres asignar vacaciones
4. Haz clic en el botón **"Editar"** (icono de lápiz) junto a su nombre

![Listado de empleados](/assets/images/placeholder-empleados-list.png)

### Paso 2: Configurar días de vacaciones

1. En el formulario de edición del empleado, busca la sección **"Vacaciones"**
2. Introduce los días de vacaciones anuales en el campo **"Días de vacaciones"**
3. Selecciona la fecha de inicio del período de vacaciones (por defecto 1 de enero)
4. Establece la fecha de caducidad (opcional)
5. Haz clic en **"Guardar cambios"**

![Configurar vacaciones del empleado](/assets/images/placeholder-configurar-vacaciones.png)

{: .note }
> **Ejemplo práctico**: Si un empleado tiene derecho a 22 días de vacaciones al año desde el 1 de enero hasta el 31 de diciembre, introduce:
> - Días de vacaciones: **22**
> - Fecha inicio período: **01/01/2024**
> - Fecha caducidad: **31/12/2024**

---

## Configurar fechas de caducidad

### ¿Qué es la fecha de caducidad?

La fecha de caducidad indica hasta cuándo el empleado puede consumir los días de vacaciones asignados. Una vez pasada esa fecha, los días no consumidos pueden:

- Perderse automáticamente
- Arrastrarse al siguiente período (según política de empresa)

### Configurar caducidad

1. En el formulario de edición del empleado (sección Vacaciones)
2. Marca la casilla **"Establecer fecha de caducidad"**
3. Selecciona la fecha límite (ejemplo: 31/12/2024)
4. Guarda los cambios

{: .tip }
> **Recomendación**: La mayoría de empresas establecen el 31 de diciembre como fecha de caducidad, aunque el Convenio Colectivo puede permitir arrastrar días al año siguiente.

---

## Asignar días adicionales o extraordinarios

En ocasiones, los empleados pueden tener derecho a días adicionales por:

- Antigüedad en la empresa
- Convenio colectivo especial
- Días compensatorios por festivos trabajados
- Política interna de la empresa

### Cómo añadir días extras

1. Ve a **"Empleados"** → Selecciona el empleado → **"Editar"**
2. En la sección **"Vacaciones"**, busca el campo **"Días adicionales"**
3. Introduce el número de días extras
4. (Opcional) Añade un comentario explicativo del motivo
5. Guarda los cambios

![Días adicionales de vacaciones](/assets/images/placeholder-dias-adicionales.png)

{: .note }
> Los días adicionales se suman a los días anuales. Si un empleado tiene 22 días anuales + 3 adicionales, su saldo total será de **25 días**.

---

## Modificar vacaciones ya asignadas

Si necesitas ajustar los días de vacaciones de un empleado (por error, cambio de contrato, etc.):

1. Ve a **"Empleados"** → Editar empleado
2. Modifica el valor en el campo **"Días de vacaciones"**
3. El sistema recalculará automáticamente el saldo disponible
4. Guarda los cambios

{: .warning }
> **Importante**: Si el empleado ya ha solicitado o consumido vacaciones, al reducir los días asignados puede quedar con saldo negativo. Verifica siempre el historial antes de modificar.

---

## Consultar el saldo de vacaciones

### Ver el saldo de un empleado

1. Ve a **"Empleados"**
2. En el listado, verás una columna **"Vacaciones"** con el saldo actual
3. El formato será: **Días consumidos / Días totales** (ejemplo: 10/22)
4. Para más detalle, haz clic en **"Ver detalle"** junto al empleado

![Saldo de vacaciones](/assets/images/placeholder-saldo-vacaciones.png)

### Consultar el historial de vacaciones

1. Ve a **"Vacaciones y Ausencias"** en el menú lateral
2. Filtra por empleado usando el buscador
3. Verás todas las solicitudes: **Pendientes**, **Aprobadas** y **Rechazadas**
4. Puedes exportar el informe en PDF o Excel

---

## Casos especiales

### Empleado de nueva incorporación

Para empleados que se incorporan a mitad de año, calcula los días de vacaciones proporcionalmente:

**Ejemplo**: Si la política es 22 días al año y el empleado entra el 1 de julio:
- Días correspondientes: 22 / 12 meses × 6 meses = **11 días**

1. Asigna los días proporcionales en el campo **"Días de vacaciones"**
2. Establece la fecha de inicio del período como su fecha de alta
3. Fecha de caducidad: 31 de diciembre del año actual

### Empleado con contrato temporal

Para contratos temporales, los días de vacaciones deben calcularse también proporcionalmente según la duración del contrato.

**Ejemplo**: Contrato de 3 meses (90 días):
- Días correspondientes: 22 / 365 días × 90 días = **5,42 días** (redondear según convenio)

### Baja laboral durante el período de vacaciones

Si un empleado se pone de baja estando de vacaciones:

1. El período de vacaciones se interrumpe automáticamente
2. Los días posteriores a la baja no se descuentan del saldo
3. El empleado podrá solicitar esos días en otra fecha

{: .note }
> El sistema de AhoraFicho **no gestiona automáticamente** las bajas médicas durante vacaciones. Deberás ajustar manualmente el saldo si es necesario.

---

## Preguntas frecuentes

### ¿Puedo asignar diferentes días de vacaciones a cada empleado?

Sí, cada empleado puede tener un número de días diferente según su contrato, antigüedad o convenio colectivo.

### ¿Qué pasa si un empleado no consume todas sus vacaciones?

Depende de la política de tu empresa y el convenio colectivo:
- **Opción 1**: Los días se pierden al finalizar el año (establece fecha de caducidad)
- **Opción 2**: Se arrastran al año siguiente (no establezcas caducidad o ajústala manualmente)

### ¿Puedo modificar las vacaciones si ya han sido aprobadas?

Sí, pero debes:
1. Cancelar la solicitud de vacaciones aprobada
2. Ajustar el saldo manualmente si es necesario
3. Informar al empleado del cambio

### ¿Los días festivos cuentan como vacaciones?

No, los días festivos **no** se descuentan del saldo de vacaciones. Si un empleado solicita vacaciones que incluyen festivos, solo se descuentan los días laborables.

---

## ¿Necesitas ayuda?

Si tienes problemas asignando vacaciones:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Solicitar Vacaciones (Empleado)](/guias-por-rol/empleado/solicitar-vacaciones/)
- 👉 [Crear Horarios](/guias-por-rol/administrador/crear-horarios/)
- 👉 [Dar de Alta Empleados](/guias-por-rol/administrador/dar-alta-empleados/)
- 👉 [Gestión de Departamentos](/guias-por-rol/administrador/gestion-departamentos/)