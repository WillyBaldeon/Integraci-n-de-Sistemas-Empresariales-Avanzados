## Laboratorio 05 - Ventas
*Alumno: Baldeón Ayala, Willy Alexis*

## Procedimiento

# 2.8.1 Creación de Cotización a cliente
**Vemos que la Cotización creada se convierte en un Presupuesto:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%205/2.8.1%20Creaci%C3%B3n%20de%20Cotizaci%C3%B3n%20a%20cliente.png)

# 2.8.2 Creación de Cotización a cliente
**Al seleccionar "Enviar por Email", se genera un archivo PDF con el siguiente formato:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%205/2.8.2%20Creaci%C3%B3n%20de%20Cotizaci%C3%B3n%20a%20cliente.png)

# 4.5 Facturación y registro de pago de una Cotización
**Una vez validada la factura, el estado del cliente involucrado cambia agregando un indicador del número de sus ventas:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%205/4.5%20Facturaci%C3%B3n%20y%20registro%20de%20pago%20de%20una%20Cotizaci%C3%B3n.png)

# 4.6 Facturación y registro de pago de una Cotización
**Al realizar el pago, el detalle de la factura se actualiza indicando el monto registrado y el saldo pendiente:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%205/4.6%20Facturaci%C3%B3n%20y%20registro%20de%20pago%20de%20una%20Cotizaci%C3%B3n.png)

# 5.3 Configuración de envío de Correos
**Una vez agregadas las credenciales de nuestro correo y configuradas las opciones de seguridad del mismo, probamos la conexión desde el servidor y vemos la aviso exitoso:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%205/5.3%20Configuraci%C3%B3n%20de%20env%C3%ADo%20de%20Correos.png)

# 5.4 Configuración de envío de Correos
**Verificamos el correo enviado desde nuestro módulo de Ventas:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%205/5.4%20Configuraci%C3%B3n%20de%20env%C3%ADo%20de%20Correos.png)

# 8.4 Portal del cliente
**Al habilitar nuevos accesos al sistema a un cliente, se realiza una notificación vía correo electrónico:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%205/8.4%20Portal%20del%20cliente.png)

# 8.6 Portal del cliente
**La vista que el usuario tiene al acceder al sistema consta de sus Pedidos de Venta y Facturas. Aquí puede ver detalles de cada uno de sus movimientos:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%205/8.6%20Portal%20del%20cliente.png)

## Conclusiones:
* Utilizamos el módulo **Gestión de Ventas** para crear **Cotizaciones** interactuando con los productos de nuestra base de datos y sus Stocks en los diferentes almacenes comprendidos en el sistema. Las cotizaciones son un método que le permiten al cliente saber el monto total de una posible transacción.

* Validamos las cotizaciones creadas para iniciar el proceso de cobros. Cuando el cliente realiza un pago parcial, el módulo emite una factura indicando los detalles del pago y el saldo restante. Sin embargo, para que el sistema de correos funcione adecuadamente debemos configurar un correo emisor desde los **Ajustes** del módulo. Si lo anterior se realizó correctamente, los correos que la aplicación envíe serán emitidos desde el correo indicado.

* Activamos la opción **Múltiples Precios de Venta** que nos permite crear **Listas de Precio**. Esta práctica consiste en modificar los precios de los productos que veamos por conveniente de modo que los vendamos con las tarifas más adecuadas a clientes específicos. Esta opción es útil cuando trabajemos con mayoristas o proveedores, a los cuales los productos se proporcionan en cantidades enormes y podamos ofrecerles un precio más barato.

* Habilitamos el acceso al Portal de Ventas a uno de nuestros clientes. La sola habilitación envía una notificación al cliente para que esté enterado de esta característica adjuntando un enlace. Este portal le brinde al cliente opciones para visualizar sus Pedidos de Ventas y Facturas. Esta caraterística es una buena manera de ofrecer **Calidad de Servicio**, puesto que los usuarios podrán controlar de una manera óptima todos sus movimientos.

* Al desarrollar el laboratorio, manejamos múltiples funcionalidades útiles del módulo de ventas que nos permitan adecuarlas a una situación real. Vimos el manejo de cotizaciones, listas de precios y el acceso al portal de usuario. También, configuramos el correo electrónico para habilitar el envío de emails.
