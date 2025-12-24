---
layout: default
title: Gestión de Edificios
parent: Guía del Administrador
grand_parent: Guías por Rol
nav_order: 10
---

# Gestión de Edificios
{: .no_toc }

Aprende a crear y gestionar las ubicaciones físicas (edificios o centros de trabajo) de tu empresa, configurar restricciones de fichaje por geolocalización e IP, y asignar departamentos a cada ubicación.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué son los edificios en AhoraFicho?

Los edificios son las **ubicaciones físicas** o **centros de trabajo** donde tus empleados realizan su actividad laboral. También se les llama "ubicaciones" o "centros". Gestionar los edificios te permite:

- ✅ Organizar empleados por ubicación geográfica
- ✅ Controlar fichajes por geolocalización (GPS)
- ✅ Restringir fichajes por dirección IP (fichaje solo desde la oficina)
- ✅ Asignar departamentos específicos a cada edificio
- ✅ Configurar festivos locales por ubicación
- ✅ Generar reportes segmentados por centro de trabajo

{: .important }
> **Concepto clave**: Un edificio representa una ubicación física real (oficina, almacén, fábrica, tienda, etc.). Cada empleado debe estar asignado a un edificio para un correcto control horario.

---

## Crear un nuevo edificio

### Paso 1: Acceder a la gestión de edificios

1. Inicia sesión como **Administrador**
2. Ve al menú lateral y haz clic en **"Configuración"**
3. Selecciona **"Edificios"**
4. Haz clic en el botón **"Nuevo Edificio"**

![Acceso a gestión de edificios](/assets/images/placeholder-edificios-menu.png)

### Paso 2: Completar los datos básicos

En el formulario, introduce la siguiente información:

| Campo | Descripción | Ejemplo |
|-------|-------------|---------|
| **Nombre** | Nombre del edificio o centro | Oficina Madrid Centro |
| **Código** | Identificador corto (opcional) | MAD-01 |
| **Dirección** | Dirección completa | Calle Gran Vía, 28, Madrid |
| **Ciudad** | Municipio | Madrid |
| **Código Postal** | CP | 28013 |
| **Provincia** | Provincia | Madrid |
| **País** | País | España |
| **Activo** | Estado del edificio | ✅ Sí |

![Formulario datos básicos edificio](/assets/images/placeholder-crear-edificio-basico.png)

### Paso 3: Configurar geolocalización (opcional)

Si quieres restringir los fichajes solo cuando el empleado esté físicamente en la ubicación:

1. Marca la casilla **"Activar control por geolocalización"**
2. Introduce las coordenadas GPS del edificio:
   - **Latitud**: 40.4193
   - **Longitud**: -3.6919
3. Establece el **radio permitido** en metros (ejemplo: 100 metros)

![Configurar geolocalización](/assets/images/placeholder-geolocalizacion-edificio.png)

{: .tip }
> **¿Cómo obtener las coordenadas?** Abre Google Maps, busca tu dirección, haz clic derecho en el marcador y selecciona "¿Qué hay aquí?". Aparecerán las coordenadas GPS.

### Paso 4: Configurar restricción por IP (opcional)

Si quieres que los fichajes solo se permitan desde la red de la oficina:

1. Marca la casilla **"Activar control por IP"**
2. Introduce las direcciones IP permitidas (separadas por comas)
   - Ejemplo: `192.168.1.100, 192.168.1.101`
   - O un rango: `192.168.1.0/24`

![Configurar restricción IP](/assets/images/placeholder-ip-edificio.png)

{: .note }
> **Nota técnica**: Si activas control por IP, los empleados solo podrán fichar desde dispositivos conectados a la red WiFi de la oficina o mediante VPN corporativa.

### Paso 5: Guardar el edificio

1. Revisa que todos los datos sean correctos
2. Haz clic en **"Guardar"**
3. El edificio aparecerá en el listado principal

---

## Asignar departamentos a un edificio

Una vez creado el edificio, puedes asignarle los departamentos que operan en esa ubicación.

### ¿Por qué asignar departamentos a edificios?

Esta relación te permite:

- Organizar la estructura de tu empresa por ubicación física
- Saber qué departamentos operan en cada centro
- Generar reportes combinando ubicación + departamento
- Configurar festivos locales que afecten solo a ciertos departamentos

### Asignar departamentos al edificio

1. Ve a **"Configuración"** → **"Edificios"**
2. Edita el edificio al que quieres asignar departamentos
3. Desplázate hasta la sección **"Departamentos en este edificio"**
4. Marca las casillas de los departamentos que operan en esta ubicación
5. Guarda los cambios

![Asignar departamentos a edificio](/assets/images/placeholder-asignar-departamentos-edificio.png)

{: .note }
> **Ejemplo práctico**: Si tienes una oficina en Madrid donde trabajan los departamentos de Ventas, Marketing y Administración, marca solo esos tres departamentos. El departamento de Producción que está en Barcelona no se marcará.

### Estructura resultante

Después de asignar departamentos, tu estructura quedará así:

```
Oficina Madrid Centro
├── Ventas
├── Marketing
└── Administración

Oficina Barcelona
├── Producción
├── Logística
└── IT
```

---

## Asignar empleados a un edificio

Para que los empleados puedan fichar correctamente, deben estar asignados a un edificio.

### Opción 1: Desde el perfil del empleado

1. Ve a **"Empleados"** → Selecciona el empleado
2. Haz clic en **"Editar"**
3. En el campo **"Edificio"**, selecciona la ubicación del desplegable
4. Guarda los cambios

### Opción 2: Asignación masiva

1. Ve a **"Empleados"**
2. Selecciona varios empleados marcando las casillas
3. Haz clic en **"Acciones masivas"**
4. Selecciona **"Cambiar edificio"**
5. Elige el edificio de destino
6. Confirma la acción

![Asignación masiva de edificios](/assets/images/placeholder-asignar-masivo-edificio.png)

{: .warning }
> **Importante**: Si un empleado no tiene edificio asignado, podrá fichar desde cualquier ubicación sin restricciones. Asegúrate de asignar siempre un edificio a cada empleado activo.

---

## Tipos de control de ubicación

AhoraFicho ofrece tres formas de controlar la ubicación desde donde se permite fichar:

### 1. Sin restricciones (por defecto)

El empleado puede fichar desde cualquier lugar.

**Cuándo usar:**
- Empleados en teletrabajo permanente
- Comerciales que trabajan en la calle
- Equipos remotos

**Configuración:** No actives ni geolocalización ni IP.

---

### 2. Control por geolocalización (GPS)

El empleado solo puede fichar si está dentro del radio permitido del edificio.

**Cuándo usar:**
- Oficinas físicas con presencia obligatoria
- Almacenes y fábricas
- Tiendas físicas
- Control de presencialidad en obra

**Ventajas:**
- ✅ Verifica que el empleado está físicamente en la ubicación
- ✅ Funciona con App Móvil (Android/iOS)
- ✅ El radio es configurable (50m, 100m, 200m, etc.)

**Configuración:**
1. Edita el edificio
2. Activa **"Control por geolocalización"**
3. Introduce coordenadas GPS
4. Define el radio permitido

![Control geolocalización activo](/assets/images/placeholder-control-gps.png)

{: .tip }
> **Recomendación de radio**: 
> - **50 metros**: Edificios pequeños, control estricto
> - **100 metros**: Edificios medianos (recomendado)
> - **200 metros**: Edificios grandes o campus empresariales

---

### 3. Control por dirección IP

El empleado solo puede fichar si está conectado a la red corporativa.

**Cuándo usar:**
- Oficinas con red WiFi corporativa
- Control de fichaje solo desde ordenadores de empresa
- Restricción a dispositivos corporativos conectados por VPN

**Ventajas:**
- ✅ Funciona para fichaje Web y App (si está en WiFi)
- ✅ Permite configurar varias IPs o rangos
- ✅ Compatible con VPN corporativa

**Configuración:**
1. Edita el edificio
2. Activa **"Control por IP"**
3. Introduce las IPs permitidas (separadas por comas)

**Ejemplos de configuración:**

