### Historias de usuario

#### 1-Iniciar sesión

**Usuario:** Administrador / Usuario normal.

**Historia:**

Como usuario del sistema, quiero iniciar sesión
con mis credenciales para acceder a las
funcionalidades correspondientes a mi perfil.

**Criterios de aceptación:**

- El sistema debe validar las credenciales.
- Debe permitir el acceso si son correctas.
- Debe mostrar un mensaje si son incorrectas.

---

#### 2-Registrar productos

**Usuario:** Administrador.

**Historia:**

Como administrador, quiero registrar productos
con su nombre, descripción, precio y categoría
para mantener actualizado el catálogo.

**Criterios de aceptación:**

- Permitir ingresar los datos del producto.
- Validar los campos obligatorios.
- Guardar el producto en la base de datos.

---
#### 3-Consultar Productos

**Usuario:** Administrador / Usuario normal.

**Historia:**

Como usuario, quiero consultar y buscar productos
para conocer su informacion.

**Criterios de aceptación:**

- Mostrar los productos registrados.
- Permitir buscar productos por nombre o categoria.
- Mostrar información del producto seleccionado.

---
#### 4-Registrar una venta

**Usuario:** Administrador / Usuario normal.

**Historia:**

Como usuario del sistema, quiero registrar una venta con sus productos,
cantidades, costo de envío y método de pago para llevar un control
de las operaciones comerciales.

**Criterios de aceptación:**

- Permitir seleccionar productos y cantidades.
- Calcular automáticamente los importes.
- Permitir ingresar manualmente el costo de envío.
- Permitir seleccionar el método de pago.
- Validar los datos ingresados.
- Guardar la venta en la base de datos.

---
#### 5-Generar comprobante de venta

**Usuario:** Administrador / Usuario normal.

**Historia:**

Como usuario del sistema, quiero generar un comprobante
después de registrar una venta para consultar sus detalles
y poder imprimirlo.

**Criterios de aceptación:**

- Generar el comprobante después de registrar la venta.
- Mostrar los productos, cantidades y precios.
- Mostrar el costo de envío y el método de pago.
- Mostrar el importe total de la venta.
- Permitir imprimir el comprobante.

---
#### 6-Consultar historia de ventas

**Usuario:** Administrador

**Historia:**

Como administrador, quiero consultar el historial de ventas.

**Criterios de aceptación:**

- Mostrar las ventas registradas.
- Permitir buscar ventas por fecha o período.
- Mostrar los detalles de la venta seleccionada.

---
#### 7-Consultar estadisticas

**Usuario:** Administrador

**Historia:**

Como administrador, quiero consultar estadísticas de productos
y ventas.

**Criterios de aceptación:**

- Mostrar los productos más vendidos.
- Mostrar los ingresos por ventas.
- Permitir consultar estadísticas por período.
- Mostrar las ventas según el método de pago.

---
#### 8-Gestionar usuarios

**Usuario:** Administrador

**Historia:**

Como administrador, quiero gestionar los usuarios del sistema
para controlar sus accesos y permisos.

**Criterios de aceptación:**

- Mostrar los usuarios registrados.
- Permitir registrar nuevos usuarios.
- Permitir modificar los datos de los usuarios.
- Permitir dar de baja usuarios.
- Asignar un perfil de acceso a cada usuario.

---
**Proyecto:** Sistema de Gestión de Productos y Ventas

**Documento:** Historias de Usuario

**Estado:** En desarrollo
