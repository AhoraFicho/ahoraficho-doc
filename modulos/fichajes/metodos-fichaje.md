---
layout: default
title: Métodos de Fichaje
parent: Fichajes
nav_order: 1
---

# Métodos de Fichaje
{: .no_toc }

AhoraFicho ofrece 4 métodos diferentes para que los empleados registren su entrada y salida. Cada método está diseñado para diferentes entornos de trabajo y necesidades. El fichaje por código QR estará disponible próximamente.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{: .important }
> **Conexión a internet**: Todos los métodos de fichaje requieren conexión a internet en el momento del fichaje. No existe modo offline: el fichaje se registra en el servidor de forma inmediata.

---

## Comparativa de métodos

| Método | Velocidad | Requiere | Ideal para |
|--------|-----------|----------|------------|
| **🌐 Web** | ⭐⭐⭐ | Usuario + contraseña | Oficinas con ordenador |
| **📱 App Móvil** | ⭐⭐⭐⭐ | App instalada | Teletrabajo, movilidad |
| **🔢 PIN** | ⭐⭐⭐⭐⭐ | Solo PIN (6 dígitos) | Fábricas, almacenes |
| **🏷️ RFID** | ⭐⭐⭐⭐⭐ | Tarjeta/llavero | Oficinas grandes, hoteles |
| **📷 QR** | — | — | 🔜 Próximamente |

Cada trabajador puede tener habilitados uno o varios métodos: el Administrador los configura en la ficha del empleado (alta o edición).

---

## 1. 🌐 Fichaje Web

Fichar desde el navegador accediendo a la plataforma web.

### Cómo funciona

1. Abre tu navegador (Chrome, Firefox, Edge, Safari)
2. Ve a la url de tu empresa, por ejemplo: **demo.ahoraficho.es**
3. Inicia sesión con tu usuario y contraseña
4. Pulsa el botón de fichaje de la barra superior: **"Iniciar jornada"**, **"Iniciar pausa"**, **"Terminar pausa"**, **"Finalizar jornada"** o **"Fichar ahora"**, según el momento del día

<!-- ![Fichaje web](/assets/images/placeholder-fichaje-web.png) -->

### El botón se adapta a tu horario

El botón cambia automáticamente según tus fichajes de hoy y tu horario:

| Situación | Botón |
|-----------|-------|
| Primer fichaje del día | **Iniciar jornada** |
| Pausa (salida intermedia) | **Iniciar pausa** |
| Volver de la pausa | **Terminar pausa** |
| Último fichaje del día | **Finalizar jornada** |
| Jornada ya completa (horas extra) | **Fichar ahora** |

### Registro de jornada en un paso

Si tu empresa ha activado el **fichaje en un paso** en tu horario, en lugar del botón habitual verás **"Registrar Jornada"**: se abre un modal con los bloques de tu horario de hoy, que puedes ajustar antes de confirmar. Al confirmar se registran todos los fichajes del día de una sola vez.

### Ventajas

✅ No requiere instalar nada
✅ Funciona en cualquier ordenador con internet
✅ Muestra el estado de tu jornada en todo momento

### Desventajas

❌ Requiere escribir usuario y contraseña (a menos que guardes sesión)
❌ Más lento que PIN o RFID

### Ideal para

- Empleados con ordenador de sobremesa en oficina
- Trabajadores con tareas administrativas
- Teletrabajo desde casa

{: .tip }
> **Consejo**: Guarda la url de tu empresa como marcador/favorito en tu navegador para acceder rápidamente.

---

## 2. 📱 Fichaje App Móvil

Fichar desde la aplicación móvil de AhoraFicho en tu smartphone.

### Cómo funciona

1. Descarga la app **AhoraFicho** desde Google Play (Android) o App Store (iOS)
2. Inicia sesión con tu usuario y contraseña (o escanea el código QR de configuración desde la web)
3. Abre la app
4. Toca el botón grande de fichaje
5. ¡Fichaje registrado!

<!-- ![Fichaje app móvil](/assets/images/placeholder-fichaje-app.png) -->

### Ventajas

✅ Muy rápido (la app se abre al instante)
✅ Puede usar **GPS** para verificar ubicación
✅ Recibes notificaciones push (recordatorios, aprobaciones, alertas)
✅ Mismo botón adaptativo que la web

### Desventajas

