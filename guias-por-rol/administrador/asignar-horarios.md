---
layout: default
title: Asignar Horarios
parent: Administrador
grand_parent: Guías por Rol
nav_order: 4
---

# Asignar Horarios
{: .no_toc }

Cómo asignar horarios a empleados de forma individual o masiva.
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

Existen **tres formas** de asignar horarios:

### 1. Asignación individual simple
Al dar de alta o editar un empleado

### 2. Asignación masiva
Asignar el mismo horario a múltiples empleados a la vez

### 3. Asignación programada
Programar cambios de horario para fechas futuras

---

## Asignación Individual Simple

### Durante el alta de empleado

Cuando [das de alta un empleado](/guias-por-rol/administrador/dar-alta-empleados/):

1. En el formulario de empleado
2. Sección **"Configuración Laboral"**
3. Campo **"Horario"**
4. Selecciona el horario del desplegable
5. Guarda el empleado

### Para empleado existente

1. Ve a **"Configuraciones"** → **"Trabajadores"**
2. Busca el empleado
3. Haz clic en **"Editar"** ✏️
4. Cambia el horario en el desplegable
5. Haz clic en **"Guardar"**

{: .note }
> Este método cambia el horario **inmediatamente**. Para cambios programados, usa la asignación masiva.

---

## Asignación Masiva de Horarios

### Cuándo usar asignación masiva

- 📅 Cambio de horario de verano (muchos empleados)
- 🏢 Nuevo departamento con mismo horario
- 🔄 Reorganización empresarial
- 📊 Ajustes por departamento

### Acceder a Asignación Masiva

1. Ve a **"Configuraciones"** → **"Horarios"**
2. Haz clic en el horario que quieres asignar
3. Haz clic en **"Asignación Masiva"** o botón similar

**O desde el menú:**

1. Busca la opción **"Asignación Masiva de Horarios"** en Configuraciones
2. Se abrirá el panel de asignación masiva

---

## Panel de Asignación Masiva

### Sección 1: Seleccionar Empleados

**Filtrar empleados:**

Puedes filtrar por:
- **Todos los empleados** (marca/desmarca todos)
- **Por departamento**: Solo empleados de un departamento específico
- **Por horario actual**: Empleados que tengan X horario ahora
- **Búsqueda**: Por nombre o email

**Seleccionar empleados:**

```
☑️ Seleccionar Todos   |  ☐ Deseleccionar Todos

🔍 Filtrar por departamento: [Todos ▼]

Empleados seleccionados: 12

☑️ Juan Pérez - Ventas (Horario actual: Jornada Partida)
☑️ María García - Ventas (Horario actual: Jornada Partida)
☐ Pedro López - Marketing (Horario actual: Intensivo)
☑️ Ana Martínez - Ventas (Horario actual: Jornada Partida)
...
```

{: .tip }
> **Consejo**: Usa los filtros para seleccionar rápidamente grupos de empleados.

### Sección 2: Seleccionar Horario

**Horario a asignar:**

Selecciona del desplegable el horario que quieres asignar:

```
Seleccionar Horario: [Jornada Intensiva Verano ▼]

Opciones:
- Jornada Partida 9-18h
- Jornada Intensiva 8-15h
- Jornada Intensiva Verano ✓
- Media Jornada Mañanas
- Media Jornada Tardes
```

### Sección 3: Fecha de Inicio

**¿Cuándo aplicar el cambio?**

Opciones:
- **Ahora (inmediato)**: Se aplica al guardar
- **Fecha específica**: Programa para una fecha futura

```
Fecha de inicio: [01/06/2025 📅]
```

**Ejemplo de uso:**
- Hoy es 15 de mayo
- Seleccionas fecha: 1 de junio
- El cambio se aplicará automáticamente el 1 de junio

### Sección 4: Descripción (opcional)

Campo de texto libre para documentar el cambio:

```
Descripción: _________________________________

Ejemplo: "Cambio a horario de verano según acuerdo laboral"
```

{: .tip }
> **Recomendación**: Documenta siempre cambios masivos para futuras referencias.

---

## Aplicar cambios

Una vez configurado todo:

1. Revisa el resumen:
   ```
   Empleados seleccionados: 25
   Horario a asignar: Jornada Intensiva Verano
   Fecha de inicio: 01/06/2025
   Descripción: Cambio a horario de verano
   ```

2. Haz clic en **"Aplicar Cambios"** o **"Guardar"**

3. Verás confirmación:
   ```
   ✅ Cambio de horario programado correctamente
   
   Se aplicará a 25 empleados el 01/06/2025
   ```

---

## Ver cambios programados

