# 6. Vista de Ejecución

## Escenario: Registro de un Nuevo Producto

El proceso inicia cuando el Administrador de Compras accede al módulo de productos y diligencia el formulario de registro.

La aplicación web envía la información al backend mediante una petición HTTP.

La API valida que todos los datos sean correctos y cumplan con las reglas de negocio.

Una vez superada la validación, el sistema almacena la información en la base de datos PostgreSQL.

Finalmente, el backend responde con un mensaje de confirmación y la aplicación actualiza automáticamente el listado de productos.

## Diagrama de Secuencia

![Diagrama de Secuencia](./images/Imagen%203.png)

Este diagrama representa la comunicación entre el usuario, la interfaz web, la API y la base de datos durante el proceso de registro de un producto.

