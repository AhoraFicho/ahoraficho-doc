---
layout: default
title: Reporte Mensual
parent: Reportes
nav_order: 5
---

# Reporte Mensual
{: .no_toc }

Genera el informe mensual completo de fichajes por empleado, ideal para el cálculo de nóminas, auditorías internas y cumplimiento normativo. Es el mismo sistema que el Informe para Inspección de Trabajo, pero orientado a usos internos.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué es el Reporte Mensual?

Es un **informe completo en PDF** que contiene todos los fichajes de un empleado durante un mes (o un año entero). Es el mismo formato que el [Informe para Inspección de Trabajo](/reportes/informe-inspeccion-trabajo/), pero lo usamos internamente para:

- 💰 **Cálculo de nóminas**: Verificar horas trabajadas para el pago mensual
- 📊 **Auditorías internas**: Documentar el cumplimiento horario
- 📝 **Archivo histórico**: Conservar registros mensuales como respaldo
- 📧 **Comunicación con empleados**: Enviar a cada trabajador su resumen mensual
- 🔍 **Revisión de RRHH**: Analizar cumplimiento individual

{: .tip }
> **Buena práctica**: Genera y archiva el reporte mensual de cada empleado al finalizar cada mes. Esto te ahorrará tiempo si necesitas consultar datos históricos.

---

## Generar el Reporte Mensual

### Paso 1: Acceder al módulo de reportes

1. Inicia sesión como **Administrador** o **Manager**
2. Ve al menú lateral y haz clic en **"Reportes"**
3. Selecciona **"Informe Mensual"** o **"Reporte Mensual"**

![Acceso a reportes mensuales](/assets/images/placeholder-acceso-reporte-mensual.png)

{: .note }
> El **Informe Mensual** y el **Informe para Inspección de Trabajo** son el mismo reporte, solo cambia el nombre según el contexto de uso.

### Paso 2: Seleccionar el empleado

1. En el desplegable **"Empleado"**, busca y selecciona el trabajador
2. Los empleados aparecen ordenados alfabéticamente
3. Se muestra: Nombre completo - ID de empleado

![Seleccionar empleado](/assets/images/placeholder-seleccionar-empleado-mensual.png)

### Paso 3: Seleccionar el período

**Para un mes específico:**
1. Elige el **año** (últimos 5 años disponibles)
2. Elige el **mes** concreto (enero a diciembre)

**Para el año completo:**
1. Elige el **año**
2. Selecciona **"Todos"** en el desplegable de mes

![Seleccionar período](/assets/images/placeholder-periodo-mensual.png)

{: .warning }
> **Informe anual**: Si seleccionas "Todos", el PDF incluirá los 12 meses del año. Será un documento extenso (puede tener más de 20 páginas).

### Paso 4: Añadir observaciones (opcional)

Puedes incluir comentarios que aparecerán al final del PDF:

**Ejemplos de observaciones útiles:**
- "Para nómina de diciembre 2024"
- "Incluye período de formación del 10 al 15"
- "Empleado con reducción de jornada autorizada"
- "Período con baja médica del 20 al 25"

### Paso 5: Descargar el PDF

1. Haz clic en **"Descargar Informe"**
2. El PDF se generará automáticamente
3. Guarda el archivo en tu sistema

{: .tip }
> El archivo se descarga con nombre descriptivo: `Informe_[NombreEmpleado]_[Mes][Año].pdf` para facilitar su organización.

---

## Contenido del Reporte Mensual

El PDF generado incluye las siguientes secciones:

### 1. Encabezado

- Logo de tu empresa (si está configurado)
- Nombre de la empresa
- Título: "Informe de Registro de Jornada"
- Período del informe: "Marzo 2024" o "Año 2024"

### 2. Datos del empleado

- **Nombre completo**: Juan Pérez García
- **ID de empleado**: EMP-001
- **Departamento**: Ventas
- **Horario asignado**: Jornada Estándar 9-18h
- **Edificio/Ubicación**: Oficina Madrid Centro

### 3. Tabla de fichajes diarios

Para cada día laborable del mes:

| Fecha | Día | Entrada | Salida | Horas | Observaciones |
|-------|-----|---------|--------|-------|---------------|
| 01/03/2024 | Viernes | 09:00 | 18:00 | 8h 00m | - |
| 04/03/2024 | Lunes | 09:05 | 18:10 | 8h 05m | - |
| 05/03/2024 | Martes | - | - | - | Vacaciones |
| 06/03/2024 | Miércoles | 09:00 | 14:00 | 5h 00m | Media jornada |

