---
layout: default
title: Configurar Turnos Rotativos
parent: Administrador
grand_parent: Guías por Rol
nav_order: 5
---

# Configurar Turnos Rotativos
{: .no_toc }

Cómo gestionar turnos rotativos y horarios variables para empleados con jornadas cambiantes.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué son los turnos rotativos?

Los **turnos rotativos** permiten asignar horarios cambiantes a empleados que trabajan en diferentes franjas:

- 🌅 **Turno de mañana**: 06:00 - 14:00
- 🌞 **Turno de tarde**: 14:00 - 22:00
- 🌙 **Turno de noche**: 22:00 - 06:00

**Casos de uso comunes:**
- Fábricas con producción 24/7
- Hospitales y centros de salud
- Empresas de seguridad
- Call centers
- Servicios de limpieza y mantenimiento

---

## Diferencia entre Horarios y Turnos

### Horarios (fijos)
- El empleado tiene el **mismo horario** todos los días
- Ejemplo: Lunes a Viernes 9:00-18:00
- Se configura una vez y no cambia

### Turnos (variables)
- El empleado tiene **horarios diferentes** según el día
- Ejemplo: Lunes mañana, Martes tarde, Miércoles noche
- Se planifica semana a semana o mes a mes

{: .note }
> Si tus empleados tienen horario fijo, usa [Horarios](/guias-por-rol/administrador/crear-horarios/). Solo usa Turnos si los horarios rotan.

---

## Acceder a Gestión de Turnos

1. Ve al menú lateral **"Empresa"** (sección ADMIN)
2. Selecciona **"Gestión de Turnos"**
3. Verás el calendario de turnos

---

## Vista del Calendario de Turnos

El calendario muestra:

```
┌─────────────────────────────────────────────────────┐
│  < Mayo 2025 >            [Semana] [Mes] [Día]     │
├─────────────────────────────────────────────────────┤
│                                                     │
│  Lun 5  │ Mar 6  │ Mié 7  │ Jue 8  │ Vie 9        │
├─────────┼────────┼────────┼────────┼────────────────┤
│ 06-14h  │ 14-22h │ 06-14h │ 22-06h │ 06-14h       │
│ Juan P. │ Juan P.│ Juan P.│ Juan P.│ Juan P.      │
│         │        │        │        │              │
│ 14-22h  │ 06-14h │ 14-22h │ 06-14h │ LIBRE        │
│ Ana M.  │ Ana M. │ Ana M. │ Ana M. │ Ana M.       │
└─────────┴────────┴────────┴────────┴──────────────┘
```

**Leyenda de colores:**
- 🟢 **Verde**: Turno de mañana (06-14h)
- 🟡 **Amarillo**: Turno de tarde (14-22h)
- 🔵 **Azul**: Turno de noche (22-06h)
- ⚪ **Blanco**: Día libre

---

## Crear un turno

### Método 1: Desde el calendario (arrastrar y soltar)

1. Haz clic en una celda del calendario
2. Se abrirá el modal de creación de turno

### Método 2: Botón "Crear turno"

1. Haz clic en **"Crear turno"** (botón superior)
2. Se abrirá el formulario

---

## Formulario de creación de turno

**Trabajador** (obligatorio)
- Selecciona el empleado
- Solo empleados con módulo de turnos activo

**Fecha** (obligatorio)
- Día del turno
- Selecciona del calendario

**Primer turno:**
- **Hora inicio**: Ej: 06:00
- **Hora fin**: Ej: 14:00

**Segundo turno (opcional):**
- **Hora inicio**: Ej: 16:00
- **Hora fin**: Ej: 18:00
- Útil para turnos partidos

**Descripción** (opcional)
- Notas sobre el turno
- Ejemplo: "Cobertura por baja", "Turno extra"

---

## Tipos de turnos estándar

### Turno de Mañana
```
Hora inicio: 06:00
Hora fin: 14:00
Total: 8 horas
```

### Turno de Tarde
```
Hora inicio: 14:00
Hora fin: 22:00
Total: 8 horas
```

### Turno de Noche
```
Hora inicio: 22:00
Hora fin: 06:00 (día siguiente)
Total: 8 horas
```

{: .note }
> El sistema calcula correctamente turnos que cruzan medianoche.

