---
layout: default
title: Fichajes
nav_order: 6
has_children: true
permalink: /modulos/fichajes/
---

# Módulo de Fichajes
{: .no_toc }

El módulo de Fichajes es el núcleo de AhoraFicho. Permite registrar la entrada y salida de los empleados cumpliendo con el Real Decreto-ley 8/2019 sobre control horario obligatorio.
{: .fs-6 .fw-300 }

---

## ¿Qué es el módulo de Fichajes?

El **módulo de Fichajes** es el sistema de registro de jornada laboral que permite a los empleados marcar su entrada y salida del trabajo. Es el componente principal de AhoraFicho y está **siempre activo** (no se puede desactivar).

### Características principales

- ⏰ **Registro de entrada/salida**: Los empleados fichan al llegar y al salir
- 📱 **Múltiples métodos**: Web, App móvil, PIN, RFID (QR próximamente)
- 🌍 **Control de ubicación**: GPS y restricción por IP (opcional)
- 📊 **Historial completo**: Todos los fichajes quedan registrados
- 🔏 **Cierre mensual**: El trabajador puede cerrar y firmar su mes con confirmación de fichajes
- ✅ **Cumplimiento legal**: 100% conforme al RD 8/2019

{: .important }
> **Obligatorio**: Este módulo está siempre activo porque es un requisito legal en España desde 2019. No puede desactivarse.

---

## ¿Quién puede fichar?

Todos los empleados activos pueden fichar, independientemente de su rol:

| Rol | Puede fichar | Puede ver fichajes de otros |
|-----|--------------|------------------------------|
| **Empleado** | ✅ Sí | ❌ No (solo los suyos) |
| **Manager** | ✅ Sí | ✅ Sí (su equipo: departamento y/o asignados, vía reportes) |
| **Validador** | ✅ Sí | ✅ Sí (ámbito de validación, vía gestiones de fichajes) |
| **Administrador** | ✅ Sí | ✅ Sí (todos) |
| **SuperAdmin** | ✅ Sí | ✅ Sí (todas las empresas) |

---

## Métodos de fichaje disponibles

AhoraFicho ofrece **4 métodos diferentes** para fichar:

### 1. 🌐 Fichaje Web

Fichar desde el navegador accediendo a la url de tu empresa, por ejemplo demo.ahoraficho.es

- **Ventajas**: No requiere instalar nada
- **Ideal para**: Empleados con ordenador de sobremesa
- **Requiere**: Usuario y contraseña

👉 [Ver guía: Primer Fichaje](/primeros-pasos/primer-fichaje/)

### 2. 📱 Fichaje App Móvil

Fichar desde la aplicación Android/iOS

- **Ventajas**: Acceso rápido, puede usar GPS
- **Ideal para**: Empleados en movimiento, teletrabajo
- **Requiere**: App instalada + usuario y contraseña

👉 [Ver guía: Descarga App Móvil](/primeros-pasos/descarga-app-movil/)

### 3. 🔢 Fichaje PIN

Fichar desde un terminal compartido usando código de 6 dígitos

- **Ventajas**: Muy rápido, no requiere login
- **Ideal para**: Fábricas, almacenes, cocinas
- **Requiere**: Terminal fijo + PIN personal

👉 [Ver guía: Métodos de Fichaje](/modulos/fichajes/metodos-fichaje/)

### 4. 🏷️ Fichaje RFID

Fichar con tarjeta o llavero RFID

- **Ventajas**: Más rápido, profesional
- **Ideal para**: Oficinas grandes, hoteles
- **Requiere**: Lector RFID + tarjetas

👉 [Ver guía: Métodos de Fichaje](/modulos/fichajes/metodos-fichaje/)

### 📷 Fichaje QR (próximamente)

El fichaje por código QR estará disponible próximamente. El QR actual de la plataforma sirve para configurar el acceso a la app móvil, no para fichar.

---

## Funcionamiento básico

### Ciclo de fichaje normal

