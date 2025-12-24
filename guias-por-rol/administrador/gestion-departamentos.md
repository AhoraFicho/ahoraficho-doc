---
layout: default
title: Gestión de Departamentos
parent: Guía del Administrador
grand_parent: Guías por Rol
nav_order: 8
---

# Gestión de Departamentos
{: .no_toc }

Aprende a crear, editar y organizar la estructura de departamentos de tu empresa para clasificar empleados, asignar responsables y generar reportes segmentados.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué son los departamentos en AhoraFicho?

Los departamentos te permiten organizar a los empleados de tu empresa en unidades funcionales o áreas de trabajo. Esto facilita:

- ✅ Segmentar empleados por áreas (Ventas, Producción, Administración, etc.)
- ✅ Asignar responsables (Managers) a cada departamento
- ✅ Generar reportes filtrados por departamento
- ✅ Gestionar horarios y turnos por áreas específicas
- ✅ Controlar accesos y permisos según estructura organizativa

{: .tip }
> **Ventaja**: Organizar tu empresa por departamentos te permite delegar responsabilidades a los Managers de cada área, que podrán supervisar solo a su equipo.

---

## Crear un nuevo departamento

### Paso 1: Acceder a la gestión de departamentos

1. Inicia sesión como **Administrador**
2. Ve al menú lateral y haz clic en **"Configuración"**
3. Selecciona **"Departamentos"**
4. Haz clic en el botón **"Nuevo Departamento"**

![Acceso a gestión de departamentos](/assets/images/placeholder-departamentos-menu.png)

### Paso 2: Completar los datos del departamento

En el formulario, introduce la siguiente información:

| Campo | Descripción | Ejemplo |
|-------|-------------|---------|
| **Nombre** | Nombre del departamento | Ventas |
| **Código** | Identificador corto (opcional) | VNT |
| **Descripción** | Información adicional | Equipo comercial y ventas |
| **Responsable** | Manager asignado (opcional) | Juan Pérez |
| **Activo** | Estado del departamento | ✅ Sí |

![Formulario nuevo departamento](/assets/images/placeholder-crear-departamento.png)

### Paso 3: Guardar el departamento

1. Revisa que todos los datos sean correctos
2. Haz clic en **"Guardar"**
3. El departamento aparecerá en el listado principal

{: .note }
> **Ejemplo de estructura típica**:
> - Administración
> - Recursos Humanos
> - Ventas
> - Marketing
> - Producción
> - Logística
> - IT / Sistemas

---

## Editar un departamento existente

Si necesitas modificar los datos de un departamento:

1. Ve a **"Configuración"** → **"Departamentos"**
2. Busca el departamento en el listado
3. Haz clic en el botón **"Editar"** (icono de lápiz)
4. Modifica los campos necesarios
5. Haz clic en **"Guardar cambios"**

![Editar departamento](/assets/images/placeholder-editar-departamento.png)

{: .warning }
> **Importante**: Si cambias el nombre de un departamento, todos los empleados asignados a él mantendrán su vinculación, pero aparecerán con el nuevo nombre en los reportes.

---

## Asignar empleados a un departamento

Existen dos formas de asignar empleados a departamentos:

### Opción 1: Desde el perfil del empleado

1. Ve a **"Empleados"** → Selecciona el empleado
2. Haz clic en **"Editar"**
3. En el campo **"Departamento"**, selecciona el departamento del desplegable
4. Guarda los cambios

### Opción 2: Asignación masiva

1. Ve a **"Empleados"**
2. Selecciona varios empleados marcando las casillas
3. Haz clic en **"Acciones masivas"**
4. Selecciona **"Cambiar departamento"**
5. Elige el departamento de destino
6. Confirma la acción

![Asignación masiva de departamentos](/assets/images/placeholder-asignar-masivo-departamento.png)

{: .tip }
> La asignación masiva es útil cuando incorporas varios empleados nuevos o reorganizas la estructura de la empresa.

---

## Asignar un responsable (Manager) al departamento

Los Managers son empleados con permisos para supervisar a otros empleados de su departamento. Para asignar un responsable:

1. Ve a **"Configuración"** → **"Departamentos"**
2. Edita el departamento deseado
3. En el campo **"Responsable"**, selecciona un empleado con rol **Manager**
4. Guarda los cambios

{: .important }
> **Requisito**: El empleado seleccionado como responsable **debe tener rol de Manager**. Si no lo tiene, primero debes cambiar su rol desde la gestión de empleados.

### Permisos del Manager sobre su departamento

Un Manager asignado a un departamento podrá:

- ✅ Ver los fichajes de los empleados de su departamento
- ✅ Aprobar o rechazar solicitudes de vacaciones
- ✅ Validar modificaciones de fichajes (olvidos)
- ✅ Consultar reportes del equipo
- ❌ No puede crear ni editar empleados (solo Administrador)

