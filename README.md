# Funeraria
Funerariaapp


sistema de gestión de pedidos y facturación para nuestra funeraria. Este sistema te permite administrar productos, facturas, menús de pedido, registros y tablas de una manera eficiente. A continuación, te proporcionamos instrucciones sobre los endpoints disponibles y cómo utilizar Postman para interactuar con nuestro sistema.

Endpoints Disponibles:

Productos:

Obtener todos los productos:

Método: GET
Endpoint: /product/all
Obtener un producto por ID:

Método: GET
Endpoint: /product/{productId}
Guardar un producto:

Método: POST
Endpoint: /product/save
Body: JSON con los datos del producto
Eliminar un producto por ID:

Método: DELETE
Endpoint: /product/delete/{id}
Facturas (Invoices):

Obtener todas las facturas:

Método: GET
Endpoint: /invoice/all
Obtener una factura por ID:

Método: GET
Endpoint: /invoice/{invoiceId}
Guardar una factura:

Método: POST
Endpoint: /invoice/save
Body: JSON con los datos de la factura
Eliminar una factura por ID:

Método: DELETE
Endpoint: /invoice/delete/{id}
Menú de Pedido (Order Menu):

Obtener todos los menús de órdenes:

Método: GET
Endpoint: /ordermenu/all
Obtener menú de órdenes por ID:

Método: GET
Endpoint: /ordermenu/{id}
Guardar menú de órdenes:

Método: POST
Endpoint: /ordermenu/save
Body: JSON con los datos del menú
Eliminar menú de órdenes por ID:

Método: DELETE
Endpoint: /ordermenu/delete/{id}
Registro (Register):

Obtener todos los registros:

Método: GET
Endpoint: /register/all
Obtener un registro por identificación:

Método: GET
Endpoint: /register/{registerId}
Guardar un registro:

Método: POST
Endpoint: /register/save
Body: JSON con los datos del registro
Tabla (Table):

Obtener una tabla por ID:

Método: GET
Endpoint: /table/{tableId}
Guardar una tabla:

Método: POST
Endpoint: /table/save
Body: JSON con los datos de la tabla
Uso en Postman:

Obtener todos los productos:

Método: GET
URL: http://localhost:puerto/product/all
Obtener un producto por ID:

Método: GET
URL: http://localhost:puerto/product/{productId}
Guardar un producto:

Método: POST
URL: http://localhost:puerto/product/save
Body: JSON con los datos del producto
Eliminar un producto por ID:

Método: DELETE
URL: http://localhost:puerto/product/delete/{id}
Recuerda reemplazar "puerto" y "{productId}" o "{id}" con los valores correspondientes para tu aplicación.
