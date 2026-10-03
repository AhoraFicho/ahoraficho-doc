---
layout: default
title: Dar de Alta Empleados
parent: Administrador
grand_parent: Guías por Rol
nav_order: 1
---

# Dar de Alta Empleados
{: .no_toc }

Cómo registrar nuevos trabajadores en AhoraFicho de forma individual o masiva.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Antes de empezar

### Información necesaria

Antes de dar de alta un empleado, ten preparada esta información:

**Datos personales:**
- ✅ Nombre completo
- ✅ Email corporativo (será su usuario)
- ✅ DNI o ID del empleado
- ✅ Teléfono de contacto
- ✅ Fecha de nacimiento

**Datos laborales:**
- ✅ Departamento
- ✅ Horario de trabajo
- ✅ Fecha de alta en la empresa
- ✅ Rol (Empleado, Manager, Admin)

**Configuración de fichaje:**
- ✅ Métodos de fichaje permitidos (Web, App, PIN, QR, RFID)
- ✅ ¿Requiere geolocalización?
- ✅ ¿Requiere fichaje obligatorio?

**Vacaciones:**
- ✅ Días de vacaciones anuales
- ✅ Fecha de caducidad de vacaciones

---

## Alta individual de empleado

### Paso 1: Acceder a Trabajadores

1. Ve al menú lateral **"Configuraciones"** (sección ADMIN)
2. Selecciona **"Trabajadores"**
3. Verás el listado de empleados actuales

### Paso 2: Crear nuevo empleado

1. Haz clic en el botón **"Crear nuevo"** (parte superior)
2. Se abrirá el formulario de alta de empleado

---

## Formulario de alta

El formulario está dividido en varias secciones:

### 📋 Información Personal

**Nombre completo** (obligatorio)
- Nombre y apellidos del empleado
- Ejemplo: "Juan Pérez García"

**Email** (obligatorio)
- Email corporativo del empleado
- Será su **usuario de acceso**
- Debe ser único en el sistema
- Ejemplo: "juan.perez@empresa.com"

{: .warning }
> **Importante**: El email no puede cambiarse después. Asegúrate de que sea correcto.

**DNI/ID Empleado** (obligatorio)
- DNI, NIE o código de empleado
- Ejemplo: "12345678A"
- Útil para identificación en nóminas

**Teléfono** (opcional)
- Número de contacto del empleado
- Formato: Con o sin prefijo internacional
- Ejemplo: "+34 600123456" o "600123456"

**Fecha de nacimiento** (opcional)
- Selecciona del calendario
- Útil para felicitaciones automáticas (si está configurado)

---

### 💼 Información de Contacto

**Usuario** (se genera automáticamente)
- Se crea a partir del email
- No necesitas rellenarlo manualmente

**Contraseña** (obligatoria en alta)
- Contraseña temporal para el primer acceso
- **Requisitos mínimos:**
  - 8 caracteres
  - 1 mayúscula
  - 1 número
  - 1 carácter especial

**Confirmar contraseña**
- Repite la contraseña anterior

{: .tip }
> **Consejo**: Usa una contraseña temporal sencilla como "Temporal123!" y pide al empleado que la cambie en su primer acceso.

---

### 🏢 Configuración Laboral

**Empresa**
- Tu empresa (ya seleccionada por defecto)
- No modificable

**Departamento** (obligatorio)
- Selecciona el departamento inicial del empleado
- En el alta se elige **un** departamento; puedes añadir más departamentos después editando su ficha (asignación múltiple desde edición)

**Horario** (obligatorio)
- Selecciona el horario de trabajo del empleado
- Si aún no existe, créalo primero en [Horarios](/guias-por-rol/administrador/crear-horarios/)
- Puedes cambiarlo después si es necesario

{: .note }
> **Responsables y roles**: Los campos **"Responsable"** y **"Responsable 2"**, así como el **rol** del usuario (Manager, Validador...), se configuran **después del alta**, editando la ficha del trabajador. Sin responsable asignado, las aprobaciones de sus ausencias irán al Administrador.

---

### 🔐 Configuración de PIN para Terminal

