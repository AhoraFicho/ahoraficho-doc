---
layout: default
title: Informe para Inspección de Trabajo
parent: Reportes
nav_order: 1
---

# Informe para Inspección de Trabajo
{: .no_toc }

Genera el documento oficial que necesitas presentar en caso de inspección laboral. Este informe cumple 100% con el Real Decreto-ley 8/2019 sobre registro de jornada obligatorio.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué es el Informe para Inspección de Trabajo?

Es el **documento oficial** que debes presentar a la Inspección de Trabajo cuando te lo requieran. Contiene el registro completo de jornada de un empleado durante un período determinado, cumpliendo con todos los requisitos legales del **Real Decreto-ley 8/2019**.

{: .important }
> **Obligación legal**: Todas las empresas en España están obligadas a llevar un registro de jornada diaria de sus trabajadores y conservarlo durante **4 años** a disposición de la Inspección de Trabajo, los representantes legales de los trabajadores y los propios empleados.

### ¿Qué información contiene?

El informe incluye:

- ✅ **Datos del empleado**: Nombre completo, ID de empleado
- ✅ **Período consultado**: Mes y año del informe
- ✅ **Fichajes diarios**: Entrada y salida de cada día laborable
- ✅ **Horas trabajadas**: Total de horas por día y acumulado mensual
- ✅ **Ausencias justificadas**: Vacaciones, bajas médicas, permisos
- ✅ **Festivos**: Días festivos nacionales, autonómicos y locales
- ✅ **Observaciones**: Comentarios sobre incidencias o modificaciones

---

## Generar el Informe para Inspección

### Paso 1: Acceder a la gestión de fichajes

1. Inicia sesión como **Administrador** (o SuperAdmin)
2. Ve al menú lateral **"Empresa"** → **"Gestión de Fichajes"**
3. En la parte superior encontrarás los botones de **exportación para inspección**

{: .note }
> **Solo Administradores**: las exportaciones de inspección están en la gestión de fichajes de la empresa. Los Managers disponen del [Reporte Mensual](/reportes/reporte-mensual/) de su equipo para uso interno.

### Paso 2: Aplicar los filtros

Filtra por empleado, departamento, edificio y rango de fechas según lo que requiera la inspección (un mes, un trimestre, un año...).

### Paso 3: Elegir el formato de exportación

| Formato | Qué contiene | Uso recomendado |
|---------|--------------|-----------------|
| **Excel crudo** | Una fila por fichaje, con hora real de registro | Análisis detallado |
| **PDF crudo** | Una fila por fichaje | Presentación oficial detallada |
| **Excel consolidado** | Una fila por jornada (agrupado por día) | Revisión rápida |
| **PDF consolidado** | Una fila por jornada | **Formato más habitual para inspección** |

### Paso 4: Descargar y archivar

1. Haz clic en el formato deseado
2. El sistema generará el documento con los datos filtrados
3. Guarda el archivo con la fecha de generación

{: .important }
> **Integridad de los datos**: las exportaciones de inspección incluyen un **hash de verificación de integridad**, y avisan si hay jornadas con un número impar de fichajes (posible salida sin registrar). Esto aporta fiabilidad al documento presentado.

{: .note }
> **Cambios de fichaje con aprobador**: si un fichaje fue modificado mediante una solicitud de cambio, el informe muestra **quién aprobó o rechazó el cambio y en qué fecha**. El Excel consolidado y los dos PDF incluyen las columnas dedicadas **"Aprobado por"** y **"Fecha aprobación"**; en el Excel crudo el detalle completo aparece en la columna de observaciones (por ejemplo, "aprobado por Ana García el 05/10/2026 10:15").

### Contenido del informe

- ✅ **Datos del empleado**: Nombre completo
- ✅ **Período consultado**: fechas incluidas
- ✅ **Fichajes diarios**: entrada y salida de cada día (y hora de registro real)
- ✅ **Horas trabajadas**: totales por día
- ✅ **Ausencias justificadas**: vacaciones, bajas, permisos
- ✅ **Observaciones**: notas de modificaciones de fichaje (con quién las aprobó), comentarios por jornada
- ✅ **Aprobado por / Fecha aprobación**: en el Excel consolidado y en los PDF, quién validó cada cambio de fichaje y cuándo

![Descargar informe](/assets/images/placeholder-descargar-informe-pdf.png)

