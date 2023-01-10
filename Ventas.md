# APLICACIÓN INVENTARIO

## **ÍNDICE DE CONTENIDOS**
1. [INTRODUCCION](#introducción)
2. [INSTALACION](#instalación)
3. [TRABAJAR CON LA APLICACIÓN](#trabajar-con-la-aplicación)
   1. [Pedidos](#menú-pedidos)
      1. [Presupuestos](#presupuestos)
      2. [Pedidos](#pedidos)
      3. [Equipo de ventas](#equipos-de-ventas)
      4. [Cliente](#cliente)
   2. [A facturar](#a-facturar)
      1. [Pedidos a facturar](#pedidos-a-facturar)
      2. [Pedidos para aumentar las ventas](#pedidos-para-aumentar-las-ventas)
   3. [Productos](#menú-productos)
   4. [Informes](#menú-informes)
   5. [Configuración](#menú-configuración)
      1. [Ajustes](#ajustes)
      2. [Equipos de ventas](#equipos-de-ventas-configuracion)
      3. [Categorias](#categorias)
   


## **INTRODUCCIÓN**
Una empresa necesita conocer en todo momento las ventas que ha realizado, a quien a vendido, cuantos productos a vendido, asi como el precio que se ha sacado. Una mala gestion de las ventas realizadas puede tener unas consecuencias nefastas para la empresa. 

Como tareas principales que podemos llevar a cabo están:

- Permite crear cotizaciones profesionales en solo un par de minutos.
- Transforma tus cotizaciones en órdenes de ventas.
- Gestiona los contratos
- Los clientes pueden encargarse y acceder a sus cotizaciones, órdenes de venta y de entrega.


## **INSTALACIÓN**
Lo primero que debemos realizar es la instalación de esta aplicación.
Para tener más control entraremos en modo desarrollador.

Recuerda que puedes entrar al modo desarrollador a través de 
*`Ajustes - Developer Tools - Activar el modo desarrollador`*

o

*`?debug=1 antes de # y depués de ?`*

Recuerda que a través de los …  podemos gestionar actualizar, desinstalar, más información y aprende más. 

Este último siempre es interesante echarlo un vistazo para así poder ver dependencias, y objetos creados (menús, vistas, informes, etc.) 


## **TRABAJAR CON LA APLICACIÓN**
Al entrar en la aplicación de Inventario, nos encontraremos inicialmente con algo como esto. Los 2 pedidos aparecidos en la lista los hemos creado nosotros como prueba.

![barraNavegacion]

Como podemos ver los menús en la parte superior presentan muchas opciones.

Esto que estamos viendo ahora mismo es el tablero principal o dashboard. 
Aquí podemos ver el flujo de trabajo en el que tenemos de la gestión de las ventas.


### ***Menú Pedidos***

En el aparatado de *Pedidos* podemos encontrar 4 secciones diferentes:
* Presupuestos
* Pedidos
* Equipos de ventas
* Cliente

![menu pedidos]

---


### ***Presupuestos***

Podemos apreciar en la imagen de la barra de navegacion que ya hemos creado 2 presupuestos como prueba. En esta seccion se nos muestra una lista de los presupuestos que hemos creado junto al cliente para el que se lo hemos preparado. Al marcar sobre alguno de los presupuestos creados nos permite exportar, suprimir (que seria eliminar), crear facturas o marcar el presupuesto como enviado al cliente. 

![lista presupuestos]


A la hora de crear un presupuesto nos pide informacion para la creacion del mismo: 
* Nombre del cliente
* Fecha de expiracion
* Plazo de pago

Podemos añadir una lista indefinida de productos, asi como la cantidad y el precio pues lo estipulamos nosotros:

![datos presupuestos]

Una vez creado el presupuesto nos saldra la informacion del mismo en formato de pedido de venta.

![lista presupuestos 2]

![datos presupuestos creado]

---


### ***Pedidos***

En el apartado Pedidos nos aparece el listado de todos los pedidos ya esten facturados o sin facturar:

![menu lista pedidos]

---


### ***Equipos de ventas***

En la seccion de equipos de ventas del apartado Pedidos nos aparece todos los equipos de ventas. Para crear un equipo de ventas hay que acceder a `Configuracion - Equipos de ventas`.

![menu equipos]

Al acceder sobre el equipo de ventas te muestra un grafico sobre los proyectos y ventas llevados a cabo por este equipo. Al clickar sobre los presupuestos u orden para facturar nos mostraria una lista con las ordenes o presupuestos llevados a cabo por este equipo en concreto.

![grafico equipos]

---


### ***Cliente***

En la seccion de clientes nos aparece el perfil de todos los clientes que hay en la base de datos, asi como la opcion de crearlos:

![menu clientes]

En el perfil del cliente podemos modificar sus datos de contacto, asi como si se trata de un individuo o de una compañia, si es un individuo asociado a una compañia los datos de contacto del cliente se rellenan automaticamente con los datos de la empresa. Tambien podemos observar cuantas ventas tiene este cliente asi como el total que ha facturado.

![datos clientes]

---


### ***A facturar***

En el aparatado de *A facturar* podemos encontrar 2 secciones diferentes:
* Pedidos a facturar
* Pedidos para aumentar las ventas

![menu facturar]

---


### ***Pedidos a facturar***

En este apartado solo se muestran los pedidos que aun estan sin facturar:

![menu pedidos a facturar]

---


### ***Pedidos para aumentar las ventas***

En este apartado solo se muestran los pedidos en los que se han entregado mas cantidades de las que los clientes pidieron originalmente pero aun asi terminaron pagando, es decir, lo que se ha cobrado en excendente.

![menu pedidos aumentar]

---



### ***Menú Productos***

El aparatado de productos muestra la cantidad de productos que tenemos en el catalogo (Podemos maracar nuestros productos favoritos).

![menu productos]

Este seria los datos del perfil de cada producto:

![datos productos]

En esta pantalla puedo cambiar los diferentes parametros que la confrorman, indicando propiedades como:

* Nombre
* Si puede ser vendido o puede ser comprado, porque aqui hay tanto productos que nosotros vendemos como productos que nosotros compramos.
* Tipo de producto (si es consumible o un servicio)
* Politica de facturacion. Establece si se factura segun lo pedido o lo entregado. 
* El precio de venta.
* Impuesto.
* El coste total (impuestos incluidos).
* Categoria perteneciente del producto.
* Referencia.
* Codigo de barras.
* Etiqueta de producto.

---

### ***Menú Informes***

El aparatado de informes es un análisis de sus presupuestos y pedidos de venta. El análisis verifica los ingresos de sus ventas y las ordena por diferentes grupos de criterios (comercial, contacto, producto, etc.)..
Si no hemos realizado ninguna venta este es el resultado.

![menu informes]

Cuando especificamos un equipo de ventas, aparece el analisis de ventas de ese equipo en concreto:

![grafico equipos]

---



### ***Menú Configuración***

En primer vamos a hechar un vistazo a las posibles configuraciones que tiene esta aplicación.

![menu configuracion]

---

### ***Ajustes***

Para acceder a esta seccion hay que acceder a `Configuración - Ajustes`

Desde aquí podemos hacer todos los ajustes de esta aplicación, el comportamiento general de esta.

![configuracion ajustes]

Comentemos alguna de las opciones que aparecen

  ***Catalogo del producto***
  Me permite gestionar las opciones para el catalogo de productos como las unidades de medida de venta y compra o los atributos de los productos.

  ***Precio***
  Establece requisitos y condiciones para el cambio del precio a la hora de realizar las ventas. Permite, ademas, crear e infomar de promociones asi como descuentos.

  ***Presupuestos y Pedidos***
  Configuraciones relacionadas con la creacion de presupuestos y la realizacion de los pedidos. 

  ***Envio***
  Gestion de las formas de envio de los pedidos

  ***Facturacion***
  Establece los criterios que entran en funcionamiento a la hora de crear las facturas.

  ***Conectores***
  Permite la sincronizacion exclusiva con Amazon

---


### ***Equipos de ventas Configuracion***

Para llevar a cabo la gestión de los equipos de ventas lo tenemos que realizar a través de 
`Ventas - Configuración - Equipos de ventas`

Nos muestra una lista de los equipos de ventas creados al realizar una venta. 

![configuracion equipos]

Al pulsar sobre crear o el nombre de uno de los equipos te permite modificar los datos del equipo. Te permite establecer datos como el lider del equipo, los miembros del equipo (añadir, modificar y eliminar) y cuanto es la meta de ventas para este mes:

![datos equipos]

---


### ***Categorias***

En esta seccion, se permite la creacion de categorias para los productos, se accede a traves de  
`Ventas - Configuración - Categorias`
A la hora de editar las categorias solo puedes cambiar el nombre y el color de la misma.

![configuracion categorias]

![datos categorias]






[barraNavegacion]: imagenes_ventas/barra_navegacion.PNG "Situación inicial Ventas"
[menu pedidos]: imagenes_ventas/menu_pedidos.PNG "Menu pedidos"
[lista presupuestos]: imagenes_ventas/lista_presupuestos.PNG "Lista presupuestos"
[datos presupuestos]: imagenes_ventas/datos_presupuestos.PNG "Datos presupuestos"
[lista presupuestos 2]: imagenes_ventas/lista_presupuestos_2.PNG "Lista presupuestos 2"
[datos presupuestos creado]: imagenes_ventas/datos_presupuestos_creado.PNG "Datos presupuestos creado"
[menu productos]: imagenes_ventas/menu_productos.PNG "Menu productos"
[datos productos]: imagenes_ventas/datos_productos.PNG "Datos Productos"
[menu informes]: imagenes_ventas/menu_informes.PNG "Menu informes"
[menu configuracion]: imagenes_ventas/menu_configuracion.PNG "Menu configuracion"
[configuracion ajustes]: imagenes_ventas/configuracion_ajustes.PNG "Configuracion Ajustes"
[configuracion equipos]: imagenes_ventas/configuracion_equiposdeventas.PNG "Configuracion Equipos"
[datos equipos]: imagenes_ventas/datos_equipos.PNG "Datos Equipos"
[configuracion categorias]: imagenes_ventas/configuracion_categorias.PNG "Configuracion Categorias"
[datos categorias]: imagenes_ventas/datos_categorias.PNG "Datos Categorias"
[menu clientes]: imagenes_ventas/menu_clientes.PNG "Menu Clientes"
[datos clientes]: imagenes_ventas/datos_clientes.PNG "Datos Clientes"
[menu equipos]: imagenes_ventas/menu_equiposdeventas.PNG "Menu Equipos de ventas"
[grafico equipos]: imagenes_ventas/grafico_equipos.PNG "Grafico Equipos de ventas"
[menu facturar]: imagenes_ventas/menu_afacturar.PNG "Menu Facturar"
[menu pedidos a facturar]: imagenes_ventas/menu_pedidosfacturar.PNG "Menu Pedidos a Facturar"
[menu pedidos aumentar]: imagenes_ventas/menu_pedidosaumentar.PNG "Menu Pedidos a aumentar"
[menu lista pedidos]: imagenes_ventas/menu_listapedidos.PNG "Menu Lista Pedidos"