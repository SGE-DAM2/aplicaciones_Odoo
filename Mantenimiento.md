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

## Resumen de la aplicación
Resumen.

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