**PIN de terminal** (opcional)
- Código de **6 dígitos numéricos** para fichaje en terminales (modo kiosco)
- Solo si vas a habilitar el fichaje por PIN
- Debe ser único por empleado

{: .note }
> Si dejas vacío, el empleado no podrá fichar por PIN.

---

### 📱 Métodos de Fichaje Permitidos

Selecciona qué métodos de fichaje puede usar este empleado:

**☑️ Fichaje Web**
- Desde navegador de escritorio/móvil
- Por defecto: activado

**☑️ Fichaje Móvil**
- Desde aplicación iOS/Android
- Por defecto: activado

**☑️ Fichaje PIN**
- Desde terminal en modo kiosco con código PIN
- Al activarlo se solicita el **PIN de terminal** (6 dígitos)

**☑️ Fichaje RFID**
- Con tarjeta RFID en terminal con lector
- Al activarlo se solicita el **Tag RFID** (identificador de la tarjeta/llavero)

{: .important }
> **Fichaje QR**: estará disponible próximamente, por lo que aún no aparece en el alta. Recuerda habilitar al menos un método disponible: si no activas ninguno, el empleado no podrá fichar.

Los métodos se pueden modificar en cualquier momento desde la **edición del trabajador**.

---

### ⚙️ Configuración General

**☑️ Habilitado**
- Marca esta casilla para que el empleado pueda acceder
- Desactívala para dar de baja temporal
- Por defecto: Marcado

**☑️ Requiere Fichaje**
- Si está marcado, el empleado DEBE fichar
- Si no está marcado, el fichaje es opcional
- Recomendado: Marcado para la mayoría

**☑️ Requiere Geolocalización**
- Si está marcado, debe compartir ubicación al fichar
- Si no, puede fichar sin ubicación
- Útil para trabajadores de campo

---

### 🌴 Configuración de Ausencias

Esta sección la veremos en detalle en [Asignar Vacaciones](/guias-por-rol/administrador/asignar-vacaciones/).

**Días de vacaciones anuales** (opcional)
- Número de días de vacaciones al año
- Ejemplo: 22, 23, 30
- Si dejas vacío, no podrá solicitar vacaciones

**Fecha de caducidad** (opcional)
- Cuándo expiran los días de vacaciones
- Ejemplo: 31/12/2025
- Si dejas vacío, no caducan

---

## Guardar el empleado

Una vez completado el formulario:

1. Revisa que todos los datos son correctos
2. Verifica el email (no podrás cambiarlo después)
3. Haz clic en **"Guardar"** o **"Crear"**

Verás un mensaje de confirmación:
✅ "Empleado creado correctamente"

---

## Después de crear el empleado

### Email de bienvenida

El empleado recibirá automáticamente un email con:
- 👤 Su usuario (el email que configuraste)
- 🔑 Contraseña temporal
- 🔗 Enlace de acceso a AhoraFicho
- 📱 Enlaces de descarga de apps móviles

### Configuración adicional

Después de crear el empleado, puedes:

1. **Asignar vacaciones específicas**
   - Ve a su ficha de empleado
   - Haz clic en "Ausencias Máximas"
   - Configura años específicos

2. **Configurar horario personalizado**
   - Si necesita horario diferente del asignado inicialmente
   - Ve a [Asignar Horarios](/guias-por-rol/administrador/asignar-horarios/)

3. **Añadir a proyectos** (si módulo activo)
   - Asigna el empleado a proyectos específicos

---

## Editar empleado existente

Para modificar datos de un empleado:

1. Ve a **"Configuraciones"** → **"Trabajadores"**
2. Busca el empleado en el listado
3. Haz clic en **"Editar"** (icono de lápiz ✏️)
4. Modifica los campos necesarios
5. Haz clic en **"Guardar"**

### Campos que NO puedes editar

- ❌ Email (es el identificador único)
- ❌ Empresa

Para cambiar el email, debes crear un nuevo usuario.

### Cambiar contraseña de un empleado

Si un empleado olvida su contraseña y no puede recuperarla:

1. Edita el empleado
2. En el campo **"Nueva contraseña"** introduce una temporal
3. En **"Confirmar nueva contraseña"** repite la contraseña
4. Guarda
5. Comunica la contraseña temporal al empleado
6. Pídele que la cambie en su primer acceso

