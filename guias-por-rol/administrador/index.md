---
layout: default
title: Administrador
parent: Guías por Rol
nav_order: 3
has_children: true
permalink: /guias-por-rol/administrador/
---

# Guía del Administrador
{: .no_toc }

Documentación completa para administradores de AhoraFicho. Gestión de usuarios, configuración y reportes.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué puedes hacer como Administrador?

Como administrador de AhoraFicho, tienes acceso completo a la gestión de tu empresa:

### 👥 Gestión de Empleados
- Dar de alta nuevos trabajadores
- Editar información de empleados
- Activar y desactivar usuarios
- Asignar roles y permisos
- Gestionar departamentos

### ⏰ Gestión de Horarios
- Crear horarios personalizados
- Asignar horarios a empleados
- Configurar flexibilidad horaria
- Gestionar turnos rotativos
- Historial de cambios de horario

### 🌴 Gestión de Vacaciones
- Asignar días de vacaciones anuales
- Configurar fechas de caducidad
- Aprobar o rechazar solicitudes
- Crear ausencias para empleados
- Gestionar tipos de ausencias

### 🏢 Configuración de la Empresa
- Gestionar edificios y centros de trabajo
- Configurar días festivos
- Configurar departamentos
- Gestionar dispositivos de fichaje
- Configurar notificaciones

### 📊 Reportes e Inspecciones
- Generar informe para inspección de trabajo
- Reportes mensuales por empleado
- Informes de impuntualidad
- Exportación de datos
- Estadísticas de la empresa

### ⚙️ Configuración Avanzada
- Tipos de ausencias personalizados
- Tipos de gastos
- Proyectos e imputaciones
- Alias de IPs
- Roles y permisos

---

## Accesos rápidos

### 🚀 Tareas más frecuentes

<div class="code-example" markdown="1">

#### [Dar de Alta Empleados](/guias-por-rol/administrador/dar-alta-empleados/)
Proceso completo para registrar nuevos trabajadores en el sistema.

#### [Desactivar Usuarios](/guias-por-rol/administrador/desactivar-usuarios/)
Cómo desactivar temporalmente o definitivamente un empleado.

#### [Crear Horarios](/guias-por-rol/administrador/crear-horarios/)
Configurar horarios de trabajo personalizados.

#### [Asignar Horarios](/guias-por-rol/administrador/asignar-horarios/)
Asignar horarios a empleados individual o masivamente.

#### [Configurar Turnos Rotativos](/guias-por-rol/administrador/configurar-turnos-rotativos/)
Gestionar turnos para trabajadores con horarios cambiantes.

#### [Asignar Vacaciones](/guias-por-rol/administrador/asignar-vacaciones/)
Configurar días de vacaciones anuales para empleados.

#### [Gestión de Departamentos](/guias-por-rol/administrador/gestion-departamentos/)
Crear y gestionar la estructura departamental.

#### [Gestión de Edificios](/guias-por-rol/administrador/gestion-edificios/)
Configurar centros de trabajo y geolocalización.

#### [Días Festivos](/guias-por-rol/administrador/dias-festivos/)
Configurar el calendario de festivos de la empresa.

</div>

---

## Responsabilidades del Administrador

### Configuración inicial
- ✅ Estructura de departamentos
- ✅ Centros de trabajo/edificios
- ✅ Horarios base
- ✅ Calendario de festivos
- ✅ Tipos de ausencias

### Gestión diaria
- ✅ Validar solicitudes de cambios de fichaje
- ✅ Aprobar/rechazar ausencias
- ✅ Resolver incidencias de empleados
- ✅ Monitorizar fichajes

### Gestión mensual
- ✅ Revisar reportes mensuales
- ✅ Generar informes para nómina
- ✅ Actualizar días de vacaciones
- ✅ Revisar impuntualidades

### Auditorías e inspecciones
- ✅ Mantener registros actualizados
- ✅ Generar informes oficiales
- ✅ Garantizar cumplimiento normativo (RD 8/2019)
- ✅ Preparar documentación para inspecciones

---

## Estructura del menú de Administrador

Como administrador, verás estas secciones adicionales:

### ⚙️ Configuraciones

```
Configuraciones
├── Trabajadores
├── Departamentos  
├── Edificios
├── Departamento Edificios
├── Horarios
├── Días festivos
├── Proyectos (si módulo activo)
├── ─────────────────
├── Notificaciones
├── Dispositivos
├── Alias de IP
├── Tipos de Ausencias
├── Tipos de Gastos (si módulo activo)
├── Tipos de Servicios (si módulo activo)
├── Categorías de Documentos (si módulo activo)
└── Roles
```

