# APLICACIÓN SITIO WEB

## **ÍNDICE DE CONTENIDOS**
1. [INTRODUCCION](#introducción)
2. [INSTALACIÓN](#instalación)
3. [TRABAJAR CON LA APLICACIÓN](#trabajar-con-la-aplicación)
   1. [Como funciona Sitio Web](#como-funciona-Sitio-Web)
   2. [Ajustes de la aplicación](#ajustes-de-la-aplicación)
   3. [Crear nuestro sitio web](#crear-nuestro-sitio-web)
   4. [El editor](#el-editor)
   5. [Herramientas de la aplicación](#herramientas-de-la-aplicación)
   6. [Promoción y el SEO](#promoción-y-el-seo)
   7. [Cuentas y perfil de usuario](#cuentas-y-perfil-de-usuario)
   8. [Pestaña de analítica](#pestaña-de-analítica)
   9. [Conclusión](#conclusión)


## **INTRODUCCIÓN**
Toda empresa a día de hoy necesita una página web, adaptada, diseñada y manejada de acuerdo a sus necesidades, y Odoo nos da la oportunidad de esto mismo con su aplicación de Sitio Web

Con el sitio web de Odoo podemos:

- Crear y diseñar un sitio web, con todas las herramientas convencionales a nuestra disposición.
- Personalizar varias webs e integrarlas con las distintas aplicaciones de Odoo
- Promocionar nuestra página con herramientas de SEO

La aplicación Sitio Web está integrada con otras, como Comercio Electronico, Foro, Empleo en línea y formularios, entre muchas otras. Veremos algún ejemplo más adelante.




## **INSTALACIÓN**


Lo primero que debemos realizar es la instalación de esta aplicación.
Para tener más control entraremos en modo desarrollador.

Recuerda que puedes entrar al modo desarrollador a través de 
*`Ajustes - Developer Tools - Activar el modo desarrollador`*

o

*`?debug=1 antes de # y depués de ?`*

Recuerda que a través de los …  podemos gestionar actualizar, desinstalar, más información y aprende más. 

Este último siempre es interesante echarlo un vistazo para así poder ver dependencias, y objetos creados (menús, vistas, informes, etc.) 

Una vez en la aplicación de Sitio Web, deberemos acceder al botón de Personalizar para elegir qué aplicaciones vamos a integrar con nuestro sitio web. 
Como ejemplo para el resto del trabajo, yo integraré Comercio Electrónico, y todas las imagenes mostrarán la integración con Comercio Electrónico, aunque hay integración con muchas otras aplicaciones. A pesar de usar esta integración como ejemplo, limitaré la explicación a las funciones del Sitio web.


![!integracion]

---


## **TRABAJAR CON LA APLICACIÓN**


Esta es la ventana principal del sitio web


![web]

Como podemos ver los menús en la parte superior presentan opciones de Páginas, Personalizar, Promover, Publicar, Nuevo, Editar y el desplegable de las distintas webs que pueda tener nuestra empresa, así como un botón para previsualizar la versión de móvil de tu app.

Lo que vemos en el centro de la pantalla es la previsualización de la web que hemos diseñado, que posee una interfaz gráfica y se opera similar a otros editores web online. 

La web como base nos muestra una pestaña en blanco con una barra superior con el logo vacío, las diferentes pestañas de la página, un botón de contacto y un desplegable de inicio de sesión 

---


### Como funciona Sitio Web


La aplicación toma como base una página web en blanco muy similar a la vista en editores online de diseño web, con un sistema de bloques y la oportunidad de editar el HTML y CSS de la página desde el botón Personalizar. 
El botón Editar nos abre un menú de componentes, bloques y similares para hacer un diseño web intuitivo, junto con una pestaña para configurar  opciones estéticas


![!editor1] ![!editor2]

A su vez, genera una página de contacto, que muestra dirección, correo, telefono y otros datos de contacto de la empresa.
Estas aparecen a su vez en el pie de página generado automáticamente en la parte inferior


![!contacto]


![!piePagina]

---


### Ajustes de la aplicación


Podemos acceder a los ajustes de la aplicación desde la pestaña de Configuración en la ventana de Analitica, que se abre cuando accedemos al Sitio Web mediante el menú de aplicaciones de Odoo. 

En la parte superior de la configuración, elegimos mediante un desplegable a qué página queremos aplicar los cambios.

![!ajustes1]


Una vez seleccionamos nuestra web, podemos modificar los elementos básicos de la misma, como nombre, compañía, idiomas, dominios, y URLs de redes sociales. Bajo los ajustes de la web en sí, podemos configurar aspectos de la web relativos a las aplicaciones de Odoo integradas en la web.



![!ajustes2]

La parte inferior muestra también opciones relativas al SEO y promoción de la web.


![!ajustes3]


---



### Crear nuestro sitio web


Si queremos crear un nuevo sitio web, aparte del generado automaticamente al instalar la aplicación, deberemos dirigirnos a los ajustes de la aplicación, desde la pestaña de Analítica o desde el menú de ajustes de Odoo. Una vez ahí, el botón "Crear un nuevo sitio web" nos abre un cuadro con la información básica a introducir para crear una web.


![!nuevaWeb]

Tras esto, nos mostrará la pestaña de selección de plantilla predeterminada, en caso de que queramos utilizar una, y nos dará acceso al editor.


---


### El editor


El editor parte principalmente de los botones de la barra superior de la aplicación, y más concretamente, del botón de edición.

El Botón Nuevo en la barra superior de la aplicación permite crear otra página u otros apartados de la web relacionados con la integración de Odoo, como blogs, foros, ofertas de trabajo y más, dentro de la web actual.

![!editor3]

Pulsando el botón editar, entramos en el modo de edición. Al salir del modo edición, se nos ofrece siempre las opciones de guardar o descartar los cambios realizados en la última edición.


![!editor4]

A la parte derecha, un cuadro de herramientas con una gran cantidad de bloques y componenetes, tanto estáticos como dinámicos, nos permiten personalizar la página web a nuestro gusto, inclutyendo desde bloques de texto y enlaces hasta listas de precios, accesos a Google Maps y popups. Podemos editar todos los componentes y bloques de manera gráfica o con código en la pestaña correespondiente.
Además, una de las pestañas del menú de edición nos permiten modificar opciones estéticas como fuentes, el tema, colores y estilos.


![!editor5]


![!editor6]

Además, la opción de "Cambiar Tema" en la pestaña de editar tema del editor nos permitirá elegir una plantilla de entre varias plantillas predefinidas disponibles. A partir de aquí, utilizaremos la plantilla "CLEAN" para el ejemplo.


![!plantilla]


---


### Herramientas de la aplicación


Además de todo esto, desde la pestaña de Editor HTML/CSS/JS del botón Personalizar, podremos modificar el codigo fuente de nuestra web directamente con los lenguajes indicados.


![!editor7]

Para controlar el sistema de ventanas de la aplicación, así como determinar la URL o administrar la visibilidad de las distintas ventanas, utilizamos las distintas opciones del botón Páginas de la barra superior.


![!editor8] ![!editor9]


El interruptor de publicado nos permite decidir si nuestra página es visible para usuarios que accedan a la URL.


![!publicado]

La previsualización de móvil nos muestra una versión creada automáticamente para móvil de nuestra web, reescalando los bloques y controles.


![!editor10]

Además, podemos usar el desplegable de la zona superior para elegir qué web utilizar al momento, pudiento manejar varias webs para una misma compañía.


---


### Pestaña personalizar


La pestaña personalizar de la barra superior, aparte de dar acceso a la integración y el editor de código, cambia y añade funciones en función de las aplicaciones integradas. Sin ninguna integración, la única opción extra de personalizar es el rastreo de visitas.


![!personalizar]


---


### Promoción y el SEO


Aparte de todas estas opciones de previsualización, otra de las pestañas de la aplicación, promover, nos permite ver y modificar opciones que ayudan al posicionamiento de nuestra página en función del SEO, así como previsualizar nuestro resultado de búsqueda en el navegador.


![!SEO]

Podemos modificar elementos importantes para el SEO y la visibilidad de nuestra web en buscadores, como las palabras clave, idiomas, o la imagen visible.


### Cuentas y perfil de usuario


El editor, aparte de darnos una pestaña de inicio, otra de contacto y el pie de página totalmenet editables, nos ofrece un sistema de cuentas e inicio de sesión. Al abrirlo, nos muestra una página de perfil, que podremos editar con la misma libertad que las otras, pudiendo crear desde un perfil de trabajador hasta uno de cliente electrónico. 

Al instalar aplicaciones de Odoo con integración del Sitio Web, el perfil de usuario es modificado y editado automaticamente para manejar las aplicaciones instaladas.


![!cuenta]


---


### Pestaña de Analítica


La aplicación de sitio web de Odoo cuenta con una pestaña de Analítica que permite ver estadísticas y datos de la misma. Esta pestaña mostrará también las analíticas de las distintas integraciones de la web. En cuando a la web en sí, posee integración con Google Analytics para ver las visitas y actividad de la página.


![!analítica1]


![analítica2]
 
 Para la conexión con Google Analytics, necesitaríamos hacernos de un ID de seguimiento y seguir una serie de pasos indicados por Google.


---


## **CONCLUSIÓN**


Sitio Web es probablemente una de las aplicaciones clave de Odoo a la hora de trabajar a nivel de empresa, ofreciendo una gran herramienta tanto para el cliente como para el desarrollador. Se trata de una aplicación diseñada con el propósito de trabajar con otras aplicaciones de Odoo, como comercio web y similares, a la vez que con componentes básicos como inventario o ventas, que aún sin esas extensiones funciona como un editor web bastante competente.









[integracion]: imagenesWeb/integracion.png "integración de aplicaciones"
[web]: imagenesWeb/webvacia.png "Plantilla de pagina web"
[contacto]: inagenesWeb/contacto.png "Página de contacto"
[piePagina]: imagenesWeb/pie.png"Pie de página"
[editor1]: imagenesWeb/editor1.png "Imagen Editor 1"
[editor2]: imagenesWeb/editor2.png "Imagen Editor 2"
[editor3]: imagenesWeb/editor3.png "Boton Nuevo"
[editor4]: imagenesWeb/editor4.png "Modo de edición"
[editor5]: imagenesWeb/editor5.png "Menú herramientas"
[editor6]: imagenesWeb/editor6.png "Menú temas"
[editor7]: imagenesWeb/editor7.png "Editor de código"
[editor8]: imagenesWeb/editor8.png "Administrar URL"
[editor9]: imagenesWeb/editor9.png "Administrar páginas"
[editor10]: imagenesWeb/editor10.png "Previsualizar movil"
[publicado]: imagenesWeb/publicado.png "Página publicada"
[SEO]: imagenesWeb/seo.png "Pestaña de promoción"
[cuenta]: imagenesWeb/cuenta.png "perfil vacío"
[ajustes1]: imagenesWeb/ajustes1.PNG "Seleccionar web"
[ajustes2]: imagenesWeb/ajustes2.PNG "Ajustes de la web"
[ajustes3]: imagenesWeb/ajustes3.PNG "Opciones de SEO"
[nuevaWeb]: imagenesWeb/nuevaWeb.PNG "Creando un nuevo sitio web"
[plantilla]: imagenesWeb/plantilla.PNG "Las plantillas de web ofrecidas por Odoo"
[personalizar]: imagenesWeb/personalizar.PNG "La pestaña personalizar"
[analitica1]: imagenesWeb/analitica1.PNG "Pestaña de analítica"
[analitica2]: imagenesWeb/analitica2.PNG "Integración con Google Analytics"