{: .tip }
> **Nombre del archivo**: El PDF se descarga con un nombre descriptivo tipo: `Informe_JuanPerez_Marzo2024.pdf` para facilitar su organización.

---

## Estructura del informe generado

El PDF incluye las siguientes secciones:

### 1. Encabezado del documento

- Logo de tu empresa (si está configurado)
- Nombre de la empresa
- Título: "Informe de Registro de Jornada"
- Período del informe

### 2. Datos del empleado

- Nombre completo del trabajador
- ID de empleado
- Departamento
- Horario asignado

### 3. Tabla de fichajes diarios

Para cada día laborable del período:

| Fecha | Día semana | Entrada | Salida | Total horas | Observaciones |
|-------|-----------|---------|--------|-------------|---------------|
| 01/03/2024 | Viernes | 09:00 | 18:00 | 8h 00m | - |
| 04/03/2024 | Lunes | 09:05 | 18:10 | 8h 05m | - |
| 05/03/2024 | Martes | - | - | - | Vacaciones |

{: .note }
> Los días festivos aparecen marcados claramente y no se cuentan como ausencias injustificadas.

### 4. Resumen mensual

- **Total días laborables**: Días que debería haber trabajado
- **Días trabajados**: Días con fichaje completo
- **Días de ausencia**: Vacaciones, bajas, permisos
- **Total horas trabajadas**: Suma de todas las horas del mes
- **Horas teóricas**: Horas que debería haber trabajado según horario
- **Diferencia**: Desviación entre horas reales y teóricas

### 5. Observaciones y comentarios

Incluye:
- Comentarios añadidos por el administrador al generar el informe
- Notas automáticas sobre fichajes modificados
- Ausencias justificadas con su tipo (vacaciones, baja médica, etc.)

---

## Cumplimiento normativo (RD 8/2019)

### ¿Qué exige la normativa?

El **Real Decreto-ley 8/2019** establece:

> **Artículo 34.9 del Estatuto de los Trabajadores**:
> "La empresa garantizará el registro diario de jornada, que deberá incluir el horario concreto de inicio y finalización de la jornada de trabajo de cada persona trabajadora, sin perjuicio de la flexibilidad horaria."

### ¿Qué debe incluir el registro?

Según la normativa, el registro debe contener:

1. ✅ **Hora de inicio de la jornada**: Fichaje de entrada
2. ✅ **Hora de finalización de la jornada**: Fichaje de salida
3. ✅ **Identificación del trabajador**: Nombre completo
4. ✅ **Fecha del registro**: Día completo (DD/MM/AAAA)
5. ✅ **Conservación**: Mínimo 4 años

{: .important }
> **AhoraFicho cumple 100% con todos estos requisitos**. El informe generado incluye toda la información exigida por la Inspección de Trabajo.

---

## Casos especiales

### Empleado con fichajes incompletos

Si un empleado tiene días con fichajes incompletos (olvidó fichar entrada o salida):

- El informe mostrará las horas que consten en el sistema
- Aparecerá una nota indicando "Fichaje modificado" o "Fichaje manual"
- Es recomendable añadir un comentario explicativo en el campo de observaciones

{: .warning }
> **Recomendación**: Antes de generar un informe oficial, revisa que todos los fichajes estén completos y corregidos. Ve a la sección de [Fichajes](/modulos/fichajes/) para validar y completar registros pendientes.

### Empleado con jornada flexible

Si el empleado tiene horario flexible o teletrabajo:

- El informe mostrará las horas reales fichadas
- En observaciones, añade manualmente: "Empleado con horario flexible autorizado"
- La diferencia entre horas teóricas y reales es normal en estos casos

### Empleado con reducción de jornada

Para empleados con jornada reducida:

1. Asegúrate de que su horario asignado refleje la reducción
2. Añade en observaciones: "Jornada reducida del XX% desde DD/MM/AAAA"
3. El sistema calculará correctamente las horas teóricas según su horario reducido

### Empleado de baja médica prolongada

Si un empleado estuvo de baja todo el mes:

- El informe mostrará "Baja médica" en todos los días del período
- Total de horas trabajadas: 0h
- En observaciones, indica el tipo de baja y período

---

## Preguntas frecuentes

### ¿Cuándo debo generar este informe?

- **Mensualmente**: Es recomendable generarlo al finalizar cada mes para conservarlo como respaldo
- **Bajo requerimiento**: Cuando la Inspección de Trabajo lo solicite
- **Auditorías internas**: Para revisiones de RRHH o auditorías de cumplimiento

