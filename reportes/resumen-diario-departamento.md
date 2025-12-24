---
layout: default
title: Resumen Diario por Departamento
parent: Reportes
nav_order: 3
---

# Resumen Diario por Departamento
{: .no_toc }

Visualiza los fichajes, horas trabajadas e incidencias de tu equipo día a día. Este reporte te permite supervisar el cumplimiento horario diario de cada empleado de forma rápida y visual.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué es el Resumen Diario por Departamento?

Es un **reporte en tiempo real** que muestra el detalle de los fichajes de cada empleado de un departamento, día a día. Te permite:

- 📅 **Visualizar fichajes diarios**: Ver cada día laborable individualmente
- 👥 **Supervisar empleados**: Revisar el cumplimiento de cada persona
- ⏰ **Controlar horas**: Ver horas totales y efectivas trabajadas
- ⚠️ **Detectar incidencias**: Identificar problemas automáticamente
- 📊 **Filtrar fácilmente**: Por fecha, empleado o estado

{: .tip }
> Este reporte es ideal para **Managers** que necesitan hacer seguimiento diario de su equipo sin tener que revisar fichaje por fichaje.

---

## Acceder al Resumen Diario

### Paso 1: Navegar al reporte

1. Inicia sesión como **Manager** o **Administrador**
2. Ve al menú lateral y haz clic en **"Departamentos"**
3. Selecciona el departamento que quieres consultar
4. Haz clic en **"Resumen Diario"** o **"Ver Fichajes"**

![Acceso a resumen diario](/assets/images/placeholder-acceso-resumen-diario.png)

{: .note }
> **Para Managers**: Solo verás los departamentos de los que eres responsable. Los Administradores pueden ver todos los departamentos de la empresa.

---

## Entender las tarjetas de resumen

En la parte superior del reporte verás **4 tarjetas** con estadísticas clave del período seleccionado:

### 📅 Total de Días

- **Qué muestra**: Número de días incluidos en el reporte según los filtros aplicados
- **Ejemplo**: 22 días (todos los días laborables de un mes)

### 👥 Total de Empleados

- **Qué muestra**: Número de empleados únicos del departamento con fichajes en el período
- **Color**: Verde
- **Ejemplo**: 15 empleados

### ⏰ Total de Horas

- **Qué muestra**: Suma de todas las horas trabajadas por todos los empleados
- **Color**: Amarillo/Naranja
- **Cálculo**: Suma de horas de todos los fichajes del período
- **Ejemplo**: 2.640 horas (15 empleados × 8h × 22 días)

### ⚠️ Incidencias

- **Qué muestra**: Número de días con problemas detectados (fichajes incompletos, retrasos, etc.)
- **Color**: Rojo
- **Ejemplo**: 8 incidencias

![Tarjetas de resumen](/assets/images/placeholder-tarjetas-resumen-diario.png)

---

## Usar los filtros

El reporte ofrece múltiples opciones de filtrado para encontrar exactamente lo que necesitas:

### Filtros disponibles

| Filtro | Descripción | Opciones |
|--------|-------------|----------|
| **Fecha Inicio** | Primer día del período | Selector de fecha |
| **Fecha Fin** | Último día del período | Selector de fecha |
| **Empleado** | Filtrar por un empleado específico | Desplegable con todos los empleados del departamento |
| **Estado** | Ver solo registros con o sin problemas | Todos / Solo incidencias / Solo correctos |

![Filtros del resumen diario](/assets/images/placeholder-filtros-resumen-diario.png)

### Filtros rápidos

AhoraFicho incluye **botones de acceso rápido** para los períodos más comunes:

- **Hoy**: Muestra solo el día actual
- **Ayer**: Muestra el día anterior
- **Esta semana**: Desde el lunes hasta hoy
- **Semana pasada**: Lunes a domingo de la semana anterior
- **Este mes**: Desde el día 1 del mes actual hasta hoy
- **Mes pasado**: Todo el mes anterior completo

{: .tip }
> Los filtros rápidos son muy útiles para revisiones rutinarias. Por ejemplo, cada lunes puedes hacer clic en "Semana pasada" para revisar el cumplimiento de la semana anterior.

### Cómo aplicar filtros

