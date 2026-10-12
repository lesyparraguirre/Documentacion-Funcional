# 02. Alcance del Sistema

## Sistema de Gestión de Productos y Ventas para una Pizzería o Negocio

### Descripción del alcance

El sistema permitirá gestionar productos y registrar ventas
de una pizzería o negocio.

También incluirá el registro de métodos de pago, costos de envío,
generación de comprobantes, estadísticas comerciales
y administración de usuarios.

---

### Funcionalidades incluidas

- **Productos:** alta, baja, modificación, búsqueda y categorización.
- **Ventas:** selección de productos y cantidades, cálculo automático
  de importes y registro de la venta.
- **Pagos:** selección del método de pago (efectivo o Mercado Pago)
  mediante un desplegable para su registro y análisis estadístico.
- **Envíos:** ingreso manual del costo de envío, que se sumará
  automáticamente al total de la venta.
- **Comprobantes:** generación de comprobantes internos de venta.
- **Estadísticas:** productos más vendidos, ingresos, ventas por período
  y cantidad de ventas por método de pago.
- **Usuarios:** inicio de sesión y permisos según el perfil.
- **Base de datos:** almacenamiento de la información comercial en SQL Server.

---

### Perfiles de usuario

**Administrador:**
- Gestionar productos, precios, categorías y usuarios.
- Registrar y consultar ventas.
- Acceder a estadísticas y reportes.

**Usuario normal:**
- Consultar productos.
- Seleccionar productos y cantidades.
- Registrar ventas.
- Seleccionar el método de pago.
- Ingresar manualmente el costo de envío.
- Generar comprobantes.

---

### Funcionalidades excluidas

- Gestión de materias primas, ingredientes y recetas.
- Administración de proveedores y compras.
- Facturación electrónica fiscal.
- Procesamiento e integración de pagos electrónicos.
- Cálculo automático de envíos por distancia.
- Integración con plataformas de delivery.
- Seguimiento de repartidores.
- Gestión de múltiples sucursales.
- Aplicación móvil y pedidos en línea.

---

### Restricciones

- Aplicación de escritorio desarrollada en C# y Windows Forms.
- Base de datos SQL Server.
- Arquitectura de tres capas.
- Acceso según permisos de usuario.
- Registro manual del método de pago y del costo de envío.
- Comprobantes sin validez fiscal.

---

### Aspectos pendientes

- Seguimiento de estados de pedidos.
- Registro de clientes y direcciones de entrega.
- Descuentos y promociones.
- Cálculo automático del vuelto.
- Pagos combinados.
- Cancelación o modificación de ventas.
- Impresión o exportación de comprobantes.
- Variantes de productos y control de stock.
- Condiciones para confirmar una venta.

---

**Proyecto:** Sistema de Gestión de Productos y Ventas

**Documento:** Alcance del Sistema

**Estado del proyecto:** En desarrollo

**Estado del documento:** Borrador