### ¿Dónde debo conservar los informes?

- Guarda los PDF en un sistema de archivo digital organizado por año/mes
- Según la ley, debes conservarlos durante **mínimo 4 años**
- Recomendación: Almacenamiento en la nube con copias de seguridad

### ¿Qué hago si la Inspección me pide el informe de un empleado que ya no trabaja?

- AhoraFicho conserva el historial completo de empleados desactivados
- Genera el informe normalmente seleccionando al empleado (aparecerá en la lista aunque esté inactivo)
- El PDF incluirá todos sus fichajes del período solicitado

### ¿Puedo modificar el PDF una vez generado?

No debes modificar el PDF oficial, ya que pierde su validez legal. Si necesitas añadir información:
- Vuelve a generar el informe incluyendo los comentarios necesarios
- O adjunta un documento complementario explicativo

### ¿El informe incluye horas extras?

Sí, el informe muestra el total de horas trabajadas. Si un empleado trabajó más horas de las teóricas, aparecerá en la diferencia como horas adicionales.

### ¿Qué pasa si un empleado tiene varios fichajes en un mismo día?

El sistema suma automáticamente todos los períodos trabajados en el día. Por ejemplo:
- Entrada: 09:00 | Salida: 14:00 (5 horas)
- Entrada: 16:00 | Salida: 19:00 (3 horas)
- **Total día: 8 horas**

### ¿Los festivos locales se tienen en cuenta?

Sí, si has configurado correctamente los festivos por edificio/ubicación, aparecerán marcados en el informe y no se contarán como ausencias injustificadas.

---

## Sanciones por incumplimiento

{: .warning }
> **Importante**: No llevar un registro de jornada o tenerlo incompleto puede resultar en sanciones graves.

### Tipos de sanciones

Según la **Ley de Infracciones y Sanciones del Orden Social (LISOS)**:

| Tipo de Infracción | Sanción Económica |
|-------------------|-------------------|
| **Leve** | 60€ - 625€ por trabajador afectado |
| **Grave** | 626€ - 6.250€ por trabajador afectado |
| **Muy Grave** | 6.251€ - 187.515€ por trabajador afectado |

{: .important }
> **Prevención**: Genera y conserva los informes mensuales de todos tus empleados para evitar sanciones. Con AhoraFicho, cumples automáticamente con la normativa.

---

## Consejos para inspecciones

### Antes de la inspección

1. ✅ Genera los informes de los **últimos 4 años** de todos los empleados
2. ✅ Organiza los PDF por año y mes en carpetas digitales
3. ✅ Revisa que no haya fichajes incompletos pendientes de corregir
4. ✅ Prepara una copia de seguridad de todos los informes

### Durante la inspección

1. Presenta los informes en **formato PDF original** (no modificado)
2. Si el inspector solicita un empleado específico, genera el informe en el momento
3. Muestra que usas un sistema automatizado (AhoraFicho) que cumple la normativa
4. Ten disponible el acceso a la plataforma para consultas en tiempo real

### Documentación complementaria

Además de los informes de fichajes, ten disponible:
- Contratos de trabajo
- Horarios asignados a cada empleado
- Calendario laboral con festivos
- Documentación de vacaciones aprobadas

---

## ¿Necesitas ayuda?

Si tienes dudas sobre cómo generar o presentar el informe:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)
- 📞 Contacta con nuestro equipo de soporte especializado en normativa laboral

---

## Guías relacionadas

- 👉 [Reporte Mensual](/reportes/reporte-mensual/)
- 👉 [Consultar Mis Fichajes (Empleado)](/guias-por-rol/empleado/consultar-mis-fichajes/)
- 👉 [¿Olvidé Fichar?](/guias-por-rol/empleado/olvide-fichar/)
- 👉 [Gestión de Edificios](/guias-por-rol/administrador/gestion-edificios/)

---

## Referencias legales

- **Real Decreto-ley 8/2019, de 8 de marzo**: Medidas urgentes de protección social y de lucha contra la precariedad laboral en la jornada de trabajo
- **Artículo 34.9 del Estatuto de los Trabajadores**: Registro de jornada obligatorio
- **LISOS**: Ley sobre Infracciones y Sanciones en el Orden Social

---

**Última actualización**: Octubre 2026
**Normativa aplicable**: RD 8/2019 y Estatuto de los Trabajadores