---

## Alta masiva de empleados

Si necesitas dar de alta a muchos empleados a la vez:

### Opción 1: Importar desde Excel/CSV

1. Ve a **"Configuraciones"** → **"Trabajadores"**
2. Haz clic en **"Importar"**
3. Descarga la **plantilla de ejemplo**
4. Rellena la plantilla con los datos de tus empleados
5. Guarda el archivo en formato **CSV** o **Excel**
6. Sube el archivo
7. Revisa los datos antes de confirmar
8. Haz clic en **"Importar"**

### Estructura de la plantilla

La plantilla incluye estas columnas:

| Campo | Obligatorio | Ejemplo |
|:------|:------------|:--------|
| Nombre completo | Sí | Juan Pérez García |
| Email | Sí | juan.perez@empresa.com |
| DNI | Sí | 12345678A |
| Teléfono | No | 600123456 |
| Departamento | Sí | Ventas |
| Horario | Sí | Jornada Partida |
| Contraseña | Sí | Temporal123! |

{: .warning }
> **Importante**: Todos los emails deben ser únicos. Emails duplicados causarán error en la importación.

### Ventajas de la importación masiva

- ✅ Ahorra tiempo con muchos empleados
- ✅ Menos errores de tipeo
- ✅ Puedes preparar los datos fuera del sistema
- ✅ Puedes revisar antes de confirmar

---

## Roles y permisos

El rol **no se asigna en el formulario de alta**: se configura después, editando la ficha del trabajador o desde **"Configuraciones" → "Roles"**.

### Roles disponibles

**Empleado** (sin rol asignado)
- Acceso básico
- Solo ve su información
- No puede validar ni configurar

**Manager**
- Todo lo anterior +
- Valida **ausencias, gastos e imputaciones** de su equipo (departamentos y/o asignados)
- Ve reportes de su equipo

**Validador**
- Valida los **cambios de fichaje** de los empleados de su ámbito
- Consulta los **cierres mensuales**
- Ver [Guía del Validador](/guias-por-rol/validador/)

**Admin**
- Todo lo anterior +
- Valida ausencias, gastos, imputaciones **y cambios de fichaje**
- Puede dar de alta/baja empleados, configurar la empresa y **reabrir cierres mensuales**

**SuperAdmin** (solo para Solutions2AZ)
- Acceso total al sistema
- Gestión multi-empresa
- No asignes este rol a empleados normales

### Asignar rol

Los roles se asignan en la sección **"Configuraciones"** → **"Roles"**:

1. Ve a Roles
2. Selecciona el rol (Manager, Validador, Admin)
3. Añade el usuario al rol
4. Guarda

{: .note }
> Un usuario puede tener múltiples roles. Por ejemplo, puede ser Manager Y Validador a la vez.

---

## Verificar usuarios activos disponibles

### Límite de usuarios

Tu plan de AhoraFicho tiene un **límite de usuarios activos**:

1. Ve a **"Configuraciones"** → **"Trabajadores"**
2. En la parte superior verás:
   ```
   Usuarios activos: 45 / 50
   Usuarios disponibles: 5
   ```

{: .warning }
> **Atención**: Si alcanzas el máximo de usuarios activos, no podrás dar de alta más empleados hasta que desactives alguno o amplíes tu plan.

### Ampliar plan

Si necesitas más usuarios:
1. Contacta con soporte: soporte@ahoraficho.es
2. O con tu comercial asignado
3. Se actualizará tu plan según necesidades

---

## Casos especiales

### Empleado con múltiples departamentos

En el **alta** se selecciona el departamento inicial. Para asignar varios departamentos a un empleado:

1. Guarda el alta con su departamento principal
2. Edita la ficha del trabajador
3. Marca **todos** los departamentos a los que pertenece

### Empleado sin departamento

{: .warning }
> **No recomendado**: Siempre asigna al menos un departamento. Sin departamento, el empleado puede tener problemas de acceso a ciertas funcionalidades.

Si temporalmente no sabes el departamento:
- Crea un departamento "Sin asignar" o "General"
- Asígnalo provisionalmente
- Cámbialo cuando tengas la información correcta

