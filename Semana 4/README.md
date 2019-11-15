## Laboratorio 04 - Logística
*Alumno: Baldeón Ayala, Willy Alexis*

## Procedimiento

# 4.8 Gestión de Productos
**Configuramos el Stock a mano de nuestro producto Manzana Verde manejando nuestro almacén principal y secundario:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%204/4.8%20Gesti%C3%B3n%20de%20Productos.png)

# 5.6 Importación y exportación masiva de productos
**Modificamos nuestra tabla en Excel para importar nuevos productos:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%204/5.6%20Importaci%C3%B3n%20y%20exportaci%C3%B3n%20masiva%20de%20productos.png)

# 5.9 Importación y exportación masiva de productos
**Una vez se realice satisfactoriamente la importación, los productos cargarán en nuestra base de datos y se mostrarán en el listado de registros:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%204/5.9%20Importaci%C3%B3n%20y%20exportaci%C3%B3n%20masiva%20de%20productos.png)

# 6.7 Ajustes de inventarios.
**Modificamos a la vez todos los Stocks de nuestros productos haciendo uso del Ajuste de Inventario configurado:**  
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%204/6.7%20Ajustes%20de%20inventarios..png)

# 9.1 Tarea
**Habilite las opciones Atributos y variantes, y Unidades de medida. Vaya a la ficha de producto e indique las diferencias, así como adjunte imágenes de productos con varios atributos y/o unidades de medida distintas.**  

![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%204/9.1.1%20Tarea.png)   
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%204/9.1.2%20Tarea.png)   
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%204/9.1.3%20Tarea.png)   
![](https://github.com/WillyBaldeon/Integraci-n-de-Sistemas-Empresariales-Avanzados/blob/master/Semana%204/9.1.4%20Tarea.png)

## Conclusiones:
* Instalamos el módulo **Gestión de Inventarios** para administrar adecuadamente nuestro almacenes y productos. Para ello, habilitamos la configuración *multialmacén* y creamos un almacén secundario.

* Creamos sucursales de venta para un par de compañías. Indicamos la dirección y los clientes encargados. También, relacionamos cada sucursal a un almacén para abastecer sus productos. 

* Creamos **Productos Almacenables** indicando Stock y un almacén. Debido a que activamos el multialmacén, podemos relacionar un mismo producto a distintos almacenes que tengamos configurados y manejar un Stock diferente en cada uno. Los productos almacenables también tienen los campos "A mano", "Previsto" y "Movimientos"; puesto que se tratan como items adquiribles que deben tener un seguimiento.

* Para acelerar el proceso de creación de diversos productos, utilizamos el método **Importar** que vimos en el laboratorio anterior. A través de un archivo **'.csv'** creado en Excel, podemos implementar rápidamente un gran número de elementos a nuestra base de datos. Utilizamos esta característica para agregar algunos productos sin mucho esfuerzo. Así mismo, el módulo nos permite **Exportar** nuestros registros actuales en un archivo **'.csv'** para hacer una clonación o migración efectiva y veloz.

* Habilitamos las opciones de **Atributos, Variantes y Unidades de Medida** para poder manejar más adecuadamente productos que se vendan de distintas maneras. También, nos permite agregar características puntuales para realizar filtros y agrupaciones de productos con pocos clics.
