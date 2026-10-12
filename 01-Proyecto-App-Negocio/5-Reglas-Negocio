# 05. Reglas de Negocio

## Sistema de Gestión de Productos y Ventas

### 1. Objetivo

Establecer las condiciones y restricciones que deberá
cumplir el sistema para gestionar correctamente
los productos y las ventas.

---

### 2. Reglas de negocio

#### 2.1. Gestión de productos

| ID | Regla | Descripción |
|---|---|---|
| RN-001 | Datos obligatorios | Todo producto deberá tener nombre, precio y categoría. |
| RN-002 | Precios | Los precios de venta deberán ser mayores a cero. |
| RN-003 | Productos inactivos | Los productos dados de baja no podrán incluirse en nuevas ventas. |

#### 2.2. Gestión de ventas

| ID | Regla | Descripción |
|---|---|---|
| RN-004 | Productos por venta | Toda venta deberá contener al menos un producto. |
| RN-005 | Cantidades | Las cantidades deberán ser mayores a cero. |
| RN-006 | Subtotal | Se calculará multiplicando el precio unitario por la cantidad. |
| RN-007 | Costo de envío | Se ingresará manualmente y no podrá ser negativo. |
| RN-008 | Total de venta | Será la suma de los subtotales y el costo de envío. |
| RN-009 | Registro de venta | Cada venta tendrá un identificador único, fecha y hora. |

#### 2.3. Métodos de pago

| ID | Regla | Descripción |
|---|---|---|
| RN-010 | Método obligatorio | Toda venta deberá registrar un método de pago. |
| RN-011 | Métodos permitidos | Se podrá seleccionar Efectivo o Mercado Pago. |
| RN-012 | Registro manual | El sistema no procesará ni verificará pagos electrónicos. |

#### 2.4. Usuarios y estadísticas

| ID | Regla | Descripción |
|---|---|---|
| RN-013 | Permisos | Solo el administrador podrá gestionar productos y usuarios. |
| RN-014 | Estadísticas | Se calcularán a partir de las ventas registradas. |
| RN-015 | Acceso a estadísticas | Solo el administrador podrá consultar estadísticas comerciales. |

---

### 3. Consideraciones generales

- Los cálculos de importes serán automáticos.
- El costo de envío se ingresará manualmente.
- El método de pago se seleccionará mediante un desplegable.
- Los comprobantes serán internos y sin validez fiscal.
- Las operaciones deberán respetar los permisos del usuario.

---

**Proyecto:** Sistema de Gestión de Productos y Ventas

**Documento:** Reglas de Negocio

**Estado:** En desarrollo
