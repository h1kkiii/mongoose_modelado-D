## Sistema de Registro de Ventas para Supermercados

# Descripción:

Aplicación web diseñada para registrar las ventas individuales de cada empleado en un supermercado. Requiere autenticación de usuarios.

# Características:

- Registro de ventas por empleado.
- Autenticación de empleados.
- Base de datos MongoDB con Mongoose.
- Modelo de Datos:

- Empleado: Nombre, edad, usuario (nombre de usuario, correo, contraseña), ventas (fecha, productos [nombre, precio, cantidad]).
- Ventas: Array de objetos con detalles de cada venta (producto, cantidad, precio total, fecha).
- Diseño:

- Modelo embebido para ventas y productos dentro de cada empleado para un acceso y consultas más eficientes.
- Información del usuario dentro del documento del empleado para centralizar datos.

- Instalación:

- Clonar repositorio.
- npm install