| Caso | Configuración IP | Ejemplo |
|------|------------------|---------|
| IP única | Una sola IP | `192.168.1.100` |
| Varias IPs | Separadas por comas | `192.168.1.100, 192.168.1.101` |
| Rango de red | Notación CIDR | `192.168.1.0/24` |
| IP pública + VPN | IP pública de oficina | `80.34.123.45` |

{: .note }
> **Nota**: Si un empleado intenta fichar desde una IP no autorizada, recibirá un mensaje de error indicando que debe estar en la red corporativa.

---

### 4. Control combinado (GPS + IP)

Puedes activar ambos controles simultáneamente para máxima seguridad.

**Cuándo usar:**
- Entornos de alta seguridad
- Control estricto de presencialidad
- Prevención de fichajes fraudulentos

**Funcionamiento:**
- El empleado debe cumplir **AMBAS** condiciones para fichar:
  - Estar dentro del radio GPS del edificio
  - Estar conectado a una IP autorizada

---

## Editar un edificio existente

Si necesitas modificar los datos de un edificio:

1. Ve a **"Configuración"** → **"Edificios"**
2. Busca el edificio en el listado
3. Haz clic en el botón **"Editar"** (icono de lápiz)
4. Modifica los campos necesarios
5. Haz clic en **"Guardar cambios"**

{: .warning }
> **Atención**: Si cambias las restricciones de geolocalización o IP, los empleados asignados a este edificio se verán afectados inmediatamente. Comunica los cambios con antelación.

---

## Desactivar un edificio

Si un edificio deja de usarse (cierre, mudanza, etc.):

1. Ve a **"Configuración"** → **"Edificios"**
2. Edita el edificio que quieres desactivar
3. Desmarca la casilla **"Activo"**
4. Guarda los cambios

{: .important }
> **Importante**: Al desactivar un edificio:
> - No se podrán asignar nuevos empleados a él
> - Los empleados actuales **permanecerán asignados** pero no podrán fichar
> - Primero reasigna los empleados a otro edificio activo
> - El edificio seguirá apareciendo en reportes históricos

{: .warning }
> **Nunca elimines un edificio** con empleados o departamentos asignados. Primero reasígnalos y luego desactívalo.

---

## Consultar información de un edificio

### Ver detalles del edificio

1. Ve a **"Configuración"** → **"Edificios"**
2. Haz clic sobre el nombre del edificio
3. Verás un resumen con:
   - Datos de ubicación
   - Empleados asignados
   - Departamentos asignados
   - Restricciones activas (GPS, IP)
   - Festivos configurados para esta ubicación

![Detalle de edificio](/assets/images/placeholder-detalle-edificio.png)

### Ver empleados por edificio

1. Ve a **"Empleados"**
2. Usa el filtro **"Edificio"** en la parte superior
3. Selecciona el edificio
4. Verás solo los empleados de esa ubicación

---

## Festivos por edificio

Cada edificio puede tener su propio calendario de festivos locales.

### Configurar festivos específicos

1. Ve a **"Configuración"** → **"Días Festivos"**
2. Al crear un nuevo festivo, selecciona el **"Edificio"** al que aplica
3. Los festivos locales solo afectarán a empleados de ese edificio

{: .note }
> **Ejemplo**: Si tienes oficinas en Madrid y Barcelona:
> - Madrid: 15 mayo (San Isidro), 9 noviembre (Almudena)
> - Barcelona: 24 septiembre (La Mercè), 26 diciembre (Sant Esteve)

**Resultado:**
- Los empleados de Madrid no trabajarán el 15 de mayo
- Los empleados de Barcelona no trabajarán el 24 de septiembre
- Los festivos nacionales aplican a todos

👉 **Más información**: [Gestión de Días Festivos](/guias-por-rol/administrador/dias-festivos/)

---

## Casos especiales

### Empleado que trabaja en varias ubicaciones

Si un empleado trabaja en diferentes edificios (ejemplo: comercial que visita varias oficinas):

**Opción 1**: Asignarlo al edificio principal y desactivar restricciones de ubicación
**Opción 2**: Cambiar su edificio asignado según su planificación semanal

{: .tip }
> **Solución recomendada**: Para empleados que trabajan en múltiples ubicaciones, crea un edificio genérico llamado "Teletrabajo" o "Ubicación múltiple" sin restricciones de GPS ni IP.