{: .note }
> **Festivos**: Aparecen marcados claramente y no se cuentan como ausencias. Ejemplo: "8 diciembre - Inmaculada Concepción - Festivo Nacional"

### 4. Resumen del mes

**Estadísticas clave:**

- **Días laborables del mes**: 22 días
- **Días trabajados**: 20 días
- **Días de vacaciones**: 2 días
- **Días de baja médica**: 0 días
- **Festivos**: 1 día
- **Total horas trabajadas**: 160h 30m
- **Horas teóricas**: 160h 00m
- **Diferencia**: +0h 30m (horas extras)

### 5. Desglose de ausencias

Si hubo ausencias en el mes, se detallan:

| Tipo | Fechas | Días | Estado |
|------|--------|------|--------|
| Vacaciones | 05-06/03/2024 | 2 | Aprobado |
| Baja médica | - | 0 | - |
| Permiso retribuido | - | 0 | - |

### 6. Observaciones finales

- Comentarios añadidos por el administrador
- Notas sobre fichajes modificados o ajustados
- Justificaciones de ausencias

---

## Usos principales del Reporte Mensual

### 1. Cálculo de nóminas 💰

**Objetivo**: Verificar las horas trabajadas antes de procesar el pago.

**Proceso:**
1. Genera el reporte de cada empleado al finalizar el mes
2. Compara "Horas trabajadas" con "Horas teóricas"
3. Identifica horas extras (si las hay)
4. Verifica ausencias justificadas (vacaciones, bajas)
5. Introduce los datos en el sistema de nóminas

{: .tip }
> **Automatización**: Si usas software de nóminas, puedes exportar los datos y cargarlos directamente sin tener que introducirlos manualmente.

### 2. Archivo histórico 📁

**Objetivo**: Conservar registros para cumplir con la obligación legal de 4 años.

**Proceso:**
1. Al finalizar cada mes, genera el reporte de todos los empleados
2. Guárdalos en una carpeta organizada por año/mes
3. Ejemplo de estructura:
```
/Reportes_Mensuales/
  └── 2024/
      ├── Enero/
      │   ├── Juan_Perez_Enero2024.pdf
      │   └── Maria_Garcia_Enero2024.pdf
      └── Febrero/
          └── ...
```

{: .important }
> **Obligación legal**: Según el RD 8/2019, debes conservar los registros durante **mínimo 4 años**. Este archivo mensual te asegura el cumplimiento.

### 3. Comunicación con empleados 📧

**Objetivo**: Enviar a cada trabajador su resumen mensual de forma transparente.

**Proceso:**
1. Genera el reporte del empleado
2. Envíale el PDF por email con un mensaje tipo:

```
Asunto: Resumen de fichajes - Marzo 2024

Hola [Nombre],

Adjunto encontrarás tu informe mensual de fichajes correspondiente a marzo 2024.

Horas trabajadas: 160h 30m
Días trabajados: 20 días
Ausencias: 2 días (vacaciones)

Si detectas algún error, por favor contacta con RRHH antes del día 5.

Saludos,
Departamento de RRHH
```

### 4. Auditorías internas 🔍

**Objetivo**: Revisar el cumplimiento de un empleado durante un período extenso.

**Proceso:**
1. Genera el informe anual (selecciona "Todos" en mes)
2. Analiza tendencias: ¿Ha mejorado la puntualidad? ¿Muchas ausencias?
3. Documenta para reuniones de evaluación de desempeño
4. Conserva como evidencia objetiva en caso de conflictos laborales

---

## Diferencias entre Reporte Mensual e Informe de Inspección

{: .note }
> Son el **mismo informe**, pero con diferentes contextos de uso:

| Aspecto | Reporte Mensual | Informe Inspección |
|---------|-----------------|-------------------|
| **Uso** | Interno (nóminas, RRHH) | Externo (Inspección de Trabajo) |
| **Frecuencia** | Mensual (proactivo) | Bajo requerimiento (reactivo) |
| **Destinatario** | Empresa, empleado | Inspección de Trabajo, auditorías |
| **Observaciones** | Más flexibles | Más formales |
| **Conservación** | Recomendado | Obligatorio (4 años) |

---

## Casos especiales

### Empleado con múltiples fichajes por día

