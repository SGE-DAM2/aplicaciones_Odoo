# APLICACIÓN INVENTARIO

## **ÍNDICE DE CONTENIDOS**
1. [INTRODUCCION](#introducción)
2. [INSTALACIÓN](#instalación)
3. [TRABAJAR CON LA APLICACIÓN](#trabajar-con-la-aplicación)
   1. [Como funciona internamente el planificador](#como-funciona-internamente-el-Planificador)
   2. [Menú configuración](#menú-configuración)
   3. [Impresion de Horario](#Impresion-de-Horario)
   4. [Como funciona internamente el parte de horas](#como-funciona-internamente-el-parte-de-horas)
   5. [Menú Configuración 2](#desde-el-menu-de-configuracion-del-parte-de-horas-se-nos-permite-cambiar-la-unidad-de-medida-seleccionar-o-no-los-increíbles-partes-de-horas-lo-que-nos-permire-que-el-tiempo-de-los-partes-de-hora-se-pueda-ver-desde-distintos-dispositivos-modificar-el-redondeo-de-tiempo-bloquear-fechas-mandar-recordatorioa-tanto-a-empleados-como-a-gerentes-y-decidir-si-queremos-que-los-partes-de-hora-se-generen-tras-validar-las-ausenciasconfiguracion2)
   6. [Generacion de informes Parte de Horas](#generacion-de-informes-de-partes-de-horas)
   7. [Impresión de parte de horas](#impresion-de-parte-de-hora)
   8. [Conclusión](#conclusión)

## **INTRODUCCIÓN**
Una empresa necesita tener la planificacion de los turnos de los empleados, los horarios de estos, sus horas de trabajo... Pero no solo la empresa, si no tambien los empleados. Que la empresa o los empleados desconozca los horarios o no los tengan debidamente organizados podria resultar en empleados no asistiendo a sus horas o varios empleados asistiendo a la misma. Esta aplicación nos va a permitir llevar a cabo la gestión de los horarios y los turnos de los empleados.

Como tareas principales que podemos llevar a cabo están:

- Modificacion de horarios.
- Creacion de horarios especificos para empleados.
- Gestion de faltas laborales
 



## **INSTALACIÓN**
Lo primero que debemos realizar es la instalación de esta aplicación.
Para tener más control entraremos en modo desarrollador.

Recuerda que puedes entrar al modo desarrollador a través de 
*`Ajustes - Developer Tools - Activar el modo desarrollador`*

o

*`?debug=1 antes de # y depués de ?`*

Recuerda que a través de los …  podemos gestionar actualizar, desinstalar, más información y aprende más. 

Este último siempre es interesante echarlo un vistazo para así poder ver dependencias, y objetos creados (menús, vistas, informes, etc.) 


![planificacion] 
![planificacion2]

## **TRABAJAR CON LA APLICACIÓN**
Al entrar en la aplicación de Planificación, nos encontraremos inicialmente con algo como esto

![planificacion3]

Como podemos ver los menús en la parte superior presentan opciones como añadir un nuevo horario, el dia, copiar la semana anterios, publicar etc.

Esto que estamos viendo ahora mismo es el tablero principal o dashboard. 
Aqui podremos ver los dias de la semana planificados.

* el dia que es
* Las horas que estan ocupadas por un trabajador en un dia

Los horarios se podran modificar de manera interactiva seleccionando la cantidad de horas a trabajar segun el empleado.

### Como funciona internamente el Planificador

La forma de trabajar es muy sencilla. tenemos multiples opciones de planificacion como Gantt,Kanban... Segun la opcion selecion de planificacion(como ejemplo usaremos solamente el gantt), seleccionaremos el/los empleados de los cuales queremos crear el horario y añadiremos las horas de la semana, el mes, o el año segun cuanto queramos planificar. Una vez hemos terminado de seleccionar las horas pulsaremos el boton publicar y se le enviara a los empleados un email con las horas añadidas de trabajo.


### ***Menú Configuración***

En primer vamos a hechar un vistazo a las posibles configuraciones que tiene esta aplicación. Para ello podemos entrar a través de

`Configuración - Ajustes`

![[Configuracion]]

Los ajustes que se nos permiten realizar son bastante limitada. Desde el menu de configuracion se nos permite permitir que los empleados se desasignen de los turnos o no y tambien ajustar con cuanta antelacion se generan los turnos que se repiten


---


### ***Impresion de Horario***

si entramos en la opcion de Kanban, pulsando uno de los "post-it" que hay de cada empleado, se nos permite imprimir su horario por si decidimos tenerlo en papel.

![Kanban]

![Kanban2]

![Imprimir]



---
### Como funciona internamente el parte de horas

El funcionamiento del parte de horas es bastante simple, primeramente pulsaremos el boton iniciar, con lo que se iniciara el contador, a continuacion escribiremos la actividad a realiza(ejemplo, enviar email), a continuacion seleccionaremos un proyecto y por ultimo una tarea(ejemplo reunion). Una vez hemos terminado pulsamos el boton parar para parar el contador.
![partedehoras]

Para iniciar el proyecto pulsamos en la letra que aparece del proyecto y seleccionamos el tiempo que le dedicaremos.
 ![partedehoras2]

---

### ***Menú Configuración 2***

Desde el menu de configuracion del parte de horas se nos permite cambiar la unidad de medida, seleccionar o no los "Increíbles partes de horas" lo que nos permire que el tiempo de los partes de hora se pueda ver desde distintos dispositivos, modificar el redondeo de tiempo, bloquear fechas, mandar recordatorioa tanto a empleados como a gerentes y decidir si queremos que los partes de hora se generen tras validar las ausencias.
![configuracion2]
---
### Generacion de informes de partes de horas
La propia aplicacion nos permite generar informes en formato excel segun empleado,proyecto o tarea y descargarlos para su posterior uso.
![informes]
![informes2]
---
### ***Impresion de parte de hora***
Al igual que con el planificador, entrando en la vision de kanban y pulsando en uno de los "post-it" se nos permite imprimir el parte de hora para su posterior uso.
![impresionparte]

---
### ***Conclusión***
Aunque la aplicacion sea pequeña y de uso muy sencillo, considero que es una de las más necesarias para las empresas. Si las empresas no dejan claros su horarios los empleados no sabran a las horas que tienen que estar, por lo que lo más probable es que no vayan a trabajar.




[planificacion]: imagenes_planificacion/planificacion.png "icono de planificacion"
[planificacion2]: imagenes_planificacion/planificacion2.png "icono de planificacion"
[Planificacion3]: imagenes_planificacion/planificacion3.png "Situación inicial inventario"
[Configuracion]: imagenes_planificacion/Configuracion.png "Ajustes de planificacion" 
[Kanban]: imagenes_planificacion/Kanban.png "Menú de configuración"
[Kanban2]: imagenes_planificacion/Kanban2.png
[Imprimir]: imagenes_planificacion/Imprimir.png
[partedehoras]: imagenes_planificacion/Partedehoras.png
[partedehoras2]: imagenes_planificacion/partedehoras2.png
[configuracion2]: imagenes_planificacion/configuracion2.png
[informes]: imagenes_planificacion/informes.png
[informes2]: imagenes_planificacion/informes2.png
[impresionparte]: imagenes_planificacion/impresionparte.png
