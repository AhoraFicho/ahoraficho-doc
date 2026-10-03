---
layout: default
title: Crear Horarios
parent: Administrador
grand_parent: Guías por Rol
nav_order: 3
---

# Crear Horarios
{: .no_toc }

Cómo crear y configurar horarios de trabajo personalizados en AhoraFicho.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué es un horario en AhoraFicho?

Un **horario** define la jornada laboral de un empleado:

- ⏰ Hora de entrada y salida
- ☕ Pausas (comida, descansos)
- 📅 Días de trabajo
- ⚖️ Flexibilidad permitida
- 🔔 Notificaciones de impuntualidad

---

## Tipos de horarios comunes

### Jornada continua (Horario intensivo)
- **Ejemplo**: 08:00 - 15:00 (sin pausa)
- **Total**: 7 horas diarias
- **Común en**: Verano, viernes

### Jornada partida
- **Ejemplo**: 09:00 - 14:00 y 16:00 - 19:00
- **Pausa**: 2 horas para comida
- **Total**: 8 horas diarias
- **Común en**: Oficinas, comercios

### Jornada reducida
- **Ejemplo**: 09:00 - 14:00
- **Total**: 5 horas diarias
- **Común en**: Media jornada, conciliación

### Horario flexible
- **Ejemplo**: Entrada entre 07:00-10:00
- **Flexibilidad**: ±30 minutos
- **Común en**: Empresas tecnológicas

---

## Acceder a Horarios

1. Ve al menú lateral **"Configuraciones"** (sección ADMIN)
2. Selecciona **"Horarios"**
3. Verás el listado de horarios existentes

---

## Crear nuevo horario

### Paso 1: Iniciar creación

1. Haz clic en **"Crear nuevo"** (botón superior)
2. Se abrirá el formulario de creación de horario

### Paso 2: Configuración básica

**Nombre del horario** (obligatorio)
- Nombre descriptivo del horario
- Ejemplos:
  - ✅ "Jornada Partida 9-18h"
  - ✅ "Intensivo Verano 8-15h"
  - ✅ "Media Jornada Mañanas"
  - ❌ "Horario 1" (poco descriptivo)

**Descripción** (opcional)
- Detalles adicionales del horario
- Ejemplo: "Horario de verano aplicable de junio a septiembre"

---

## Configurar días de la semana

Para cada día de la semana, configura:

### Lunes a Viernes

Para cada día puedes configurar:

**¿Día laborable?**
- ✅ Marcar si se trabaja ese día
- ❌ Desmarcar si es día libre

**Primer turno:**
- **Hora inicio**: Hora de entrada (ej: 08:00)
- **Hora fin**: Hora de salida del primer turno (ej: 14:00)

**Segundo turno (opcional):**
- **Hora inicio**: Vuelta de la pausa (ej: 16:00)
- **Hora fin**: Hora de salida final (ej: 19:00)

{: .note }
> Si es jornada continua, solo rellena el primer turno. Deja el segundo turno vacío.

### Sábado y Domingo

Configura igual que los días laborables:
- Marca si se trabaja
- Define turnos si aplica

---

## Ejemplos de configuración

### Ejemplo 1: Jornada Partida Típica

```
Nombre: "Jornada Partida 9-14h y 16-19h"

Lunes a Viernes:
✅ Laborable
Turno 1: 09:00 - 14:00
Turno 2: 16:00 - 19:00

Sábado y Domingo:
❌ No laborable
```

**Total**: 8 horas/día × 5 días = 40 horas/semana

### Ejemplo 2: Jornada Intensiva

```
Nombre: "Intensivo 8-15h"

Lunes a Viernes:
✅ Laborable
Turno 1: 08:00 - 15:00
Turno 2: (vacío)

Sábado y Domingo:
❌ No laborable
```

**Total**: 7 horas/día × 5 días = 35 horas/semana

### Ejemplo 3: Jornada con Sábados

```
Nombre: "L-S con Sábado Intensivo"

Lunes a Viernes:
✅ Laborable
Turno 1: 09:00 - 14:00
Turno 2: 15:00 - 18:00

Sábado:
✅ Laborable
Turno 1: 09:00 - 14:00
Turno 2: (vacío)

Domingo:
❌ No laborable
```

