---
layout: default
title: Resumen Semanal por Departamento
parent: Reportes
nav_order: 4
---

# Resumen Semanal por Departamento
{: .no_toc }

Analiza el rendimiento de tu equipo agrupado por semanas completas. Este reporte te ofrece una visión más resumida y manejable que el reporte diario, ideal para identificar tendencias a medio plazo.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué es el Resumen Semanal por Departamento?

Es un **reporte agregado** que agrupa los fichajes de cada empleado por **semana completa** (de lunes a domingo). Te permite:

- 📅 **Vista por semanas**: Ver cada semana como una unidad
- 📊 **Análisis de tendencias**: Detectar patrones semanales
- ⏰ **Horas acumuladas**: Ver totales semanales de forma clara
- 🔍 **Menos información, más claridad**: Datos resumidos y manejables
- 📈 **Comparar semanas**: Identificar mejoras o empeoramiento

{: .tip }
> Este reporte es ideal para **reuniones semanales** con tu equipo o para reportar a dirección el rendimiento de tu departamento.

---

## Acceder al Resumen Semanal

### Paso 1: Navegar al reporte

1. Inicia sesión como **Manager** o **Administrador**
2. Ve al menú lateral y haz clic en **"Departamentos"**
3. Selecciona el departamento que quieres consultar
4. Haz clic en **"Resumen Semanal"**

![Acceso a resumen semanal](/assets/images/placeholder-acceso-resumen-semanal.png)

---

## Entender las tarjetas de resumen

En la parte superior del reporte verás **4 tarjetas** con estadísticas clave del período seleccionado:

### 📅 Total de Semanas

- **Qué muestra**: Número de semanas incluidas en el reporte
- **Ejemplo**: 4 semanas (todo un mes completo)

### 👥 Total de Empleados

- **Qué muestra**: Número de empleados únicos del departamento
- **Color**: Verde
- **Ejemplo**: 15 empleados

### ⏰ Total de Horas

- **Qué muestra**: Suma de todas las horas trabajadas por todos los empleados en el período
- **Color**: Amarillo/Naranja
- **Cálculo**: Suma de horas efectivas de todas las semanas
- **Ejemplo**: 2.400 horas (15 empleados × 40h/semana × 4 semanas)

### ⚠️ Incidencias

- **Qué muestra**: Número de semanas con problemas detectados
- **Color**: Rojo
- **Ejemplo**: 5 semanas con incidencias

![Tarjetas de resumen semanal](/assets/images/placeholder-tarjetas-resumen-semanal.png)

---

## Usar los filtros

El reporte ofrece las mismas opciones de filtrado que el reporte diario, pero con resultados agrupados por semanas:

### Filtros disponibles

| Filtro | Descripción |
|--------|-------------|
| **Fecha Inicio** | Primera fecha del período a analizar |
| **Fecha Fin** | Última fecha del período a analizar |
| **Empleado** | Ver solo un empleado específico |
| **Estado** | Filtrar por "Todos", "Solo incidencias" o "Solo correctos" |

### Filtros rápidos

Los mismos botones que en el reporte diario:

- **Hoy**
- **Ayer**
- **Esta semana**
- **Semana pasada**
- **Este mes**
- **Mes pasado**

{: .note }
> Aunque selecciones "Hoy", el reporte mostrará la **semana completa** a la que pertenece ese día, no solo ese día individual.

---

## Interpretar la tabla de semanas

La tabla principal muestra los registros agrupados por semana:

### Columnas de la tabla

| Columna | Descripción |
|---------|-------------|
| **Empleado** | Nombre completo con avatar circular |
| **Año** | Año del registro (badge gris) |
| **Semana** | Número de semana del año (badge azul) |
| **Inicio Semana** | Fecha del lunes de esa semana + día de la semana |
| **Nº Fichajes** | Total de fichajes de toda la semana |
| **Total Horas** | Horas totales trabajadas en la semana |
| **Horas Efectivas** | Horas efectivas trabajadas en la semana |
| **Estado** | Correcto ✅ o Incidencia ⚠️ |

![Tabla resumen semanal](/assets/images/placeholder-tabla-resumen-semanal.png)

