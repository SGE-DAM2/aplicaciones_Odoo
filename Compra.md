# APLICACIÓN COMPRAS

## **ÍNDICE DE CONTENIDOS**
1. [INTRODUCCION](#introducción)
2. [INSTALACIÓN](#instalación)
3. [TRABAJAR CON LA APLICACIÓN](#trabajar-con-la-aplicación)
   1. [Menú configuración](#menú-configuración)
   2. [Configuración Inicial Recomendada](#configuración-inicial-recomendada)
   3. [Creación de Órdenes de Compras](#creación-de-órdenes-de-compras)
   4. [Recepción de Productos](#recepción-de-productos)
   5. [Creación de la Factura](#creación-de-la-factura)
   6. [Pago a Proveedores](#pago-a-proveedores)
   7. [Informes y Análisis](#informes-y-análisis)
   8. [Integración con el módulo de Ventas  Finanzas y Contabilidad](#integración-con-el-módulo-de-ventas-finanzas-y-contabilidad)
   9. [Conclusión](#conclusión)

---

## **INTRODUCCIÓN**
La aplicación de Compra de Odoo ayuda a llevar un seguimiento de los acuerdos de compra, las cotizaciones y las órdenes de compra. 

Permite automatizar el proceso de reabastecimiento y a llevar un seguimiento tanto de las ofertas de compra como de sus órdenes.

Como taras principales que podemos llevar a cabo están:
- Crear y Gestionar Ordenes de Compras
- Registrar la recepción de productos
- Hacer pagos a Proveedores
- Obtener estadísticas detalladas de las compras realizadas

En el módulo de Compras se pueden establecer los productos que se compran, y se establecen los proveedores con los que se trabaja, también se pueden establecer los términos comerciales internacionales, los impuestos, y la moneda en la que se realizarán las compras.

El módulo se puede integrar con otros módulos de Odoo, como Ventas, Finanzas, Contabilidad, entre otros, lo que permite una mayor eficiencia en el control y gestión de la empresa (esto lo veremos en una [sección](#integración-con-el-módulo-de-ventas-finanzas-y-contabilidad) posteriormente).

---

## **INSTALACIÓN**
Lo primero que debemos realizar es la instalación de esta aplicación.
Para tener más control entraremos en modo desarrollador.

Recuerda que puedes entrar al modo desarrollador a través de 
*`Ajustes - Developer Tools - Activar el modo desarrollador`*

o

*`?debug=1 antes de # y depués de ?`*

Recuerda que a través de los …  podemos gestionar actualizar, desinstalar, más información y aprende más. 

Este último siempre es interesante echarlo un vistazo para así poder ver dependencias, y objetos creados (menús, vistas, informes, etc.) 

![compras]
![compras2]

## **TRABAJAR CON LA APLICACIÓN**
Al entrar en la aplicación de Compra, nos encontraremos inicialmente con algo como esto

![compras3]

Como podemos ver los menús en la parte superior presentan muchas opciones que realizarán las operaciones que he comentado en el apartado de Introducción.

Esto que estamos viendo ahora mismo es el tablero principal o dashboard del módulo. 
Aquí podemos ver todas las solicitudes de presupuesto con su respectiva información.

* Referencia del Pedido
* Proveedor
* Representante de Compra 
* Fecha Límite del Pedido

Dentro de este dashboard podemos visualizar esta información de diferentes vistas mediantes los botones que tenemos en la parte superior a la derecha como por ejemplo esta vista

![compras6]

Antes de proceder con esto he de comentar que antes de cada paso en la columna denominada `Actividad Siguiente` podemos añadir un evento que queramos realizar de esta forma. No es obligatorio utilizarlo, pero puede ayudarnos a gestionar todo de una fora más ordenada

![compras10] ![compras18]

Y como tenemos en las opciones que nos indica en la captura desde esta pestaña podemos indicar que el evento ha concluido o incluso que se preparará otro en un futuro

---

### ***Menú Configuración***

En primer vamos a hechar un vistazo a las posibles configuraciones que tiene esta aplicación. Para ello podemos entrar a través de

`Configuración - Ajustes`

![[menu configuracion]][compras4]

Desde aquí podemos hacer todos los ajustes de esta aplicación, el comportamiento general de esta.

![[ajustes]][compras5]

Comentemos alguna de las opciones que aparecen

***Pedidos***
Como aparece en la captura de pantalla de arriba permite realizar una Aprobación del pedido de compra para pedidos superiores a cierto importe, bloquear pedidos que se confirmen para evitar su posible edición, si quertemos o no recibir avisos en los pedidos y si queremos recibir un recordatorio en el recibo de la compra.
El apartado de Acuerdos de Compra es para un tema legal por lo que no entraremos al detalle con ello.

***Facturacion***
Permite registrar y administrar facturas de proveedores. Esto incluye la capacidad de subir y adjuntar documentos de facturas y hacer seguimiento de las facturas pendientes de pago.

***Productos***
Permite realizar distinciones entre productos que son iguales por diferentes atributos que se expecifican en los menús (tamaño, color) e incluso se pueden llegar a añadir otras variantes

---

### ***Configuración Inicial Recomendada***
Antes de utilizar el módulo de Compras, es necesario configurar algunos aspectos básicos.
1. Accede al menú de Configuración.
2. Selecciona "Compras" en el menú desplegable.
3. Se recomienda configurar los siguientes aspectos:
    - Moneda: Selecciona la moneda en la que se realizarán las compras.
    - Impuestos: Define los impuestos que se aplicarán a las compras.
    - Productos: Configura los productos que se comprarán.
    - Proveedores: Crea una lista de proveedores.
    - Incoterms: Establece los términos comerciales internacionales que se utilizarán en las compras.

---

### ***Creación de Órdenes de Compras***

1. Accede al menú de Compras.
2. Haz clic en el botón "Nueva" para crear una nueva Orden de Compra.
![compras7]

3. Selecciona el proveedor para el cual se está creando la Orden de Compra.
4. Ingresa los detalles del producto o servicio que se está comprando, incluyendo la cantidad y el precio unitario.
5. Establece la fecha de entrega esperada y las condiciones de pago.
6. Haz clic en el botón "Agregar un producto" para agregar más productos a la Orden de Compra.

![compras8]

7. Utiliza la pestaña "Otra Información" para agregar contenido a la Orden de Compra como se muestra en la siguiente captura

![compras9]

8. Haz clic en el botón "Guardar" para guardar la Orden de Compra.

9. Y por último la demos a "Confirmar Pedido" 

---

### ***Recepción de Productos***

Una vez que los productos o servicios hayan sido recibidos, es posible registrar la recepción de la orden de compra.

1. Accede al menú de Compras.
2. Selecciona la Orden de Compra para la cual se están recibiendo los productos.
3. Haz clic en el botón "Recibir productos" en la parte inferior de la pantalla.
4. Ingresa la cantidad de productos que se han recibido.
![compras11] ![compras12]

5. Haz clic en el botón "Guardar" para guardar los cambios.
6. Haz clic en el botón "Validar" para validar la recepción de productos y actualizar el inventario.
![compras13]

---

### ***Creación de la Factura***

El módulo de Compras en Odoo también permite registrar y administrar facturas de proveedores. Esto incluye la capacidad de subir y adjuntar documentos de facturas y hacer seguimiento de las facturas pendientes de pago. Se hace de la siguiente manera.

1. Accede al menú de Compras.
2. Selecciona la Orden de Compra para la cual se están recibiendo los productos.
![compras19]

3. Una vez dentro editaremos el formulario según necesitemos, siempre añadiendo como campo obligatorio la fecha de la Factura
![compras20]

4. Hacer click sobre "Guardar" y posteriormente "Confirmar". Con ello tendremos una factura como esta con la que podremos realizar un futuro pago a un proveedor
![compras21]


---

### ***Pago a Proveedores***

Una vez que tenemos la factura creada ahora lo que hay que realizar el pago al Proveedor para ello:

1. Accede al menú de Compras.
2. Selecciona la Orden de Compra para la cual se está realizando el pago.
3. Haz clic en el botón "Registrar pago" en la parte inferior de la pantalla. Para acceder a esta pestaña tienes que ir aquí.
![compras17]
4. Ingresa los detalles del pago, incluyendo la cantidad y la forma de pago.
![compras14] 
5. Haz clic en el botón "Guardar" para guardar los cambios.

Una vez realizado el pago si todo ha ido correctamente la factura debería indicarse de la siguiente manera
![compras15] ![compras16] 

---

### ***Informes y Análisis***

1. Accede al menú de Compras.
2. Utiliza los informes y análisis para obtener una visión detallada de las compras, incluyendo:
   - Análisis de compras por proveedor
   - Análisis de compras por producto
   - Análisis de compras por fecha
   - Análisis de inventario de compras
   - Análisis de gastos de compras
3. Utiliza los filtros disponibles para personalizar los informes y análisis según tus necesidades.

Estos informes los podemos ver de 2 manera:
1. En forma de Gráficos
![compras24]
2. En tablas
![compras22] ![compras23]

---

### ***Integración con el módulo de Ventas Finanzas y Contabilidad***
La integración con el módulo de Ventas permite el seguimiento de los pedidos y su relación con las compras, además de facilitar la gestión del inventario. Al utilizar el módulo de Compras en conjunto con el de Ventas, se pueden planificar las compras en función de las necesidades de inventario y se pueden programar las compras de forma anticipada para no quedarnos sin existencias.

La integración con el módulo de Finanzas permite la gestión de pagos a proveedores, generar facturas y controlar los pagos. Al utilizar el módulo de Compras en conjunto con el de Finanzas, se pueden registrar automáticamente las facturas de compra en las cuentas contables correspondientes.

La integración con el módulo de Contabilidad permite una gestión financiera más completa, al poder llevar un registro detallado de los gastos relacionados con las compras y su relación con los presupuestos y las cuentas contables.

---

### ***Conclusión***
En conclusión, el módulo de Compras en Odoo es una herramienta esencial para la gestión eficiente de las compras en una empresa. Con esta herramienta, se pueden crear y gestionar órdenes de compra, registrar la recepción de productos, hacer pagos a proveedores, y llevar un registro detallado de los gastos relacionados con las compras. Además, el módulo cuenta con una serie de características y funcionalidades que ayudan a automatizar los procesos, integrarse con otros módulos de Odoo y generar informes y análisis para tener una visión detallada de las compras.

Además existen otras muchas funcionalidades pero en resumen estas son las más comunes utilizadas por las empresas.


[compras]: imagenes_compra/logo_compras.JPG
[compras2]: imagenes_compra/logo_compras2.JPG
[compras3]: imagenes_compra/dashboard_compras.JPG
[compras4]: imagenes_compra/menu_config_compras.JPG "Menú de configuración"
[compras5]: imagenes_compra/ajustes_compras.JPG "Ajustes"
[compras6]: imagenes_compra/dashboard_compras2.JPG
[compras7]: imagenes_compra/add_order_compras.JPG
[compras8]: imagenes_compra/add_order_compras2.JPG
[compras9]: imagenes_compra/add_order_compras3.JPG
[compras10]: imagenes_compra/add_event_compras.JPG
[compras11]: imagenes_compra/receive_compras.JPG
[compras12]: imagenes_compra/receive_compras2.JPG
[compras13]: imagenes_compra/receive_compras3.JPG
[compras14]: imagenes_compra/payment_compras.JPG
[compras15]: imagenes_compra/payment_compras2.JPG
[compras16]: imagenes_compra/payment_compras3.JPG
[compras17]: imagenes_compra/payment_compras4.JPG
[compras18]: imagenes_compra/add_event_compras2.JPG
[compras19]: imagenes_compra/factura_compras2.JPG
[compras20]: imagenes_compra/factura_compras3.JPG
[compras21]: imagenes_compra/factura_compras.JPG
[compras22]: imagenes_compra/informe_tabla_compras.JPG
[compras23]: imagenes_compra/informe_tabla_compras2.JPG
[compras24]: imagenes_compra/informe_grafico_compras.JPG