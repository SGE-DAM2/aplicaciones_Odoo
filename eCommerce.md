# APLICACIÓN INVENTARIO

## **ÍNDICE DE CONTENIDOS**
1. [INTRODUCCION](#introducción)
2. [INSTALACIÓN](#instalación)
3. [TRABAJAR CON LA APLICACIÓN](#trabajar-con-la-aplicación)
   1. [Editando la página web](#editando-la-pagina-web)
   2. [Crear un banner](#crear-un-banner)
   3. [Sección eCommerce](#seccion-ecommerce)
   4. [Creación de productos](#creacion-de-productos)
   5. [Crear una nueva categoría](#crear-una-nueva-categoria)
   6. [Asignar categoría a producto](#asignar-categoria-a-producto)
   7. [Creación de pedidos](#creacion-de-pedidos)
   8. [Clientes](#clientes)
   9. [Conclusión](#conclusión)

## **INTRODUCCIÓN**
La sección eCommerce nos va a ayudar a que podamos vender nuestros productos de manera rápida y cómoda en linea añadiendolos a nuestra página web.

Podremos:

- Vender productos en linea.
- Controlar las ventas dependiendo del stock.
- Aplicar ofertas durante periodos concretos de tiempo.

Como ya he dicho, esta aplicación necesita primero de una página web para poder vender en ella y una sección inventario nos va a ayudar para poder mantener control del stock y declarar que podemos vender y que no.

## **INSTALACIÓN**
En nuestro caso durante la propia creación de la empresa ya nos muestra la posibilidad de añadir la aplicación de eCommerce, por lo que vamos a aprovechar durante este paso


![instalacion] 

## **TRABAJAR CON LA APLICACIÓN**
Al entrar por primera vez en la sección de sitio web (la aplicación de eCommerce necesita de esta sección)

![eCommerce]

Obviamente es muy sosa y no tiene nada añadido, así que lo primero será hacer caso a lo que nos dicen y pulsar en el botón editar.

### Editando la página web

Como se puede ver un menú aparece al lado derecho de la pantalla y nos permite empezar a añadir bloques a la página web. Como solo necesitas una web básica, vamos a usar el ejemplo de los banner para explicar como añadir bloque desde el menú editar.
[menu_editar]

### ***Crear un banner***

El banner nos va a permitir crear una pagina de entrada a nuestra web, dando un aspecto más profesional y preparando a los que vengan para lo que pueden esperarse

`Editar - Arrastrar el bloque "Banner"`

Una vez lo tengamos en la pagina podemos empezar a editar los textos para que se parezcan más a lo que queremos

[banner]

### ***Sección eCommerce***

Lo primero será acceder a la propia sección eCommerce, la cual encontraremos bajo un menú contextual en la barra superior de nuestro odoo

[menueCommerce]

Lo primero para poder trabajar con ello será crear productos,si no hay que vender no podemos ponerlo en nuestra página asi que vamos a ello.




### ***Creación de productos***

La primera vez que accedamos a la sección de productos estará en blanco y deberemos empezar a crear productos nuevos:
[productosBlanco]

Arriba a la izquierda encontramos el botón de crear, los cual nos moverá a la siguiente pantalla

[productoNuevo1]

A la hora de crear un nuevo producto para vender podemos modificar:
- Imagen
- Nombre
- Tipo de producto y facturación
- Precio e impuestos
- Categoria
- Referencias y codigos de producto

En el caso de la imagen que he mostrado ya se han editado algunos de los campos para ver lo que se puede hacer.

A su vez se puede ver que hay una categoriá para ventas y contabilidad pero contabilidad se encuentra vacía y en ventas no podemos editar la categoria eCommerce del producto hasta que la creemos, por lo que vamos a dar click en el boton "Crear" arriba a la derecha para continuar.

[productoNuevo2]

Si volvemos a nuestra seccion productos veremos que no nos aparece, eso es porque aun no ha sido publicado y debemos desactivar en la barra de busqueda el filtro.

[productoNuevo3]

Para publicarlo podemos voler a entrar en el producto y darle a la opcion "Ir a sitio web" que se encuentra sobre la imagen del producto, una vez alli en la esquina superior derecha veremos un interruptor en rojo que pone "No publicado" y debemos cambiar. También se puede aprovechar este momento para saber como van a ver los clientes nuestro producto en la web.

[productoNuevo4]

Ya hemos publicado nuestro primer producto, ahora toca definir una nueva categoría eCommerce para él.

### ***Crear una nueva categoría***

Al igual que a la hora de crear un nuevo producto cuando en el submenú de eCommerce accedamos a la opción "Categorías eCommerce" la pantalla será la misma que con los productos y al estar vacía nos pedirá crear una categoría nueva.

[categoríaNueva]

Como se puede ver la creación de una categoría es increiblemente simple, solo debemos añadir nombre, imagen y en el caso de que lo tenga la categoría padre.

[categoríaNueva2]

Al volver de nuevo a la sección "Categorías eCommerce" ya no estará vacía, si no que encontraremos la que acabamos de crear (informática en mi caso).

### ***Asignar categoría a producto***

Una vez tengamos una categoría creada y un producto lo podremos añadir no importa si es nuevo o ya esta creado. En nuestro caso como ya está hecho el ordenador vamos a entrar al producto, movernos a la sección ventas que vimos antes y modificar su categoría eCommerce para que sea "Informática"

[productoCategoria]


### ***Creación de pedidos***

Lo primero que podemos hacer con nuestros productos y categorías creados es hacer un pedido para uno de nuestros clientes. Por ahora utilizaremos uno de los que se crean automáticamente, más adelante crearemos un cliente nuevo personalizado.

[nuevoPedido]

Una vez en la pestaña pedidos la veremos completamente desierta como las anteriores, así que nuestro primer movimiento será crear un nuevo pedido.

[nuevoPedido2]

De nuevo me he tomado la libertad de rellenar algunos de los datos que nos pide para que se entienda mejor.
En cliente arriba del todo podemos escoger el que más nos interese de los que tengamos guardados y nos rellenará el resto de campos con sus datos. Expiración y plazos de pago se definen con su propio nombre, pero lo más importante es la pestaña "Lineas de pedido". En esta sección es donde podremos añadir manualmente la cantidad, unidades y precio de los productos que queramos vender.

[nuevoPedido3]

Por otro lado la sección "otra información" se sale un poco más de nuestro ámbito, pero nos permitira tener control sobre datos como quien ha vendido el producto (En este caso Julio se lo ha vendido a si mismo), su departamento, que tipo de confirmación queremos o ya cosas más complejas como la posición fiscal o de donde ha obtenido el cliente la información sobre el producto (campaña publicitaria).

Una vez lo tengamos todo listo le daremos al boton de confirmar en la parte superior, lo que nos permitira avanzar a la fase de creación de facturas:

[nuevoPedido4]
[nuevoPedido5]

Si después le damos a crear factura nos abrira esta ventana preguntandonos que tipo de factura queremos.
Tras seleccionar factura normal y que nos la muestre nos moveremos a la pantalla de la factura (se ve casi igual que el pedido) y podremos de nuevo confirmar el borrador arriba a la izquierda para por fin terminar con el pedido.

[nuevoPedido6]
[nuevoPedido7]

Con lo que hemos hecho todavía no hemos creado ningún pago, por lo que en la ultima ventana que nos hemos quedado deberemos pulsar la opción "Resgistrar pago" y rellenar los datos que se muestran en esta imágen:

[nuevoPago]

Ahora ya por fin habremos terminado con el pedido y ya solo quedaría la parte de enviarle el producto al cliente que lo ha pedido y eliminar el objeto del inventario, pero de eso se encargan otras categorías.

### ***Clientes***

Como vimos en el apartado anterior a la hora de crear un pedido necesitamos un cliente para que lo compre, por lo que nuestro último apartado va a tratar sobre como podemos crear uno.

Primero de todo vamos a ir a la sección clientes en el menú eCommerce para poder ver los que tenemos creados, en este caso ya tenemos dos hechos de base pero vamos a darle al botón "Crear" para hacer uno nuevo.

[clientes]

[nuevoCliente]

Como se puede ver la he vuelto a rellenar de antemano para que podamos ver bien las posibilidades de cada categoría. En este caso la pestaña "contactos y direcciones" me la voy a saltar porque te permite añadir más direcciones como la que ya se pueden ver en la parte de arriba.

Ahora ya hablando sobre el cliente, podemos darle nombre, imagen, diferenciar entre empresa o privado y añadir todos los datos de dirección y contacto que necesitemos. Dentro de la pestaña "Venta y compra" podemos añadir información como la que ya vimos a la hora de crear el pedido ya que al seleccionar el cliente nos permitirá autorrellenarlo cuando hagamos nuevos pedidos.

[nuevoCliente2]

"Facturación y contabilidad" como su nombre deja adivinar nos va a permitir controlar las cuentas bancarias que el cliente tiene asociadas.
Por ultimo "Notas internas" nos lo podemos saltar porque son simplemente notas así que con darle al botón "Crear" ya tendremos nuestro nuevo cliente hecho.

[nuevoCliente3]

### ***Conclusión***
Tras haber visto casi todo lo que se puede hacer con eCommerce ("Ordenes sin pagar" y "Carros abandonados" no podemos trabajar con ellas ya que debenden de cuentas bancarias y clientes usando la página) queda bastante claro que la función de esta aplicación es ayudar con todo lo relacionado a las ventas online, pero para funcionar necesita apoyarse en muchas otras como la página web, el intentario, etc...

Es decir, que por si sola solo vale para hacer facturas así que sin una empresa sólida en la que basarse no nos va a valer de mucho. Pero si la base es buena te va a dejar acelerar mucho el ritmo de trabajo y facilitar todas las ventas que hagas a traves de la página web. 




[banner]: imagenes_eCommerce/banner.PNG 
[categoríaNueva]: imagenes_eCommerce/categoriaNueva.PNG 
[categoríaNueva2]: imagenes_eCommerce/categoríaNueva2 
[clientes]:  imagenes_eCommerce/clientes.PNG 
[eCommerce]: imagenes_eCommerce/eCommerce.PNG 
[instalación]: imagenes_eCommerce/instalacion.PNG
[menu_editar]: imagenes_eCommerce/menu_editar.PNG
[menueCommerce]: imagenes_eCommerce/menueCommerce.PNG
[nuevoCliente]: imagenes_eCommerce/nuevoCliente.PNG
[nuevoCliente2]: imagenes_eCommerce/nuevoCliente2.PNG
[nuevoCliente3]: imagenes_eCommerce/nuevoCliente3.PNG
[nuevoPago]: imagenes_eCommerce/nuevoPago.PNG 
[nuevoPedido]: imagenes_eCommerce/nuevoPedido.PNG 
[nuevoPedido2]: imagenes_eCommerce/nuevoPedido2.PNG 
[nuevoPedido3]: imagenes_eCommerce/nuevoPedido3.PNG 
[nuevoPedido4]: imagenes_eCommerce/nuevoPedido4.PNG 
[nuevoPedido5]: imagenes_eCommerce/nuevoPedido5.PNG 
[nuevoPedido6]: imagenes_eCommerce/nuevoPedido6.PNG 
[nuevoPedido7]: imagenes_eCommerce/nuevoPedido7.PNG
[productoCategoria]: imagenes_eCommerce/productoCategoria.PNG 
[productoNuevo1]: imagenes_eCommerce/productoNuevo1.PNG 
[productoNuevo2]: imagenes_eCommerce/productoNuevo2.PNG 
[productoNuevo3]: imagenes_eCommerce/productoNuevo3.PNG
[productoNuevo4]: imagenes_eCommerce/productoNuevo4.PNG
[productosBlanco]: imagenes_eCommerce/productosBlanco.PNG
