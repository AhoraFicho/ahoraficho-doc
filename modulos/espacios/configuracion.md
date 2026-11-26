---
layout: default
title: Configurar Espacios
parent: Espacios
nav_order: 2
permalink: /modulos/espacios/configuracion/
---

# Configurar Espacios (administrador)
{: .no_toc }

Guía para administradores: activar y configurar el módulo de Espacios, desde las categorías hasta los recursos, terminales y estadísticas.
{: .fs-6 .fw-300 }

---

## Dónde está todo

Con el módulo activado, en el menú lateral encontrarás:

- **Mi Trabajo → Espacios**: la pantalla de acceso para todos los usuarios.
- **Configuraciones → Espacios**: la administración del módulo, con los grupos:

| Grupo | Contenido |
|:------|:----------|
| **Espacios y reservas** | Panel de espacios · Recursos · Categorías · Características · Campos personalizados |
| (resto de Configuraciones) | Organización · Planificación · Seguridad y accesos · Mantenimiento |

Al abrir una pantalla del módulo, su submenú se despliega solo.

---

## Categorías

**Configuraciones → Espacios → Categorías**: agrupan recursos (Salas de reuniones, Escritorios, Vehículos...). Cada categoría tiene nombre, icono, color y orden. Sirven para filtrar el calendario y para limitar el ámbito de características y campos personalizados.

## Características

**Configuraciones → Espacios → Características**: catálogo de equipamiento (pantalla, videoconferencia, pizarra...). Puedes limitar cada característica a determinadas categorías. Se asignan por recurso con cantidad y detalle.

## Campos personalizados

**Configuraciones → Espacios → Campos personalizados**: campos adicionales que completas en la ficha de cada recurso y que se muestran en las tarjetas de reserva.

- **Nombre** y **categoría** (si eliges una, el campo solo aplica a sus recursos; si no, a todos).
- **Tipo**: texto, número, sí/no, desplegable o multiselección. Los tipos desplegable y multiselección exigen al menos dos **opciones** (una por línea o separadas por comas).
- **Obligatorio**: al completar la ficha del recurso.

Después, en la ficha de cada recurso (**Recursos → Editar → pestaña Campos**), completa los valores: aparecerán en las tarjetas del buscador y del asistente de reserva.

{: .note }
> Al eliminar un campo personalizado se borran también sus valores en todos los recursos.

## Recursos

**Configuraciones → Espacios → Recursos**: cada recurso es una sala, escritorio o elemento reservable. La ficha se organiza en pestañas:

| Pestaña | Contenido |
|:--------|:----------|
| **General** | Nombre, código, categoría, centro, ubicación, planta, aforo, color, icono, instrucciones |
| **Horario** | Franjas semanales en las que se puede reservar y excepciones puntuales (cerrado, horario especial, mantenimiento) |
| **Equipamiento** | Características asignadas con cantidad |
| **Acceso** | Quiénes pueden **ver** y **reservar** (departamentos, empleados, centros) y quién **aprueba** |
| **Políticas** | Duraciones mínima/máxima/por defecto, tramos de reserva, confirmación automática o manual, privacidad (detalle completo, título y hora, solo ocupación), exigir título/motivo/asistentes/descripción, check-in con su ventana, cancelación con motivo |
| **Fotos** | Imágenes del recurso, con foto principal |
| **Campos** | Valores de los campos personalizados aplicables |

La pestaña **Acceso** es la que determina la privacidad: si eliges "solo ocupación", el resto de empleados verá las franjas ocupadas sin título ni organizador.

{: .important }
> La confirmación **manual** requiere que alguien figure como **aprobador** en la pestaña Acceso; si no hay aprobadores, las reservas quedarán pendientes sin nadie que pueda aprobarlas.

## Terminales

**Configuraciones → Dispositivos**: cada tablet de puerta se registra como dispositivo con **modo Espacios** (única o multi-recurso) y los recursos asignados. El terminal se abre con un token y muestra la ocupación en tiempo real, reserva rápida y check-in/liberación por PIN de empleado.

- **App AhoraFicho (Android o iOS):** en el listado de dispositivos, abre el **Código QR - Registro de dispositivo** (icono de QR). En la app, entra en modo terminal y escanéalo con el mismo botón que usas para un terminal de fichaje. La app abre Espacios según el modo del dispositivo y conserva la dirección del terminal registrado. Si ya está registrado, no hace falta volver a escanear el QR de la app.
- **Navegador:** abre la dirección del terminal con los tokens del dispositivo: `/accessentry/terminal/{KeyToken}?secToken={SecurityToken}`.

La cabecera del terminal de Espacios muestra el logotipo principal de la aplicación a la izquierda y la hora y la fecha a la derecha.

## Panel de espacios

**Configuraciones → Espacios → Panel de espacios**: estadísticas del periodo que elijas:

- KPIs: recursos activos, reservas de hoy, próximos 7 días, reservas del periodo, no presentadas y cancelaciones.
- Horas reservadas, utilización confirmada (con check-in) y ocupación sobre las horas abiertas.
- Reservas por día y ocupación por recurso.
- **Exportación a Excel** del informe de reservas.

## Datos de ejemplo

Para probar el módulo en una empresa recién creada, el equipo de AhoraFicho puede activar la semilla de datos demo: crea categorías, características, recursos de ejemplo y algunas reservas. Solo se crea si la empresa no tiene todavía ningún recurso.

---

## Guías relacionadas

- [Reservar espacios (empleado)](/modulos/espacios/reservas/)
- [Módulos](/modulos/)