### Empleado con horario flexible

Si el empleado no tiene horario fijo:

1. Crea un horario "Flexible" sin horas específicas
2. O márcalo como "sin horario"
3. Configura **"Requiere Fichaje"** como NO obligatorio

### Becarios o temporales

Para empleados temporales:

1. Créalos normalmente
2. Anota la fecha de fin de contrato
3. Desactívalos cuando finalice el período
4. No los borres (mantén histórico)

---

## Buenas prácticas

### ✅ Recomendaciones

**Antes de crear:**
- Verifica que el email sea correcto (no podrás cambiarlo)
- Asegúrate de tener el departamento creado
- Ten listo el horario que asignarás
- Prepara los datos completos

**Durante la creación:**
- Rellena todos los campos obligatorios
- Asigna al menos un método de fichaje
- Configura un responsable (Manager)
- Establece días de vacaciones desde el inicio

**Después de crear:**
- Verifica que el empleado recibió el email de bienvenida
- Confirma que puede acceder al sistema
- Revisa su ficha para verificar datos
- Asigna vacaciones específicas si es necesario

### ❌ Evita

- Crear usuarios sin email verificado
- Usar emails personales en lugar de corporativos
- Dejar sin departamento
- Dejar sin horario asignado
- No configurar métodos de fichaje
- Usar contraseñas demasiado complejas (temporales)
- Borrar empleados en lugar de desactivarlos

---

## Solución de problemas

### El email ya existe

**Error**: "El email ya está registrado en el sistema"

**Solución:**
- Verifica si el empleado ya existe (búscalo)
- Si existe pero está desactivado, reactívalo
- Si es un empleado nuevo, usa otro email

### No recibe el email de bienvenida

**Posibles causas:**
- Email incorrecto
- Filtro de spam
- Servidor de email con problemas

**Soluciones:**
1. Verifica el email en la ficha del empleado
2. Pide al empleado que revise spam
3. Reenvía las credenciales manualmente
4. Genera nueva contraseña y envíala por otro medio

### Error al importar empleados

**Errores comunes:**
- Formato de archivo incorrecto (usa CSV o Excel)
- Emails duplicados
- Departamentos que no existen
- Horarios que no existen

**Solución:**
- Descarga la plantilla de nuevo
- Verifica que departamentos y horarios existan
- Revisa que no haya emails repetidos
- Asegúrate del formato correcto

---

## Preguntas frecuentes

### ¿Puedo crear empleados sin asignar horario?

Técnicamente sí, pero no es recomendable. Sin horario:
- No se podrán generar reportes comparativos
- No se detectarán impuntualidades
- El empleado no sabrá cuándo debe fichar

### ¿Qué pasa si creo un empleado sin activar "Habilitado"?

El empleado quedará creado pero **no podrá acceder** al sistema hasta que lo actives.

### ¿Puedo cambiar el email de un empleado?

No directamente. El email es el identificador único. Si necesitas cambiarlo:
1. Crea un nuevo usuario con el email correcto
2. Desactiva el usuario antiguo
3. Nota: Se perderá el histórico vinculado al usuario anterior

### ¿Los empleados ven su contraseña inicial?

Sí, la reciben por email. Deben cambiarla en su primer acceso por seguridad.

### ¿Cuántos empleados puedo crear?

Depende de tu plan contratado. Verifica en "Trabajadores" cuántos usuarios activos tienes disponibles.

---

## ¿Necesitas ayuda?

Si tienes problemas al dar de alta empleados:

- 🔧 Consulta esta guía completa
- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)
- 📞 Soporte telefónico (horario comercial)

---

## Guías relacionadas

- 👉 [Desactivar usuarios](/guias-por-rol/administrador/desactivar-empleados/)
- 👉 [Crear horarios](/guias-por-rol/administrador/crear-horarios/)
- 👉 [Asignar horarios](/guias-por-rol/administrador/asignar-horarios/)
- 👉 [Asignar vacaciones](/guias-por-rol/administrador/asignar-vacaciones/)
- 👉 [Gestión de departamentos](/guias-por-rol/administrador/gestion-departamentos/)