**Total**: (8h × 5 días) + (5h × 1 día) = 45 horas/semana

### Ejemplo 4: Turnos Nocturnos

```
Nombre: "Turno Noche 22-06h"

Lunes a Domingo:
✅ Laborable
Turno 1: 22:00 - 06:00 (día siguiente)
Turno 2: (vacío)
```

{: .warning }
> Para turnos que cruzan medianoche (22:00-06:00), el sistema calculará correctamente las horas.

---

## Flexibilidad horaria

### ¿Qué es la flexibilidad?

Margen de tiempo permitido para entrada/salida sin considerarse impuntualidad.

**Minutos de flexibilidad** (opcional)
- Introduce un número de minutos
- Ejemplo: 15 minutos
- Se aplica tanto a entrada como a salida

**Efecto de la flexibilidad:**

Con flexibilidad de **15 minutos** en horario 08:00-17:00:

- ✅ **Entrada válida**: 07:45 - 08:15
- ✅ **Salida válida**: 16:45 - 17:15
- ❌ **Fuera de rango**: Se marca como impuntualidad

{: .tip }
> **Recomendación**: 10-15 minutos es un margen razonable para la mayoría de empresas.

---

## Notificaciones de impuntualidad

### Configurar alertas de retraso

**Minutos para notificación de inicio** (opcional)
- Minutos de retraso antes de enviar notificación
- Ejemplo: 10 minutos
- Si se pone 10: alerta si entra >10 min tarde

**Minutos para notificación de fin** (opcional)
- Similar para la salida
- Ejemplo: 15 minutos
- Si se pone 15: alerta si sale >15 min antes

**¿A quién se notifica?**
- Al Manager del empleado
- Al Administrador
- Opcionalmente al propio empleado (si está configurado)

### Ejemplo de configuración

```
Horario: 08:00 - 17:00
Flexibilidad: 15 minutos
Notificación inicio: 10 minutos
Notificación fin: 15 minutos

Escenarios:
- Entrada 08:10 → ✅ OK (dentro de flexibilidad)
- Entrada 08:20 → ⚠️ ALERTA (>10 min tarde)
- Salida 16:50 → ✅ OK (dentro de flexibilidad)
- Salida 16:30 → ⚠️ ALERTA (>15 min antes)
```

---

## Registro de jornada en un paso

### ¿Qué es?

Sistema que permite al empleado registrar **toda su jornada de golpe**: en lugar de fichar entrada, pausas y salida una a una, pulsa **"Registrar Jornada"**, revisa (y ajusta si hace falta) los bloques de su horario del día y los confirma todos de una vez.

**¿Cuándo es útil?**
- Empleados de confianza que siempre cumplen horario
- Trabajadores sin acceso continuo a dispositivos de fichaje
- Simplificación del día a día

**☑️ Activarlo**
- Activa la opción correspondiente en el formulario del horario
- El botón del empleado cambiará de "Iniciar jornada" a **"Registrar Jornada"** en los días con ese horario
- Se registran todos los fichajes del día en una sola confirmación (transacción protegida contra duplicados)

{: .warning }
> **Atención**: Registrar la jornada sin fichar en el momento puede no cumplir requisitos legales estrictos en algunas inspecciones. Consulta con tu asesoría laboral.

---

## Guardar el horario

Una vez configurado todo:

1. Revisa que todos los datos son correctos
2. Verifica las horas de cada día
3. Comprueba la flexibilidad
4. Haz clic en **"Guardar"** o **"Crear"**

Verás un mensaje de confirmación:
✅ "Horario creado correctamente"

---

## Después de crear el horario

### Asignar a empleados

El horario creado aún no está asignado a nadie. Para asignarlo:

1. Ve a [Asignar Horarios](/guias-por-rol/administrador/asignar-horarios/)
2. Selecciona empleados
3. Asigna el horario creado

### Editar horario existente

Para modificar un horario:

1. Ve a **"Configuraciones"** → **"Horarios"**
2. Busca el horario en el listado
3. Haz clic en **"Editar"** (icono de lápiz ✏️)
4. Modifica lo necesario
5. Guarda