---

## Estructura jerárquica de departamentos

AhoraFicho permite crear **departamentos anidados** para empresas con estructuras complejas.

### Ejemplo de jerarquía

```
Empresa Principal
├── Administración
│   ├── Contabilidad
│   └── Recursos Humanos
├── Comercial
│   ├── Ventas España
│   └── Ventas Internacional
└── Operaciones
    ├── Producción
    └── Logística
```

### Crear un departamento hijo

1. Ve a **"Configuración"** → **"Departamentos"**
2. Haz clic en **"Nuevo Departamento"**
3. Completa los datos del departamento
4. En el campo **"Departamento padre"**, selecciona el departamento superior
5. Guarda los cambios

![Estructura jerárquica](/assets/images/placeholder-jerarquia-departamentos.png)

{: .note }
> Los reportes pueden generarse tanto a nivel de departamento padre (incluye hijos) como solo del departamento específico.

---

## Desactivar un departamento

Si un departamento deja de usarse (por ejemplo, tras una reorganización), puedes desactivarlo:

1. Ve a **"Configuración"** → **"Departamentos"**
2. Edita el departamento que quieres desactivar
3. Desmarca la casilla **"Activo"**
4. Guarda los cambios

{: .warning }
> **Importante**: Al desactivar un departamento:
> - No se podrán asignar nuevos empleados a él
> - Los empleados actuales **no se eliminarán**, pero aparecerán como "Sin departamento"
> - El departamento seguirá apareciendo en reportes históricos
> - Puedes reactivarlo en cualquier momento

{: .important }
> **Nunca elimines un departamento** si tiene empleados asignados. Primero reasigna a los empleados a otro departamento y luego desactívalo.

---

## Generar reportes por departamento

Los departamentos te permiten filtrar y generar reportes específicos.

### Reporte de fichajes por departamento

1. Ve a **"Reportes"** → **"Fichajes"**
2. En los filtros, selecciona **"Departamento"**
3. Elige el departamento deseado
4. Establece el rango de fechas
5. Haz clic en **"Generar reporte"**
6. Exporta en PDF o Excel

### Reporte de vacaciones por departamento

1. Ve a **"Vacaciones y Ausencias"** → **"Reportes"**
2. Filtra por **"Departamento"**
3. Consulta las vacaciones pendientes, aprobadas y consumidas
4. Exporta el informe

![Reporte por departamento](/assets/images/placeholder-reporte-departamento.png)

{: .tip }
> Los Managers solo podrán ver los reportes de su departamento asignado. Los Administradores ven todos los departamentos.

---

## Casos especiales

### Empleado sin departamento

Si un empleado no tiene departamento asignado:

- Aparecerá como **"Sin departamento"** en los listados
- Los Managers no podrán supervisarlo
- Solo los Administradores podrán gestionarlo

**Solución**: Asigna manualmente el departamento desde el perfil del empleado.

### Cambiar empleado de departamento

Si un empleado cambia de área:

1. Ve a **"Empleados"** → Edita el empleado
2. Cambia el departamento en el desplegable
3. Guarda los cambios

{: .note }
> El historial de fichajes previo se mantendrá asociado al antiguo departamento para los reportes históricos.

### Empresas pequeñas sin estructura de departamentos

Si tu empresa es pequeña y no necesitas departamentos:

- Puedes dejar todos los empleados **"Sin departamento"**
- O crear un único departamento genérico llamado "Empresa"
- Los reportes se generarán a nivel global sin filtros

---

## Preguntas frecuentes

### ¿Puedo tener empleados sin departamento?

Sí, los empleados pueden existir sin departamento asignado, aunque no es recomendable si usas Managers.

### ¿Cuántos departamentos puedo crear?

No hay límite. Puedes crear tantos departamentos como necesites según la estructura de tu empresa.

### ¿Un empleado puede estar en varios departamentos a la vez?

No, cada empleado solo puede pertenecer a **un departamento** a la vez. Si necesitas gestionar empleados que trabajan en varias áreas, considera crear departamentos transversales o usar otro método de clasificación.

### ¿Los departamentos afectan a los horarios?

No directamente, pero puedes asignar horarios específicos por departamento al crear o editar los horarios de trabajo.

### ¿Qué pasa si elimino un departamento con empleados asignados?

AhoraFicho **no permite eliminar** departamentos con empleados activos. Primero debes reasignar o desactivar los empleados.

---

## ¿Necesitas ayuda?

Si tienes problemas con la gestión de departamentos:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Dar de Alta Empleados](/guias-por-rol/administrador/dar-alta-empleados/)
- 👉 [Asignar Horarios](/guias-por-rol/administrador/asignar-horarios/)
- 👉 [Gestión de Edificios](/guias-por-rol/administrador/gestion-edificios/)
- 👉 [Guía del Manager](/guias-por-rol/manager/)