### Turno Partido
```
Primer turno: 08:00 - 12:00
Segundo turno: 16:00 - 20:00
Total: 8 horas (4h + 4h)
```

---

## Copiar turnos de una semana

Para copiar los turnos de una semana completa:

1. Selecciona la semana origen en el calendario
2. Haz clic en **"Copiar semana"** (botón superior)
3. Selecciona la semana destino
4. Confirma

**Utilidad:**
- Turnos que se repiten semanalmente
- Agiliza la planificación mensual
- Evita crear turnos uno por uno

{: .tip }
> Si tus turnos se repiten cada semana, copia la semana patrón para todo el mes.

---

## Editar un turno

Para modificar un turno existente:

### Método 1: Click en el turno del calendario
1. Haz clic en el turno
2. Se abrirá el modal de edición
3. Modifica lo necesario
4. Guarda

### Método 2: Arrastrar y soltar
1. Arrastra el turno a otro día
2. El sistema actualizará la fecha automáticamente

{: .warning }
> No puedes arrastrar turnos partidos (con 2 franjas). Debes editarlos manualmente.

---

## Eliminar un turno

Para eliminar un turno:

1. Haz clic en el turno en el calendario
2. Haz clic en **"Eliminar"** o icono 🗑️
3. Confirma la eliminación

{: .important }
> Eliminar un turno NO elimina los fichajes. Si el empleado ya fichó, su registro permanece.

---

## Filtrar vista de turnos

### Filtrar por trabajador

```
[🔍 Seleccionar trabajador ▼]

Opciones:
- Todos los trabajadores
- Juan Pérez ✓
- Ana Martínez
- Pedro López
```

Al seleccionar un trabajador:
- El calendario muestra solo sus turnos
- Útil para planificar individualmente

### Cambiar vista temporal

**Vista Semana:**
- Muestra 7 días
- Ideal para planificación semanal

**Vista Mes:**
- Muestra todo el mes
- Visión general de turnos

**Vista Día:**
- Muestra un solo día
- Todos los trabajadores en ese día

---

## Planificación de turnos rotativos

### Patrón semanal común (rotación 1 semana)

**Semana 1:**
- Lunes a Viernes: Turno mañana (06-14h)
- Sábado-Domingo: Libre

**Semana 2:**
- Lunes a Viernes: Turno tarde (14-22h)
- Sábado-Domingo: Libre

**Semana 3:**
- Lunes a Viernes: Turno noche (22-06h)
- Sábado-Domingo: Libre

**Semana 4:**
- Vuelta a semana 1

### Patrón 4-3-3 (4 días trabajo, 3 días descanso)

```
L  M  X  J  V  S  D  | L  M  X  J  V  S  D
M  M  M  M  -  -  -  | T  T  T  T  -  -  -

M = Mañana
T = Tarde
- = Libre
```

### Cobertura 24/7 con 3 empleados

**Empleado A:** Turno mañana toda la semana
**Empleado B:** Turno tarde toda la semana
**Empleado C:** Turno noche toda la semana

Rotación semanal:
- Semana 1: A=mañana, B=tarde, C=noche
- Semana 2: A=tarde, B=noche, C=mañana
- Semana 3: A=noche, B=mañana, C=tarde
- Semana 4: Vuelta a semana 1

---

## Mis Turnos (Vista del Empleado)

Los empleados pueden ver sus turnos asignados:

1. **"Mi Trabajo"** → **"Mis Turnos"**
2. Ven su calendario personal con:
   - Turnos asignados
   - Horas por turno
   - Resumen semanal

**Resumen del período:**
```
┌───────────────────────────────┐
│ Resumen del período actual    │
├───────────────────────────────┤
│ Turnos totales: 20           │
│ Horas totales: 160h          │
│ Esta semana: 40h             │
│ Promedio diario: 8h          │
└───────────────────────────────┘
```

---

## Notificaciones de turnos

### Recordatorios automáticos

Si está configurado, los empleados reciben:

**Email/WhatsApp:**
- 📧 Turno asignado para mañana
- 📧 Recordatorio 1 hora antes del turno
- 📧 Cambios en turnos asignados

### Configurar notificaciones

1. Ve a **"Configuraciones"** → **"Notificaciones"**
2. Configura:
   - ☑️ Notificar nuevos turnos
   - ☑️ Recordatorio antes de turno
   - ⏰ Horas de antelación (ej: 24h)

---