{: .important }
> **Importante**: Los cambios en un horario afectan a TODOS los empleados que lo tengan asignado.

---

## Casos especiales

### Horario con 3 turnos (muy raro)

Si necesitas más de 2 turnos:
- Crea horarios separados por franja
- O contacta con soporte para personalización

### Horarios cambiantes (por fechas)

Si tienes empleados con horarios cambiantes (por ejemplo, mañana/tarde/noche o horario de verano):
- NO cambies el horario fijo a mano cada semana
- Usa la **Asignación Masiva de Horarios** con cambios **temporales** (fecha de inicio y fecha de fin, con vuelta automática al horario habitual)
- Ver: [Asignar Horarios](/guias-por-rol/administrador/asignar-horarios/)

### Horario sin horas fijas (100% flexible)

Para trabajadores completamente flexibles:

```
Nombre: "Flexible Sin Horario"
Lunes a Viernes:
✅ Laborable
Turno 1: 00:00 - 23:59
Flexibilidad: 1440 minutos (todo el día)
Autofichaje: ❌ NO
```

{: .note }
> Con este horario, cualquier fichaje será válido. Útil para teletrabajo total.

### Media jornada

Para contratos de media jornada:

```
Nombre: "Media Jornada Mañana"
Lunes a Viernes:
✅ Laborable
Turno 1: 09:00 - 14:00

Total: 5 horas/día = 25 horas/semana
```

---

## Visualizar y gestionar horarios

### Listado de horarios

En **"Configuraciones"** → **"Horarios"** verás:

| Nombre | Descripción | Empleados | Acciones |
|:-------|:------------|:----------|:---------|
| Jornada Partida 9-18h | Horario estándar | 45 | ✏️ 🗑️ 👁️ |
| Intensivo Verano | Jun-Sep | 12 | ✏️ 🗑️ 👁️ |
| Media Jornada | 5h diarias | 8 | ✏️ 🗑️ 👁️ |

**Columna "Empleados":**
- Muestra cuántos empleados tienen ese horario asignado
- Haz clic en el número para ver el listado

### Ver detalles de un horario

1. Haz clic en el nombre del horario o en 👁️ "Ver detalles"
2. Verás:
   - Configuración completa del horario
   - Empleados que lo tienen asignado
   - Historial de cambios (si aplica)

---

## Eliminar un horario

### ¿Cuándo puedes eliminar?

Solo puedes eliminar un horario si:
- ❌ **NO tiene empleados asignados** actualmente
- ❌ **NO tiene histórico** (nunca estuvo asignado)

### Proceso de eliminación

1. Ve a **"Configuraciones"** → **"Horarios"**
2. Localiza el horario a eliminar
3. Haz clic en 🗑️ **"Eliminar"**
4. Confirma la eliminación

{: .warning }
> **Atención**: Si el horario tiene empleados asignados, primero debes reasignarles otro horario.

### ¿Qué hacer si tiene empleados asignados?

1. Crea el nuevo horario
2. [Reasigna los empleados](/guias-por-rol/administrador/asignar-horarios/) al nuevo horario
3. Una vez todos reasignados, elimina el antiguo

---

## Duplicar un horario

Para crear un horario similar a uno existente:

1. Ve a **"Configuraciones"** → **"Horarios"**
2. Haz clic en 📋 **"Duplicar"** (si está disponible)
3. O crea uno nuevo manualmente copiando la configuración

---

## Mejores prácticas

### ✅ Recomendaciones

**Nomenclatura clara:**
- Usa nombres descriptivos
- Incluye las horas en el nombre
- Ejemplo: "Partida 9-14 / 16-19" mejor que "Horario A"

**Crear horarios base:**
- "Jornada Partida Estándar"
- "Jornada Continua"
- "Media Jornada Mañanas"
- "Media Jornada Tardes"

**Configuración de flexibilidad:**
- 10-15 minutos es razonable para oficinas
- 5 minutos para trabajos de atención al cliente
- 30 minutos para teletrabajo

**Notificaciones:**
- Activa notificaciones de impuntualidad
- Configura según severidad deseada
- Evita alertas excesivas (desmotiva)

