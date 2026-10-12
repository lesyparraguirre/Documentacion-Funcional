# 03. Requerimientos Funcionales

## Sistema de Gestión de Productos y Ventas

### 1. Objetivo

Definir las funcionalidades que deberá cumplir el sistema
para gestionar productos, ventas, métodos de pago, costos de envío
y usuarios de una pizzería o comercio.

---

### 2. Requerimientos funcionales

#### 2.1. Gestión de usuarios

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-001 | Inicio de sesión | Permitir el acceso mediante usuario y contraseña. |
| RF-002 | Gestión de usuarios | Registrar, modificar y desactivar usuarios. |
| RF-003 | Control de permisos | Restringir funcionalidades según el perfil del usuario. |

#### 2.2. Gestión de productos

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-004 | Alta de productos | Registrar productos con nombre, precio, descripción, imagen y categoría. |
| RF-005 | Consulta de productos | Listar, buscar y visualizar productos. |
| RF-006 | Modificación de productos | Actualizar la información de productos existentes. |
| RF-007 | Baja de productos | Desactivar productos sin eliminar su historial. |
| RF-008 | Categorías | Registrar, modificar y clasificar productos por categorías. |

#### 2.3. Gestión de ventas

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-009 | Selección de productos | Agregar productos y cantidades a una venta. |
| RF-010 | Cálculo de importes | Calcular automáticamente subtotales y total, incluyendo el costo de envío. |
| RF-011 | Registro de ventas | Guardar productos, cantidades, método de pago, costo de envío e importe total. |
| RF-012 | Historial de ventas | Permitir al administrador consultar las operaciones registradas. |

#### 2.4. Métodos de pago

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-013 | Selección del método de pago | Permitir seleccionar Efectivo o Mercado Pago mediante un desplegable. |
| RF-014 | Registro del método de pago | Guardar el método seleccionado junto con la venta, sin procesar pagos electrónicos. |

#### 2.5. Gestión de envíos

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-015 | Ingreso del costo de envío | Permitir ingresar manualmente el importe del envío. |
| RF-016 | Incorporación del envío | Sumar automáticamente el costo de envío al total de la venta. |

#### 2.6. Comprobantes

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-017 | Generación de comprobantes | Generar un comprobante interno con productos, cantidades, precios, envío, método de pago y total. |

#### 2.7. Estadísticas comerciales

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-018 | Productos más vendidos | Mostrar los productos con mayor cantidad de unidades vendidas. |
| RF-019 | Ingresos | Consultar los ingresos registrados por ventas. |
| RF-020 | Ventas por período | Consultar cantidad de ventas e importes por fechas. |
| RF-021 | Métodos de pago | Mostrar cantidad de ventas e importes agrupados por método de pago. |

---

### 3. Reglas generales

- El administrador tendrá acceso a todas las funcionalidades.
- El usuario normal podrá consultar productos y registrar ventas.
- El método de pago se seleccionará manualmente.
- El costo de envío se ingresará manualmente.
- El sistema calculará automáticamente los importes de la venta.
- Los comprobantes no tendrán validez fiscal.
- Los datos se almacenarán en SQL Server.
- Las estadísticas estarán disponibles para el administrador.

---

### 4. Funcionalidades pendientes de definición

- Estados de pedidos.
- Registro de clientes y direcciones de entrega.
- Descuentos y promociones.
- Cálculo del vuelto en efectivo.
- Pagos combinados.
- Cancelación o modificación de ventas.
- Impresión o exportación de comprobantes.
- Control de stock.
- Variantes de productos.
- Condiciones para confirmar una venta.

---

**Proyecto:** Sistema de Gestión de Productos y Ventas

**Documento:** Requerimientos Funcionales

**Estado:** En desarrollo
