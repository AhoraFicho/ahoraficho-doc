---
layout: default
title: Copias de Seguridad
parent: Guía del Administrador
grand_parent: Guías por Rol
nav_order: 12
---

# Copias de Seguridad
{: .no_toc }

Configura copias de seguridad automáticas de la base de datos de AhoraFicho y envíalas a tu propio servidor FTP o FTPS, con la frecuencia y la retención que decidas.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué son las copias de seguridad en AhoraFicho?

La pantalla de **Copias de seguridad** te permite proteger los datos de tu empresa creando una copia completa de la base de datos y subiéndola automáticamente a un servidor que tú controlas:

- ✅ Copia completa de la base de datos en formato estándar SQLite (`.db`), restaurable
- ✅ Destino propio: tu servidor **FTP o FTPS** (con TLS, recomendado)
- ✅ Programación flexible: **cada día a una hora fija** o **cada X horas**
- ✅ **Retención automática**: se eliminan del servidor las copias más antiguas
- ✅ **Historial** de ejecuciones con estado, tamaño y duración
- ✅ Aviso por **correo a los administradores** si una copia programada falla

{: .important }
> **Disponibilidad**: esta función está disponible en despliegues que usan base de datos **SQLite** (la mayoría de los clientes). Si tu despliegue usa PostgreSQL, la pantalla lo indicará con un aviso y la función permanecerá deshabilitada.

{: .note }
> La contraseña de tu servidor FTP se guarda **cifrada** y nunca se muestra de nuevo en pantalla: si la escribes en blanco al editar, se mantiene la guardada.

---

## Acceder a la pantalla

1. Inicia sesión como **Administrador**
2. Ve al menú lateral y haz clic en **"Configuraciones"**
3. Selecciona **"Copias de seguridad"**

La pantalla tiene dos pestañas: **Configuración** (servidor, programación y retención) y **Historial** (ejecuciones realizadas).

---

## Configurar la copia de seguridad

### Paso 1: Datos del servidor FTP

En la pestaña **Configuración**, completa los datos de conexión:

| Campo | Descripción | Ejemplo |
|-------|-------------|---------|
| **Servidor (host)** | Dirección del servidor FTP | `ftp.tudominio.es` |
| **Puerto** | Puerto de conexión (por defecto 21) | `21` |
| **Usuario** | Usuario del servidor | `backups` |
| **Contraseña** | Contraseña del servidor | `••••••••` |
| **Carpeta remota** | Carpeta de destino en el servidor; se crea si no existe | `/backups/ahoraficho` |
| **Usar FTPS (TLS)** | Cifra la conexión para proteger credenciales y datos | Activado ✅ |

{: .warning }
> Siempre que tu servidor lo soporte, activa **FTPS (TLS)**: con FTP plano las credenciales y las copias viajan sin cifrar por la red.

### Paso 2: Programación

Elige la frecuencia con la que se generará la copia:

| Frecuencia | Comportamiento |
|------------|----------------|
| **Cada día a una hora fija** | Se genera una copia al día a la hora indicada |
| **Cada X horas** | Se genera una copia cada X horas (entre 1 y 24) |

{: .note }
> La **hora de ejecución** es la **hora del servidor** donde está instalada la aplicación. En despliegues en la nube suele ser UTC; tenlo en cuenta al elegir la hora.

Si una copia diaria falla (por ejemplo, si el servidor FTP no responde), la aplicación **reintenta automáticamente** durante las dos horas siguientes a la hora programada.

### Paso 3: Retención

En **Copias a conservar** indica cuántas copias quieres mantener en tu servidor. Tras cada subida correcta, la aplicación elimina del servidor las copias más antiguas que superen ese número, de modo que el espacio usado se mantiene estable.

### Paso 4: Guardar y comprobar

1. Revisa los datos del formulario
2. Haz clic en **"Probar conexión"** para verificar que la aplicación puede conectar con tu servidor y crear la carpeta de destino, sin guardar todavía los cambios
3. Haz clic en **"Guardar configuración"**

{: .tip }
> La prueba de conexión usa los valores escritos en el formulario, así que puedes verificarla antes de guardar. Si dejas la contraseña en blanco, se probará con la ya guardada.

---

## Ejecutar una copia manualmente

Junto al título de la pantalla tienes el botón **"Ejecutar ahora"**:

1. Confirma la acción en el diálogo que aparece
2. La aplicación genera la copia completa y la sube a tu servidor con la configuración guardada
3. Al terminar verás un mensaje con el nombre del fichero, su tamaño y la duración

Las copias manuales también se registran en el historial y aplican la retención configurada.

---

## Consultar el historial

En la pestaña **Historial** verás las últimas ejecuciones (las 100 más recientes):

| Columna | Contenido |
|---------|-----------|
| **Fecha** | Cuándo comenzó la copia |
| **Fichero** | Nombre del fichero subido (con fecha y hora) |
| **Tamaño** | Tamaño de la copia generada |
| **Duración** | Tiempo total de la ejecución |
| **Origen** | **Programada** (automática) o **Manual** |
| **Estado** | **Correcta** o **Fallida** |

En las copias fallidas, al pasar el cursor sobre el badge de estado verás el detalle del error.

{: .important }
> Si una copia **programada** falla, se envía automáticamente un correo a los administradores del despliegue con el detalle del error. Revisa también el historial para ver si los reintentos tuvieron éxito.

---

## Preguntas frecuentes

### ¿Cómo restauro una copia?

Los ficheros son bases de datos SQLite completas. Si necesitas restaurar una copia, contacta con soporte en soporte@ahoraficho.es e indica la fecha de la copia a recuperar.

### ¿Los ficheros de copia contienen mis datos de acceso al servidor FTP?

No. Cada fichero contiene únicamente la base de datos de la aplicación. Las credenciales del servidor FTP solo se guardan cifradas en la propia aplicación.

### ¿Puedo usar dos destinos distintos?

No, la configuración admite un único servidor de destino. Si necesitas más, puedes planificar copias adicionales desde tu propio servidor descargando las copias subidas.

### ¿Qué pasa si cambio el servidor FTP?

Guarda los nuevos datos y usa **"Probar conexión"** antes de dar por buena la nueva configuración. La retención se aplicará solo sobre los ficheros subidos por AhoraFicho en la nueva carpeta.

---

## Guías relacionadas

- [Dar de alta empleados](/guias-por-rol/administrador/dar-alta-empleados/)
- [Informe para inspección](/reportes/informe-inspeccion-trabajo/)
- [Preguntas frecuentes](/preguntas-frecuentes/)
