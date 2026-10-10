# 📋 02. Alcance del Sistema

## Sistema de Gestión de Productos y Ventas para una Pizzería

### 1. Propósito del documento

El presente documento tiene como finalidad definir el alcance funcional del **Sistema de Gestión de Productos y Ventas para una Pizzería**, estableciendo las funcionalidades que serán desarrolladas, sus límites, restricciones y condiciones generales de funcionamiento.

Este documento servirá como referencia para las etapas de análisis, diseño, desarrollo y pruebas de la aplicación.

---

### 2. Descripción del alcance

El sistema consistirá en una **aplicación de escritorio destinada a la gestión comercial de una pizzería**.

Permitirá administrar el catálogo de productos, registrar pedidos y ventas, identificar los métodos de pago utilizados, calcular costos de envío y generar comprobantes de compra.

La aplicación contará con diferentes niveles de acceso según el perfil del usuario.

Toda la información comercial será almacenada en una base de datos, permitiendo su consulta y administración.

---

### 3. Funcionalidades incluidas

Las siguientes funcionalidades forman parte del alcance inicial del proyecto.

#### 3.1. Gestión de productos

El sistema permitirá:

- Registrar nuevos productos.
- Consultar el listado de productos disponibles.
- Buscar productos mediante diferentes criterios.
- Modificar la información de productos existentes.
- Dar de baja productos.
- Consultar el detalle completo de cada producto.
- Registrar y modificar precios.
- Incorporar imágenes y descripciones.
- Clasificar productos mediante categorías.
- Identificar productos activos e inactivos.

**Categorías de productos:**

- Pizzas.
- Empanadas.
- Bebidas.
- Promociones.
- Otros productos.

#### 3.2. Gestión de pedidos y ventas

El sistema permitirá:

- Seleccionar productos del catálogo.
- Agregar uno o varios productos a una operación.
- Indicar la cantidad de unidades solicitadas.
- Modificar las cantidades antes de confirmar la venta.
- Eliminar productos de una operación antes de confirmarla.
- Calcular automáticamente los subtotales.
- Calcular el importe total de la venta.
- Registrar las ventas realizadas.
- Consultar el historial de ventas.

El seguimiento de estados de los pedidos queda pendiente de definición.

#### 3.3. Registro de métodos de pago

El sistema permitirá registrar el método de pago utilizado por el cliente al realizar una compra.

Se contemplarán inicialmente los siguientes métodos:

**Pago en efectivo:**

- Seleccionar efectivo como método de pago.
- Registrar el importe recibido.
- Validar que el importe recibido sea suficiente.
- Calcular automáticamente el vuelto.
- Registrar el método de pago asociado a la venta.

**Pago mediante Mercado Pago:**

- Seleccionar Mercado Pago como método de pago.
- Registrar el importe abonado.
- Asociar el método de pago a la venta.

**Consideraciones:**

- El sistema únicamente registrará la información del pago.
- No realizará transacciones financieras.
- No verificará automáticamente la acreditación de pagos.
- No se integrará con plataformas externas de pago.

#### 3.4. Cálculo de costos de envío

El sistema permitirá:

- Identificar si una venta requiere envío a domicilio.
- Ingresar manualmente la distancia del envío en kilómetros.
- Configurar una tarifa por kilómetro.
- Calcular automáticamente el costo del envío.
- Incorporar el costo de envío al importe total de la venta.
- Mostrar el importe del envío en el comprobante.

**Fórmula de cálculo:**

Costo de envío = Distancia en kilómetros × Tarifa por kilómetro

La tarifa será administrada por usuarios con permisos de administrador.

#### 3.5. Generación de comprobantes

El sistema permitirá generar un comprobante por cada venta registrada.

El comprobante incluirá:

- Identificador de la venta.
- Fecha y hora de la operación.
- Productos vendidos.
- Cantidades.
- Precios unitarios.
- Subtotales.
- Costo de envío, cuando corresponda.
- Importe total.
- Método de pago utilizado.
- Vuelto, cuando corresponda.

Los comprobantes tendrán carácter comercial interno y no reemplazarán los comprobantes fiscales exigidos por la normativa vigente.

#### 3.6. Gestión de usuarios

El sistema contará con dos perfiles de usuario con diferentes permisos.

**Administrador:**

- Registrar, modificar y dar de baja productos.
- Administrar categorías.
- Modificar precios.
- Gestionar usuarios.
- Configurar tarifas de envío.
- Registrar ventas.
- Consultar el historial de ventas.
- Generar comprobantes.

