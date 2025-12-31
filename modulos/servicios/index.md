---
# layout: default
# title: Servicios
# nav_order: 11
# has_children: true
# permalink: /modulos/servicios/
---

# Módulo de Servicios
{: .no_toc }

Gestiona servicios programados de limpieza, mantenimiento o cualquier servicio recurrente. Programa, asigna y registra el cumplimiento de cada servicio.
{: .fs-6 .fw-300 }

{: .note }
> **Módulo opcional**: Solo disponible si tu empresa tiene el módulo de **Servicios** activado. Ideal para empresas de limpieza, mantenimiento, seguridad, etc.

---

## ¿Qué es el módulo de Servicios?

Permite programar servicios recurrentes (diarios, semanales, mensuales) en diferentes ubicaciones y registrar su cumplimiento.

### Funcionalidades

- 📅 **Programación**: Crear calendarios de servicios
- 📍 **Ubicaciones**: Múltiples clientes/edificios
- 👷 **Asignación**: Qué empleado hace qué servicio
- ✅ **Registro**: Marcar servicio como completado
- 📊 **Reportes**: Cumplimiento y control de calidad

---

## Ejemplo de uso: Empresa de limpieza

**Cliente**: Oficinas ABC
**Servicios contratados:**
- Limpieza diaria (lunes a viernes)
- Limpieza profunda (último viernes del mes)
- Cristales (1 vez al mes)

**Programación en AhoraFicho:**
1. Creas el cliente "Oficinas ABC"
2. Creas los 3 tipos de servicio
3. Asignas empleados a cada servicio
4. El sistema genera el calendario automáticamente

---

## Tipos de servicios

### Por frecuencia
- **Diario**: Lunes a viernes, o 7 días/semana
- **Semanal**: Cada lunes, cada martes, etc.
- **Quincenal**: Cada 15 días
- **Mensual**: Día específico del mes
- **Anual**: Servicios puntuales

### Por tipo
- Limpieza general
- Limpieza profunda
- Mantenimiento preventivo
- Mantenimiento correctivo
- Revisiones
- Inspecciones

---

## Programar un servicio

**Como Administrador:**

1. Ve a **"Servicios"** → **"Nuevo servicio"**
2. Completa:
   - **Cliente**: Oficinas ABC
   - **Ubicación**: Planta 3
   - **Tipo**: Limpieza diaria
   - **Frecuencia**: Lunes a Viernes
   - **Horario**: 19:00 - 21:00
   - **Empleado asignado**: María García
3. Guarda y el calendario se genera automáticamente

---

## Registrar cumplimiento

**Como Empleado:**

1. Ve a **"Mis Servicios"**
2. Verás los servicios asignados para hoy
3. Al llegar al cliente, ficha entrada
4. Al terminar, ficha salida
5. Marca el servicio como **"Completado"**
6. (Opcional) Añade fotos del resultado
7. (Opcional) Añade observaciones

**Estados:**
- 🟡 **Pendiente**: Aún no realizado
- 🟢 **Completado**: Realizado correctamente
- 🔴 **Incidencia**: Hubo algún problema
- ⚫ **Cancelado**: Cliente canceló

---

## Incidencias en servicios

Si hay un problema:
1. Marca el servicio con **"Incidencia"**
2. Describe qué pasó:
   - Cliente no estaba
   - Falta de material
   - Área inaccesible
   - Otros
3. Sube fotos si es relevante
4. El Manager recibe notificación

---

## Control de calidad

### Inspecciones aleatorias

Los Managers pueden:
- Marcar servicios para inspección
- Acudir in situ a verificar
- Calificar el servicio (1-5 estrellas)
- Dar feedback al empleado

### Quejas de clientes

Si un cliente se queja:
1. Registra la queja en el servicio
2. Investiga qué pasó
3. Toma medidas correctivas
4. Comunica solución al cliente

---

## Reportes de servicios

### Para clientes

Genera informes mensuales:
- Servicios realizados
- Fechas y horarios
- Empleados que los realizaron
- Fotos (si aplica)
- Incidencias registradas

**Uso**: Enviar al cliente como justificante del servicio

### Internos

- **Cumplimiento**: % de servicios completados
- **Productividad**: Servicios por empleado
- **Incidencias**: Frecuencia de problemas
- **Calidad**: Puntuación media

---

## Facturación por servicios

Si facturas por servicio realizado:

1. Marca los servicios facturables
2. Al final de mes, exporta servicios completados
3. Genera factura basada en:
   - Número de servicios
   - Horas trabajadas
   - Tarifa acordada

---

## Notificaciones

### Para empleados
- 📧 Recordatorio 1 día antes del servicio
- 📧 Recordatorio 1 hora antes
- 📧 Alerta si no se ha marcado como completado

### Para Managers
- 📧 Servicios no realizados
- 📧 Incidencias registradas
- 📧 Quejas de clientes

---

## Casos de uso

### Empresa de limpieza
- Programar limpiezas en múltiples oficinas
- Asignar equipos a cada edificio
- Registrar cumplimiento diario
- Reportar al cliente mensualmente

### Empresa de mantenimiento
- Mantenimiento preventivo de ascensores
- Mantenimiento de calderas
- Inspecciones de seguridad
- Revisiones periódicas

### Empresa de seguridad
- Rondas de vigilancia
- Inspecciones de cámaras
- Control de accesos
- Verificación de alarmas

---

## Guías relacionadas

- 👉 [Gestión de Edificios](/guias-por-rol/administrador/gestion-edificios/)
- 👉 [Módulo de Fichajes](/modulos/fichajes/)
