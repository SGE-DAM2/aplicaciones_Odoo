# APLICACIÓN MANTENIMIENTO

## ÍNDICE
1. [RESUMEN DE LA APLICACIÓN](#resumen-de-la-aplicación)
2. [INSTALACIÓN](#instalación)
3. [USO DE LA APLICACIÓN](#uso-de-la-aplicación)
    1. [TABLERO](#tablero)
    2. [MANTENIMIENTO](#mantenimiento)
       1. [PETICIONES](#peticiones-de-mantenimiento)
       2. [CALENDARIO](#calendario-de-mantenimiento)
    3. [EQUIPOS](#equipos)
    4. [INFORMES](#informes)
    5. [CONFIGURACIÓN](#configuración)
    6. [CASOS DE USO](#casos-de-uso)
       1. [CONDICIONES DEL ESCENARIO](#condiciones-del-escenario)
       2. [CREAR UNA PETICIÓN DE MANTENIMIENTO](#crear-una-petición-de-mantenimiento)
       3. [CREAR NUEVA CATEGORÍA DE EQUIPAMIENTO Y USARLA](#crear-una-nueva-categoría-de-equipamiento-y-usarla)
       4. [CREAR NUEVO EQUIPO DE MANTENIMIENTO Y DARLES UNA PETICIÓN](#crear-un-nuevo-equipo-de-mantenimiento-y-darles-una-petición)
       5. [FINALIZAR UNA PETICIÓN](#finalizar-una-petición)

## Resumen de la aplicación
Esta aplicación nos permite gestionar los mantenimientos que debes hacer en tu empresa y asignarselos a equipos de mantenimiento, los cuales se encargaran de realizar el mantenimiento, también te permite gestionar el equipamiento que llevarán los equipos a la hora de realizar el mantenimiento

## Instalación
Es recomendable entrar en modo desarrollador para realizar la instalación de la aplicación, para ello cambiaremos la parte correspondiente de la url (?debug=# ?debug=1#)
Seguido nos iremos a aplicaciones y buscaremos la aplicación de mantenimiento

![instalarMantenimiento]

Le daremos a instalar y automáticamente se instalará la aplicación

## Uso de la aplicación
Fraccionaremos por los diferentes apartados de la barra de arriba los apartados para ver las opciones que nos da esta aplicación ( Tablero | Mantenimiento | Equipos | Informes | Configuración )

![barraDeArriba]

### **Tablero**
Este apartado nos permite ver que mantenimientos quedan por hacer en los diferentes grupos de mantenimiento que tengamos, a su vez nos permite agruparlos y filtrarlos, en el caso del filtrado incluso teniendo la posibilidad de crear un filtrado propio

![tablero]

Si le damos a los tres puntitos del equipo de mantenimiento interno podemos filtrar desde los mantenimientos pendientes, realizados o en progreso del equipo hasta los informes del del equipo, también nos permite configurar el grupo para, por ejemplo, cambiarle el nombre o la descripción

![filtradoGrupo]

### **Mantenimiento**
Este apartado tiene dos opciones, las peticiones de mantenimiento y el calendario de mantenimiento

![apartadoMantenimiento]

### Peticiones de mantenimiento
Aquí podremos administrar las peticiones de mantenimiento desde su creación hasta su finalización
Si le damos a crear una nueva petición veremos la siguiente pantalla

![crearPeticion]

En ella podremos ajustar parámetros como la prioridad, el equipo y responsable del mantenimiento o la fecha prevista para la cual estará solucionada la petición, si pulsamos en acción nos permitirá duplicar la solicitud, si no podemos pulsar en crear para, valga la redundancia, crearla.
También podemos seleccionar el estado en el que se encuentra la petición pulsando en Nueva solicitud, en progreso, reparado o desechar

![apartadoMantenimientoConPeticion]

Una vez creada una petición podemos ver el mantenimiento en todo su esplendor

Podemos mover las diferentes peticiones a las diferentes etapas e incluso crear nuevas si así lo deseamos, también podemos modificar la petición y marcarla como realizada o planificar la actividad que se debe hacer para realizar el mantenimiento, también nos permite gestionar las peticiones a través de filtrado y agrupación.

Por último tengo que mencionar que a la derecha, debajo de la lupa, se encuentran diferentes tipos de perspectivas para ver las peticiones, las cuales son verla en Kanban (por defecto), en lista, en tabla, en gráfico y por último en calendario (siguiente apartado)

### Calendario de mantenimiento
Tiene una interfaz que recuerda al Google Calendar la cuál nos permite gestionar eventos

![calendario]

Se pueden crear diferentes eventos para la realización de los mantenimientos, también aparecen las fechas esperadas de las peticiones

![calendarioPeticiones]

### **Equipos**
En este apartado podemos gestionar el equipo (de equipación) para que los equipos de mantenimiento (de grupo) puedan realizar el mantenimiento de forma efectiva

![apartadoEquipos]

Podemos crear nuevos equipos (de equipación) y gestionarlos, si pulsamos en el reloj del equipo podemos asignar las actividades para las que usar el equipo (de equipación), como todos los apartados tiene su filtrado y agupación y a la derecha, debajo de la lupa, podemos cambiar a una vista de lista

Para crear o modificar un equipo le damos a crear o en su defecto pulsamos el equipo a modificar

![crearEquipo]

Aquí podemos seleccionar la categoría del equipo (de equipación), el equipo de mantenimiento al que pertenece así como el técnico o el propietario, también podemos añadirle una descripción o datos de mantenimiento o información del producto (datos del equipo como su proveedor o número de serie)

### **Informes**
Este apartado nos redirige a peticiones de informe, las mismas peticiones que vimos en [mantenimiento](#mantenimiento) pero en vista de gráfico

![apartadoInformes]

Nos permite ver las peticiones filtradas y agrupadas (como todos los apartados) y verlo en tres diferentes formatos (gráfico de barras, gráfico de líneas y gráfico circular)

### **Configuración**
Aquí podemos gestionar los equipos de mantenimiento y las categorías del equipamiento que usarán los equipos de mantenimiento

### Equipos de mantenimiento
Podremos crear nuevos equipos y gestionarlos, odoo nos permite cambiar entre una vista de lista y de kanban (para la gestión se debe usar la vista de lista), como todos los apartados es filtrable y agrupable, a los equipos podemos añadirles campos personalizados en el símbolo a la derecha del todo del grupo, si seleccionamos uno o varios grupos aparecerá una opción Acción que nos permitirá exportar, archivar, desarchivar y suprimir los grupos de mantenimiento

![apartadoConfiguracionEquipos]

Si le damos a crear añadirá una línea debajo del último equipo y podremos escribir el nombre del equipo, así como añadir los miembros en la parte derecha, en caso de tener más campos personalizados también podríamos configurarlos

![crearEquipoConfiguracion]

### Categorías de equipamiento
Este apartado nos permite gestionar las categorías que se podían seleccionar en los equipos (de equipación), su funcionamiento es similar al del apartado anterior [equipos de mantenimiento](#equipos-de-mantenimiento), pero con ligeros cambios, al seleccionar categorías las opciones de Acción son solo exportar y suprimir, otro cambio es que para la configuración de las categorías no se puede editar si entrar en otra pantalla más "compleja", obviamente en vez de tener mienbros de grupo, tenemos a un reponsable de la categoría

![apartadoCategorias]

Cuando creamos una categoría, o la modificamos, podremos gestionar los campos que tengamos y un campo llamado comentarios, en Acción podremos duplicar la categoría o suprimirla

### **Casos de uso**
Aquí veremos unos casos de uso realmente simples, pues la aplicación, al menos por lo que yo he probado, no tiene mucha complejidad

### Condiciones del escenario
Al ser un módulo que no depende en gran medida de usuarios extra (quitando lo miembros de los equipo) y tampoco necesita desarrollar los datos de la empresa, no he creado/modificado ninguna de esas cosas, pues no son realmente necesarias, lo que sí que vamos a aprovechar es lo que hemos ido creando a partir de la explicación del proyecto, como el equipo de ejemplo o la categoría de ejemplo (aunque esta última no será usada, crearemos otra)

### Crear una petición de mantenimiento
Nos tendremos que dirigir a [mantenimiento](#mantenimiento) y a [peticiones de mantenimiento](#peticiones-de-mantenimiento), una vez allí le daremos al botón de crear y se nos abrirá la siguiente intefaz

![crearPeticionCDU]

Tendremos una petición como esta, pero con los campos vacios, en el título debemos poner el problema, por ejempo "No me va el ordenador", en la descripción se pone el problema con más detalle, como se ve en la imagen, en el equipamiento ponemos el equipo que sea necesario para llevar a cabo el mantenimiento, por ejemplo un set de limpieza para el ordenador, la fecha de solicitud es cuando creas la peticióon, el tipo de mantenimiento, si es correctivo es un arreglo y si es preventivo es para evitar problemas a futuro, en equipo ponemos el equipo encargado de realizar el mantenimiento, como responsable el que se hará cargo de la petición, la fecha prevista es cuando se cree que se hará el mantenimiento, la duración el tiempo que se tarde en llevar el mantenimiento a cabo y la prioridad la urgencia del mantenimiento, en este caso es una estrella pues estará usando el equipo de un compañero

Una vez pulsado el botón de crear se creará, en caso de querer crear más de una petición similar, se pueden duplicar en Acción

### Crear una nueva categoría de equipamiento y usarla
Vamos a [configuración](#configuración) y a [categorías de equipamiento](#categorías-de-equipamiento), seguido pulsamos en crear y tendremos la siguiente pantalla

![crearCategoriaCDU]

Aquí podemos ponerle un nombre a la categoría con sus respectivos comentarios y responsable a cargo de la categoría, seguido rellenaríamos con los datos deseados y pulsaríamos en crear, ahora nos vamos a [equipos](#equipos) y modificamos/creamos un equipo al cual darle la categoría, en mi caso modificaré el ejemplo usado en [equipos](#equipos)

![asignarCategoriaCDU]

Como podemos ver al darle al apartado de categoría se nos habré un desplegable en el que podemos seleccionar la categoría que queramos, será tan sencillo como seleccionarla y darle a crear

### Crear un nuevo equipo de mantenimiento y darles una petición
Nos dirigiremos a [configuración](#configuración) y craeremos un equipo, para ello le damos a crear y ponemos el nombre del equipo, seguido le ponemos sus miembros (en mi caso solo tengo uno que es el administrador), y en caso de tener más campos también los rellenamos

![crearEquipoDeMantenimientoCDU]

Una vez hemos rellenado los datos necesarios haremos lo mismo que en [crear una petición de mantenimiento](#crear-una-petición-de-mantenimiento), solo que en equipo pondremos el equipo que creamos anteriormente, para ello podemos crear o modificar una petición, en mi caso crearé una nueva

![crearPeticionParaEDMCDU]

Una vez asignado el equipo damos a crear

### Finalizar una petición
Para ello iremos  a [mantenimiento](#mantenimiento) y a [peticiones de mantenimiento](#peticiones-de-mantenimiento) y daremos clic en la petición a finalizar, seguido clicamos en Reparado (en caso de querer guardar la petición), o en deshechar, si queremos eliminar las peticiones finalizadas

#### Punto fuera del contexto de la actividad hasta cierto punto
No tengo ningún punto de exportación de datos, porque no he encontrado ninguna opción de exportación dentro de la propia aplicación de mantenimiento


[instalarMantenimiento]: imagenes_mantenimiento/instalarMantenimiento.png "Apartado mantenimiento"
[barraDeArriba]: imagenes_mantenimiento/barraDeArriba.png "Barra de arriba"
[tablero]: imagenes_mantenimiento/tablero.png "Tablero"
[filtradoGrupo]: imagenes_mantenimiento/tablero_filtradoDentroDelGrupo.png "Opciones de filtrado dentro del grupo"
[apartadoMantenimiento]: imagenes_mantenimiento/apartadoMantenimiento.png "Mantenimiento"
[crearPeticion]: imagenes_mantenimiento/crearPeticion.png "Nueva petición"
[apartadoMantenimientoConPeticion]: imagenes_mantenimiento/apartadoMantenimientoConPeticion.png "Mantenimiento"
[calendario]: imagenes_mantenimiento/calendarioMantenimiento.png "Calendario"
[calendarioPeticiones]: imagenes_mantenimiento/calendarioConPeticiones.png "Calendario con peticiones"
[apartadoEquipos]: imagenes_mantenimiento/apartadoEquipo.png "Equipos"
[crearEquipo]: imagenes_mantenimiento/crearEquipoParaMantenimiento.png "Crear Equipo"
[apartadoInformes]: imagenes_mantenimiento/apartadoInformes.png "Informes"
[apartadoConfiguracionEquipos]: imagenes_mantenimiento/apartadoConfiguracionEquipos.png "Equipos de mantenimiento"
[crearEquipoConfiguracion]: imagenes_mantenimiento/creacionDeEquiposConfiguracion.png "Crear Equipo"
[apartadoCategorias]: imagenes_mantenimiento/apartadoCategoriasConfiguracion.png "Categorías"
[crearCategoria]: imagenes_mantenimiento/crearCategoriaConfiguracion.png "Crear Categoría"
[crearPeticionCDU]: imagenes_mantenimiento/casoDeUsoCrearPeticionDeMantenimiento.png "Crear petición de mantenimiento"
[crearCategoriaCDU]: imagenes_mantenimiento/crearCategoriaDeEquipoCDU.png "Crear categoría"
[asignarCategoriaCDU]: imagenes_mantenimiento/asignarCategoriaCDU.png "Asignar categoría"
[crearEquipoDeMantenimientoCDU]: imagenes_mantenimiento/equipoDeMantenimientoCDU.png "Equipos de mantenimiento"
[crearPeticionParaEDMCDU]: imagenes_mantenimiento/crearPeticionParaEquipoDeMCDU.png "Asignar equipo de mantenimiento"