❌ Requiere instalación previa
❌ Consume batería si usa GPS constantemente
❌ Necesita smartphone personal o corporativo
❌ **Requiere conexión a internet** (datos móviles o WiFi)

### Ideal para

- Empleados en teletrabajo
- Comerciales que viajan
- Equipos de campo
- Trabajadores sin ordenador fijo
- Cualquier empleado con smartphone

{: .important }
> **Geolocalización**: Si tu empresa tiene activado el control por GPS, la app verificará que estés en la ubicación correcta antes de permitir fichar.

👉 [Ver guía: Descarga App Móvil](/primeros-pasos/descarga-app-movil/)

---

## 3. 🔢 Fichaje PIN

Fichar usando un código PIN de 6 dígitos en un terminal compartido (tablet u ordenador en modo kiosco).

### Cómo funciona

1. Accede al terminal de fichaje
2. La pantalla muestra un **teclado numérico**
3. Introduce tu **PIN de 6 dígitos** (ej: 123456)
4. El sistema valida el PIN y muestra un resumen: tu nombre, **"Tiempo trabajado hoy"** y tus **"Fichajes de hoy"**
5. Pulsa el botón de fichaje y verás la confirmación **"Fichaje registrado"** con la hora

<!-- ![Fichaje PIN](/assets/images/placeholder-fichaje-pin.png) -->

### ¿Dónde está mi PIN?

Tu PIN de terminal se define cuando el Administrador te da de alta (o al importar empleados masivamente). No puedes cambiarlo tú mismo: si lo olvidas, pide a tu Administrador que te asigne uno nuevo.

### Ventajas

✅ **Muy rápido**: Fichar en 3 segundos
✅ No requiere login completo
✅ No necesita smartphone personal
✅ Un terminal sirve para todos
✅ Muestra el tiempo trabajado del día al fichar

### Desventajas

❌ Requiere un terminal fijo compartido
❌ Puede haber colas si hay muchos empleados
❌ Hay que recordar el PIN
❌ Riesgo de que alguien vea tu PIN

### Ideal para

- **Fábricas** con muchos operarios
- **Almacenes** y centros logísticos
- **Cocinas** industriales
- **Tiendas** físicas
- Cualquier lugar donde los empleados no tengan ordenador o móvil durante el trabajo

### Configurar terminal PIN

**Para Administradores:**
1. Ve a **"Configuraciones"** → **"Dispositivos"**
2. Registra un nuevo dispositivo: el sistema genera los tokens de acceso del terminal
3. Abre en el dispositivo la url del terminal (formato `/AccessEntry/Terminal/{token}?secToken={tokenSeguridad}`)
4. La pantalla queda en **modo kiosco**: teclado numérico de PIN a pantalla completa, sin acceso a ninguna otra función
5. Coloca el terminal en un lugar accesible para todos

{: .warning }
> **Seguridad**: El terminal en modo kiosco no permite acceder a ninguna otra función de la plataforma. Solo fichar con PIN.

---

## 4. 🏷️ Fichaje RFID

Fichar acercando una tarjeta o llavero RFID a un lector conectado a un terminal registrado.

### Cómo funciona

1. Tu empresa instala un **lector RFID** conectado a un terminal registrado en **"Configuraciones" → "Dispositivos"**
2. Cada empleado recibe una **tarjeta** o **llavero RFID** personal, cuyo identificador (Tag RFID) se da de alta en su ficha
3. El empleado acerca su tarjeta al lector (sin tocar)
4. El fichaje se registra y el terminal muestra el resultado

<!-- ![Fichaje RFID](/assets/images/placeholder-fichaje-rfid.png) -->

### Ventajas

✅ **Rapidísimo**: 1 segundo
✅ **Sin contacto**: Solo acercar la tarjeta
✅ Muy profesional y moderno
✅ No requiere batería ni carga (tarjetas pasivas)
✅ Duradero (tarjetas duran años)
✅ Puede integrarse con control de acceso (puertas)

### Desventajas

❌ **Requiere hardware**: Lector RFID y terminal (coste adicional)
❌ Requiere tarjetas/llaveros para cada empleado
❌ Si pierdes la tarjeta, no puedes fichar hasta tener otra
❌ Instalación inicial más compleja

### Ideal para

- **Oficinas grandes** (50+ empleados)
- **Hoteles** y resorts
- **Hospitales** y centros médicos
- **Edificios corporativos**
- Empresas que quieren control de acceso integrado

### Tipos de tarjetas RFID

