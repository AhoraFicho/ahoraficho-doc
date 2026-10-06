---
layout: default
title: Sincronización con Google Calendar
parent: Vacaciones y Ausencias
nav_order: 3
---

# Sincronización de vacaciones con Google Calendar
{: .no_toc }

AhoraFicho puede volcar automáticamente las **vacaciones aprobadas** en un calendario de **Google Calendar** llamado "Vacaciones", para que tu equipo consulte las vacaciones de todos desde Google, sin entrar en la plataforma.

---

## ¿Cómo funciona?

- La sincronización es **unidireccional**: de AhoraFicho hacia Google Calendar. Los cambios hechos en Google no afectan a la plataforma.
- Se sincronizan únicamente las vacaciones con estado **Aceptada**. Las solicitudes pendientes o rechazadas no aparecen en Google.
- Se incluye una ventana de fechas amplia: desde **30 días atrás** hasta unos **13 meses hacia adelante** desde hoy.
- Los días completos consecutivos se agrupan en **un único evento** de varios días. Las medias jornadas se crean como eventos individuales con el título "Vacaciones Nombre (mañana)" o "Vacaciones Nombre (tarde)".
- La sincronización se ejecuta **automáticamente cada noche** y también puedes lanzarla manualmente cuando quieras.

{: .note }
> Si una vacación se cancela o deja de estar aprobada, el evento correspondiente se **elimina automáticamente** de Google Calendar en la siguiente sincronización.

---

## Conectar Google Calendar

1. Entra en **"Empresa" → "Calendario de la empresa"**.
2. Localiza la tarjeta **"Sincronización de vacaciones con Google Calendar"**.
3. Pulsa **"Conectar con Google"** e inicia sesión con la cuenta de Google de tu empresa.
4. Autoriza los permisos solicitados. La plataforma buscará (o creará si no existe) un calendario llamado **"Vacaciones"** en esa cuenta.

Una vez conectada, la tarjeta muestra el estado de la conexión: cuenta conectada, calendario de destino, fecha de la última sincronización y resultado.

### Botones disponibles

| Botón | Acción |
|-------|--------|
| **"Conectar con Google"** | Inicia la autorización con la cuenta de Google |
| **"Sincronizar ahora"** | Lanza una sincronización inmediata (creados, actualizados y eliminados) |
| **"Desconectar"** | Revoca el acceso y elimina la conexión; los eventos ya creados permanecen en Google |

---

## ¿Qué vacaciones se envían?

La plataforma admite dos modos de funcionamiento, configurado por el proveedor en cada despliegue:

- **Calendario único (predeterminado)**: un solo calendario de Google conectado recibe las vacaciones aprobadas de **todas las empresas** de la plataforma. Es el modo adecuado cuando una única cuenta de Google centraliza las vacaciones.
- **Por empresa**: cada empresa conecta su propia cuenta de Google y su calendario recibe únicamente las vacaciones de sus propios trabajadores.

{: .important }
> En el modo de calendario único solo es necesaria **una conexión**. Si conectas varias empresas, la sincronización automática nocturna utiliza la primera conexión activa, cuyo calendario recibe todas las vacaciones.

---

## Preguntas frecuentes

### ¿Los empleados aparecen con su nombre en los eventos?

Sí. Cada evento se titula "Vacaciones" seguido del nombre completo del trabajador, con el sufijo "(mañana)" o "(tarde)" en el caso de medias jornadas.

### ¿Se envían otros tipos de ausencias (bajas, permisos)?

No. Solo se sincronizan las vacaciones aprobadas.

### ¿Puedo editar los eventos en Google?

Puedes hacerlo, pero no es recomendable: en la siguiente sincronización la plataforma restaurará el evento según el estado real de las vacaciones.

### ¿Qué pasa si la autorización de Google caduca?

La tarjeta de estado lo indicará y será necesario pulsar de nuevo **"Conectar con Google"** para volver a autorizar la cuenta.

### ¿Necesitas ayuda?

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Vacaciones y Ausencias](/modulos/vacaciones/)
- 👉 [Gestionar Solicitudes](/modulos/vacaciones/gestionar-solicitudes/)
- 👉 [Aprobar Vacaciones (Manager)](/guias-por-rol/manager/aprobar-vacaciones/)