### Cambios pendientes

Para ver cambios de horario programados que aún no se han aplicado:

1. Ve a **"Configuraciones"** → **"Horarios"**
2. Busca sección **"Cambios Programados"** o **"Cambios Pendientes"**

Verás una tabla:

| Empleados | Horario Nuevo | Fecha Aplicación | Estado | Acciones |
|:----------|:--------------|:-----------------|:-------|:---------|
| 25 empleados | Intensivo Verano | 01/06/2025 | Pendiente | ❌ Cancelar |
| 5 empleados | Media Jornada | 15/06/2025 | Pendiente | ❌ Cancelar |

### Cancelar cambio programado

Si necesitas cancelar un cambio que aún no se ha aplicado:

1. Localiza el cambio en "Cambios Programados"
2. Haz clic en ❌ **"Cancelar"**
3. Confirma la cancelación

{: .warning }
> Solo puedes cancelar cambios **pendientes**. Los ya aplicados no pueden deshacerse (pero sí puedes hacer otro cambio).

---

## Historial de Cambios de Horario

### Ver historial global

1. Ve a **"Configuraciones"** → **"Horarios"**
2. Sección **"Historial de Cambios"**

Verás un registro de todos los cambios de horario realizados:

| Fecha | Empleados | Horario Anterior | Horario Nuevo | Aplicado Por | Estado |
|:------|:----------|:-----------------|:--------------|:-------------|:-------|
| 01/06/2025 | 25 | Partida 9-18h | Intensivo Verano | Admin | Aplicado |
| 15/05/2025 | 5 | Intensivo | Media Jornada | Admin | Aplicado |

### Ver historial de un empleado

Para ver el historial de horarios de un empleado específico:

1. Ve a **"Configuraciones"** → **"Trabajadores"**
2. Haz clic en el empleado
3. Sección **"Historial de Horarios"**

```
Horario Actual: Jornada Intensiva Verano
Desde: 01/06/2025

Historial:
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
01/06/2025 - Actual
Jornada Intensiva Verano
Aplicado por: Admin
Motivo: Cambio a horario de verano
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
01/01/2025 - 31/05/2025
Jornada Partida 9-18h
Aplicado por: Admin
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
15/09/2024 - 31/12/2024
Jornada Intensiva (antiguo)
Aplicado por: Admin
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## Casos de uso comunes

### Caso 1: Cambio de horario de verano

**Situación:**
- 50 empleados pasan a jornada intensiva en verano
- Del 1 de junio al 30 de septiembre

**Solución:**

**Paso 1 - 15 de mayo: Programar cambio a verano**
1. Asignación masiva
2. Selecciona 50 empleados
3. Horario: "Jornada Intensiva Verano"
4. Fecha: 01/06/2025
5. Descripción: "Cambio a horario de verano"
6. Aplicar

**Paso 2 - 15 de septiembre: Programar vuelta**
1. Asignación masiva
2. Selecciona los mismos 50 empleados
3. Horario: "Jornada Partida Estándar"
4. Fecha: 01/10/2025
5. Descripción: "Fin horario de verano"
6. Aplicar

{: .tip }
> Los cambios se aplicarán automáticamente en las fechas programadas.

### Caso 2: Nuevo departamento completo

**Situación:**
- Se crea departamento "Atención al Cliente" con 15 empleados
- Horario especial: 10:00 - 19:00

**Solución:**

1. Crea el horario "Atención Cliente 10-19h"
2. Asignación masiva
3. Filtra por departamento: "Atención al Cliente"
4. Selecciona todos (15 empleados)
5. Horario: "Atención Cliente 10-19h"
6. Fecha: Inmediato
7. Aplicar

### Caso 3: Empleado en reducción de jornada

**Situación:**
- Empleado pasa a media jornada temporal por conciliación
- Del 1 de julio al 31 de diciembre

**Solución:**

**Opción A: Individual simple**
1. Edita el empleado
2. Cambia horario a "Media Jornada"
3. Anota en observaciones la fecha de fin
4. Recordatorio manual para volver a cambiar en enero

**Opción B: Con asignación masiva (mejor)**
1. Programa cambio individual para 01/07/2025 a "Media Jornada"
2. Programa segundo cambio para 01/01/2026 de vuelta a "Jornada Completa"

### Caso 4: Empleados de campo con horario flexible

**Situación:**
- 10 comerciales sin horario fijo
- Necesitan fichaje pero sin restricciones horarias

**Solución:**

1. Crea horario "Flexible Comerciales"
   - Lun-Vie: 00:00 - 23:59
   - Flexibilidad: Todo el día
   - Sin notificaciones de impuntualidad
   
2. Asignación masiva
3. Selecciona los 10 comerciales
4. Asigna "Flexible Comerciales"

---

## Notificaciones a empleados

### ¿Se notifica el cambio?

Cuando cambias el horario de un empleado:

**Con cambio inmediato:**
- El empleado ve el nuevo horario en su perfil inmediatamente
- Se recomienda avisar por email/mensaje

**Con cambio programado:**
- El empleado ve su horario actual hasta la fecha programada
- Opcionalmente puede ver "Próximo cambio programado"

{: .important }
> **Recomendación**: SIEMPRE comunica cambios de horario a los empleados, aunque sea opcional. Evita malentendidos.

### Email de notificación manual

Puedes enviar email a los afectados:

```
Asunto: Cambio de horario - Junio 2025