1. **Entrada mañana**: Empleado ficha al llegar (ej: 09:00)
2. **Salida pausa**: Empleado ficha al salir a comer (ej: 14:00)
3. **Entrada tarde**: Empleado ficha al volver (ej: 15:30)
4. **Salida final**: Empleado ficha al terminar (ej: 18:30)

**Resultado**:
- Total fichajes: 4 (2 pares completos)
- Horas totales: 9h 30m (de 09:00 a 18:30)
- Horas efectivas: 8h (5h mañana + 3h tarde)

### Tipos de fichaje

El botón de fichaje cambia automáticamente según tu horario y tus fichajes del día:

- 🟢 **Iniciar jornada** (primer fichaje del día)
- 🔵 **Iniciar pausa** (salida intermedia)
- 🟣 **Terminar pausa** (regreso de la pausa)
- 🔴 **Finalizar jornada** (último fichaje del día)
- ⚡ **Fichar ahora** (cuando la jornada ya está completa)

{: .tip }
> **Automático**: El empleado solo pulsa el botón; el sistema determina el tipo de fichaje según tu horario y los registros del día. Si tu horario tiene activado el **registro de jornada en un paso**, verás el botón "Registrar Jornada" para registrar todos los fichajes del día de una sola vez.

---

## Control de ubicación

### Fichaje sin restricciones (por defecto)

Los empleados pueden fichar desde cualquier lugar sin limitaciones.

**Ideal para**:
- Equipos en teletrabajo
- Comerciales en la calle
- Equipos remotos

### Fichaje con GPS (geolocalización)

Los empleados solo pueden fichar si están dentro del radio configurado del edificio.

Si el trabajador pertenece a un departamento con un centro con GPS y otro centro sin restricciones (por ejemplo, "Teletrabajo"), sí podrá fichar desde fuera del centro: el fichaje quedará asociado automáticamente al centro sin restricciones.

**Ideal para**:
- Oficinas físicas con presencia obligatoria
- Fábricas y almacenes
- Control de presencialidad en obra

👉 [Ver guía: Gestión de Edificios](/guias-por-rol/administrador/gestion-edificios/)

### Fichaje con restricción IP

Los empleados solo pueden fichar si están conectados a la red corporativa.

**Ideal para**:
- Oficinas con WiFi corporativa
- Control estricto de ubicación
- Empresas con VPN

👉 [Ver guía: Gestión de Edificios](/guias-por-rol/administrador/gestion-edificios/)

---

## Consultar fichajes

### Para empleados

Los empleados pueden consultar sus propios fichajes:

1. Ve a **"Mis Fichajes"** en el menú
2. Selecciona el rango de fechas
3. Verás todos tus fichajes con hora y ubicación

👉 [Ver guía: Consultar Mis Fichajes](/guias-por-rol/empleado/consultar-mis-fichajes/)

### Para Managers

Los Managers pueden ver los fichajes de su equipo en los reportes:

1. Ve a **"Reportes"**
2. Haz clic en **"Resumen diario"** o **"Resumen semanal"**
3. Verás los fichajes del equipo

👉 [Ver guía: Resumen Diario por Departamento](/reportes/resumen-diario-departamento/)

### Para Administradores

Los Administradores pueden ver todos los fichajes:

1. Ve a **"Reportes"**
2. Filtra por empleado, departamento, edificio, fecha
3. Exporta a PDF o Excel si es necesario

---

## ¿Olvidé fichar?

Si un empleado olvida fichar, dispone de dos mecanismos:

**1. Fichar ahora**: lo primero es fichar lo antes posible con la hora real (aunque sea tarde).

**2. Solicitar un cambio de fichaje** para corregir la hora:
1. Ve a **"Mi Trabajo"** → **"Mis Fichajes"**
2. Localiza el día afectado y pulsa el icono del lápiz (**"Solicitar cambio"**)
3. Introduce la hora correcta y el motivo
4. Un Validador o Administrador aprobará o rechazará la solicitud

Además, si un día aparece como **"Sin fichajes"** o con **"Incidencia"**, verás un botón **"Solucionar"** que permite crear o corregir los fichajes de ese día de forma guiada (queda registrado como cambio con su trazabilidad).

