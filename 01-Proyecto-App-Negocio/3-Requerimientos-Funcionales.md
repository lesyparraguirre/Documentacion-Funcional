# 03. Requerimientos Funcionales

## Sistema de Gestión de Productos y Ventas

### 1. Objetivo

Definir las funcionalidades que deberá cumplir el sistema
para gestionar productos, ventas, pagos, envíos y usuarios
de una pizzería o comercio.

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
| RF-010 | Cálculo de importes | Calcular subtotales y total automáticamente. |
| RF-011 | Registro de ventas | Guardar productos, cantidades, pago, envío e importe total. |
| RF-012 | Historial de ventas | Consultar las operaciones registradas. |

#### 2.4. Métodos de pago

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-013 | Pago en efectivo | Registrar el importe recibido y calcular el vuelto. |
| RF-014 | Mercado Pago | Registrar el pago por el importe exacto, sin integración externa. |

#### 2.5. Gestión de envíos

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-015 | Tarifa de envío | Permitir al administrador configurar el precio por kilómetro. |
| RF-016 | Cálculo de envío | Registrar dirección y kilómetros, calcular el costo y sumarlo al total. |

#### 2.6. Comprobantes

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-017 | Generación de comprobantes | Generar un comprobante interno con productos, cantidades, precios, envío, pago y total. |

#### 2.7. Estadísticas comerciales

| ID | Requerimiento | Descripción |
|---|---|---|
| RF-018 | Productos más vendidos | Mostrar los productos con mayor cantidad de ventas. |
| RF-019 | Ingresos | Consultar los ingresos registrados. |
| RF-020 | Ventas por período | Consultar cantidad de ventas e importes por fechas. |
| RF-021 | Métodos de pago | Mostrar cantidad de ventas e importes por método de pago. |

---

### 3. Reglas generales

- El administrador tendrá acceso a todas las funcionalidades.
- El usuario normal podrá registrar ventas, pagos y envíos.
- Los pagos se registrarán manualmente.
- Los comprobantes no tendrán validez fiscal.
- Los datos se almacenarán en SQL Server.
- Las estadísticas estarán disponibles para el administrador.

---

### 4. Funcionalidades pendientes de definición

- Estados de pedidos.
- Registro de clientes.
- Descuentos y promociones.
- Pagos combinados.
- Cancelación de ventas.
- Control de stock.
- Variantes de productos.

---

**Proyecto:** Sistema de Gestión de Productos y Ventas

**Documento:** Requerimientos Funcionales

**Estado:** En desarrollo