### ❌ Evita

- Nombres genéricos: "Horario 1", "Horario 2"
- Flexibilidad excesiva (>30 min) sin justificación
- Modificar horarios asignados sin avisar
- Crear horarios duplicados innecesariamente
- Borrar horarios con histórico

---

## Horarios especiales por temporada

### Horario de verano

Muchas empresas usan jornada intensiva en verano:

```
Nombre: "Jornada Intensiva Verano"
Periodo: Junio - Septiembre

Lunes a Viernes:
✅ Laborable
Turno 1: 08:00 - 15:00
Turno 2: (vacío)

Descripción: "Horario de verano del 1 de junio al 30 de septiembre"
```

**Cómo aplicarlo:**
1. Crea el horario de verano
2. En junio, reasigna empleados a este horario
3. En octubre, reasigna al horario estándar

Ver: [Asignar Horarios](/guias-por-rol/administrador/asignar-horarios/) para asignación masiva.

### Jornada reducida (viernes verano)

Otra opción común: viernes intensivo

```
Nombre: "Estándar con Viernes Intensivo"

Lunes a Jueves:
✅ Laborable
Turno 1: 09:00 - 14:00
Turno 2: 15:00 - 18:00

Viernes:
✅ Laborable
Turno 1: 08:00 - 15:00
Turno 2: (vacío)
```

---

## Validación de horarios

### Verificar cálculo de horas

AhoraFicho calcula automáticamente las horas semanales:

En la vista de detalle del horario verás:
```
Lunes: 8h
Martes: 8h
Miércoles: 8h
Jueves: 8h
Viernes: 7h
─────────
TOTAL: 39h/semana
```

Verifica que coincide con lo esperado.

### Probar con un empleado de prueba

Antes de asignar masivamente:
1. Asigna el horario a un empleado de prueba
2. Haz que fiche un día completo
3. Revisa el resumen diario
4. Verifica que los cálculos son correctos

---

## Preguntas frecuentes

### ¿Puedo tener horarios diferentes por día?

Sí, cada día de la semana puede tener horario diferente. Por ejemplo:
- Lunes a Jueves: 9-18h
- Viernes: 8-15h
- Sábado: 9-14h
- Domingo: No laborable

### ¿Qué pasa si modifico un horario asignado?

Los cambios se aplican inmediatamente a TODOS los empleados que tengan ese horario. Los empleados verán el nuevo horario en su perfil.

### ¿Puedo tener horarios con diferentes flexibilidades?

Sí, crea horarios separados:
- "Oficina - Flex 15min"
- "Atención Cliente - Flex 5min"
- "Teletrabajo - Flex 30min"

### ¿El horario afecta al cálculo de vacaciones?

No directamente. Las vacaciones se configuran en días, no en horas. Pero sí afecta a:
- Cálculo de horas trabajadas
- Reportes mensuales
- Comparación con jornada laboral

### ¿Qué hago si un empleado necesita horario único?

Opciones:
1. Crea un horario específico para él
2. Usa horario flexible y que fiche manualmente
3. Modifica uno existente si es temporal

---

## Integración con otros módulos

### Horarios y cambios temporales

Si necesitas que un empleado rote de horario por periodos (verano, turnos de mañana/tarde por semanas):
- El horario asignado es su horario base
- Usa la **Asignación Masiva** con **cambios temporales** (fecha inicio/fin) para rotaciones, con vuelta automática al horario base
- Ver [Asignar Horarios](/guias-por-rol/administrador/asignar-horarios/)

### Horarios y registro de jornada en un paso

Si activas el registro de jornada en un paso en el horario:
- El empleado registrará toda la jornada de golpe con el botón **"Registrar Jornada"**
- Útil para empleados muy regulares
- Ver [Registro de jornada en un paso](#registro-de-jornada-en-un-paso)

---

## ¿Necesitas ayuda?

Si tienes problemas al crear horarios:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)
- 📞 Soporte telefónico

---

## Guías relacionadas

- 👉 [Asignar Horarios](/guias-por-rol/administrador/asignar-horarios/)
- 👉 [Dar de alta empleados](/guias-por-rol/administrador/dar-alta-empleados/)