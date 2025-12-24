---
layout: default
title: Consultar Mis Fichajes
parent: Empleado
grand_parent: Guías por Rol
nav_order: 3
---

# Consultar Mis Fichajes
{: .no_toc }

Cómo consultar tu historial de fichajes, resúmenes y estadísticas.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Acceder a tus fichajes

Para ver tus fichajes tienes dos secciones principales:

### 📋 Mis Fichajes
**Ruta**: "Mi Trabajo" → "Mis Fichajes"

Listado detallado de todos tus registros de entrada/salida con:
- Fecha y hora exacta
- Tipo de fichaje (entrada, salida, pausa)
- Ubicación (si aplica)
- Dispositivo usado
- IP de conexión

### 📊 Mi Resumen Diario
**Ruta**: "Mi Trabajo" → "Mi resumen diario"

Vista consolidada por día con:
- Horas totales trabajadas
- Horas efectivas (descontando pausas)
- Comparación con tu horario
- Indicadores de incidencias

---

## Mis Fichajes - Vista detallada

### Información que verás

Para cada fichaje registrado se muestra:

| Campo | Descripción | Ejemplo |
|:------|:------------|:--------|
| **Fecha y hora** | Momento exacto del fichaje | 23/12/2024 08:15:32 |
| **Tipo** | Entrada, Pausa, Fin pausa, Salida | 🟢 Entrada |
| **Ubicación** | Dirección GPS (si está habilitado) | Calle Mayor 123, Madrid |
| **Precisión** | Margen de error del GPS | ±10 metros |
| **Dispositivo** | Desde dónde fichaste | App móvil Android |
| **IP** | Dirección IP de conexión | 192.168.1.100 |
| **Estado** | Normal o con solicitud de cambio | ✅ Normal |

### Códigos de color

Los fichajes se muestran con diferentes colores según su tipo:

- 🟢 **Verde**: Entrada (inicio jornada)
- 🟡 **Amarillo**: Pausas (inicio y fin)
- 🔴 **Rojo**: Salida (fin jornada)
- 🔵 **Azul**: Fichaje automático (si está configurado)

---

## Filtros y búsqueda

### Filtrar por fecha

Puedes filtrar tus fichajes de varias formas:

**Por rango de fechas:**
1. Selecciona **"Fecha desde"**
2. Selecciona **"Fecha hasta"**
3. Haz clic en **"Filtrar"** o **"Buscar"**

**Filtros rápidos:**
- 📅 **Hoy**: Fichajes del día actual
- 📅 **Ayer**: Fichajes de ayer
- 📅 **Esta semana**: Lunes a domingo de esta semana
- 📅 **Semana pasada**: Lunes a domingo de la semana anterior
- 📅 **Este mes**: Todo el mes en curso
- 📅 **Mes pasado**: Mes anterior completo

{: .tip }
> **Consejo**: Usa los filtros rápidos para consultas habituales y el rango personalizado para períodos específicos.

### Exportar fichajes

Puedes exportar tus fichajes en diferentes formatos:

1. Aplica los filtros deseados
2. Haz clic en **"Exportar"** o **"Descargar"**
3. Selecciona el formato:
   - **Excel (.xlsx)**: Para análisis en hojas de cálculo
   - **PDF**: Para impresión o archivo
   - **CSV**: Para importar en otros sistemas

{: .note }
> Los fichajes exportados incluyen todos los campos: fecha, hora, ubicación, IP, dispositivo, etc.

---

## Mi Resumen Diario

### Vista de resumen

Esta pantalla te muestra un resumen consolidado por día:

```
┌─────────────────────────────────────────────┐
│ Lunes 23/12/2024                           │
├─────────────────────────────────────────────┤
│ 🟢 Entrada:        08:15                   │
│ 🟡 Inicio pausa:   14:00                   │
│ 🟡 Fin pausa:      15:00                   │
│ 🔴 Salida:         18:30                   │
├─────────────────────────────────────────────┤
│ ⏱️ Horas totales:   10h 15m                │
│ ✅ Horas efectivas: 9h 15m                 │
│ 📋 Horario:         8h 00m                 │
│ ➕ Extras:          +1h 15m                │
└─────────────────────────────────────────────┘
```

### Cálculo de horas

**Horas totales:**
- Tiempo desde entrada hasta salida
- Incluye pausas

**Horas efectivas:**
- Tiempo trabajado real
- Excluye pausas

**Comparación con horario:**
- 🟢 Verde: Cumplido o superado
- 🟡 Amarillo: Cerca del objetivo
- 🔴 Rojo: Incompleto

