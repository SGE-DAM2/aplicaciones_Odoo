# Aplicación: **Punto de venta**
## **ÍNDICE**
## [Aplicación: **Punto de venta**](#aplicación-punto-de-venta)
1. [**ÍNDICE**](#índice)
2. [INTRODUCCIÓN](#introducción)
3. [USO DE LA APLICACIÓN](#uso-de-la-aplicación)
    - [Cómo funciona](#cómo-funciona)
    - [Configuración](#configuración)
    - [Control de apertura](#control-de-apertura)
    - [Funcionalidad](#funcionalidad)
      - [Productos](#productos)
      - [Clientes](#clientes)
      - [Reembolsos](#reembolsos)
      - [Información del pedido](#información-del-pedido)
      - [Modificar pedido](#modificar-pedido)
      - [Realizar pago](#realizar-pago)
4. [CONCLUSIÓN](#conclusión)


---

## INTRODUCCIÓN

La aplicación de Odoo ***punto de venta*** permite dirigir tiendas, restaurantes, o cualquier negocio de manera muy sencilla. Esta aplicación requiere de internet para iniciarse, pero puede seguir funcionando incluso si se pierde la conexión.  

![app_punto_venta]  

Es compatible con todo tipo de hardware, no requiere de instalación ni de hardware específico.  
Utiliza una interfaz inteligente que cualquier empresa minorista puede usar de manera sencilla. Además, es extremadamente flexible, por lo que cualquiera puede adaptarla a sus propias necesidades.  
A su vez, esta aplicación se encuentra integrada con otras aplicaciones de las que dispone Odoo, lo que facilitará todavía más su uso:

- **Marketing por correo electrónico**
- **Inventario**
- **Ventas**

Entre las cosas que permite realizar esta aplicación encontramos:
- **Para tiendas**
  - [Gestión integrada del inventario](https://www.odoo.com/es_ES/app/inventory) 
  - [Facturar](https://www.odoo.com/documentation/14.0/es/applications/sales/point_of_sale/shop/invoice.html)
  - [Imprimir recibos](https://www.odoo.com/documentation/14.0/es/applications/sales/point_of_sale/shop/reprint.html)
- **Para restaurantes**
  - [Gestionar las mesas](https://www.odoo.com/documentation/14.0/es/applications/sales/point_of_sale/restaurant/restaurant.html)
  - [Imprimir órdenes en la cocina o el bar](https://www.odoo.com/documentation/14.0/es/applications/sales/point_of_sale/restaurant/kitchen_printing.html)
  - [Integrar propinas en los pagos](https://www.odoo.com/documentation/14.0/es/applications/sales/point_of_sale/restaurant/tips.html)

---

## USO DE LA APLICACIÓN

Lo primero que veremos al acceder a la aplicación ***punto de venta*** será la pantalla de inicio vacía.  

![inicio_punto_venta]  

En esta pantalla a simple vista podemos observar unas pocas opciones de filtrado, según determinados **filtros**, por **grupos** o los **favoritos**.  

También podemos seleccionar en los dos botones cuadrados a la derecha el formato de vista:  
**Bloques**  

![bloque]

**Lista**  

![lista]  

Además de que cuenta con una **barra de búsqueda**:
![barra_busqueda]  

---

## Cómo funciona  

El ***Punto de Venta*** permite **vender tus productos** tanto de forma *online* como *offline* desde cualquier dispositivo, además de **registrar los movimientos de productos** de tu inventario y generar **estadísticas en tiempo real**.  

---

## Configuración  

En la parte superior de la aplicación nos aparecerá la opción de configuración, con sus distintas opciones.

![configuracion]  

Ahora vamos a explorar estas ocpiones a ver qué ofrecen.

`Ajustes`  

Desde esta opción podrás configurar los aspectos básicos de este módulo.

![ajustes]

- ### **Interfaz**  

Permite modificar la interfaz del módulo según los intereses del usuario, facilitando el acceso a la información que se requiera.  

![interfaz]  

- ### **Contabilidad**  

Sirve para ajustar las opciones de contabilidad, el IVA, impuestos o los datos para órdenes y facturas.

![contabilidad]

- ### **Precio**  

Aquí se encuentran las principales opciones para regular los precios de los productos registrados, gestionar descuentos, promociones, entre otras cosas.

![precio]  

- ### **Pagos**  

Aquí se gestionan todas las opciones relacionadas con el tema de los pagos, qué métodos de pagos se aceptan, a través de que dispositivos se pueden efectuar pagos, monedas que se podrán usar...  

![pagos]  

- ### **Inventario**  

Se puede gestionar el registro de los productos a través del punto de venta, que está directamente comunicado con el módulo de inventario.  

![inventario]  

`Categoría de productos`  

Aquí permite gestionar las categorías de los productos de la tienda, pudiendo editar las categorías existentes, crearlas o borrarlas.  

![categorias]  

---

## Control de apertura

Según creamos una nueva sesión en el punto de venta, lo primero que nos aparecerá será una ventana pequeña en la que podremos pasarle una información inicial. Concretamente, podremos asignar una cantidad de efectivo de apertura y una anotación para la sesión que hemos abierto.  

![control_apertura]  

- Por un lado, la cantidad de efectivo podremos introducirla manualmente  
![efectivo_manual]  

- O también podemos asignar una cantidad determinada de monedas o billetes de distintos valores  
![efectivo_monedas]

  `Si asignamos una cantidad con la segunda opción se nos autocompletará una nota de apertura por defecto.`  
![nota_auto]

- Mantenemos los datos de apertura como se muestra en la imágen anterior y seleccionamos *abrir sesión*. Para esta demostración, he dejado que la aplicación cree unos productos de muestra.  

![punto_de_venta]  

---

## Funcionalidad

Una vez estamos en la ventana principal, vemos que hay diferentes funciones. A la derecha aparecerán todos los productos que haya disponibles, pudiendo filtrarlos según sus categorías.  

![cat_productos]  

### Productos

Podemos añadir, simplemente clicando sobre los productos, aquellos que se vayan a vender y la cantidad que queramos. La propia aplicación nos mostrará ya la información con el precio por unidad y el precio final de cada producto según la cantidad seleccionada, así como el total de todos los productos y lo correspondiente a los impuestos.  

### ![compra_prods]  

### Clientes

En la parte inferior de la última imágen, el botón `Cliente` permite seleccionar, de entre los clientes registrados en la aplicación, aquel que realizará la compra, e incluso se podrá crear un nuevo cliente si aún no está registrado.  

![clientes_compra]  

El botón `Nota del cliente`, por encima del botón de cliente, permitirá guardar en la venta, una información sobre el cliente que se escriba.  

![nota_cliente]  

### Reembolsos

Con la opción de `Reembolso`, se puede acceder a pedidos ya realizados y actuar sobre ellos, pudiendo acceder de nuevo a los datos de **clientes** o a **sus facturas**, **imprimir recibos** de los pedidos, realizar alguna **modificación** o hacer **reembolsos**.  

![reembolsos]

Por último, el botón de `Información` nos ofrece datos más detallados sobre los productos añadidos al pedido.  

### Información del pedido

![info_pedido]

En este caso se muestran los datos sobre uno de los productos de prueba, la estantería pequeña. Podemos ver datos sobre:  

- **Finanzas**: Aparece el precio base del producto por unidad, su costo añadido en el caso de que lo tuviera y la tarifa pública.
- **Inventario**: Como ya mencioné anteriormente, el módulo de Punto de Venta está comunicado directamente con el módulo de Inventario. Gracias a esto, podemos acceder directamente al stock de cada producto registrado desde el Punto de Venta. Así mismo, podremos ver las unidades disponibles de un producto directamente en el momento de gestionar un pedido sin tener que acceder al Inventario.  
- **Pedido**: Aquí aparece el precio base de todo el pedido, así como el costo total que pudiera tener.   

### Modificar pedido

Por último, tenemos tres funciones más en la parte inferior. Estos tres botones serán los de  

> `Cantidad`

> `% Descuento`

> `Precio`  

![tres_opciones]  

Según la opción que tengamos seleccionada, modificaremos un determinado campo del pedido. La opción seleccionada se mostrará con el fondo morado. También se debe tener en cuenta que el campo del pedido a modificar corresponderá al del producto que tengamos seleccionado, el cual se mostrará con un fondo azul claro.  

![prod_seleccionado] 

- **Descuento**: El primer campo a modificar que hemos seleccionado en este caso es el descuento. Si observamos esta imágen, podemos ver que, al asignar un descuento a un producto del 6% como en el ejemplo. En la parte inferior del producto nos indica dicho descuento, además de que se modifica el precio de la [imágen anterior](#compraprods) según el descuento asignado.  

- **Cantidad**: Con esta opción podremos modificar la cantidad incluida en el pedido para el producto que tengamos seleccionado.  

- **Precio**: Aquí modificaremos el precio del producto que tengamos seleccionado del pedido. Es importante destacar ciertos aspectos de esta función: 

  - El precio a modificar es el **precio por unidad**. Es decir, si estableces cierta cantidad para un producto del que quieres vender 2 unidades, el precio total será el doble de la cantidad introducida. 

  - El precio que modifiques será el **precio base** del producto, por lo que a la hora de ver dicho precio en el pedido, la cantidad se verá incrementada según el IVA que esté establecido.  

  - El precio modificado **corresponde únicamente al pedido** que se esté realizando. Mientras que el producto del que modifiques el precio mantendrá su valor inicial. Para modificar ese valor, deberás actuar directamente sobre el producto almacenado en la aplicación de Inventario.  

En este caso, he seleccionado un producto y modificado su precio para que cueste 2€ y seleccionado dos unidades del mismo para el pedido. A continuación se verá como se muestra el valor realmente a partir de mis modificaciones.  

![prod_mod]

### Realizar pago  

Una vez terminamos de rellenar los datos del pedido, se procede a efectuar el pago.  

![realizar_pago]  

Aquí seleccionaremos a la izquierda qué **método de pago** se usará en el pedido, en la parte central indicaremos **la cantidad** que se va a pagar, la cual se mostrará en la parte izquierda. En esta sección, podremos ver el *precio final* del pedido, la *cantidad restante* para pagar el pedido y *el cambio* que se devolverá si se paga de más.  

En la parte de la derecha se mostrarán el cliente que realiza el pedido *(o en caso de que aún no esté seleccionado, nos permitirá ahí mismo seleccionarlo)*, además de las facturas de dicho cliente.  

Finalmente, validamos el pedido y nos aparecerá la siguiente pantalla:  

![validar_pedido]  

En esta pantalla nos aparecerá a la derecha el recibo del pedido que acabamos de realizar y nos da la opción de enviarle por correo electrónico dicho recibo al cliente.  

También tendremos la opción de imprimir el recibo por si nos interesa guardarlo.  
Para esta demostración, se guardará [este archivo](Recibo_Punto_de_Venta.pdf) como PDF.

![imprimir_pdf]

A partir de aquí podemos salirnos de la aplicación, o empezar un nuevo pedido.  

---

## Conclusión  

Gracias al **Punto de Venta**, se pueden realizar de manera sencilla, rápida e intuitiva diferentes pedidos de una empresa, gracias a su conexión directa con los módulos de inventario y clientes, podemos gestionar los productos y clientes de la empresa al mismo tiempo que se realiza el pedido, sin la necesidad de ir alternando entre estos módulos.



[app_punto_venta]: imagenes_punto_venta/app_punto_venta.png "Aplicación punto de venta"
[inicio_punto_venta]: imagenes_punto_venta/inicio_punto_venta.png "Pantalla inicio de punto de venta"
[bloque]: imagenes_punto_venta/bloques_tiendas.png "Vista en bloque"
[lista]: imagenes_punto_venta/listas_tiendas.png "Vista en lista"
[barra_busqueda]: imagenes_punto_venta/barra_busqueda.png "Barra de búsqueda"
[configuracion]: imagenes_punto_venta/configuracion_pdv.png "Configuración"
[ajustes]: imagenes_punto_venta/ajustes_pdv.png "Ajustes"
[interfaz]: imagenes_punto_venta/interfaz_pdv.png "Interfaz"
[contabilidad]: imagenes_punto_venta/contabilidad_pdv.png "Contabilidad"
[precio]: imagenes_punto_venta/precio_pdv.png "Precios"
[pagos]: imagenes_punto_venta/pagos_pdv.png "Pagos"
[inventario]: imagenes_punto_venta/inventario_pdv.png "Inventario"
[categorias]: imagenes_punto_venta/categorias_pdv.png "Categorías de producto"
[control_apertura]: imagenes_punto_venta/control_de_apertura.png "Control de apertura"
[efectivo_manual]: imagenes_punto_venta/efectivo_manual.png "Efectivo"
[efectivo_monedas]: imagenes_punto_venta/efectivo_monedas.png "Monedas y billetes"
[nota_auto]: imagenes_punto_venta/nota_auto.png "Nota automática"
[punto_de_venta]: imagenes_punto_venta/punto_de_venta.png "Pantalla principal"
[cat_productos]: imagenes_punto_venta/cat_productos.png "Categorías de los productos"
[compra_prods]: imagenes_punto_venta/compra_prods.png "Lista de productos a comprar"
[clientes_compra]: imagenes_punto_venta/clientes_compra.png "Clientes registrados"
[nota_cliente]: imagenes_punto_venta/nota_cliente.png "Nota del cliente"
[reembolsos]: imagenes_punto_venta/reembolsos.png "Reembolsos"
[info_pedido]: imagenes_punto_venta/informacion_pedido.png "Información del pedido"
[tres_opciones]: imagenes_punto_venta/tres_opciones.png "Opciones de cantidad, descuento y precio"
[prod_seleccionado]: imagenes_punto_venta/prod_seleccionado.png "Producto del pedido seleccionado"
[prod_mod]: imagenes_punto_venta/precio_modificado.png "Precio de producto modificado"
[realizar_pago]: imagenes_punto_venta/realizar_pago.png "Pantalla para realizar el pago"
[validar_pedido]: imagenes_punto_venta/pedido_finalizado.png "Pedido realizado"
[imprimir_pdf]: imagenes_punto_venta/imprimir_pdf.png "Imprimir el recibo"