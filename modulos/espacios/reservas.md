---
layout: default
title: Reservar espacios
parent: Espacios
nav_order: 1
permalink: /modulos/espacios/reservas/
---

# Reservar espacios
{: .no_toc }

Guía para empleados: consultar la disponibilidad, crear una reserva, hacer check-in, liberar antes de tiempo y gestionar tus reservas.
{: .fs-6 .fw-300 }

---

## Acceder

Entra en **Mi Trabajo → Espacios**. Verás la pantalla principal con los accesos:

| Acceso | Qué hace |
|:-------|:---------|
| **Calendario y búsqueda** | Calendario de recursos con buscador de disponibilidad |
| **Mis reservas** | Tus reservas, invitaciones y solicitudes pendientes |

Si eres responsable de algún recurso, también verás el número de solicitudes pendientes de aprobar junto a **Mis reservas**.

---

## El calendario: día, semana y mes

En la pestaña **Calendario** puedes cambiar el modo de vista con los botones **Día**, **Semana** y **Mes**:

- **Día**: rejilla horizontal con los recursos en filas y las horas en columnas. La franja roja marca la hora actual. Pulsar sobre una franja libre crea una reserva en ese hueco.
- **Semana**: cada recurso en una fila y los siete días en columnas, con un recuadro por reserva. Pulsa sobre un día para abrirlo en detalle.
- **Mes**: rejilla mensual con los días del mes; cada día muestra hasta tres reservas y un contador si hay más. Pulsa sobre un día para abrirlo en detalle.

Los colores de los recuadros:

| Color | Significado |
|:------|:------------|
| Azul | Reserva confirmada |
| Naranja | Reserva pendiente de aprobación |
| Gris | Recurso bloqueado o en mantenimiento |

{: .tip }
> Usa los filtros de **Categoría** y **Centro** de la barra superior para acotar los recursos visibles. La vista se actualiza sola cada 30 segundos.

---

## Buscar disponibilidad

En la pestaña **Buscar disponibilidad** indica fecha, hora de inicio y fin (y opcionalmente aforo mínimo, categoría o centro). El buscador muestra los recursos libres en ese intervalo con sus características y un botón **Reservar aquí**.

---

## Crear una reserva

1. Pulsa **Nueva reserva** (o una franja libre del calendario o **Reservar aquí** en el buscador).
2. Paso 1 — **Elige cuándo**: fecha, hora de inicio y duración.
3. Paso 2 — **Elige recurso**: los recursos disponibles en ese hueco. Los no disponibles aparecen atenuados.
4. Paso 3 — **Datos de la reserva**: titular (tú o, si tienes permiso, otra persona), título, motivo, asistentes internos e invitados externos (email por línea con el formato `Nombre <email>`).

{: .note }
> Algunos recursos exigen completar el **título**, el **motivo**, los **asistentes** o la **descripción** según su configuración. Los campos marcados con \* son obligatorios.

5. Pulsa **Confirmar reserva**:
   - Si el recurso tiene **confirmación automática**, queda confirmada al instante.
   - Si tiene **aprobación manual**, queda **pendiente** hasta que un responsable la apruebe o rechace.

### Series repetitivas

Activa **Repetir serie** para crear la misma reserva en varios días (semanal, quincenal, diaria o mensual) hasta una fecha o un número máximo de repeticiones. Verás una previsualización de las ocurrencias antes de crear; los conflictos se marcan. Después puedes **cancelar toda la serie** de una vez desde Mis reservas.

---

## Mis reservas

En **Mis reservas** tienes tres pestañas de filtro: **Próximas**, **Pasadas** y **Todas**. Cada reserva muestra estado, recurso, fecha y acciones:

| Acción | Cuándo aparece |
|:-------|:---------------|
| **Check-in** (✓ verde) | Si el recurso exige confirmar asistencia y estás dentro de la ventana de check-in |
| **Liberar** (salida ámbar) | Cuando la reserva ya ha empezado: terminas antes y el recurso queda libre |
| **Descargar ICS** | Siempre, incluso en canceladas (el archivo retira el evento de tu calendario) |
| **Cancelar** (papelera) | En reservas activas; si el recurso lo exige, se pide un motivo |

Estados de una reserva: **Pendiente** → **Confirmada** → **En curso** → **Completada**. Si no haces check-in dentro del margen, la reserva pasa a **No presentada**. La pantalla se actualiza sola cada minuto.

### Invitaciones

Si te invitan a una reserva, verás la tarjeta de invitación con botones para **aceptar** o **rechazar**. Las personas externas reciben un email con un enlace público equivalente y el archivo de calendario.

### Solicitudes pendientes de aprobar

Los responsables de un recurso ven en esta misma pantalla las solicitudes pendientes con botones **Aprobar** y **Rechazar** (con motivo opcional). También llegan notificaciones push/email por cada solicitud.

---

## Reservar desde el terminal de puerta

En una tablet colocada a la entrada (terminal de Espacios), los empleados pueden ver la ocupación del recurso y reservar o hacer check-in con su **PIN**:

- El terminal muestra el estado: **Disponible**, **Ocupada**, **Reserva pendiente**, **Mantenimiento**, **Bloqueada** o **Fuera de horario**.
- **Reserva rápida por PIN** para recursos que no exigen título ni motivo; para el resto, usa la web.
- El check-in y la liberación por PIN funcionan igual que en la web.

{: .important }
> El terminal necesita conexión a internet para funcionar. Tras varios intentos de PIN incorrectos, el terminal se bloquea unos minutos por seguridad.

---

## Preguntas frecuentes

**¿Puedo reservar en nombre de otra persona?**
Solo si eres responsable o administrador: en el paso 3 aparecerá el desplegable de titular.

**¿Por qué mi reserva sigue "pendiente"?**
El recurso tiene aprobación manual. Un responsable debe aceptarla; recibirás una notificación cuando ocurra.

**¿Puedo modificar una reserva creada?**
Puedes cancelarla y crear una nueva. Las series completas se cancelan de una vez desde Mis reservas.