### Indicadores de estado

Cada día puede tener diferentes estados:

| Indicador | Significado |
|:----------|:------------|
| ✅ **Correcto** | Jornada completa, fichajes correctos |
| ⚠️ **Incidencia** | Falta fichaje o solicitud pendiente |
| 🔄 **Solicitud pendiente** | Cambio de fichaje en validación |
| 🔴 **Incompleto** | Falta fichar salida o pausa |
| 📅 **Festivo** | Día festivo, no aplica |
| 🌴 **Ausencia** | Vacaciones o permiso |

---

## Resumen Semanal

Algunas vistas también ofrecen resumen semanal:

### Tabla semanal

```
┌──────────┬──────────┬──────────┬─────────┐
│   Día    │ Entrada  │  Salida  │  Horas  │
├──────────┼──────────┼──────────┼─────────┤
│ Lunes    │  08:15   │  18:30   │  9h 15m │
│ Martes   │  08:10   │  17:45   │  8h 35m │
│ Miércoles│  08:20   │  18:00   │  8h 40m │
│ Jueves   │  08:05   │  17:30   │  8h 25m │
│ Viernes  │  08:30   │  15:00   │  6h 30m │
├──────────┴──────────┴──────────┼─────────┤
│ TOTAL SEMANA                   │ 41h 25m │
└────────────────────────────────┴─────────┘
```

### Estadísticas semanales

- 📊 **Promedio diario**: Horas medias por día
- ⏱️ **Total semanal**: Suma de todas las horas
- 📈 **Cumplimiento**: % respecto al horario asignado
- ⚠️ **Incidencias**: Número de días con problemas

---

## Ver detalles de un fichaje

### Información ampliada

Haz clic en cualquier fichaje para ver todos los detalles:

**Información básica:**
- Fecha y hora exacta (hasta segundos)
- Tipo de acceso
- Usuario que fichó

**Información de ubicación (si aplica):**
- 📍 Latitud y Longitud
- 📍 Dirección completa
- 📍 Precisión del GPS
- 🗺️ **Ver en mapa**: Abre Google Maps con la ubicación

**Información técnica:**
- 💻 Dispositivo usado (Web, App Android, App iOS, Terminal PIN, etc.)
- 🌐 Navegador (si fue desde web)
- 🔢 IP de conexión
- 🏢 Edificio asociado (si aplica)

**Historial de cambios:**
- Si hubo solicitud de cambio: fecha, motivo, estado
- Aprobador y fecha de aprobación

---

## Solicitudes de cambio en fichajes

### Identificar fichajes con solicitudes

Los fichajes con solicitudes de cambio se marcan con:

- 🟡 **Pendiente**: Amarillo, esperando aprobación
- ✅ **Aprobado**: Verde, cambio aplicado
- ❌ **Rechazado**: Rojo, solicitud denegada

### Ver estado de solicitud

Para cada solicitud puedes ver:

1. **Fecha y hora original**: La que estaba registrada
2. **Fecha y hora solicitada**: La que pediste cambiar
3. **Observaciones**: Tu justificación
4. **Estado**: Pendiente / Aprobada / Rechazada
5. **Aprobador**: Quién lo revisó
6. **Comentarios del aprobador**: Si hay feedback

### Cancelar solicitud pendiente

Si una solicitud está pendiente, puedes cancelarla:

1. Localiza el fichaje con solicitud pendiente
2. Haz clic en **"Cancelar solicitud"**
3. Confirma la cancelación

{: .warning }
> Una vez aprobada o rechazada, no puedes cancelar la solicitud.

---

## Comparar con tu horario

### Horario asignado

En el resumen diario puedes ver:

**Tu horario estándar:**
- Entrada esperada: 08:00
- Salida esperada: 17:00
- Pausa: 1 hora
- Total: 8 horas diarias

**Tu fichaje real:**
- Entrada: 08:15 (⚠️ +15 min tarde)
- Salida: 18:30 (✅ +1h 30m extra)
- Pausa: 1 hora
- Total: 9h 15m (+1h 15m)

### Flexibilidad horaria

Si tu empresa tiene margen de flexibilidad:

- **Flexibilidad**: ±15 minutos
- **Entrada válida**: Entre 07:45 - 08:15
- **Salida válida**: Entre 16:45 - 17:15

Los fichajes dentro del margen se consideran correctos.

---

## Notificaciones de impuntualidad

### Sistema de alertas

Si tu empresa tiene configuradas notificaciones de impuntualidad:

