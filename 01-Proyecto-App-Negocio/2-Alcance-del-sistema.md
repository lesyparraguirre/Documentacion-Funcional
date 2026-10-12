# 02. Alcance del Sistema

## Sistema de Gestión de Productos y Ventas para una Pizzería o Negocio

### 1. Descripción del alcance

El sistema permitirá gestionar productos, pedidos, ventas,
pagos y envíos de una pizzería o negocio.

También incluirá estadísticas comerciales, generación de
comprobantes y administración de usuarios.

---

### 2. Funcionalidades incluidas

- **Productos:** alta, baja, modificación, búsqueda y categorización.
- **Ventas:** registro de pedidos, cálculo de totales e historial de ventas.
- **Pagos:** registro de efectivo y Mercado Pago, con cálculo de vuelto.
- **Envíos:** cálculo del costo según distancia y tarifa por kilómetro.
- **Comprobantes:** generación de comprobantes internos de venta.
- **Estadísticas:** productos más vendidos, ingresos, ventas por período
  y métodos de pago.
- **Usuarios:** inicio de sesión y permisos según el perfil.
- **Base de datos:** almacenamiento de la información comercial en SQL Server.

---

### 3. Perfiles de usuario

**Administrador:**
- Gestionar productos, precios, categorías y usuarios.
- Configurar tarifas de envío.
- Registrar y consultar ventas.
- Acceder a estadísticas y reportes.

**Usuario normal:**
- Consultar productos.
- Registrar pedidos, ventas y pagos.
- Calcular envíos y generar comprobantes.

---

### 4. Funcionalidades excluidas

- Gestión de materias primas, ingredientes y recetas.
- Administración de proveedores y compras.
- Facturación electrónica fiscal.
- Procesamiento e integración de pagos electrónicos.
- Integración con plataformas de delivery.
- Seguimiento de repartidores.
- Gestión de múltiples sucursales.
- Aplicación móvil y pedidos en línea.

---

### 5. Restricciones

- Aplicación de escritorio desarrollada en C# y Windows Forms.
- Base de datos SQL Server.
- Arquitectura de tres capas.
- Acceso según permisos de usuario.
- Registro manual de pagos y distancias de envío.
- Comprobantes sin validez fiscal.

---

### 6. Aspectos pendientes

- Seguimiento de estados de pedidos.
- Registro de clientes.
- Descuentos y promociones.
- Pagos combinados.
- Cancelación o modificación de ventas.
- Impresión o exportación de comprobantes.
- Variantes de productos y control de stock.
- Condiciones para confirmar una venta.

---

**Estado:** En desarrollo.