### 🏢 Empresa

```
Empresa
├── Calendarios (ausencias, gastos, imputaciones)
├── Gestión de Fichajes
├── Gestión de Ausencias
├── Gestión de Gastos
├── Gestión de Imputaciones
├── Gestión de Turnos
├── Gestión de Servicios
└── Gestión de Documentos
```

### ✅ Validaciones

```
Validaciones
├── Cambios de Fichajes
├── Ausencias Pendientes
├── Gastos Pendientes
└── Imputaciones Pendientes
```

### 📊 Reportes

```
Reportes
├── Resumen Diario Departamento
├── Resumen Semanal Departamento
├── Reporte Mensual
├── Impuntualidades
├── Resumen Ausencias
├── Resumen por Proyectos
└── Reporte de Servicios
```

---

## Mejores prácticas

### ✅ Recomendaciones

**Configuración inicial:**
- Planifica bien la estructura de departamentos antes de empezar
- Importa empleados en lote si tienes muchos
- Configura horarios estándar primero
- Establece festivos del año completo

**Gestión diaria:**
- Revisa validaciones pendientes diariamente
- Responde rápido a solicitudes de empleados
- Mantén actualizada la información de empleados
- Documenta cambios importantes

**Seguridad:**
- No compartas credenciales de administrador
- Revisa regularmente usuarios activos
- Desactiva empleados que ya no trabajan
- Audita cambios importantes

### ❌ Evita

- Crear usuarios sin departamento asignado
- Modificar horarios sin avisar al empleado
- Rechazar solicitudes sin justificación
- Activar/desactivar usuarios aleatoriamente
- Borrar datos históricos (mejor desactivar)

---

## Delegación de tareas

### Manager vs Administrador

Puedes delegar algunas tareas a Managers:

| Tarea | Manager | Admin |
|:------|:--------|:------|
| Aprobar ausencias de su equipo | ✅ | ✅ |
| Aprobar cambios de fichaje | ✅ | ✅ |
| Ver reportes de su equipo | ✅ | ✅ |
| Dar de alta empleados | ❌ | ✅ |
| Modificar horarios | ❌ | ✅ |
| Configurar empresa | ❌ | ✅ |
| Gestionar departamentos | ❌ | ✅ |

{: .tip }
> **Consejo**: Asigna Managers a departamentos para distribuir la carga de validaciones.

---

## Cumplimiento normativo (RD 8/2019)

Como administrador, eres responsable de garantizar:

### ✅ Obligaciones legales

1. **Registro diario de jornada**
   - Todos los empleados deben fichar entrada y salida
   - Registros deben ser fiables, inalterables y accesibles

2. **Conservación de registros**
   - Mínimo 4 años
   - Disponibles para Inspección de Trabajo

3. **Información a representantes**
   - Entregar resúmenes mensuales si lo solicitan
   - Formato comprensible y accesible

4. **Documentación para inspecciones**
   - Tener informes listos para auditorías
   - Ver guía: [Informe para Inspección](/reportes/informe-inspeccion-trabajo/)

---

## Soporte y recursos

### 📚 Documentación relacionada

- [Dar de alta empleados](/guias-por-rol/administrador/dar-alta-empleados/)
- [Crear y asignar horarios](/guias-por-rol/administrador/crear-horarios/)
- [Configurar turnos rotativos](/guias-por-rol/administrador/configurar-turnos-rotativos/)
- [Informe para inspección](/reportes/informe-inspeccion-trabajo/)

### 🆘 ¿Necesitas ayuda?

- 📧 Email soporte: soporte@ahoraficho.es
- 💬 Consulta las [Preguntas Frecuentes](/preguntas-frecuentes/)
- 📞 Soporte telefónico (horario comercial)
- 🎓 Formación personalizada disponible

---

## Formación continua

### Recursos disponibles

- 📖 Esta documentación completa
- 🎥 Videotutoriales (próximamente)
- 👨‍🏫 Sesiones de formación personalizadas
- 📧 Newsletter con novedades y tips

### Actualizaciones del sistema

Mantente informado de:
- Nuevas funcionalidades
- Cambios en la normativa
- Mejoras del sistema
- Casos de uso y mejores prácticas

---

{: .important }
> **Recuerda**: Como administrador, eres el responsable de garantizar el correcto funcionamiento del sistema de control horario en tu empresa y del cumplimiento de la normativa vigente.