**Usuario normal:**

- Consultar productos disponibles.
- Seleccionar productos para una venta.
- Registrar operaciones de venta.
- Seleccionar métodos de pago.
- Registrar importes recibidos.
- Calcular costos de envío.
- Generar comprobantes.

El usuario normal no tendrá permisos para modificar productos, precios, usuarios ni configuraciones generales.

#### 3.7. Persistencia de datos

El sistema almacenará la información necesaria para administrar las operaciones comerciales.

Se contemplará el registro de:

- Productos.
- Categorías de productos.
- Usuarios.
- Perfiles de usuario.
- Ventas.
- Detalles de venta.
- Métodos de pago.
- Pagos registrados.
- Tarifas de envío.

La información será almacenada y gestionada mediante una base de datos SQL Server.

---

### 4. Funcionalidades excluidas

Las siguientes funcionalidades no formarán parte del alcance inicial del proyecto:

- Gestión de materias primas.
- Administración de ingredientes.
- Gestión de recetas de elaboración.
- Control de consumo de insumos.
- Gestión de proveedores.
- Administración de compras a proveedores.
- Facturación electrónica fiscal.
- Procesamiento automático de pagos.
- Integración con Mercado Pago.
- Integración con entidades bancarias.
- Integración con plataformas de delivery.
- Seguimiento de repartidores en tiempo real.
- Administración de múltiples sucursales.
- Aplicación móvil.
- Plataforma de pedidos en línea.
- Integración con sistemas contables externos.

Estas funcionalidades podrán evaluarse para futuras versiones del sistema.

---

### 5. Restricciones del sistema

El desarrollo estará sujeto a las siguientes restricciones:

- La aplicación será de escritorio.
- Se desarrollará utilizando C# y Windows Forms.
- Se utilizará SQL Server para la persistencia de datos.
- Se implementará una arquitectura de tres capas.
- El acceso a las funcionalidades dependerá del perfil del usuario.
- Los productos deberán estar registrados para poder incorporarse a una venta.
- Los precios serán administrados por usuarios autorizados.
- Las tarifas de envío serán configuradas por el administrador.
- La distancia del envío será ingresada manualmente.
- Los métodos de pago serán registrados manualmente.
- El sistema no procesará transacciones financieras.
- No se emitirán comprobantes fiscales electrónicos.

---

### 6. Supuestos y dependencias

Para el desarrollo y funcionamiento del sistema se consideran los siguientes supuestos:

- Los usuarios contarán con credenciales de acceso.
- Los productos estarán previamente registrados en el sistema.
- Los precios serán definidos por usuarios autorizados.
- Las operaciones utilizarán los precios registrados en el sistema.
- El administrador establecerá las tarifas de envío.
- El usuario ingresará la distancia correspondiente cuando se requiera un envío.
- El usuario seleccionará el método de pago informado por el cliente.
- Los pagos serán registrados sin validación automática con plataformas externas.
- La base de datos deberá estar disponible para registrar y consultar operaciones.

---

### 7. Aspectos pendientes de definición

Antes de finalizar el análisis funcional, será necesario determinar:

- Si los pedidos tendrán estados de seguimiento.
- Si se registrarán datos de los clientes.
- Si se permitirán descuentos y promociones.
- Si se admitirán pagos combinados.
- Si se podrán cancelar o anular ventas.
- Si los comprobantes podrán imprimirse o exportarse a PDF.
- Si se permitirá modificar una venta confirmada.
- Si los productos tendrán diferentes tamaños o variantes.
- Si se gestionará el stock de productos de reventa, como bebidas.
- En qué momento un pedido se considerará una venta confirmada.

Estas decisiones deberán resolverse antes de cerrar la especificación de requerimientos funcionales.

---

### 8. Resultado esperado

Al finalizar el desarrollo, se espera contar con una **aplicación de escritorio que permita administrar las operaciones comerciales de una pizzería**.

El sistema deberá facilitar:

- La administración del catálogo de productos.
- El registro de pedidos y ventas.
- El cálculo automático de importes.
- El registro de métodos de pago.
- El cálculo de costos de envío.
- La generación de comprobantes.
- La consulta de operaciones comerciales.
- La administración de usuarios y permisos.

La aplicación permitirá centralizar la información comercial, reducir errores operativos y facilitar las tareas habituales del negocio.

---

**Proyecto:** Sistema de Gestión de Productos y Ventas para una Pizzería

**Tipo de documento:** Alcance del Sistema

**Estado:** Borrador
