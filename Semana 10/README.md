## Laboratorio 10 - Llamadas a API externas
*Alumno: Baldeón Ayala, Willy Alexis*

## Procedimiento

# 2.5 Creación de modelo Documentos 
**Configuramos detalles finales para la extensión "Documentos" de nuestro módulo. Entonces, instalamos la aplicación habilitando el modo desarrollador:**   
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%2010/2.5.1%20Creaci%C3%B3n%20de%20modelo%20Documentos.png)   
**Vemos que la lista generada se puede editar directamente seleccionando algún registro en vez de desplegar un formulario adicional. Esto se logró gracias al atributo "editable".**
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%2010/2.5.2%20Creaci%C3%B3n%20de%20modelo%20Documentos.gif)

# 4.2 Consumo de API externa
**Nos registramos en la página APIsPERU con nuestro correo para que posteriormente nos envíen credenciales de acceso para utilizar su servicio (key de acceso).**   
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%2010/4.2%20Consumo%20de%20API%20externa.png)

# 4.5 Consumo de API externa
**Iniciamos el Log de Odoo y vemos los mensajes que configuramos con el método "onChange" importado de la API recién establecida. Estos Logs indican cómo está interactuando el usuario con los cuadros de texto del formulario. Gracias al método mencionado, la aplicación detecta los cambios en el formulario y actúa de la manera más adecuada.**   
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%2010/4.5%20Consumo%20de%20API%20externa.gif)

# 4.9 Consumo de API externa
**Configuramos la lógica de manejo de los datos ingresados por el usuario. De este modo, la aplicación difiere si los dígitos provistos corresponden a un número de DNI o RUC válido. Probamos la aplicación ingresando un número de DNI y seleccionamos la opción correspondiente. Lo que sucede es que la aplicación consulta directamente a la API y cuando obtiene una respuesta, los datos adecuados se cargarán automáticamente en los demás campos.**   
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%2010/4.9.1%20Consumo%20de%20API%20externa.gif)   
**Así mismo, probamos la función de reconocimiento de RUC con la cadena de tiendas propuesta:**   
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%2010/4.9.2%20Consumo%20de%20API%20externa.gif)

# 5.3 Constraint o limitantes.
**Puesto que ya creamos a un usuario con el número de DNI ingresado a continuación; el módulo niega la creación de este registro, porque se suponque que se trata de un campo único e irremplazable. A la vez, se muestra un diálogo en la parte superior.**   
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%2010/5.3%20Constraint%20o%20limitantes..gif)

# 6.4 Campos relacionados
**Probamos el formulario de creación de formularios seleccionando tanto el tipo de serie "Boleta" como de "Factura".**   
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%2010/6.4%20Campos%20relacionados.gif)

## Conclusiones:
* Integramos una API pública a nuestro módulo ingresando una Key de acceso provista directamente por los encargados de dicho servicio. Utilizamos esta API para consultar número de DNI y RUC y obtener datos públicos.
* Cuando agregamos dependencias a nuestra aplicación, antes de instalarlo debemos asegurarnos de que tales módulos están, a su vez, intalados y configurados. De lo contrario, Odoo no nos permitirá instalar nuestra aplicación.
* Interactuamos con el Log de Odoo para ver en tiempo real distintos cambios y estados por los que pasa todo nuestro servidor.