---
layout: default
title: Días Festivos
parent: Guía del Administrador
grand_parent: Guías por Rol
nav_order: 9
---

# Días Festivos
{: .no_toc }

Aprende a configurar el calendario de días festivos de tu empresa, diferenciando festivos nacionales, autonómicos y locales según cada centro de trabajo.
{: .fs-6 .fw-300 }

---

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## ¿Qué son los días festivos en AhoraFicho?

Los días festivos son jornadas no laborables que afectan al cálculo de horarios, vacaciones y reportes. AhoraFicho te permite configurar:

- ✅ Festivos nacionales (comunes a toda España)
- ✅ Festivos autonómicos (según Comunidad Autónoma)
- ✅ Festivos locales (por municipio o provincia)
- ✅ Festivos específicos por edificio/centro de trabajo
- ✅ Festivos personalizados de empresa

{: .important }
> **Impacto en el sistema**: Los días festivos **no se descuentan** del saldo de vacaciones cuando un empleado solicita un período que incluye festivos. Además, afectan al cálculo de horas laborables en los reportes.

---

## Configurar días festivos

### Paso 1: Acceder a la gestión de festivos

1. Inicia sesión como **Administrador**
2. Ve al menú lateral y haz clic en **"Configuraciones"**
3. Selecciona **"Días Festivos"**
4. Verás el calendario anual con los festivos configurados

![Acceso a días festivos](/assets/images/placeholder-festivos-menu.png)

### Paso 2: Añadir un nuevo festivo

1. Haz clic en el botón **"Nuevo Festivo"**
2. Completa el formulario con los siguientes datos:

| Campo | Descripción | Ejemplo |
|-------|-------------|---------|
| **Fecha** | Día del festivo | 01/01/2024 |
| **Nombre** | Descripción del festivo | Año Nuevo |
| **Tipo** | Nacional / Autonómico / Local / Empresa | Nacional |
| **Edificio** | Centro de trabajo (si aplica) | Oficina Madrid |
| **Recurrente** | Se repite cada año | ✅ Sí |

![Formulario nuevo festivo](/assets/images/placeholder-crear-festivo.png)

### Paso 3: Guardar el festivo

1. Revisa que todos los datos sean correctos
2. Haz clic en **"Guardar"**
3. El festivo aparecerá marcado en el calendario

{: .tip }
> **Festivos recurrentes**: Marca esta opción para festivos que se repiten cada año (Navidad, Año Nuevo, etc.). Así no tendrás que crearlos manualmente cada año.

---

## Tipos de festivos

### Festivos Nacionales

Son comunes a toda España. Algunos ejemplos:

- 1 de enero: Año Nuevo
- 6 de enero: Epifanía del Señor
- 1 de mayo: Fiesta del Trabajo
- 15 de agosto: Asunción de la Virgen
- 12 de octubre: Fiesta Nacional de España
- 1 de noviembre: Todos los Santos
- 6 de diciembre: Día de la Constitución
- 8 de diciembre: Inmaculada Concepción
- 25 de diciembre: Navidad

{: .note }
> AhoraFicho incluye **por defecto** los festivos nacionales oficiales cada año. Solo necesitas añadir los específicos de tu comunidad y localidad.

### Festivos Autonómicos

Cada Comunidad Autónoma tiene festivos propios. Ejemplos:

- **Madrid**: 2 de mayo (Fiesta de la Comunidad)
- **Cataluña**: 11 de septiembre (Diada)
- **Andalucía**: 28 de febrero (Día de Andalucía)
- **País Vasco**: 25 de octubre (Euskadi Eguna)

**Configuración**: Al crear el festivo, selecciona **"Tipo: Autonómico"** y asígnalo al edificio correspondiente.

### Festivos Locales

Son específicos de cada municipio o provincia. Cada localidad puede tener hasta **2 festivos locales** adicionales.

