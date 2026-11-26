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

- **Día**: rejilla horizontal con los recursos en filas y las horas en columnas. La franja roja marca la hora actual. En el ordenador, arrastra sobre una franja libre para crear la reserva con ese horario; en el móvil, toca el hueco deseado y elige la duración entre las propuestas. Los nombres de las salas quedan fijos a la izquierda mientras te desplazas por las horas.
- **Semana**: en ordenador y tablet, cada recurso en una fila y los siete días en columnas, con un recuadro por reserva. En el móvil se muestra como una lista compacta por día con sus reservas. En ambos casos, pulsa sobre un día para abrirlo en detalle.
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
4. Paso 3 — **Datos de la reserva**: título y **número de asistentes**, asistentes internos e invitados externos (correos separados por `;`).
   La reserva se crea siempre a tu nombre.

{: .note }
> Algunos recursos exigen completar el **título**, el **motivo**, los **asistentes** o la **descripción** según su configuración. Motivo y descripción solo aparecen cuando el recurso los exige, y los campos marcados con \* son obligatorios.

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

- La pantalla se divide en dos zonas: a la izquierda, el estado grande de la sala con sus acciones; a la derecha, **"Reservas de hoy"**, la agenda del día **siempre visible** con todas las reservas del recurso.
- El estado grande puede ser: **Disponible**, **Ocupado**, **Reserva pendiente**, **Mantenimiento**, **Bloqueada** o **Fuera de horario**, y el color de la banda superior acompaña al estado en todo momento.
- En la agenda, la reserva activa aparece destacada con la etiqueta **En curso**, las solicitudes pendientes con **Pendiente** y las pasadas quedan atenuadas. La agenda se actualiza sola.
- Para reservar, pulsa **Reservar ahora** e introduce tu **PIN**. Elige una hora de inicio y después una de las duraciones disponibles para esa hora, con el intervalo exacto que se creará. Comprueba el intervalo y pulsa **Confirmar reserva**. El terminal muestra el resultado y vuelve a la pantalla principal.
- Elige **Ahora** para empezar al confirmar, si el recurso permite reservar sin antelación y queda un hueco suficiente. Los inicios programados siguen las franjas del recurso.
- Si el recurso exige confirmar utilización, el botón **Confirmar utilización** aparece solo dentro de la ventana configurada en la sala (desde unos minutos antes del inicio hasta unos minutos después) y desaparece al confirmar o al cerrarse la ventana.
- Si la sala está ocupada, **Liberar sala** termina antes la reserva activa con el PIN del organizador y deja la sala libre.
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
