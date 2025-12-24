---
layout: default
title: Reporte de Impuntualidades
parent: Reportes
nav_order: 2
---

# Reporte de Impuntualidades
{: .no_toc }

Detecta y analiza automáticamente los retrasos en las entradas de tus empleados. Este reporte te ayuda a identificar patrones de impuntualidad y tomar medidas correctivas.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué es el Reporte de Impuntualidades?

Es un **reporte automático** que analiza los fichajes de entrada de tus empleados y detecta cuándo llegan tarde según su horario asignado. El sistema calcula automáticamente:

- ⏰ **Minutos de retraso**: Diferencia entre hora esperada y hora real de entrada
- 📊 **Nivel de gravedad**: Bajo, medio o alto según los minutos de retraso
- 📧 **Notificaciones enviadas**: Si se alertó al manager o administrador
- 📈 **Estadísticas**: Total de retrasos, promedio y tendencias

{: .tip }
> Este reporte es especialmente útil para **Managers y Administradores** que necesitan supervisar la puntualidad de su equipo sin tener que revisar manualmente cada fichaje.

---

## Acceder al Reporte de Impuntualidades

### Paso 1: Navegar al reporte

1. Inicia sesión como **Administrador** o **Manager**
2. Ve al menú lateral y haz clic en **"Reportes"**
3. Selecciona **"Impuntualidades"**

![Acceso a reporte de impuntualidades](/assets/images/placeholder-acceso-impuntualidades.png)

---

## Usar los filtros del reporte

El reporte ofrece múltiples filtros para analizar la información exactamente como necesitas:

### Filtros disponibles

| Filtro | Descripción | Ejemplo |
|--------|-------------|---------|
| **Departamento** | Ver retrasos de un departamento específico | Ventas, Producción |
| **Empleado** | Ver retrasos de un empleado concreto | Juan Pérez |
| **Fecha desde** | Inicio del período a analizar | 01/01/2024 |
| **Fecha hasta** | Fin del período a analizar | 31/01/2024 |

![Filtros del reporte](/assets/images/placeholder-filtros-impuntualidades.png)

### Cómo aplicar filtros

1. Selecciona los filtros que necesites en la parte superior del reporte
2. Haz clic en el botón **"Filtrar"** (icono de lupa)
3. El reporte se actualizará automáticamente con los resultados

{: .tip }
> **Limpiar filtros**: Haz clic en el botón **"X"** junto al botón Filtrar para resetear todos los filtros y ver todos los retrasos.

### Ejemplos de uso de filtros

**Ejemplo 1: Retrasos del último mes**
- Fecha desde: 01/12/2024
- Fecha hasta: 31/12/2024
- Departamento: (Todos)
- Empleado: (Todos)

**Ejemplo 2: Retrasos de un empleado específico**
- Fecha desde: 01/01/2024
- Fecha hasta: 31/12/2024
- Departamento: (Todos)
- Empleado: Juan Pérez

**Ejemplo 3: Retrasos de un departamento esta semana**
- Fecha desde: 18/12/2024
- Fecha hasta: 24/12/2024
- Departamento: Producción
- Empleado: (Todos)

---

## Entender las estadísticas del reporte

En la parte superior del reporte verás **4 tarjetas con estadísticas clave**:

### 📊 Total de Registros

- **Qué muestra**: Número total de retrasos detectados en el período filtrado
- **Color**: Azul
- **Ejemplo**: 45 registros de impuntualidad

### ⏱️ Total de Minutos

- **Qué muestra**: Suma de todos los minutos de retraso acumulados
- **Color**: Cyan
- **Ejemplo**: 320 minutos (5 horas y 20 minutos en total)

### 📈 Promedio de Minutos

- **Qué muestra**: Promedio de minutos de retraso por incidencia
- **Color**: Amarillo
- **Cálculo**: Total minutos / Total registros
- **Ejemplo**: 7 minutos de promedio por retraso

### 🚨 Registros Críticos

- **Qué muestra**: Número de retrasos considerados "graves" (más de 30 minutos)
- **Color**: Rojo
- **Ejemplo**: 8 retrasos críticos

![Estadísticas del reporte](/assets/images/placeholder-estadisticas-impuntualidades.png)

---

## Interpretar la tabla de impuntualidades

La tabla principal muestra todos los retrasos detectados con la siguiente información:

### Columnas de la tabla