Si un empleado tiene pausas largas (por ejemplo, jornada partida):

**Ejemplo:**
- Entrada: 09:00
- Salida: 14:00 (pausa comida)
- Entrada: 16:00
- Salida: 20:00

**En el reporte aparecerá:**
- Fichajes: 4 (2 pares)
- Total horas: 9 horas (de 09:00 a 20:00)
- Horas efectivas: 9 horas (restando la pausa)

### Empleado con jornada intensiva en verano

Si el empleado cambia a jornada intensiva (solo mañanas) en verano:

1. Asegúrate de que su horario asignado refleje el cambio temporal
2. El reporte mostrará las horas según el nuevo horario
3. En observaciones, añade: "Jornada intensiva de verano: junio-agosto"

### Empleado con horas extras

Si un empleado trabaja más horas de las teóricas:

- El reporte mostrará la diferencia como **positiva**
- Ejemplo: "Diferencia: +8h 00m"
- En observaciones, indica si las horas extras fueron autorizadas

### Empleado de baja todo el mes

Si un empleado estuvo de baja médica todo el mes:

- Días trabajados: 0
- Total horas: 0h 00m
- En cada día aparecerá: "Baja médica"
- El reporte sigue siendo válido y debe conservarse

---

## Automatizar la generación mensual

### Proceso recomendado

Para empresas con muchos empleados, puedes automatizar parte del proceso:

1. **Día 1-3 del mes siguiente**:
   - Genera el reporte de todos los empleados
   - Usa la opción de exportación masiva si está disponible

2. **Día 4-5**:
   - Revisa los reportes
   - Detecta ausencias injustificadas o fichajes incompletos
   - Contacta con empleados para corregir antes de nóminas

3. **Día 6-8**:
   - Vuelve a generar los reportes (versión final)
   - Archiva en carpetas organizadas
   - Envía a cada empleado su PDF

{: .tip }
> **Consejo**: Crea una plantilla de email para enviar a los empleados cada mes. Solo tendrás que cambiar el mes y adjuntar el PDF correspondiente.

---

## Preguntas frecuentes

### ¿Puedo generar reportes de años anteriores?

Sí, AhoraFicho conserva todo el histórico. Puedes generar reportes de cualquier mes desde que empezaste a usar la plataforma (dentro de los últimos 5 años en el desplegable).

### ¿Qué hago si detecto un error en un reporte ya generado?

1. Corrige el error en el sistema (edita el fichaje incorrecto)
2. Vuelve a generar el reporte
3. El nuevo PDF reflejará los datos correctos
4. **No modifiques manualmente** el PDF, pierde validez

### ¿Los empleados pueden descargar su propio reporte?

Depende de la configuración. Si lo permites, los empleados con rol "Empleado" pueden acceder a su historial y descargar sus propios reportes desde su perfil.

### ¿El reporte incluye datos de otros empleados?

No, cada reporte es **individual**. Solo contiene datos del empleado seleccionado.

### ¿Puedo generar un reporte de varios empleados a la vez?

Actualmente no en un solo PDF. Debes generar un PDF por cada empleado. Sin embargo, puedes usar el [Resumen Semanal](/reportes/resumen-semanal-departamento/) o [Diario](/reportes/resumen-diario-departamento/) para ver múltiples empleados en un solo reporte.

---

## Consejos para gestionar reportes mensuales

✅ **Establece una rutina**: Genera los reportes siempre los primeros días del mes

✅ **Organiza bien los archivos**: Usa una estructura de carpetas clara (año/mes)

✅ **Haz backups**: Guarda copias en la nube (Drive, OneDrive, Dropbox)

✅ **Revisa antes de nóminas**: Verifica que no haya errores antes de procesar pagos

✅ **Comunica con transparencia**: Envía a los empleados su resumen para evitar malentendidos

✅ **Conserva 4 años**: Cumple con la obligación legal de conservación

---

## ¿Necesitas ayuda?

Si tienes dudas sobre cómo generar o gestionar reportes mensuales:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Informe para Inspección de Trabajo](/reportes/informe-inspeccion-trabajo/)
- 👉 [Resumen Diario por Departamento](/reportes/resumen-diario-departamento/)
- 👉 [Consultar Mis Fichajes (Empleado)](/guias-por-rol/empleado/consultar-mis-fichajes/)
- 👉 [Asignar Vacaciones](/guias-por-rol/administrador/asignar-vacaciones/)