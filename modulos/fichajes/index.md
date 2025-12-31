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
- 📱 **Múltiples métodos**: Web, App móvil, PIN, QR, RFID
- 🌍 **Control de ubicación**: GPS y restricción por IP (opcional)
- 📊 **Historial completo**: Todos los fichajes quedan registrados
- ✅ **Cumplimiento legal**: 100% conforme al RD 8/2019

{: .important }
> **Obligatorio**: Este módulo está siempre activo porque es un requisito legal en España desde 2019. No puede desactivarse.

---

## ¿Quién puede fichar?

Todos los empleados activos pueden fichar, independientemente de su rol:

| Rol | Puede fichar | Puede ver fichajes de otros |
|-----|--------------|------------------------------|
| **Empleado** | ✅ Sí | ❌ No (solo los suyos) |
| **Manager** | ✅ Sí | ✅ Sí (su departamento) |
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

<!-- ### 4. 📷 Fichaje QR

Fichar escaneando código QR desde la app móvil

- **Ventajas**: Higiénico (sin tocar pantalla), rápido
- **Ideal para**: Oficinas, tiendas
- **Requiere**: App móvil + código QR visible

👉 [Ver guía: Métodos de Fichaje](/modulos/fichajes/metodos-fichaje/) -->

### 4. 🏷️ Fichaje RFID

Fichar con tarjeta o llavero RFID

- **Ventajas**: Más rápido, profesional
- **Ideal para**: Oficinas grandes, hoteles
- **Requiere**: Lector RFID + tarjetas

👉 [Ver guía: Métodos de Fichaje](/modulos/fichajes/metodos-fichaje/)

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

Cuando un empleado ficha, el sistema alterna automáticamente entre:

- 🟢 **Entrada** (fichaje impar: 1º, 3º, 5º...)
- 🔴 **Salida** (fichaje par: 2º, 4º, 6º...)

{: .tip }
> **Automático**: El empleado solo hace clic en "Fichar", el sistema detecta automáticamente si es entrada o salida según el último fichaje.

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

Los Managers pueden ver fichajes de su equipo:

1. Ve a **"Reportes"**
2. Haz clic en **"Resumen Diario Dpto"** o **"Resumen Semanal Dpto"**
3. Verás todos los fichajes del equipo

👉 [Ver guía: Resumen Diario por Departamento](/reportes/resumen-diario-departamento/)

### Para Administradores

Los Administradores pueden ver todos los fichajes:

1. Ve a **"Reportes"**
2. Filtra por empleado, departamento, edificio, fecha
3. Exporta a PDF o Excel si es necesario

---

## ¿Olvidé fichar?

Si un empleado olvida fichar, puede solicitar una corrección:
1. **"Ficha lo antes posible"**
2. Ve a **"Mis Fichajes"**
3. Selecciona el registro de ahora mismo
4. Haz clic en **"Solicitar cambio"**
5. Introduce la hora correcta y el motivo
6. El Manager aprobará o rechazará la solicitud

👉 [Ver guía: ¿Olvidé Fichar?](/guias-por-rol/empleado/olvide-fichar/)

{: .important }
> **Trazabilidad**: Todos los cambios de fichaje quedan registrados con el nombre del aprobador para cumplir con el RD 8/2019.

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

No directamente. Los empleados deben solicitar cambios que deben ser aprobados por un Manager o Administrador.

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
- 👉 [Gestión de Edificios](/guias-por-rol/administrador/gestion-edificios/)