👉 [Ver guía: ¿Olvidé Fichar?](/guias-por-rol/empleado/olvide-fichar/)

{: .important }
> **Trazabilidad**: Todos los cambios de fichaje quedan registrados con el nombre del aprobador para cumplir con el RD 8/2019.

---

## Cierre mensual

El trabajador puede **cerrar su mes de forma mensual**: confirma cada uno de sus fichajes del mes anterior, firma digitalmente y el mes queda cerrado. Una vez cerrado un mes, no se pueden solicitar cambios de fichaje de ese mes.

- Se realiza desde **"Mis Fichajes" → "Cierre Mensual"** durante los primeros días de cada mes (plazo configurable).
- El historial de cierres está en **"Mi Trabajo" → "Mis Cierres"**, con descarga de PDF firmado.
- Validadores y Administradores consultan los cierres en **"Validaciones" → "Cierres Mensuales"**; los Administradores pueden reabrir un cierre con su motivo registrado.

👉 [Ver guía: Cierre Mensual (empleado)](/guias-por-rol/empleado/cierres-mensuales/)

👉 [Ver guía: Revisar Cierres Mensuales (validador/admin)](/guias-por-rol/validador/revisar-cierres/)

---

## Reportes de fichajes

Los fichajes se pueden exportar en varios formatos para diferentes propósitos:

### Informe para Inspección de Trabajo

Documento oficial que cumple 100% con el RD 8/2019.

👉 [Ver guía: Informe para Inspección de Trabajo](/reportes/informe-inspeccion-trabajo/)

### Reporte Mensual

Informe mensual para nóminas y auditorías.

👉 [Ver guía: Reporte Mensual](/reportes/reporte-mensual/)

### Resumen Diario/Semanal

Para supervisión del día a día del equipo.

👉 [Ver guía: Resumen Diario](/reportes/resumen-diario-departamento/)

---

## Cumplimiento normativo

El módulo de Fichajes cumple con:

- ✅ **Real Decreto-ley 8/2019**: Registro de jornada obligatorio
- ✅ **Artículo 34.9 del Estatuto de los Trabajadores**: Hora de inicio y fin
- ✅ **LOPD**: Protección de datos personales
- ✅ **Conservación**: Registros durante 4 años

{: .note }
> **Transparencia**: Los fichajes deben estar disponibles para empleados, representantes legales e Inspección de Trabajo.

---

## Preguntas frecuentes

### ¿Puedo fichar varias veces al día?

Sí, no hay límite. Si sales a comer o a una reunión externa y vuelves, debes fichar salida y entrada cada vez.

### ¿Qué pasa si olvido fichar?

Solicita una corrección desde "Mis Fichajes". Tu Manager deberá aprobar el cambio.

### ¿Los fichajes se pueden modificar?

No directamente. Los empleados deben solicitar cambios que deben ser aprobados por un **Validador** o **Administrador**. Si el mes ya está cerrado con el cierre mensual, no se pueden solicitar cambios (salvo que un Administrador reabra el cierre).

### ¿Puedo fichar desde mi móvil personal?

Sí, descarga la app de AhoraFicho (Android/iOS) e inicia sesión con tu usuario.

### ¿Los fichajes tienen en cuenta festivos?

Sí, si un día es festivo configurado en el sistema, no se contará como ausencia si no fichas.

### ¿Se puede fichar sin conexión a internet?

No, siempre se necesita acceso a internet para poder fichar.

---

## ¿Necesitas ayuda?

Si tienes dudas sobre el módulo de Fichajes:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Primer Fichaje](/primeros-pasos/primer-fichaje/)
- 👉 [Métodos de Fichaje](/modulos/fichajes/metodos-fichaje/)
- 👉 [Historial de Fichajes](/guias-por-rol/empleado/consultar-mis-fichajes/)
- 👉 [¿Olvidé Fichar?](/guias-por-rol/empleado/olvide-fichar/)
- 👉 [Cierre Mensual](/guias-por-rol/empleado/cierres-mensuales/)
- 👉 [Gestión de Edificios](/guias-por-rol/administrador/gestion-edificios/)