| Tipo | Formato | Uso |
|------|---------|-----|
| **Tarjeta** | Tamaño tarjeta crédito | Llevar en cartera |
| **Llavero** | Llavero pequeño | Llevar con llaves |
| **Pulsera** | Pulsera silicona | Hospitales, eventos |
| **Pegatina** | Adhesivo redondo | Pegar en móvil, casco |

### Adquirir sistema RFID

{: .note }
> **Contacta con soporte**: Para instalar sistema RFID, contacta con soporte@ahoraficho.es. Te asesoraremos sobre el hardware compatible y la configuración.

---

## 5. 📷 Fichaje QR (Próximamente)

El fichaje escaneando un código QR desde la app móvil estará disponible próximamente.

{: .note }
> **No confundir**: El código QR actual de la plataforma sirve para **configurar y acceder a la app móvil** (se genera desde el menú **"Descargar APP"**), no para fichar. Ver [Descarga App Móvil](/primeros-pasos/descarga-app-movil/).

---

## Comparativa técnica

### Requisitos de cada método

| Método | Hardware | Software | Internet | Coste adicional |
|--------|----------|----------|----------|-----------------|
| **Web** | Ordenador/móvil | Navegador | ✅ Sí | No |
| **App Móvil** | Smartphone | App instalada | ✅ Sí | No |
| **PIN** | Terminal compartido | Navegador (modo kiosco) | ✅ Sí | Dispositivo terminal |
| **RFID** | Lector RFID + terminal | — | ✅ Sí | Lector + tarjetas |

### Velocidad de fichaje

1. **RFID**: 1 segundo ⚡⚡⚡⚡⚡
2. **PIN**: 3 segundos ⚡⚡⚡⚡
3. **App Móvil**: 5 segundos ⚡⚡⚡⚡
4. **Web**: 10 segundos ⚡⚡⭐

---

## Combinar varios métodos

Las empresas pueden habilitar **múltiples métodos** simultáneamente, incluso distintos métodos para cada trabajador:

**Ejemplo: Oficina + Teletrabajo**
- Empleados en oficina: PIN en terminal (rápido)
- Empleados en remoto: App móvil (con GPS)

**Ejemplo: Fábrica con turnos**
- Operarios: PIN en terminal en entrada
- Supervisores: App móvil para moverse por planta
- Oficinistas: Web desde sus ordenadores

{: .tip }
> **Flexibilidad**: Cada empleado puede usar cualquiera de los métodos que tenga habilitados según donde esté trabajando ese día.

---

## Habilitar métodos por trabajador

**Para Administradores:**

Los métodos se habilitan **por empleado**, no globalmente:

- En el **alta de trabajador** (sección **"Métodos de Fichaje Permitidos"**): Fichaje Web y Fichaje Móvil vienen activados por defecto; Fichaje PIN y Fichaje RFID se activan introduciendo el PIN de 6 dígitos o el Tag RFID.
- En la **edición del trabajador** (Configuraciones → Trabajadores → Editar): se pueden activar o desactivar los métodos en cualquier momento.

👉 [Ver guía: Dar de Alta Empleados](/guias-por-rol/administrador/dar-alta-empleados/)

---

## Preguntas frecuentes

### ¿Puedo usar diferentes métodos en diferentes días?

Sí, puedes fichar con cualquier método que tengas habilitado.

### ¿Qué método es más seguro?

Todos son seguros. RFID es más difícil de suplantar que el PIN (que alguien podría ver al marcarlo).

### ¿El PIN puede repetirse entre empleados?

No, cada trabajador tiene su propio PIN de 6 dígitos.

### ¿Puedo cambiar mi PIN?

No desde la aplicación. Solicita a tu Administrador que te asigne un PIN nuevo.

### ¿Qué pasa si pierdo mi tarjeta RFID?

Informa inmediatamente a tu Administrador para que te asigne un nuevo Tag RFID.

### ¿Necesito internet para fichar?

Sí, todos los métodos requieren conexión a internet en el momento del fichaje.

---

## ¿Necesitas ayuda?

Si tienes dudas sobre los métodos de fichaje:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Primer Fichaje](/primeros-pasos/primer-fichaje/)
- 👉 [Descarga App Móvil](/primeros-pasos/descarga-app-movil/)
- 👉 [Gestión de Edificios](/guias-por-rol/administrador/gestion-edificios/)
- 👉 [Módulo de Fichajes](/modulos/fichajes/)