**Recibirás alerta cuando:**
- 🔴 Llegues más de X minutos tarde (según configuración)
- 🔴 No fiches la entrada antes de X hora

**Niveles de severidad:**
- 🟡 **Bajo** (5-15 min tarde): Aviso informativo
- 🟠 **Medio** (15-30 min tarde): Alerta al Manager
- 🔴 **Alto** (>30 min tarde): Alerta crítica

{: .note }
> Las notificaciones de impuntualidad son configuradas por tu empresa y pueden variar.

---

## Gráficos y estadísticas

### Vista de gráficos (si está disponible)

Algunas empresas tienen habilitados gráficos con:

**Gráfico de horas semanales:**
- Barras por día de la semana
- Comparación con horario objetivo
- Media semanal

**Gráfico de puntualidad:**
- Días con entrada puntual vs. tarde
- Promedio de retraso

**Gráfico mensual:**
- Total horas por mes
- Comparación mes a mes

---

## Casos especiales

### Día sin fichar

Si un día aparece sin fichajes:

- ❓ **Sin datos**: No fichaste ese día
- ⚠️ **Incidencia**: Se marca en rojo

**Qué hacer:**
1. Verifica que realmente trabajaste ese día
2. Si trabajaste: [Solicita un cambio de fichaje](/guias-por-rol/empleado/olvide-fichar/)
3. Si no trabajaste: Verifica si hay ausencia registrada

### Fichajes duplicados

Si aparecen fichajes duplicados:

- Puede ser un error de sincronización
- Contacta con tu administrador para que lo corrija
- O solicita eliminación del duplicado

### Fichajes automáticos

Si tu empresa tiene configurado autofichaje:

- 🔵 Aparecen marcados como "Automático"
- Se generan según tu horario
- Puedes solicitar cambios si no son correctos

---

## Preguntas frecuentes

### ¿Puedo ver fichajes de hace más de 1 año?

Sí, el historial completo está disponible. Usa los filtros de fecha para acceder a períodos antiguos.

### ¿Por qué algunos fichajes no tienen ubicación?

Posibles razones:
- GPS desactivado en tu dispositivo
- Fichaste desde terminal PIN/RFID (no tienen GPS)
- No diste permisos de ubicación
- Fichaste desde web sin activar ubicación

### ¿Puedo modificar un fichaje directamente?

No, por seguridad los empleados no pueden modificar fichajes directamente. Debes [solicitar un cambio](/guias-por-rol/empleado/olvide-fichar/) que será aprobado por tu superior.

### ¿Las horas extras se pagan automáticamente?

No, AhoraFicho solo registra las horas. La compensación de horas extras depende de:
- Política de tu empresa
- Tu contrato laboral
- Acuerdos con tu Manager

### ¿Qué significa "IP no permitida"?

Indica que fichaste desde una IP no autorizada. Tu empresa puede tener restricciones de IP para mayor seguridad.

---

## Consejos útiles

### ✅ Revisa regularmente

- **Diario**: Verifica que fichaste correctamente
- **Semanal**: Revisa tu resumen y horas totales
- **Mensual**: Antes del cierre de nómina

### ✅ Exporta para tus registros

- Descarga mensualmente tus fichajes
- Guarda copias en PDF
- Útil para futuras consultas

### ✅ Actúa rápido ante errores

- Si detectas un error, solicita corrección de inmediato
- No esperes días o semanas
- Más fácil de justificar reciente que antiguo

---

## Impresión y reportes

### Imprimir resumen mensual

Para imprimir un resumen de tus fichajes:

1. Aplica filtros del mes deseado
2. Ve a **"Mi resumen diario"**
3. Haz clic en **"Imprimir"** o usa Ctrl+P
4. Selecciona tu impresora o "Guardar como PDF"

### Reporte para nómina

Si necesitas un reporte oficial para nómina:

1. Contacta con tu administrador
2. Ellos pueden generar reportes oficiales firmados digitalmente
3. O usa la función de exportar con todos los detalles

---

## ¿Necesitas ayuda?

Si tienes problemas al consultar tus fichajes:

- 🔧 Contacta con tu Administrador
- 📧 Email: soporte@ahoraficho.es
- 💬 Consulta las [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Cómo fichar correctamente](/primeros-pasos/primer-fichaje/)
- 👉 [¿Olvidé fichar?](/guias-por-rol/empleado/olvide-fichar/)
- 👉 [Mi perfil y configuración](/guias-por-rol/empleado/mi-perfil/)