### Ejemplo de registro

```
Empleado: María García
Año: 2024 (badge gris)
Semana: Semana 50 (badge azul)
Inicio Semana: 11/12/2024 (Lunes)
Nº Fichajes: 10 (5 días × 2 fichajes)
Total Horas: 42h 30m
Horas Efectivas: 40h 00m
Estado: ✅ Correcto
```

### Cómo se calculan las semanas

AhoraFicho usa el **estándar ISO 8601** para la numeración de semanas:

- **Semana 1**: La primera semana del año que contiene un jueves
- **Semanas**: Van de lunes a domingo
- **Número**: De 1 a 52 (o 53 en años especiales)

**Ejemplo:**
- Año 2024, Semana 1: del 1 al 7 de enero
- Año 2024, Semana 52: del 23 al 29 de diciembre

---

## Interpretación de colores y estados

### Número de Fichajes

- 🟢 **Verde (par)**: Número par = Todas las jornadas cerradas correctamente
- 🟡 **Amarillo (impar)**: Número impar = Al menos una jornada sin cerrar

**Ejemplo:**
- 10 fichajes (verde) = 5 días × 2 fichajes = Todo correcto
- 9 fichajes (amarillo) = Falta 1 fichaje de salida

### Estado de la Semana

- 🟢 **Verde "Correcto"**: Toda la semana sin problemas
- 🔴 **Rojo "Incidencia"**: Al menos un día de la semana tiene problemas

---

## Diferencias clave con el Resumen Diario

| Característica | Resumen Diario | Resumen Semanal |
|----------------|----------------|-----------------|
| **Agrupación** | Cada día individual | Semana completa (5-7 días) |
| **Volumen de datos** | Muchos registros | Menos registros, más manejable |
| **Detalle** | Máximo detalle | Vista más resumida |
| **Ideal para** | Seguimiento operativo diario | Análisis de tendencias, reuniones |
| **Número de fichajes** | Por día (normalmente 2) | Por semana (normalmente 10) |

{: .tip }
> **Cuándo usar cada uno:**
> - **Diario**: Para control operativo del día a día
> - **Semanal**: Para reuniones de equipo, análisis de tendencias, reportes a dirección

---

## Ver el total del período

Al final de la tabla verás una **fila de totales** con:

- **Total Horas Trabajadas**: Suma de todas las horas del período completo
- **Total Horas Efectivas**: Suma de todas las horas efectivas del período

![Fila de totales](/assets/images/placeholder-totales-resumen-semanal.png)

**Ejemplo - 4 semanas:**
- 15 empleados
- 40 horas/semana por empleado
- **Total Horas Esperadas**: 15 × 40 × 4 = 2.400 horas
- **Total Horas Efectivas Reales**: 2.350 horas
- **Diferencia**: -50 horas (ausencias, retrasos, etc.)

---

## Casos de uso prácticos

### Caso 1: Preparar reunión semanal de equipo

**Objetivo**: Tener datos de la semana anterior para la reunión del lunes.

**Pasos:**
1. El lunes por la mañana, haz clic en **"Semana pasada"**
2. Revisa el total de horas efectivas del equipo
3. Identifica empleados con incidencias
4. Prepara los puntos de conversación para la reunión
5. Exporta a PDF y proyecta en la reunión

### Caso 2: Análisis mensual de productividad

**Objetivo**: Ver la evolución del departamento durante el mes.

**Pasos:**
1. Filtra por **"Mes pasado"**
2. Verás las 4 semanas del mes
3. Compara las horas efectivas de cada semana
4. Identifica si hay tendencias (mejora, empeoramiento, estabilidad)
5. Genera gráficos en Excel si exportas los datos

### Caso 3: Detectar semanas problemáticas

**Objetivo**: Identificar semanas con muchas ausencias o problemas.

**Pasos:**
1. Filtra por "Solo incidencias"
2. Ordena por semana
3. Identifica semanas con más registros problemáticos
4. Investiga las causas (¿festivos?, ¿formaciones?, ¿bajas?)

### Caso 4: Comparar rendimiento entre empleados