### Empleado en teletrabajo ocasional

Si un empleado trabaja habitualmente en la oficina pero algunos días en remoto:

1. Configura el edificio con restricción de geolocalización
2. Cuando el empleado esté en remoto autorizado:
   - Desmarca temporalmente la restricción de ubicación
   - O permite fichaje manual con justificación

### Mudanza de oficina

Si cambias de edificio:

1. Crea el nuevo edificio con la nueva dirección
2. Reasigna todos los empleados al nuevo edificio (asignación masiva)
3. Actualiza las coordenadas GPS e IPs si aplica
4. Desactiva el edificio antiguo (no elimines para conservar históricos)

### Apertura de nueva sucursal

Al abrir un nuevo centro de trabajo:

1. Crea el nuevo edificio con todos los datos
2. Configura restricciones de ubicación si aplica
3. Asigna los departamentos que operarán en esa sucursal
4. Asigna los empleados que trabajarán allí
5. Configura los festivos locales específicos

---

## Reportes por edificio

Los edificios te permiten generar reportes segmentados por ubicación.

### Reporte de fichajes por edificio

1. Ve a **"Reportes"** → **"Fichajes"**
2. Filtra por **"Edificio"**
3. Selecciona el edificio deseado
4. Establece el rango de fechas
5. Genera y exporta el reporte

### Reporte combinado: edificio + departamento

Puedes generar reportes más específicos combinando filtros:

**Ejemplo**: Fichajes del departamento de Ventas en la oficina de Madrid

1. Filtra por **Edificio**: Oficina Madrid
2. Filtra por **Departamento**: Ventas
3. Genera el reporte

![Reporte por edificio](/assets/images/placeholder-reporte-edificio.png)

---

## Preguntas frecuentes

### ¿Es obligatorio crear edificios?

No es obligatorio, pero es **altamente recomendable** para un control horario preciso y cumplir con el RD 8/2019, especialmente si tienes varias ubicaciones o necesitas control de presencialidad.

### ¿Puedo tener empleados sin edificio asignado?

Sí, pero no es recomendable. Los empleados sin edificio podrán fichar desde cualquier ubicación sin restricciones.

### ¿Cuántos edificios puedo crear?

No hay límite. Puedes crear tantos edificios como centros de trabajo tenga tu empresa.

### ¿Qué pasa si activo geolocalización y un empleado no tiene GPS?

El empleado no podrá fichar desde su dispositivo. Tendrías que:
- Desactivar la restricción GPS para ese empleado específicamente
- O permitir que fiche manualmente (requiere aprobación del manager)

### ¿Puedo cambiar un empleado de edificio temporalmente?

Sí, edita el perfil del empleado y cambia su edificio asignado. Puedes volver a cambiarlo cuando finalice el período temporal.

### ¿Los edificios afectan al cálculo de nóminas?

Los edificios en sí no afectan directamente, pero los **festivos locales** configurados por edificio sí impactan en el cálculo de días laborables y horas trabajadas.

### ¿Qué pasa si un empleado intenta fichar fuera del radio GPS permitido?

Recibirá un mensaje de error indicando que no está en la ubicación autorizada. El fichaje no se registrará hasta que esté dentro del radio permitido.

---

## Resumen de mejores prácticas

✅ **Crea edificios** para cada ubicación física real
✅ **Asigna departamentos** a cada edificio según su estructura
✅ **Configura geolocalización** si necesitas control de presencialidad
✅ **Usa control por IP** para oficinas con red corporativa
✅ **Establece festivos locales** específicos por ubicación
✅ **Revisa asignaciones** periódicamente (empleados nuevos, cambios)
✅ **No elimines edificios** con historial, mejor desactívalos
✅ **Documenta** las restricciones activas en cada edificio

---

## ¿Necesitas ayuda?

Si tienes problemas con la gestión de edificios:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Gestión de Departamentos](/guias-por-rol/administrador/gestion-departamentos/)
- 👉 [Días Festivos](/guias-por-rol/administrador/dias-festivos/)
- 👉 [Dar de Alta Empleados](/guias-por-rol/administrador/dar-alta-empleados/)
- 👉 [Primer Fichaje](/primeros-pasos/primer-fichaje/)