1. Selecciona las fechas manualmente **o** haz clic en uno de los botones rápidos
2. (Opcional) Selecciona un empleado específico en el desplegable
3. (Opcional) Filtra por estado: "Solo incidencias" o "Solo correctos"
4. Haz clic en **"Filtrar"** (icono de lupa)
5. La tabla se actualizará automáticamente

---

## Interpretar la tabla de fichajes

La tabla principal muestra todos los registros diarios con la siguiente información:

### Columnas de la tabla

| Columna | Descripción |
|---------|-------------|
| **Empleado** | Nombre completo con avatar circular |
| **Fecha** | Día en formato DD/MM/AAAA |
| **Día Semana** | Día de la semana (badge azul) |
| **Nº Fichajes** | Cantidad de fichajes del día (entrada/salida) |
| **Total Horas** | Horas totales trabajadas (incluyendo pausas) |
| **Horas Efectivas** | Horas reales de trabajo (descontando pausas) |
| **Estado** | Correcto ✅ o Incidencia ⚠️ |

![Tabla resumen diario](/assets/images/placeholder-tabla-resumen-diario.png)

### Ejemplo de registro

```
Empleado: Juan Pérez
Fecha: 15/12/2024
Día Semana: Viernes
Nº Fichajes: 4 (badge verde)
Total Horas: 8h 30m
Horas Efectivas: 8h 00m
Estado: ✅ Correcto (badge verde)
```

### Interpretación de colores

**Número de Fichajes:**
- 🟢 **Verde (par)**: Número par de fichajes = Jornada cerrada correctamente
- 🟡 **Amarillo (impar)**: Número impar = Falta fichaje de salida

**Estado:**
- 🟢 **Verde "Correcto"**: Todo en orden
- 🔴 **Rojo "Incidencia"**: Hay algún problema detectado

---

## ¿Qué es una incidencia?

El sistema marca automáticamente como incidencia cuando detecta:

### Tipos de incidencias comunes

1. **Fichaje incompleto**: Falta entrada o salida
2. **Número impar de fichajes**: Jornada no cerrada
3. **Retraso significativo**: Entrada muy tarde respecto al horario
4. **Horas insuficientes**: Menos horas de las teóricas del horario
5. **Sin fichajes**: El empleado no registró ningún fichaje ese día

{: .important }
> Las incidencias requieren **revisión manual** por parte del manager o administrador. Accede al detalle del empleado para corregir o justificar el problema.

---

## Diferenciar Total Horas vs Horas Efectivas

### Total Horas

Son las horas **totales** desde el primer fichaje de entrada hasta el último de salida, incluyendo:
- ✅ Tiempo trabajado
- ✅ Pausas (comida, descansos)
- ✅ Tiempo entre fichajes

**Ejemplo:**
- Entrada: 09:00
- Salida comida: 14:00
- Entrada comida: 15:30
- Salida final: 18:30
- **Total Horas: 9h 30m** (de 09:00 a 18:30)

### Horas Efectivas

Son las horas **realmente trabajadas**, descontando las pausas:

**Mismo ejemplo:**
- Mañana: 09:00 a 14:00 = 5h
- Tarde: 15:30 a 18:30 = 3h
- **Horas Efectivas: 8h** (5h + 3h)

{: .tip }
> Para nóminas y cálculo de productividad, usa siempre las **Horas Efectivas**, ya que representan el tiempo real de trabajo.

---

## Ver el total del período

Al final de la tabla verás una **fila de totales** con:

- **Total Horas Trabajadas**: Suma de todas las horas del período
- **Total Horas Efectivas**: Suma de todas las horas efectivas del período

![Fila de totales](/assets/images/placeholder-totales-resumen-diario.png)

**Ejemplo:**
- 15 empleados
- 22 días laborables
- Jornada: 8 horas/día
- **Total Horas Esperadas**: 15 × 22 × 8 = 2.640 horas
- **Total Horas Efectivas Reales**: 2.580 horas
- **Diferencia**: -60 horas (ausencias, retrasos, etc.)

---

## Casos de uso prácticos

### Caso 1: Revisión diaria de cumplimiento

**Objetivo**: Supervisar que todos los empleados ficharon correctamente hoy.

**Pasos:**
1. Haz clic en el filtro rápido **"Hoy"**
2. Revisa la columna "Estado"
3. Si hay incidencias (badge rojo), haz clic en el empleado para ver detalles
4. Contacta con el empleado si es necesario

