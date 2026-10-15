# 06. Casos de Uso

## Sistema de Gestión de Productos y Ventas

### 1. Objetivo

Identificar las principales operaciones que los usuarios
podrán realizar dentro del sistema.

---

### 2. Actores

- **Administrador:** gestiona productos, usuarios, ventas y estadísticas.
- **Usuario normal:** consulta productos, registra ventas y genera comprobantes.

---

### 3. Casos de uso

| ID | Caso de uso | Actor | Descripción |
|---|---|---|---|
| CU-001 | Iniciar sesión | Ambos | Acceder al sistema mediante credenciales. |
| CU-002 | Gestionar productos | Administrador | Registrar, modificar y dar de baja productos y categorías. |
| CU-003 | Consultar productos | Ambos | Buscar y visualizar productos disponibles. |
| CU-004 | Registrar venta | Ambos | Seleccionar productos, cantidades, envío y método de pago. |
| CU-005 | Generar comprobante | Ambos | Generar el comprobante interno de una venta. |
| CU-006 | Consultar ventas | Administrador | Visualizar el historial de ventas. |
| CU-007 | Consultar estadísticas | Administrador | Consultar ingresos, productos vendidos y métodos de pago. |
| CU-008 | Gestionar usuarios | Administrador | Registrar, modificar y desactivar usuarios. |

---

### 4. Caso de uso principal: Registrar venta

**ID:** CU-004  
**Actor:** Administrador / Usuario normal.

**Flujo principal:**

1. Seleccionar productos y cantidades.
2. Ingresar manualmente el costo de envío.
3. Seleccionar el método de pago (Efectivo o Mercado Pago).
4. El sistema calcula el importe total.
5. Confirmar y registrar la venta.

**Resultado:** Venta almacenada en la base de datos.

---

### 5. Consideraciones

- Las funcionalidades dependerán del perfil del usuario.
- Toda venta deberá contener al menos un producto.
- El costo de envío será ingresado manualmente.
- Los comprobantes no tendrán validez fiscal.

---

**Proyecto:** Sistema de Gestión de Productos y Ventas

**Documento:** Casos de Uso

**Estado:** En desarrollo