| Columna | Descripción |
|---------|-------------|
| **Fecha** | Día en que ocurrió el retraso (con día de la semana) |
| **Empleado** | Nombre completo y email del trabajador |
| **Departamento** | Departamento(s) al que pertenece |
| **Horario** | Nombre del horario asignado |
| **Hora Esperada** | Hora de entrada según su horario |
| **Hora Real** | Hora en la que realmente fichó |
| **Minutos Retraso** | Diferencia en minutos (en rojo) |
| **Margen Flexible** | Minutos de tolerancia permitidos |
| **Gravedad** | Nivel del retraso: Bajo, Medio, Alto |
| **Notificado** | Si se envió alerta al responsable |

![Tabla de impuntualidades](/assets/images/placeholder-tabla-impuntualidades.png)

### Ejemplo de registro

```
Fecha: 15/12/2024 (Viernes)
Empleado: Juan Pérez (juan.perez@empresa.com)
Departamento: Ventas
Horario: Jornada Estándar 9-18h
Hora Esperada: 09:00
Hora Real: 09:25
Minutos Retraso: 25 min
Margen Flexible: 10 min
Gravedad: Medio
Notificado: ✅ Sí
```

---

## Niveles de gravedad

AhoraFicho clasifica automáticamente los retrasos en 3 niveles según los minutos:

### 🟢 Gravedad Baja (Low)

- **Rango**: 0-15 minutos de retraso
- **Color**: Azul claro
- **Descripción**: Retrasos leves, dentro del margen habitual
- **Acción recomendada**: Seguimiento pasivo

### 🟡 Gravedad Media (Medium)

- **Rango**: 16-30 minutos de retraso
- **Color**: Amarillo/Naranja
- **Descripción**: Retrasos significativos que requieren atención
- **Acción recomendada**: Conversación con el empleado

### 🔴 Gravedad Alta (High)

- **Rango**: Más de 30 minutos de retraso
- **Color**: Rojo
- **Descripción**: Retrasos graves que afectan la operativa
- **Acción recomendada**: Medidas correctivas inmediatas

{: .note }
> **Margen flexible**: Si has configurado un margen de tolerancia (por ejemplo, 10 minutos), el sistema lo resta antes de calcular la gravedad. Ejemplo: Llega a las 09:12 con margen de 10 min → Solo 2 minutos de retraso real.

---

## Sistema de notificaciones

### ¿Cuándo se envían notificaciones?

El sistema puede configurarse para enviar alertas automáticas cuando:

1. Un empleado llega tarde más de X minutos
2. Un empleado acumula Y retrasos en un período
3. Un departamento supera un umbral de impuntualidad

### Estado de notificación

En la última columna de la tabla verás:

- ✅ **Icono verde (check)**: Notificación enviada correctamente
- ❌ **Icono rojo (X)**: Notificación no enviada o fallida

{: .tip }
> Si ves muchas notificaciones fallidas, verifica que los emails de los managers estén correctamente configurados en sus perfiles.

---

## Margen flexible de entrada

### ¿Qué es el margen flexible?

Es un **tiempo de tolerancia** que puedes configurar por horario para permitir pequeños retrasos sin penalización.

**Ejemplo práctico:**
- Horario de entrada: 09:00
- Margen flexible: 10 minutos
- El empleado puede fichar hasta las **09:10** sin que se considere retraso

### Configurar el margen flexible

1. Ve a **"Configuración"** → **"Horarios"**
2. Edita el horario deseado
3. En el campo **"Margen de tolerancia entrada"**, introduce los minutos (ejemplo: 10)
4. Guarda los cambios

{: .note }
> El margen flexible aparece en el reporte para que veas cuántos minutos de tolerancia tiene cada empleado. Los minutos de retraso mostrados ya tienen el margen descontado.

---

## Exportar el reporte

### Formatos disponibles

Puedes exportar el reporte de impuntualidades en:

- **📄 PDF**: Formato oficial para presentaciones o archivo
- **📊 Excel**: Formato editable para análisis avanzados o gráficos

### Cómo exportar

1. Aplica los filtros que necesites
2. Haz clic en el botón **"Exportar"** en la parte superior
3. Selecciona el formato deseado (PDF o Excel)
4. El archivo se descargará automáticamente

![Exportar reporte](/assets/images/placeholder-exportar-impuntualidades.png)

---

## Casos de uso prácticos

### Caso 1: Detectar empleados con impuntualidad recurrente

**Objetivo**: Identificar empleados que llegan tarde habitualmente.

