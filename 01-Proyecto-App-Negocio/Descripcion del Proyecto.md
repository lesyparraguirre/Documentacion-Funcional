# 📋 01. Descripción General del Proyecto

## Sistema de Gestión de Productos y Ventas para una Pizzería

### 1. Descripción del proyecto

El proyecto consiste en el desarrollo de una **aplicación de escritorio**
destinada a la administración de productos y la gestión de ventas
de una pizzería.

El sistema permitirá centralizar la información comercial y facilitar
las operaciones diarias del negocio, mediante una interfaz que permita
administrar los productos disponibles, registrar ventas y generar
comprobantes de compra.

La aplicación contará con funcionalidades para:

- Administrar el catálogo de productos.
- Registrar operaciones de venta.
- Gestionar diferentes métodos de pago.
- Calcular costos de envío a domicilio.
- Generar comprobantes de compra.
- Administrar usuarios y permisos de acceso.
- Almacenar la información en una base de datos.

---

### 2. Problemática identificada

La administración de una pizzería mediante registros manuales
o herramientas no integradas puede generar dificultades en
la organización y el control de las operaciones comerciales.

Entre las principales problemáticas que el sistema busca resolver
se encuentran:

- Errores en el registro de productos y precios.
- Demoras en la toma y el registro de pedidos.
- Errores en el cálculo de importes y costos de envío.
- Dificultades para consultar las ventas realizadas.
- Falta de centralización de la información comercial.
- Errores en el cálculo del vuelto.
- Dificultades para generar comprobantes de compra.

---

### 3. Objetivo general

Desarrollar una **aplicación de escritorio para la gestión comercial
de una pizzería**, que permita centralizar la administración
de productos y automatizar el proceso de ventas.

El sistema buscará facilitar las operaciones comerciales,
reducir los errores asociados a los registros manuales
y mejorar la organización de la información del negocio.

---

### 4. Objetivos específicos

- Permitir el alta, baja, modificación y consulta de productos.
- Organizar los productos mediante categorías.
- Facilitar la búsqueda de productos mediante diferentes criterios.
- Registrar ventas con uno o varios productos.
- Automatizar el cálculo de subtotales e importes totales.
- Registrar operaciones mediante diferentes métodos de pago.
- Calcular automáticamente el vuelto en pagos en efectivo.
- Calcular los costos de envío según la distancia y la tarifa configurada.
- Generar comprobantes con el detalle de las operaciones.
- Administrar permisos de acceso según el perfil del usuario.
- Almacenar la información comercial en una base de datos.

---

### 5. Usuarios del sistema

El sistema contará con dos perfiles de usuario,
cada uno con diferentes permisos de acceso.

#### 👤 Administrador

Será responsable de administrar y configurar
las funcionalidades generales del sistema.

**Funciones principales:**

- Registrar, modificar y dar de baja productos.
- Administrar categorías de productos.
- Gestionar precios.
- Administrar usuarios.
- Configurar tarifas de envío.
- Registrar ventas.
- Consultar operaciones realizadas.
- Generar comprobantes de compra.

#### 👤 Usuario normal

Será responsable de registrar las operaciones
comerciales de la pizzería.

**Funciones principales:**

- Consultar los productos disponibles.
- Seleccionar productos para realizar una venta.
- Registrar pedidos y ventas.
- Seleccionar métodos de pago.
- Calcular costos de envío.
- Generar comprobantes de compra.

El usuario normal no tendrá permisos para modificar
productos, precios, usuarios ni configuraciones generales.

---

### 6. Tecnologías utilizadas

| Tecnología | Descripción |
|------------|-------------|
| **C#** | Lenguaje de programación |
| **Windows Forms** | Desarrollo de la interfaz gráfica |
| **SQL Server** | Sistema de gestión de base de datos |
| **Arquitectura de tres capas** | Organización de la aplicación en capas de presentación, negocio y acceso a datos |

---

### 7. Alcance general

El sistema estará orientado a la administración
de productos y ventas de una pizzería.

Contemplará la gestión del catálogo comercial,
el registro de operaciones de venta,
la administración de métodos de pago,
el cálculo de costos de envío y la generación
de comprobantes.

**No se incluirá la gestión de materias primas,
recetas de elaboración ni el control de ingredientes.**

Las funcionalidades específicas y las restricciones
del sistema se detallarán en el documento
de alcance funcional.

---

### 8. Estado del proyecto

🚧 **En desarrollo**

La aplicación se encuentra en proceso de análisis,
diseño y desarrollo.

La documentación funcional será actualizada
conforme avance la implementación del sistema.

---

**Proyecto:** Sistema de Gestión de Productos y Ventas para una Pizzería

**Tipo de documento:** Descripción General del Proyecto

**Estado:** Borrador