## Reportes de turnos

### Reporte de Servicios

Para empresas con módulo de Servicios (limpieza, mantenimiento):

1. **"Reportes"** → **"Reporte de servicios"**
2. Filtra por:
   - Fecha
   - Empleado
   - Tipo de servicio
3. Exporta en Excel/PDF

Ver: [Reportes](/reportes/)

---

## Casos especiales

### Turno extra o cobertura puntual

Para asignar un turno extra a un empleado:

1. Crea el turno normalmente
2. En descripción anota: "Turno extra - cobertura [nombre]"
3. Notifica al empleado manualmente

### Cambio de turno entre empleados

Si dos empleados quieren intercambiar turnos:

1. Elimina ambos turnos originales
2. Crea los nuevos turnos para cada uno
3. Anota en descripción: "Intercambio con [nombre]"

{: .note }
> No hay función automática de intercambio. Se hace manualmente.

### Empleado con horario mixto

Si un empleado tiene algunos días con horario fijo y otros con turnos:

- Asigna horario fijo como base
- Crea turnos solo para días variables
- Los turnos sobrescriben el horario fijo esos días

---

## Mejores prácticas

### ✅ Recomendaciones

**Planificación:**
- Planifica turnos con 2-4 semanas de antelación
- Comunica cambios con 48h mínimo
- Mantén patrones regulares (si es posible)

**Equidad:**
- Rota turnos nocturnos entre todos
- Distribuye fines de semana equitativamente
- Respeta preferencias cuando sea posible

**Comunicación:**
- Publica turnos visibles para todos
- Notifica cambios inmediatamente
- Permite intercambios con aprobación

### ❌ Evita

- Cambios de última hora sin motivo
- Asignar siempre noche a las mismas personas
- No respetar descansos mínimos legales
- Ignorar solicitudes de cambio justificadas

---

## Normativa legal sobre turnos

### Descansos mínimos

Según legislación laboral española:

- **Entre jornadas**: 12 horas mínimo
- **Semanal**: 1,5 días ininterrumpidos
- **Máximo consecutivo**: Normalmente 6 días

{: .warning }
> Verifica que tus turnos rotativos cumplen con el convenio colectivo de tu sector.

### Plus de nocturnidad

Los turnos nocturnos (22:00-06:00) pueden requerir:
- Plus salarial
- Reducción de jornada
- Reconocimientos médicos específicos

{: .note }
> AhoraFicho registra las horas nocturnas. El cálculo del plus se hace en nómina.

---

## Integración con fichajes

### ¿Cómo funcionan juntos?

**Turnos asignados:**
- Definen cuándo DEBE trabajar el empleado

**Fichajes:**
- Registran cuándo REALMENTE fichó el empleado

**Comparación:**
- En reportes se compara turno vs fichaje real
- Detecta impuntualidades
- Calcula horas extras

**Ejemplo:**
```
Turno asignado: 06:00 - 14:00
Fichaje real:
  Entrada: 06:10 (10 min tarde)
  Salida: 14:30 (30 min extra)
  
Resultado: ⚠️ Impuntualidad + 30 min extra
```

---

## Preguntas frecuentes

### ¿Los turnos reemplazan a los horarios?

No, son complementarios:
- **Horario fijo**: Base para empleados estables
- **Turnos**: Sobrescriben el horario en días específicos

### ¿Puedo tener empleados con horario fijo y otros con turnos?

Sí, perfectamente. Cada empleado puede tener:
- Solo horario fijo
- Solo turnos
- Horario fijo + turnos puntuales

### ¿Los empleados pueden ver turnos de compañeros?

Depende de la configuración:
- Por defecto: Solo ven sus propios turnos
- Si se habilita: Pueden ver calendario del equipo

### ¿Qué pasa si un empleado ficha sin turno asignado?

El fichaje se registra normalmente. En reportes aparecerá:
- Fichaje válido
- Sin turno asignado
- Puede considerarse irregular (según tu política)

---

## ¿Necesitas ayuda?

Si tienes problemas con turnos rotativos:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)
- 📞 Soporte telefónico

---

## Guías relacionadas

- 👉 [Crear Horarios](/guias-por-rol/administrador/crear-horarios/)
- 👉 [Asignar Horarios](/guias-por-rol/administrador/asignar-horarios/)
- 👉 [Reportes de servicios](/reportes/)