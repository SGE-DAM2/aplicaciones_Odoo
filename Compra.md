# APLICACIÓN COMPRAS

## **ÍNDICE DE CONTENIDOS**
1. [INTRODUCCION](#introducción)
2. [INSTALACIÓN](#instalación)
3. [TRABAJAR CON LA APLICACIÓN](#trabajar-con-la-aplicación)
   1. [Menú configuración](#menú-configuración)

## **INTRODUCCIÓN**
La aplicación de Compra de Odoo ayuda a llevar un seguimiento de los acuerdos de compra, las cotizaciones y las órdenes de compra. 

Permite automatizar el proceso de reabastecimiento y a llevar un seguimiento tanto de las ofertas de compra como de sus órdenes.

Como taras principales que podemos llevar a cabo están:
- Automatizar el flujo de compras
- Listas de precios de proveedor y disponibilidad de productos
- Recibir las mejores ofertas de compra
- Obtener estadísticas de las compras
- Gestiona múltiples empresas

Esta aplicación está integrada con otras, en concreto con Inventario, Facturación y Contabilidad. (esto lo veremos en una [sección](#relación-entre-aplicación-compras---inventario---facturacion---contabilidad) posteriormente)

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
Nos permite realizar un control en las cantidades facturadas por los proveedores.

***Productos***
Permite realizar distinciones entre productos que son iguales por diferentes atributos que se expecifican en los menús (tamaño, color) e incluso se pueden llegar a añadir otras variantes


[compras]: imagenes_compra/logo_compras.JPG
[compras2]: imagenes_compra/logo_compras2.JPG
[compras3]: imagenes_compra/dashboard_compras.JPG
[compras4]: imagenes_compra/menu_config_compras.JPG "Menú de configuración"
[compras5]: imagenes_compra/ajustes_compras.JPG "Ajustes"