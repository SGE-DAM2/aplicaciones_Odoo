# APLICACIÓN ENCUESTA

## **ÍNDICE DE CONTENIDOS**
1. [INTRODUCCION](#introducción)
2. [INSTALACIÓN](#instalación)
3. [TRABAJAR CON LA APLICACIÓN](#trabajar-con-la-aplicación)
   1. [Como funcionan internamente las encuestas](#como-funcionan-internamente-las-encuestas)
   2. [Menú](#menú)
   3. [Formularios de comentarios](#formularios-de-comentarios)
   4. [Crear una pregunta](#crear-una-pregunta)
   5. [Crear una encuesta](#crear-una-encuesta)
   6. [Participaciones](#participaciones)
   7. [Question & Answers](#Questions-&-answers)
   8. [Relación entre aplicación Marketing - Sitio Web](#relación-entre-aplicación-marketing---sitio-web)
   9. [Conclusión](#conclusión)

## **INTRODUCCIÓN**
Una empresa necesita en todo momento saber la calidad de sus productos o servicios de la gente que los disfruta. El vender o dar un servicio que no guste a los usuarios tiene consecuencias graves en la empresa. Esta
aplicacion va a permitir obtener la opinion de los clientes de distintos campos de la empresa

Como tareas principales que podemos llevar a cabo están:

- Formulario de comentarios.
- Certificacion.
- Presentacion online.


Esta aplicación está integrada con otras, en concreto con Marketing y Sitio Web y Contabilidad. (esto lo veremos en una [sección](#relación-entre-aplicación-Marketing---Sitio-Web) posteriormente)

## **INSTALACIÓN**
Lo primero que debemos realizar es la instalación de esta aplicación.
Para tener más control entraremos en modo desarrollador.

Recuerda que puedes entrar al modo desarrollador a través de 
*`Ajustes - Developer Tools - Activar el modo desarrollador`*

o

*`?debug=1 antes de # y depués de ?`*

Recuerda que a través de los …  podemos gestionar actualizar, desinstalar, más información y aprende más. 

Este último siempre es interesante echarlo un vistazo para así poder ver dependencias, y objetos creados (menús, vistas, informes, etc.) 


![encuesta] 
![encuesta2]

## **TRABAJAR CON LA APLICACIÓN**
Al entrar en la aplicación de Encuesta, nos encontraremos inicialmente con algo como esto

![encuesta3]

Como podemos ver los menús en la parte superior presentan muchas opciones entre las que se incluyen esas generales que he mencionado al principio.

Esto que estamos viendo ahora mismo es el tablero principal o dashboard. 
Aquí podemos diferentes acciones que podemos ejecutar

* Crear un formulario
* Crear una certificacion
* Hacer una presentacion online


### Como funcionan internamente las encuestas   

La forma de trabajar es muy sencilla e intuitiva. Y no necesitas tener nada creado para poder crear el primer formulario, eso si para hacer la presentacion en live
tengo que tener creado como minimo un formulario para poder presentarlo.

Esta forma de trabajar como luego veremos hace que este módulo esté intimamente relacionado con el módulo de marketing y sitio web.

### ***Menú***

En primer vamos a hechar un vistazo a las posibles configuraciones que tiene esta aplicación. Para ello lo podemos ver bien en la imagen principal o arriba  a 
la izquierda que vienen unos items en los cuales ppuedes configurar: encuestas, formularios y preguntas y respuestas.

![[menu configuracion]][encuesta10]

Comentemos alguna de las opciones que aparecen

  ***Encuestas***
  Permite crear un formulario de comentarios, una certificacion y una presentacion en vivo

  ***Participaciones***
  De esta forma podemos compartir los enlaces de las encuestas de diferentes modos: correos electronicos, acceso directo de invitacion, presentacion en vivo

  ***Question & Answers***
  Que nos permite acceder a varios campos como es el cuestionario, valores sugeridos o respuesta detalladas para tener mas informacion a cerca de las respuestas obtenidas en los formularios realizados por los clientes, es decir ver de manera mas esquematica las preguntas que has hecho en el cuestionario, la respuesta que es correcta y una respuesta detallada por parte del usuario.

![[questiones y respuestas]][cuestiones]

Veamos ahora algunas de las tareas más habituales que se realizn en un manejo básico de las encuestas.

---


### ***Formularios de comentarios***

Para llevar a cabo la gestión de formulario de comentarios lo tenemos que realizar a través de 
`Encuestas - Formulario de comentarios`

Al entrar en formulario de comentarios ya se crea una por defecto la cual tu puedes editar para hacer a tu manera, es decir es como si fuera una plantilla a partir de la cual tu tienes que crear tu propia encuesta

![formulario de comentarios][formulario_comentarios]

si clickeamos sobre el podemos ver la información al respecto


![almacen_datos][almacen_datos]

Aquí podemos ver las diferentes opciones como 

* Cuestionario -> hacer las preguntas y marcar la respuesta o respuestas correctas

![cuestionario][cuestionario]

* Opciones -> sobre el cuestionario, el tiempo de realizacion el codigo de sesion en vivo

![opciones][opciones]

* La descripcion -> breve resumen de la materia sobre la que va a ser preguntado en la encuesta

![descripcion][descripcion]

* Mensaje final -> El creador de la encuesta puede poner un mensaje para que veas cuando hayas finalizado la encuesta

![mensaje_final][mensaje_final]

---


### ***Crear una pregunta***

Para llevar a cabo la gestión de creacion de una pregunta para la encuesta lo tenemos que realizar a través de 
`Encuesta - Formulario de comentarios - Cuestionario`

![pregunta][pregunta]

Si hago un clic sobre añadir otra pregunta se me desplegaria una pantalla tal que asi:
![crear_pregunta][crear_pregunta]

A continuacion podemos ver como hemos creado la primera pregunta de nusestra encuesta

![realizacion_pregunta][realizacion_pregunta]

En esta pantalla puedo cambiar los diferentes paraametros que la confrorman atraves de
`Encuesta - Crear - Opciones`

* Diseño del cuestionario
* El numero de personas que pueden participar y a traves de que link se pueden unir para realizar la encuesta
* El tiempo que tienen para realizar la encuesta y si va a tener puntuacion
* El codigo de sesion en vivo, recompensa para las respuestas rapidas...

En cualquier momento puedo crear una encuesta nueva. 
Ademas es muy intuitivo formar las preguntas y no tiene perdida

---


### ***Crear una encuesta***

El objetivo de esta categoria es ver la valoracion de un cliente hacia nuestra empresa, de esta manera no es necesario aplicar la certificacion en las encuestas, esto es que tenga una puntuacion

![no_tipo][no_tipo]

Para llevar acabo una encuesta de por ejemplo preguntar que les parece el servicio atencio al cliente tendriamos que quitar la opcion certificado (Odoo es el nombre de nuestra encuesta anteriormente creada)
`Encuesta - Odoo - Opciones`

![certificacion][certificacion]

Como podemos ver en la siguiente imagen ya tendriamos creada nuestra primera encuesta

![encuesta][encuesta]

Por defecto nos vienen 6 cuestionarios ya creados que para verlos nos tendriamos que meter a traves
`Encuetsa - Question & Answers - Cuestionario`

![cuestionario_defecto][cuestionario_defecto]

---


### ***Participaciones***

En participaciones podemos ver a los clientes que han realizado las encuestas y la puntuacion que han recibido en caso de que que fuera una encuesta certificada, aunque no es lo mas comun cuando se hacen encuesta para la valoracion de una empresa

Para entrar en la pantalla de participaciones que se encuentra arriba a la izquierda es atraves
`Encuestas - Participaciones - Productos`

![participaciones][participaciones]

Vemos que tenemos mucha informacion en esta pantalla de participacione

Podemos ver que encuesta se ha realizado agrupado en un despregable pero aparte tenemos la siguiente informacion

* La encuesta realizada
* El contacto del cliente que realizo la encuesta
* El correo electronico del cliente
* Numero de veces que ha realizado la encuesta
* Si ha aprobado la encuesta(este item solo es en el caso que sea certificada)
* Estado

Nosotros hemos realizado una encuesta y he mandado el link a un cliente

Al realizar la encuesta en la pantalla de participantes nos saldria algo tipo asi:

![encuesta_participaciones][encuesta_participaciones]

Si pinchamos encima de una participacion nos saldria una pantalla como la que vemos mas abajo, la cual tiene informacion mas detallada y la respuesta que ha respondido a la pregunta

![detalle][detalle]

---

### ***Questions & Answers***

Este es otro campo dentro de las encuestas en el que encontramos 3 items
`Encuestas- Questions & Answers`

![items][items]

Dentro de este campo el primer item que encontramos es Cuestionario, en el que podemos ver a simple vista todos los cuestionarios que tenemos, el que se encuenta en español es el que hemos realizado nosotros mientras los que se encuentran en ingles son los que te vienen por defecto como ejemplos del modulo de encuestas

![cuestion][cuestion]

El segundo item que nos encontramos es Valores Sugeridos en el cual se nos abre una pantalla en la que podemos poner la puntuacion a cada una de las respuestas que se dan a elefir en cada respuesta de las encuestas
En este ejemplo hemos dado 10 puntos a la respuesta correcta de que es Odoo
Hay preguntas que no tienen puntuacion porque es la opinion personal es decir no se puede valorar

![valores][valores]

Esta tabla se puede exportar en un formato XLSX para trabjar con ella desde otra aplicacion

![descarga][descarga]

Este archivo al abrirlo en este caso con una hoja de excel se veria tal que asi

![excel][excel]
![xlsx][etiqueta]

El ultimo item que queda es Respuestas Detalladas en el que podemos ver distinta informacion sobre la encuesta que se ha realizado, para ver la siguiente pantalla mostrada en la imagen tendriamos que seleccionar un fila de la tabla

![selec][selec]

En este item se encuentran los siguientes campos

* Pregunta realizada
* Cuando ha sido creada
* Tipo de respuesta
* Omitida
* Puntuacion
* Final de la respuesta
* Respuesta sugerida que es la que ha marcado como correcta el cliente

![respuesta][respuesta]

En la anterior imagen podemos ver como tiene una puntuacion de 10 puntos porque ha acertdo la pregunta, en una imagen se puede ver un fallo en el cual la respuesta no era la correcta y se le dieron 10 puntos pues desde este menu se puede cambiar y asignar el valor correcto.

---


### ***Relación entre aplicación Marketing - Sitio Web***

Como ya comenté anteriormenete existe una clara realación entre estas tres aplicaciones, ya que la encuestra se realizaria a traves de la pagina web(Sitio Web) o enviando la encuesta por sms o correo electronico(Marketing sms)

Ya he realizado una encuesta anteriormente, ahora lo que voy ha hacer es crear un item en el sitio web y de esta manera l pulsar sobre encuesta nos lleva directamente a la encuesta que hemos creado

![encuesta_web][encuesta_web]

Si observamos al pinchar sobre encuesta nos llevaria directamente a la encuesta

![encuesta_w][encuesta_w]

Ahora vamos a enviar la encuesta por sms

![sms][sms]

De esta forma hemos enviado un sms a todos nuestros contactos para que realicen la encuesta
Tambien podemos planificar el dia que queremos que se envie un determinado dia, es decir planificar el envio de la encuesta

![dia][dia]

Cuando le damos a enviar como le hemos progromado nos saldria tal que asi

![cola][cola]

---

### ***Conclusión***
Com podemos ver es una aplicacion muy importante para ver lo que opinan los clientes acerca de nuestra empresa y de esta forma mejorar en los puntos que tengamos peor valoracion




[encuesta]: imagenes_aplicacion/encuesta_logo2.jpg "icono de encuesta"
[encuesta2]: imagenes_aplicacion/encuesta2.jpg "icono de inventario"
[encuesta3]: imagenes_aplicacion/encuesta3.jpg "Pantalla principal de la aplicacion encuesta"
[cuestiones]: imagenes_aplicacion/cuestiones.jpg "Cuestiones y respuestas" 
[encuesta10]: imagenes_aplicacion/encuesta10.jpg "Menú de configuración"
[formulario_comentarios]: imagenes_aplicacion/formulario_comentarios.jpg
[cuestionario]: imagenes_aplicacion/cuestionario.jpg "Cuestionario de las encuestas"
[opciones]: imagenes_aplicacion/opciones.jpg "Opciones de las encuestas"
[descripcion]: imagenes_aplicacion/descripcion.jpg "Descripcion de las encuestas"
[mensaje_final]: imagenes_aplicacion/mensaje_final.jpg "Mensaje final de la encuesta"
[pregunta]: imagenes_aplicacion/pregunta.jpg "Crear una pregunta para el cuestionario"
[crear_pregunta]: imagenes_aplicacion/crear_pregunta.jpg "Crear una pregunta"
[realizacion_pregunta]: imagenes_aplicacion/realizacion_pregunta.jpg "Realizar una pregunta"
[no_tipo]: imagenes_aplicacion/no_tipo.jpg "No se deben realizar este tipo de preguntas para la varoracion de clientes sobre la empresa"
[certificacion]: imagenes_aplicacion/certificacion.jpg "Certificacion"
[encuesta]: imagenes_aplicacion/encuesta.jpg "LA primera encuesta creada"
[cuestionario_defecto]: imagenes_aplicacion/cuestionario_defecto.jpg "Cuestionarios que ya vienen para tener plantillas"
[participaciones]: imagenes_aplicacion/participaciones.jpg "Entrar a la pantalla de participantes"
[encuesta_participaciones]: imagenes_aplicacion/encuesta_participaciones.jpg "Participacion de un cliente en la encuesta"
[detalle]: imagenes_aplicacion/detalle.jpg "Detalles del participante"
[items]: imagenes_aplicacion/items.jpg "Items de Questions & Answers"
[cuestion]: imagenes_aplicacion/cuestion.jpg "Todos los cuestionarios"
[valores]: imagenes_aplicacion/valores.jpg "Los valores que puede tomar cada respuesta"
[descarga]: imagenes_aplicacion/descarga.jpg "Descarga de archivo XLSX"
[excel]: imagenes_aplicacion/excel.jpg "Decarga vista en excel"
[etiqueta]: etiqueta.xlsx "Descarga de una tabla"
[selec]: imagenes_aplicacion/selec.jpg "Seleccion de la respuesta"
[respuesta]: imagenes_aplicacion/respuesta.jpg "Respuesta sugerida de la encuesta"
[encuesta_web]: imagenes_aplicacion/encuesta_web.jpg "Encuesta en la web"
[encuesta_w]: imagenes_aplicacion/encuesta_w.jpg "Encuesta accediendo desde la web"
[sms]: imagenes_aplicacion/sms.jpg "Encuesta enviada por sms"
[dia]: imagenes_aplicacion/dia.jpg "Programar envio de encuesta por sms"
[cola]: imagenes_aplicacion/cola.jpg "Envio de sms en cola"