**Objetivo**: Ver quién está cumpliendo mejor sus horas semanales.

**Pasos:**
1. Filtra por un mes completo
2. Ordena la tabla por "Horas Efectivas"
3. Compara empleados con horario similar
4. Identifica desviaciones significativas
5. Conversa individualmente si es necesario

---

## Exportar el reporte

### Formatos disponibles

- **📄 PDF**: Ideal para presentaciones o reuniones
- **📊 Excel**: Para análisis avanzados con gráficos

### Cómo exportar

1. Aplica los filtros necesarios
2. Haz clic en el botón **"Exportar"**
3. Selecciona el formato
4. El archivo se descargará como: `Resumen_Semanal_[Departamento]_[Fecha].pdf`

{: .tip }
> **Consejo**: Exporta a Excel si quieres crear gráficos de evolución de horas por semana. Excel permite hacer análisis visuales muy potentes con estos datos.

---

## Preguntas frecuentes

### ¿Las semanas empiezan en lunes o en domingo?

Las semanas empiezan en **lunes** y terminan en **domingo**, siguiendo el estándar ISO 8601 usado en España y Europa.

### ¿Qué pasa si un mes tiene 5 semanas?

Si un mes abarca 5 semanas (por ejemplo, del 1 al 31 cruza 5 lunes), el reporte mostrará las 5 semanas completas. Algunas semanas pueden pertenecer parcialmente a dos meses diferentes.

### ¿Los festivos afectan al cálculo de horas esperadas?

Sí, si una semana tiene un festivo, las horas esperadas se ajustan automáticamente. Por ejemplo, si el jueves es festivo, se esperan 32h en vez de 40h.

### ¿Puedo ver detalles de qué días específicos tienen problemas?

No directamente en el reporte semanal. Si ves una semana con incidencias, usa el **Resumen Diario** para ver el detalle día a día de esa semana específica.

### ¿El reporte incluye empleados que ya no trabajan?

No, solo muestra empleados **activos**. Si necesitas ver histórico de un empleado desactivado, consulta el [Reporte Mensual](/reportes/reporte-mensual/).

### ¿Cómo se cuentan las semanas de inicio y fin de año?

Siguiendo ISO 8601:
- La **Semana 1** es la primera que contiene un jueves del año nuevo
- Puede haber una **Semana 53** en años especiales
- Las últimas semanas de diciembre pueden pertenecer ya al año siguiente

---

## Análisis de tendencias con el reporte semanal

### Detectar patrones de mejora

Si quieres ver si tu equipo está mejorando su puntualidad/cumplimiento:

1. Filtra por los últimos 3 meses (12 semanas)
2. Exporta a Excel
3. Crea un gráfico de líneas con:
   - Eje X: Semanas
   - Eje Y: Total de incidencias
4. Analiza si la línea baja (mejora) o sube (empeoramiento)

### Comparar productividad por trimestres

Para ver cómo varía la productividad a lo largo del año:

1. Genera reportes de los 4 trimestres
2. Compara el promedio de horas efectivas por semana
3. Identifica trimestres con menor rendimiento
4. Investiga causas (vacaciones de verano, Navidad, etc.)

---

## Consejos de uso

✅ **Revisa semanalmente**: Dedica 10 minutos cada lunes a revisar la semana anterior

✅ **Compara con semanas previas**: No mires solo la última semana, compara tendencias

✅ **Comunica resultados**: Comparte los datos con tu equipo de forma transparente

✅ **Celebra las semanas sin incidencias**: Refuerzo positivo cuando todo va bien

✅ **Investiga causas**: Si una semana tiene muchas incidencias, pregunta qué pasó

---

## ¿Necesitas ayuda?

Si tienes dudas sobre cómo interpretar o usar el reporte:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Resumen Diario por Departamento](/reportes/resumen-diario-departamento/)
- 👉 [Reporte de Impuntualidades](/reportes/reporte-impuntualidades/)
- 👉 [Reporte Mensual](/reportes/reporte-mensual/)
- 👉 [Gestión de Departamentos](/guias-por-rol/administrador/gestion-departamentos/)