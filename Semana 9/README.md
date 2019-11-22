## Laboratorio 09 - Módulo Básico y Herencia 
*Alumno: Baldeón Ayala, Willy Alexis*

## Procedimiento

# 3.7 Creación de módulo Facturación
**Configuramos e iniciamos nuestro módulo con la vista "Series" implementda. Aquí podemos visualizar en una lista los registros correspondientes a nuestras series de la base de datos; como no hay ni una, procedemos a crear un par:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%209/3.7%20Creaci%C3%B3n%20de%20m%C3%B3dulo%20Facturaci%C3%B3n.gif)

# 5.2 Vista de búsqueda
**Implementamos la función de búsqueda en nuestra lista. Por defecto, el módulo solo realiza la búsqueda del campo principal. Pero, nosotros modificamos esto para que podamos realizar búsquedas de otros campos en los registros. De este modo, conseguimos filtrar tanto por nombre como por prefijo:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%209/5.2%20Vista%20de%20b%C3%BAsqueda.gif)

# 6.3 Data por defecto
**Anteriormente ingresamos datos manualmente utilizando el formulario de creación. Ahora, codificamos un archivo "Data" con el que podemos añadir cuantos registros queramos replicando unas líneas de código. Al ejecutarse la aplicación,como esto se trata de un proceso interno, automáticamente se ingreserarán esos registros a nuestra base de datos:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%209/6.3%20Data%20por%20defecto.png)

# 7.1 Verificación de API automática
**Configuramos nuestro 'package.json' y de inmediato ejecutamos el comando 'npm install' para instalar las dependencias de nuestro proyecto:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%209/7.1%20Verificaci%C3%B3n%20de%20API%20autom%C3%A1tica.png)

# 7.3 Verificación de API automática
**Configuramos la conexión de nuestra aplicación con la base de datos correspondiente y probamos el consumo de la API. Para esto, basta con agregar las credenciales y el puerto de nuestro servidor, y generar una instancia de 'odoo-xmlrpc':**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%209/7.3%20Verificaci%C3%B3n%20de%20API%20autom%C3%A1tica.gif)

# 8.5 Herencia de modelos
**Integramos una vista adicional y la configuramos con un modelo nuevo que hereda de otro existente. De este modo, conseguimos referenciar fácilmente los registros de ambos modelos y aplicarlos a la par en las diferentes vistas. El resultado es que, desde el módulo Facturación de Odoo, podemos acceder a nuestros registros 'Series' creados en nuestro propio módulo ¡Estamos unificando los módulos!**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%209/8.5%20Herencia%20de%20modelos.gif)

# 9.2 Tarea
**Aplicamos lo aprendido con los registros "Serie" para agregar un menú extra que maneje "Documentos" del formato establecido. Implementamos las funcionalidades de Editar y Buscar sobre nuestros datos:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%209/9.2%20Tarea.gif)

## Conclusiones:
* Creamos un módulo propio y lo instalamos teniendo en cuenta los conocimientos previos acerca de la localización y configuración de la ruta de módulos externos. Esta aplicación tiene soporte con NODE para su funcionamiento con una API automática.
* Comprendimos que cuando realizamos cambios únicamente a nivel '.xml', no hace falta recompilar nuestro código en Python. Es decir, no es necesario reiniciar el servicio de Odoo.
* Desarrollamos de manera jerarquica y ordenada los diferentes apartados de nuestra aplicación, teniendo especial cuidado de mantener una estructura MVC para asegurar el orden.
* Aprendimos a generar registros automáticos que se añadan a la base de datos mientras el módulo se instala. Esta práctica es muy útil y puede aplicarse en diversas situaciones en las que necesitemos de registros específicos para crear funcionalidades desde el primer momento.
* Conocimos el método de herencia que permite interrelacionar modelos para que sus datos interactúen de manera sencilla. Aplicando esta técnica, conseguimos que un módulo propio de Odoo sea capaz de consultar datos de nuestro módulo personalizado.