### Caso 2: Preparar reunión semanal con el equipo

**Objetivo**: Tener datos de la semana para la reunión del lunes.

**Pasos:**
1. El lunes por la mañana, haz clic en **"Semana pasada"**
2. Anota el total de horas trabajadas
3. Identifica empleados con más de 2 incidencias
4. Prepara puntos de conversación basados en datos reales

### Caso 3: Justificar ausencias ante RRHH

**Objetivo**: Proporcionar evidencia de que un empleado no trabajó ciertos días.

**Pasos:**
1. Filtra por el empleado específico
2. Establece el rango de fechas del período en cuestión
3. Captura pantalla o exporta a PDF
4. Adjunta como evidencia en comunicaciones con RRHH

### Caso 4: Detectar patrones de absentismo

**Objetivo**: Identificar si hay patrones en las ausencias (ej: muchos lunes).

**Pasos:**
1. Filtra por "Solo incidencias"
2. Revisa la columna "Día Semana"
3. Anota si hay días que se repiten más
4. Investiga las causas con el equipo

---

## Exportar el reporte

### Formatos disponibles

Puedes exportar el resumen diario en:

- **📄 PDF**: Para documentación o presentaciones
- **📊 Excel**: Para análisis avanzados, gráficos o importar a otras herramientas

### Cómo exportar

1. Aplica los filtros que necesites
2. Haz clic en el botón **"Exportar"** en la parte superior derecha
3. Selecciona el formato deseado
4. El archivo se descargará automáticamente con el nombre: `Resumen_Diario_[Departamento]_[Fecha].pdf`

---

## Preguntas frecuentes

### ¿Puedo ver empleados de otros departamentos?

- **Administrador**: Sí, puedes ver todos los departamentos
- **Manager**: Solo los departamentos de los que eres responsable

### ¿El reporte incluye fines de semana?

No, por defecto solo muestra días laborables según el calendario configurado. Los sábados y domingos aparecen solo si alguien fichó en esos días.

### ¿Qué pasa con los festivos?

Los festivos configurados en el sistema no aparecen como días laborables. Si un empleado ficha en festivo, aparecerá con una nota indicándolo.

### ¿Las incidencias se notifican automáticamente?

Puedes configurar notificaciones automáticas para recibir un email al final del día si hay incidencias. Ve a **"Configuración"** → **"Notificaciones"**.

### ¿Puedo comparar dos períodos diferentes?

No directamente en el mismo reporte, pero puedes exportar dos períodos a Excel y compararlos manualmente, o generar el reporte dos veces con filtros diferentes.

### ¿Cada cuánto se actualiza el reporte?

El reporte es en **tiempo real**. Cada vez que actualizas la página o cambias los filtros, los datos se refrescan desde la base de datos.

---

## Diferencias con el Resumen Semanal

| Característica | Resumen Diario | Resumen Semanal |
|----------------|----------------|-----------------|
| **Agrupación** | Por día individual | Por semana completa |
| **Detalle** | Máximo detalle día a día | Vista más resumida |
| **Ideal para** | Seguimiento operativo diario | Análisis de tendencias semanales |
| **Volumen de datos** | Más registros, más detalle | Menos registros, más manejable |

👉 **Ver también**: [Resumen Semanal por Departamento](/reportes/resumen-semanal-departamento/)

---

## Consejos de uso

✅ **Revisa diariamente**: Dedica 5 minutos cada mañana a revisar el día anterior

✅ **Actúa rápido**: Si detectas una incidencia, resuélvela el mismo día si es posible

✅ **Exporta mensualmente**: Guarda un PDF del mes completo como respaldo

✅ **Comunica expectativas**: Asegúrate de que tu equipo sabe que revisas estos reportes

✅ **No seas excesivamente punitivo**: Usa los datos para mejorar, no solo para sancionar

---

## ¿Necesitas ayuda?

Si tienes dudas sobre cómo interpretar o usar el reporte:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Resumen Semanal por Departamento](/reportes/resumen-semanal-departamento/)
- 👉 [Reporte de Impuntualidades](/reportes/reporte-impuntualidades/)
- 👉 [Gestión de Departamentos](/guias-por-rol/administrador/gestion-departamentos/)
- 👉 [¿Olvidé Fichar? (Empleado)](/guias-por-rol/empleado/olvide-fichar/)