**Ejemplo**: En Madrid capital:
- 15 de mayo: San Isidro Labrador
- 9 de noviembre: Almudena

**Configuración**: Selecciona **"Tipo: Local"** y asigna el festivo al edificio del municipio.

### Festivos de Empresa

Son días no laborables establecidos por tu empresa (no oficiales).

**Ejemplos**:
- Día del puente entre festivos
- Cierre por inventario anual
- Evento especial de empresa

**Configuración**: Selecciona **"Tipo: Empresa"** y asigna a los edificios que corresponda.

---

## Asignar festivos por edificio/centro de trabajo

Si tu empresa tiene varios centros de trabajo en diferentes localidades, cada uno puede tener su propio calendario de festivos.

### Configurar edificios con festivos diferenciados

1. Ve a **"Configuraciones"** → **"Edificios"**
2. Verifica que cada centro de trabajo esté creado (Madrid, Barcelona, Valencia, etc.)
3. Regresa a **"Días Festivos"**
4. Al crear un festivo, selecciona el **"Edificio"** al que aplica

![Festivos por edificio](/assets/images/placeholder-festivos-edificio.png)

### Ejemplo práctico

**Empresa con 3 oficinas:**

| Oficina | Festivos Locales |
|---------|------------------|
| Madrid | 15 mayo (San Isidro), 9 nov (Almudena) |
| Barcelona | 24 sept (La Mercè), 26 dic (Sant Esteve) |
| Valencia | 9 oct (Día Comunitat), 19 mar (San José) |

**Resultado**:
- Los empleados de Madrid verán los festivos de Madrid en su calendario
- Los empleados de Barcelona verán los festivos de Barcelona
- Los festivos nacionales se aplican a todos

{: .tip }
> Si un empleado cambia de edificio, automáticamente adoptará los festivos del nuevo centro de trabajo.

---

## Importar calendario de festivos

AhoraFicho permite importar calendarios oficiales de festivos para agilizar la configuración.

### Importar festivos oficiales

1. Ve a **"Configuraciones"** → **"Días Festivos"**
2. Haz clic en **"Importar calendario"**
3. Selecciona el año y la comunidad autónoma
4. Haz clic en **"Importar"**
5. El sistema cargará automáticamente los festivos nacionales y autonómicos

![Importar festivos](/assets/images/placeholder-importar-festivos.png)

{: .note }
> Tras importar, **revisa siempre** los festivos locales específicos de tu municipio, ya que estos pueden variar según el año y no siempre están incluidos en las importaciones automáticas.

---

## Editar o eliminar un festivo

### Editar un festivo existente

1. Ve a **"Configuraciones"** → **"Días Festivos"**
2. Busca el festivo en el calendario
3. Haz clic en el festivo para ver los detalles
4. Haz clic en **"Editar"**
5. Modifica los campos necesarios
6. Guarda los cambios

### Eliminar un festivo

1. Accede al detalle del festivo
2. Haz clic en **"Eliminar"**
3. Confirma la acción

{: .warning }
> **Cuidado al eliminar**: Si eliminas un festivo que afecta a solicitudes de vacaciones ya aprobadas, podrían generarse inconsistencias en el cálculo de días. Verifica antes de eliminar.

---

## Festivos y su impacto en el sistema

### Cálculo de vacaciones

Cuando un empleado solicita vacaciones que incluyen festivos:

- Los días festivos **NO se descuentan** del saldo de vacaciones
- Solo se cuentan los días laborables

**Ejemplo**:
- Empleado solicita del 24 al 26 de diciembre (3 días)
- 25 de diciembre es festivo (Navidad)
- Solo se descuentan **2 días** del saldo de vacaciones

### Cálculo de horas trabajadas

Los festivos afectan al cálculo de horas laborables en los reportes:

- Si un empleado tiene horario de **8 horas/día** y hay 2 festivos en el mes
- Horas mensuales esperadas: (22 días laborables - 2 festivos) × 8h = **160 horas**

