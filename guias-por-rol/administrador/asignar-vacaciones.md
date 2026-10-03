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
2. Ve al menú lateral **"Configuraciones"** → **"Trabajadores"**
3. Busca al empleado al que quieres asignar vacaciones
4. Haz clic en el botón **"Editar"** (icono de lápiz) junto a su nombre

![Listado de empleados](/assets/images/placeholder-empleados-list.png)

### Paso 2: Configurar días de vacaciones

1. En el formulario de edición del empleado, busca el campo de vacaciones (**"Max Ausencias"**)
2. Introduce los días de vacaciones anuales
3. Establece o verifica la **fecha de caducidad** del saldo (habitualmente 31 de diciembre)
4. Haz clic en **"Guardar cambios"**

![Configurar vacaciones del empleado](/assets/images/placeholder-configurar-vacaciones.png)

{: .note }
> **Ejemplo práctico**: Si un empleado tiene derecho a 22 días de vacaciones al año con caducidad a fin de año, introduce:
> - Max Ausencias: **22**
> - Fecha caducidad: **31/12 del año en curso**

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

1. Ve a **"Configuraciones" → "Trabajadores"** → Editar empleado
2. Ajusta el campo de vacaciones (**"Max Ausencias"**) o crea una bolsa adicional para el año correspondiente
3. Guarda los cambios

![Días adicionales de vacaciones](/assets/images/placeholder-dias-adicionales.png)

{: .note }
> Los días adicionales se suman a los días anuales. Si un empleado tiene 22 días anuales + 3 adicionales, su saldo total será de **25 días**.

---

## Modificar vacaciones ya asignadas

Si necesitas ajustar los días de vacaciones de un empleado (por error, cambio de contrato, etc.):

1. Ve a **"Configuraciones" → "Trabajadores"** → Editar empleado
2. Modifica el valor del campo de vacaciones
3. El sistema recalculará automáticamente el saldo disponible por año
4. Guarda los cambios

{: .warning }
> **Importante**: Si el empleado ya ha solicitado o consumido vacaciones, al reducir los días asignados puede quedar con saldo negativo. Verifica siempre el historial antes de modificar.

---

## Consultar el saldo de vacaciones

### Ver el saldo de un empleado

1. Ve a **"Configuraciones" → "Trabajadores"**
2. En el listado, consulta la columna de vacaciones con el saldo actual
3. Para más detalle, abre la ficha del empleado

![Saldo de vacaciones](/assets/images/placeholder-saldo-vacaciones.png)

### Consultar el historial de vacaciones

1. Ve a **"Empresa"** → **"Gestión de Ausencias"**
2. Filtra por empleado y año
3. Verás todas las solicitudes: **Pendientes**, **Aceptadas** y **Rechazadas**
4. Puedes exportar el informe en PDF o Excel

---

## Casos especiales

### Empleado de nueva incorporación

Al dar de alta a un empleado, AhoraFicho calcula automáticamente el **prorrateo** de vacaciones:

- Días proporcionales al año de entrada según los **meses devengados** (el mes inicial computa completo si se trabajan 15 días o más)
- Más la bolsa completa del año siguiente
- Caducidad: 31 de diciembre

**Ejemplo**: Si la política es 22 días al año y el empleado entra el 1 de julio:
- Días correspondientes: 22 / 12 meses × 6 meses ≈ **11 días** (generados automáticamente)

Puedes ajustar los días después del alta si tu convenio lo requiere.

### Empleado con contrato temporal

Para contratos temporales, los días de vacaciones deben calcularse también proporcionalmente según la duración del contrato.

**Ejemplo**: Contrato de 3 meses (90 días):
- Días correspondientes: 22 / 365 días × 90 días = **5,42 días** (redondear según convenio)

### Baja laboral durante el período de vacaciones

Si un empleado se pone de baja estando de vacaciones, según el Estatuto de los Trabajadores el período de vacaciones se interrumpe y los días deben poder disfrutarse en otra fecha.

{: .note }
> AhoraFicho **no gestiona automáticamente** las bajas médicas durante vacaciones. Deberás ajustar manualmente las ausencias y el saldo si es necesario.

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