Estimado equipo,

Os informamos que a partir del 1 de junio de 2025 pasaremos a 
horario de verano intensivo:

Lunes a Viernes: 08:00 - 15:00 (jornada continua)

Este horario estará vigente hasta el 30 de septiembre.

Podéis consultar vuestro horario actualizado en AhoraFicho 
en vuestro perfil.

Saludos,
RR.HH.
```

---

## Verificar asignaciones

### Comprobar que se aplicó correctamente

Después de asignar horarios:

1. Ve al listado de empleados
2. Verifica la columna "Horario"
3. Comprueba que todos tienen el horario correcto

### Generar reporte de horarios

Exporta un listado de empleados con sus horarios:

1. Ve a **"Configuraciones"** → **"Trabajadores"**
2. Haz clic en **"Exportar"**
3. El Excel incluirá la columna "Horario Asignado"

---

## Solución de problemas

### No veo la opción de asignación masiva

**Posibles causas:**
- No tienes permisos de Administrador
- La funcionalidad no está disponible en tu plan

**Solución:**
- Verifica tus permisos
- Contacta con soporte

### El cambio programado no se aplicó

**Verificaciones:**
1. ¿La fecha ya pasó?
2. ¿El cambio sigue en "Pendientes"?
3. ¿Hay algún error en el log?

**Solución:**
- Si sigue pendiente, cancélalo y vuelve a crearlo
- Contacta con soporte si persiste

### Empleado no aparece en la selección

**Causas:**
- Empleado desactivado
- Filtros activos que lo excluyen

**Solución:**
- Verifica que el empleado está activo
- Quita todos los filtros y busca por nombre

---

## Mejores prácticas

### ✅ Recomendaciones

**Planificación:**
- Programa cambios con 2 semanas de antelación
- Comunica a empleados antes del cambio
- Documenta el motivo en la descripción

**Verificación:**
- Revisa la lista de empleados seleccionados antes de aplicar
- Usa filtros para evitar seleccionar empleados incorrectos
- Genera reporte después de cambios masivos

**Comunicación:**
- Avisa siempre a los empleados
- Explica motivo y duración del cambio
- Recuerda fechas de vuelta (si aplica)

### ❌ Evita

- Cambiar horarios sin avisar
- Asignaciones masivas sin verificar selección
- Cancelar cambios programados a última hora
- No documentar cambios importantes
- Cambios retroactivos (fechas pasadas)

---

## Preguntas frecuentes

### ¿Puedo asignar diferentes horarios a empleados del mismo departamento?

Sí, cada empleado puede tener un horario diferente independientemente de su departamento.

### ¿Qué pasa si cambio el horario de un empleado a mitad de mes?

El sistema calculará correctamente:
- Días con horario antiguo → según horario antiguo
- Días con horario nuevo → según horario nuevo
- Los reportes mostrarán ambos períodos

### ¿Puedo ver qué horario tenía un empleado en una fecha pasada?

Sí, en el **Historial de Horarios** del empleado puedes ver todos sus horarios pasados con fechas exactas.

### ¿Los cambios de horario afectan a fichajes anteriores?

No, los fichajes pasados se mantienen con el horario que tenían en ese momento. Solo afecta a fichajes futuros.

### ¿Puedo programar múltiples cambios de horario?

Sí, puedes programar varios cambios para diferentes fechas futuras.

---

## ¿Necesitas ayuda?

Si tienes problemas al asignar horarios:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)
- 📞 Soporte telefónico

---

## Guías relacionadas

- 👉 [Crear Horarios](/guias-por-rol/administrador/crear-horarios/)
- 👉 [Configurar Turnos Rotativos](/guias-por-rol/administrador/configurar-turnos-rotativos/)
- 👉 [Dar de alta empleados](/guias-por-rol/administrador/dar-alta-empleados/)