### Fichajes en festivos

Si un empleado ficha en un día festivo:

- El sistema lo registrará normalmente
- Aparecerá marcado como **"Festivo trabajado"** en los reportes
- Puedes configurar alertas para detectar trabajo en festivos

{: .tip }
> **Uso recomendado**: Activa notificaciones para que, si alguien ficha en festivo, el administrador o manager reciba una alerta para verificar si fue trabajo autorizado.

---

## Casos especiales

### Festivo que cae en fin de semana

En España, si un festivo cae en domingo, puede trasladarse al lunes (según convenio colectivo).

**Configuración en AhoraFicho**:
1. Crea el festivo en la fecha oficial (domingo)
2. Si tu empresa traslada el festivo, crea un festivo adicional el lunes
3. Marca ambos como **"Tipo: Empresa"** para diferenciarlo del oficial

### Festivo local diferente según municipio

Si tienes empleados en diferentes municipios de la misma provincia:

1. Crea un edificio por cada municipio
2. Asigna los festivos locales específicos a cada edificio
3. Asegúrate de que cada empleado está asignado al edificio correcto

### Cambio de festivo por decisión de empresa

Si tu empresa decide cambiar un festivo por otro día:

1. **No elimines** el festivo oficial (aparecerá en los reportes oficiales)
2. Crea un nuevo festivo **"Tipo: Empresa"** en la nueva fecha
3. Comunica el cambio a los empleados

---

## Preguntas frecuentes

### ¿Tengo que configurar los festivos cada año?

No, si marcas los festivos como **"Recurrentes"**, se crearán automáticamente cada año. Solo tendrás que revisar los festivos locales que puedan cambiar.

### ¿Los festivos afectan a los horarios de trabajo?

Sí, si un empleado tiene un horario que incluye un festivo, ese día no se computará como jornada laboral obligatoria.

### ¿Puedo tener festivos diferentes en cada edificio?

Sí, puedes asignar festivos específicos a cada edificio/centro de trabajo.

### ¿Qué pasa si un empleado cambia de edificio?

Adoptará automáticamente los festivos del nuevo edificio. Los festivos previos seguirán aplicándose a su historial anterior.

### ¿Los festivos aparecen en el Informe de Inspección de Trabajo?

Sí, los festivos se tienen en cuenta al calcular las horas laborables teóricas en los reportes oficiales.

---

## Calendario oficial de festivos 2024 (España)

### Festivos Nacionales 2024

| Fecha | Festivo | Tipo |
|-------|---------|------|
| 1 enero | Año Nuevo | Nacional |
| 28 marzo | Jueves Santo | Nacional |
| 29 marzo | Viernes Santo | Nacional |
| 1 mayo | Fiesta del Trabajo | Nacional |
| 15 agosto | Asunción de la Virgen | Nacional |
| 12 octubre | Fiesta Nacional | Nacional |
| 1 noviembre | Todos los Santos | Nacional |
| 6 diciembre | Día de la Constitución | Nacional |
| 25 diciembre | Navidad | Nacional |

{: .note }
> Consulta el Boletín Oficial de tu Comunidad Autónoma para verificar los festivos autonómicos y locales del año en curso.

---

## ¿Necesitas ayuda?

Si tienes problemas configurando los festivos:

- 📧 Email: soporte@ahoraficho.es
- 💬 [Preguntas Frecuentes](/preguntas-frecuentes/)

---

## Guías relacionadas

- 👉 [Gestión de Edificios](/guias-por-rol/administrador/gestion-edificios/)
- 👉 [Asignar Vacaciones](/guias-por-rol/administrador/asignar-vacaciones/)
- 👉 [Crear Horarios](/guias-por-rol/administrador/crear-horarios/)
- 👉 [Informe para Inspección de Trabajo](/reportes/informe-inspeccion-trabajo/)