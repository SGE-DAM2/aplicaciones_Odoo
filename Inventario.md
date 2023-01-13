# APLICACIÓN INVENTARIO

## **ÍNDICE DE CONTENIDOS**
1. [INTRODUCCION](#introducción)
2. [INSTALACIÓN](#instalación)
3. [TRABAJAR CON LA APLICACIÓN](#trabajar-con-la-aplicación)
   1. [Como funciona internamente el inventario](#como-funciona-internamente-el-inventario)
   2. [Menú configuración](#menú-configuración)
   3. [Gestión de almacenes](#gestión-de-almacenes)
   4. [Gestión de ubicaciones](#gestión-de-ubicaciones)
   5. [Crear una categoría de productos](#crear-una-categoría-de-productos)
   6. [Crear un nuevo producto ](#crear-un-nuevo-producto)
   7. [Crear una regla de abastecimiento](#crear-una-regla-de-abastecimiento)
   8. [Generar informes y exportar datos](#generar-informes-y-exportar-datos)
   9. [Relación entre aplicación Inventario - Compras - Ventas](#relación-entre-aplicación-inventario---compras---ventas)
   10. [Conclusión](#conclusión)

## **INTRODUCCIÓN**
Una empresa necesita conocer en todo momento el número de productos que tiene almacenados. El tener exceso de ellos o defecto puede tener unas consecuencias nefastas para ella. Esta aplicación nos va a permitir llevar a cabo la gestión del stock.

Como tareas principales que podemos llevar a cabo están:

- Productos y categorías.
- Gestión de los almacenes.
- Stock de productos.
- Trazabilidad.
- Proporciona informes en tiempo real 

Esta aplicación está integrada con otras, en concreto con Ventas, Compras y Contabilidad. (esto lo veremos en una [sección](#relación-entre-aplicación-inventario---compras---ventas) posteriormente)

## **INSTALACIÓN**
Lo primero que debemos realizar es la instalación de esta aplicación.
Para tener más control entraremos en modo desarrollador.

Recuerda que puedes entrar al modo desarrollador a través de 
*`Ajustes - Developer Tools - Activar el modo desarrollador`*

o

*`?debug=1 antes de # y depués de ?`*

Recuerda que a través de los …  podemos gestionar actualizar, desinstalar, más información y aprende más. 

Este último siempre es interesante echarlo un vistazo para así poder ver dependencias, y objetos creados (menús, vistas, informes, etc.) 


![inventario] 
![inventario2]

## **TRABAJAR CON LA APLICACIÓN**
Al entrar en la aplicación de Inventario, nos encontraremos inicialmente con algo como esto

![inventario3]

Como podemos ver los menús en la parte superior presentan muchas opciones entre las que se incluyen esas generales que he mencionado al principio.

Esto que estamos viendo ahora mismo es el tablero principal o dashboard. 
Aquí podemos ver el flujo de trabajo en el que tenemos de la gestión de nuestros productos.

* lo que nos llega
* lo que sale de nuestros almacenes, por ejemplo por venderlo
* las devoluciones porque por ejemplo haya un producto que no sea de la satisfacción del usuario.

Cada uno de los paneles que se muestran se pueden configurar a través de los 3 puntos de la parte superior derecha.

### Como funciona internamente el inventario

La forma de trabajar es muy sencilla. Parto de una cantidad de productos que entran, adquiridos de alguna manera. Cuando los vendo tienen que salir y por lo tanto tendré que restarlos de los que tenía en el inventario, quedando menos para vender.

Esta forma de trabajar como luego veremos hace que este módulo esté intimamente relacionado con el módulo de compras y el de ventas.

### ***Menú Configuración***

En primer vamos a hechar un vistazo a las posibles configuraciones que tiene esta aplicación. Para ello podemos entrar a través de

`Configuración - Ajustes`

![[menu configuracion]][inventario10]

Desde aquí podemos hacer todos los ajustes de esta aplicación, el comportamiento general de esta.

![ajustes][ajustes]

Comentemos alguna de las opciones que aparecen

  ***Operaciones***
  Me permite gestionar las operaciones que son necesarias realizar dentro del inventario como por ejemplo fecha del inventario anual.

  ***Código de barras***
  Habilita el uso de ellos, ya que se usan habitualmente para dar entrada y sallida de productos de una forma agil.

  ***Envío***
  Configuraciones realacionadas con este como por ejemplo el envío de un correo electrónico al cliente cuando le enviemmos un producto. Esto os sonará de cuando compráis algun producto en Amazon por ejemplo y os llega que el mensaje 
  >Su producto ha sido enviado

***Conectores de envío***
Gestión de las principales compañías de paquetería.

***Productos***
Gestionar las características de los diferentes productos que tengo.

Por ejemplo en variantes, puedo indicar aunque sea el mismo producto que puede tener diferentes características, como pueden ser los colores de una silla.

Por ejemplo si nos fijamos en unidades de medida que es algo que usamos habitualemente, podemos una vez clickeadas.

![ajustes_productos][ajustes_productos]

Entramos a `Unidades de medida`

![categoria_unidades][categoria_unidades]

Como vemos hasta podemos crearnos nuevas unidades.

***Trazabilidad***
Me permite seguir el rastro del producto desde su origen hasta su entrega

***Almacen***
Nos permite gestionar los lugares dónde voy a guardar los productos que yo vendo.



Veamos ahora algunas de las tareas más habituales que se realizn en un manejo básico del inventario.

---


### ***Gestión de almacenes***

Para llevar a cabo la gestión de almacenes lo tenemos que realizar a través de 
`Inventario - Configuración - Almacenes`

Observa en la imagen que el por defecto ya me ha creado uno con el nombre de mi empresa.

![almacenes][almacen]

si clickeamos sobre el podemos ver la información al respecto


![almacen_datos][almacen_datos]

Aquí podemos ver las diferentes opciones como 

* nombre completo.
* nombre corto (importante para gestionarlo)
* Como gestionar las recepciones y los envios de productos. Ambos tiene las mismas opciones de pasos(podemos hacerlo directamente recibir y guardar, hacerlo en dos pasos osea pasa por una área intermedia, pro ejemplo para empaquetado, etc. Po r último en tres pasos.)

Si vais pinchando en cada una de las opciones, te permite saltar directamente a cambiar datos. Por ejemplo *Dirección* si quiero pinchando en la flecha

![direccion_almacen][direccion_almacen]

---

### ***Gestión de ubicaciones***

Las ubicaciones son los lugares donde dentro de un almacen voy a ubicar las diferentes mercancias.

Para llevar a cabo la gestión de ubicaciones lo tenemos que realizar a través de 
`Inventario - Configuración - ubicaciones`

![ubicaciones][ubicaciones]

Si hago un clic sobre una de ellas en este caso solo tengo una lo que hago es ver una pantalla de configuración como la siguiente

![ubicacion_configuracion][ubicacion_configuracion]

En esta pantalla puedo cambiar los diferentes paraametros que la confrorman, indicando propiedades como:

* Nommbre
* Ubicación padre
* Tipo de ubicación. Si es interna, está en el proveedor, en producción etc.
* Código de barras
* Logistica. Esta se peude aplicar tanto a ala entrada como a la salida. La ques aplique FIFO, LIFO, etc para gestionar como entran y salen.
* Ciclo de inventario. Cada cuanto se hace y cuando toca el siguiente.

Además de esto en la parte superior tengo dos opciones
* Reglas de estrategia de traslado. Que me permite indicar que producto, cuando llega, subdivision donde almacenar, etc.
* Stock actual.

En cualquier momento puedo crear una ubicación nueva. 
Además fijate que existen ? en muchos lugares que nos dan una ayuda en forma de pop-up sobre lo que puedes realizar.

---


### ***Crear una categoría de productos***

El objetivo es crear una categoría de productos. Esto nos permitirá tener una clasificación de nuestros productos mucho más eficiente.Es una organización jerarquica como podemos observar. Hay categoría padre, hijo, nieto etc.

Para llevar a cabo la creación de una nueva categoría lo tenemos que realizar a través de 
`Inventario - Configuración - Categoría de productos`

Esto como vemos en la imagen es muy facil de llevar a cabo
![categoria_productos][categoria_productos]

Por defecto nos vienen 3 ya creadas.

En nuestro ejemplo como puedes ver en la imagen inferior hemos creado una categoría llamada *hardware*.

Como vemos podemos indicar una serie de características, como de quien es hijo esta categoría, para poder organizarlas de forma anidada. También la logística a aplicar, así como la indicación de la manera de realizar la valoración del inventario.

![creacion_categoria_producto][creacion_categoria_producto]

Podemos observar una serie de propiedades que he debido definir durante la definición de dicha categoría.

Una vez que la categoría ha sido creada con susu propiedades, indicándole por ejemplo quien es la categoria padre, dónde va a estar almacenada, etc. Estoy en situación de agregar productos a esta.

---

### ***Crear un nuevo producto***

Una vez definida la categoría, vamos a crear un producto y lo vamos a añdir a la categoría que creamos con anterioridad.

Para llevar a cabo la creación de un nuevo producto lo tenemos que realizar a través de 
`Inventario - Productos - Productos`
Este nuevo producto será una placa base

![producto][producto]

Vemos que tenemos muchas opciones a la hora de configurarlo. 

Como podemos observar a la hora de crear este nuevo producto, nos aprecen muchisimas opciones para poder particularizarle. Entre estas podemos observar:
* Si se vende o compra o ambas
* Categoría a la que pertenece
* Precio.
* Stock.
* Impuestos
* Etc

Nosotros hemos configrado los aspectos básicos de este producto como puedes ver

Al crear el producto me doy cuenta que una categoría tan generica como Hardware no me vale, por lo que directamente desde el nuevo producto me creo otra nueva categoría.

![categoria_placa][categoria_placa]

Como podemos ver en la imagen podemos gestionar las cantidades de estos productos

![cantidad_producto][cantidad_producto]

---

### ***Crear una regla de abastecimiento***

Una regla de abastecimiento tiene com principal cometido el indicar como queremos estar abastecidos en nuestra empresa de un determinado producto. De tal manera que si yo me quedo por debajo del minimo, en el módulo de compra se realizará directamente una compra de este producto.

Para crear una regla de abastecimiento debo ir al menú `Configuración- Reglas de abastecimiento`

![regla_abastecimiento][regla_abastecimiento]

Aquí vemos como puedo crear para ese producto unos límites máximos y mínimos de stockaje, de tal forma que seamos abastecidos en el momento que lleguemos a ese límite mínimo o bién examinemos cual es la razón por la que tenemos exceso de dicho producto.

---


### ***Generar informes y exportar datos***

Existen muchos informes que podemos obtener en esta aplicación.

Para acceder a la generación de Informes tenemos a tal efecto un menú llamado *Informes*
Además tenemos las opciones de exportación de datos que se nos presentan con la posibilidad de realizarlas en diferentes formatos. 
En la imagen podemos ver esta última posibilidad en XLSX o CSV a elegir.

![informe][informe]

Recordad que para poder realizar informes en formato pdf es necesario tener instalado wkhtmltopdf (https://wkhtmltopdf.org/downloads.html). En esta instalación de Odoo para Windows yo aún no lo había instalado y por esa razón solo me da opción de exportarlos a xls o CSV.

---


### ***Relación entre aplicación Inventario - Compras - Ventas***

Como ya comenté anteriormenete existe una clara realación entre estas tres aplicaciones, dado que una empresa compra productos a un proveedor (del tipo que sean, en los ejemplos productos hardware), los necesita inventariar y almacenarlos (aplicación inventario) y por último los vende a un cliente (aplicación ventas)

Voy a realizar una compra de placas base que es el único producto que tengo. Para ello creo desde la aplicación de compras una solicitud de presupuesto.

![solicitud_compra][solicitud_compra]

Observa como al crearla, se crae simultaneamente una comunicación que se envia al vendedor que en este caso soy yo mismo, para no complicar el ejemplo.

Como puedes ver se acompaña de un [pdf](Albaran.pdf).

Si lo confirmamos y damos por buena la compra

![confirmar_pedido][confirmar_pedido]



Si volvemos a la aplicación de Inventario, veremos que tenemos para procesar una nueva solicitud

![recepcion_comprar][recepcion_comprar]

Si hacemos un clic procesar, vemos que es lo que tenemos a procesar y nos da un resumen de ello.

![muestra_recepcion][muestra_recepcion]

Luego si volvemos a compras tendriamos que seguir con el flujo correspondiente  `recibir productos - validar - etc`

---

### ***Conclusión***
Como vemos esta es una de las aplicaciones más usadas e importantes en una empresa, dado que lo normal es que haya un lugar dónde guardar y almacenar los productos.




[inventario]: imagenes_inventario/inventario_logo2.jpg "icono de inventario"
[inventario2]: imagenes_inventario/inventario2.jpg "icono de inventario"
[inventario3]: imagenes_inventario/inventario3.jpg "Situación inicial inventario"
[inventario4]: imagenes_inventario/inventario4.jpg "Creación categoria porductos" 
[inventario10]: imagenes_inventario/menu%20configuracion.jpg "Menú de configuración"
[ajustes]: imagenes_inventario/ajustes.jpg
[ajustes_productos]: imagenes_inventario/ajustes_productos.jpg
[categoria_unidades]: imagenes_inventario/Categoria_unidades.jpg
[almacen]: imagenes_inventario/alamcenes.jpg
[almacen_datos]: imagenes_inventario/almacen_datos.jpg
[direccion_almacen]: imagenes_inventario/direccion_almacen.jpg
[ubicaciones]: imagenes_inventario/ubicaciones.jpg "imagen de ubicaciones"
[ubicacion_configuracion]: imagenes_inventario/ubicacion_configuracion.jpg "configuración de las ubicaciones"
[categoria_productos]: imagenes_inventario/categoria_productos.jpg "categoria de productos"
[creacion_categoria_producto]: imagenes_inventario/creacion_categoria_productos.jpg "Creación de una nueva categoria de productos"
[categoria_placa]: imagenes_inventario/categoria_placa.jpg "categorias creadas"
[producto]: imagenes_inventario/producto.jpg "producto creado"
[regla_abastecimiento]: imagenes_inventario/regla_abastecimiento.jpg "imagen reglas de abastecimiento"
[cantidad_producto]: imagenes_inventario/cantidad_producto.jpg
[informe]: imagenes_inventario/informe.jpg "exportación de productos de inventario"
[solicitud_compra]: imagenes_inventario/solicitud_compra.jpg "Solicitud de compra de placas base"
[recepcion_comprar]: imagenes_inventario/Recepcion_compra.jpg "panel central de inventario con la compra a procesar"
[muestra_recepcion]: imagenes_inventario/muestra_recepcion.jpg "detalle de la recepción que se espera"
[confirmar_pedido]: imagenes_inventario/confirmar_pedido.jpg