**Pasos:**
1. Filtra por el último mes completo (ejemplo: diciembre)
2. Ordena la tabla por "Empleado" (agrupar por persona)
3. Identifica empleados con 5 o más registros de retraso
4. Agenda una reunión individual para abordar el tema

### Caso 2: Analizar impuntualidad por departamento

**Objetivo**: Comparar qué departamentos tienen más problemas de puntualidad.

**Pasos:**
1. Filtra por trimestre (ejemplo: octubre-diciembre)
2. Genera un reporte por cada departamento
3. Compara el promedio de minutos de retraso
4. Identifica si hay un patrón relacionado con el tipo de trabajo o ubicación

### Caso 3: Seguimiento de mejora tras una acción correctiva

**Objetivo**: Verificar si las medidas tomadas están funcionando.

**Pasos:**
1. Filtra por empleado específico
2. Compara retrasos de los últimos 3 meses:
   - Mes 1: Antes de la acción correctiva
   - Mes 2-3: Después de la acción correctiva
3. Evalúa si ha disminuido la frecuencia y gravedad

### Caso 4: Justificación de amonestaciones

**Objetivo**: Documentar retrasos para expediente disciplinario.

**Pasos:**
1. Filtra por empleado y período (últimos 6 meses)
2. Exporta el reporte a PDF
3. Incluye el documento en el expediente
4. Úsalo como evidencia objetiva en reuniones de RRHH

---

## Preguntas frecuentes

### ¿El reporte incluye retrasos de todos los empleados?

Depende de tu rol:
- **Administrador**: Ve todos los empleados de la empresa
- **Manager**: Solo ve empleados de su(s) departamento(s) asignado(s)

### ¿Qué pasa si un empleado tiene horario flexible?

Si el empleado tiene horario flexible (sin hora fija de entrada), no aparecerá en el reporte de impuntualidades, ya que no hay una hora de referencia para calcular retrasos.

### ¿Los retrasos afectan el cálculo de horas trabajadas?

No directamente. El reporte de impuntualidades es independiente del cálculo de horas totales. Un empleado que llega tarde puede compensar saliendo más tarde si su horario lo permite.

### ¿Se cuentan los retrasos en días con incidencias meteorológicas?

No, si en tu ciudad hay una incidencia oficial (nieve, temporal, etc.), puedes excluir esos días aplicando filtros o justificando manualmente los retrasos de ese día.

### ¿Puedo configurar diferentes márgenes por empleado?

No, el margen flexible se configura por **horario**, no por empleado individual. Pero puedes crear horarios diferentes con márgenes distintos y asignar a cada empleado el que corresponda.

### ¿Los retrasos se notifican automáticamente?

Sí, si has configurado el sistema de notificaciones. Puedes activar o desactivar las alertas automáticas desde **"Configuración"** → **"Notificaciones"**.

---

## Consejos para gestionar impuntualidades

### Prevención

✅ **Comunica expectativas claras**: Asegúrate de que todos los empleados conocen su horario y la política de puntualidad

✅ **Revisa los horarios**: Verifica que los horarios asignados sean realistas considerando distancias, transporte público, etc.

✅ **Margen flexible razonable**: Un margen de 10-15 minutos es habitual en muchas empresas

### Seguimiento

✅ **Revisa el reporte semanalmente**: No esperes a fin de mes para detectar problemas

✅ **Busca patrones**: ¿Los retrasos son siempre lunes? ¿Solo en invierno? Puede haber causas externas

✅ **Diferencia casos aislados de hábitos**: Un retraso ocasional no es lo mismo que impuntualidad sistemática

### Acción

✅ **Conversación privada**: Aborda el tema de forma individual y respetuosa

✅ **Escucha razones**: Puede haber motivos justificados (problemas transporte, situación personal)

✅ **Plan de mejora**: Establece objetivos claros y plazo para corregir

✅ **Documenta**: Guarda exportaciones del reporte para tener evidencia si es necesario

---

## ¿Necesitas ayuda?

Si tienes dudas sobre cómo interpretar o usar el reporte:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Crear Horarios](/guias-por-rol/administrador/crear-horarios/)
- 👉 [Asignar Horarios](/guias-por-rol/administrador/asignar-horarios/)
- 👉 [Resumen Diario por Departamento](/reportes/resumen-diario-departamento/)
- 👉 [Informe para Inspección de Trabajo](/reportes/informe-inspeccion-trabajo/)