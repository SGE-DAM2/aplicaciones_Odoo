# LAS APLICACIONES BÁSICAS DE ODOO
## INTRODUCCIÓN
Como ya comentamos anteriormente las aplicaciones proporcionan una funcionalidad concreta de un determinado proceso empresarial. Por el contrario, los módulos se encargan de aportar características adicionales a dichas aplicaciones.

Es fundamental el conocer y entender las aplicaciones básicas de Odoo. Como están conformadas y sus objetos fundamentales, para luego poder realizar adaptaciones de estas a las necesidades de la empresa. Estas las realizaremos en la unidad de aprendizaje siguiente. 

![aplicaciones][aplicaciones]

## OBJETIVO DE ESTE PROYECTO
Consiste en que los alumnos se familiaricen con las principales aplicaciones que contiene Odoo.
Para ello cada equipo deberá realizar un estudio de la aplicación asignada.

Deberá constar de los siguientes puntos:
- Nombre de la aplicación.
- Usos principales dentro de la empresa de la aplicación.
- Ralción con otras aplicaciones dentro de Odoo.
- Explicación de los elementos que conforman el entorno de la aplicación, tales como menús, opciones de configuración, etc.
- Al menos cuatro casos de uso explicados convenientemente. De estos casos de uso en uno si es psoble se debe generar un informe sobre el área de que se trate. Así por ejemplo podemos generar en inventario uno relacionado con los productos.
- Deberá investigarse si existe alguna opción respecto a la exportación de datos que estén almacenados en esa aplicación. Por ejemplo en inventario yo puedo generar una exportación a un formato XLS o CSV para poder trabajar con otra aplicación externa, por ejemplo Excel.

## OBTENCIÓN DEL REPOSITORIO DE TRABAJO
El profesor ha creado un repositorio en github llamado **aplicaciones_Odoo.git**. El alumno deberá hacer un *fork* a este repositorio con el fin de craerse una copia a su repositorio personal. Una vez allí deberá clonar este al repositorio local suyo para comenzar a trabajar en su directorio de trabajo.

## FINALIZACIÓN Y SUBIDA DE TU PARTE DEL PROYECTO
Una vez el alumno haya dado por bueno el resultado solicitará mediante un *Pull Request* al repositorio creado por el profesor la fusión con este.

## FORMATO DE LA DOCUMENTACIÓN
La documentación ha de tener una estructura similar a la mostrada en la aplicación de inventario que yo es he subido de ejemplo.

* Constará de un índice con enlaces a cada parte del documento.
* Secciones. Las mismas que las que se encuentran en inventario, pero adaptadas a vuestra aplicación.
* La carpeta para guardar la imagenes se llamará "imagenes aplicacion"
  
## ESCENARIO DE PARTIDA DE ODOO
### INTRODUCCIÓN
Esta sección tiene como objetivo el indicaros las condiciones de partida que tenéis que tener para llevar a cabo la documentación sobre la aplicación de Odoo que os haya tocado a cada uno.

### SOFTWARE A UTILIZAR

Deberéis usar la versión cloud de Odoo. Recordad la opción **-edu** para poder tener la licencia más alla de 15 días.

### CONDICIONES DEL ESCENARIO
Deberás crear una nueva compañía sobre la que trabajar dentro de Odoo, con los datos que desees. En mi caso para el ejemplo que os he puesto la he llamado **El Tuercas**.

![empresa]

Otra cuestión a tener en cuenta es dar de alta a un nuevo usuario, en mi caso **Jose**, en la compañía para que no sea el administrdaor que inicialmente creamos al instalar Odoo, sino que sea un usuario con privilegios sobre la aplicación de la que vamos a hablar, en mi caso la de inventario.

![empleado]

Si fuese necesario podéis crear más usuarios.

Una vez tengaís este escenario creado, ya podéis pasar a instalar la aplicación que os haya tocado para realizar su manual.




[empresa]:imagenes_inventario/Empresa%20tuercas.jpg
[empleado]:imagenes_inventario/Empleado%20Jose.jpg
[aplicaciones]: imagenes_inventario/aplicaciones.jpg "diferentes aplicaciones de Odoo"