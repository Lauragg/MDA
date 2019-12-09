# Primer sprint

## Plan de Iteración
|                | Día 1                    | Día 2                    | Día 3                       | Día 4                       | Día 5                                             | Día 6                   |
|----------------|--------------------------|--------------------------|-----------------------------|-----------------------------|---------------------------------------------------|-------------------------|
| David Infante  | Diseño de clases base    | Diseño de clases base    | Implementación GUI          | Implementación GUI          | Implementación GUI                                | Implementación GUI      |
| Laura Gómez    | Diseño BD                | Diseño BD                | Conexión con la BD          | Conexión con la BD          | Conexión con la BD, Interfaz de información       | Interfaz de información |
| Pedro Bonilla  | Clase contenedor         | Clase contenedor         | Conexión front-end/back-end | Conexión front-end/back-end | Conexión front-end/back-end, Botón de información | Botón de información    |
| Juan Ocaña     | Clase parque, Diseño GUI | Clase parque, Diseño GUI | Botón de mapa               | Botón de mapa               | Botón de mapa                                     |                         |
| Antonio Martín | Clase fuente             | Clase fuente             | Menú de lista               | Menú de lista               | Menú de lista, Conexión con API mapas             |                         |



## Sprint Review

Vamos empezar exponiendo las historias de usuario acabadas. Aquellas cosas que no debemos implementar en el contexto de las prácticas de la asignatura las consideraremos realizadas, por lo que en el contexto del Sprint Review se considerarán terminadas. Con esa consideración, los objetivos del sprint eran:

| ID   | Título                                            | PH   |
| ---- | ------------------------------------------------- | ---- |
| 1    | Usuario - ver un mapa funcional con los servicios | 5    |
| 8    | Usuario - ver una lista con los servicios         | 2    |
| 9    | Usuario - localizar contenedores                  | 2    |
| 3    | Usuario - localizar fuentes                       | 2    |
| 4    | Usuario - localizar parques                       | 2    |

A lo largo de este sprint hemos desarrollado los primeros pasos de la aplicación que han hecho que aumenten enormemente el valor del producto. No sólo hemos desarrollado un prototipo sino que también hemos diseñado cómo serían nuestras bases de datos, para estos diseños primero hemos necesitado pensar cómo serían las clases que formarían el esqueleto principal de nuestra aplicación, las cuales serían:

![](../imagenes/DiagramaClases.png)

Y una vez diseñadas estas clases, hemos realizado el diseño de la base de datos:

![](../imagenes/EntidadRelacion.png)

![](../imagenes/PasoATablas.png)

En la demo realizado en clase se mostró cómo funcionaba nuestro prototipo y cómo habían sido cumplidos todos los objetivos. Al finalizar este documento, adjuntaremos un video dónde se podrá ver el correcto funcionamiento de estos objetivos junto a los del segundo sprint.

No hemos tenido muchos problemas para la realización del sprint. Por otro lado, al estar utilizando herramientas que eran desconocidas para nosotros teníamos problemas de cara a su uso y utilización más básico, el cual fue solventado observando los tutoriales que venían en la página web oficial y comprobando antes, fuera del prototipo, detalles para ver si cuadraban con lo que buscábamos o no.

Después del primer sprint tenemos un producto funcional hecho bajo la planificación y potencialmente comercializable. Por estos motivos, los stakeholders están muy contentos con el progreso y no consideran ninguna novedad de cara al desarrollo del producto estando satisfechos con el camino que este está siguiendo. Se planea seguir con el proyecto establecido.

## Sprint Restrospective

En esta reunión vamos a tratar de clarificar y concretar qué cosas hemos hecho bien, qué cosas podríamos hacer mejor y, por último, qué cosas vamos a cambiar de cara a la siguiente iteración.

Empezaremos por la restosprectiva individual de cada persona, en lo que respecta a ella misma principalmente, pero con indicaciones al trabajo de otras si se ve necesario.

- Pedro Bonilla: Durante este sprint me he visto no tan colaborativo como he visto a otros compañeros. He sentido que he tardado mas de lo común en adaptarme a la nueva tecnología usada. La ayuda de Juan fue inestimable.

- David Infante: El final del sprint fue duro porque no era capaz solventar un error de la implementación de la GUI, pero gracias al extenso conocimiento sobre el tema de Juan, pudimos acabar la tarea a tiempo.

- Juan Ocaña: El aprendizaje de la herramienta de prototipado ha sido más accidentado de lo que cabría esperar, pero tras entender su funcionamiento todo ha avanzado como debiera.

- Antonio Martín: La herramienta de prototipado fue la principal dificultad al principio. Una vez que aprendimos a manejarla correctamente todo fue mucho más fácil.

- Laura Gómez: El diseño de clases y de la base de datos fue relativamente sencillo y viable. El problema vino cuando tocó utilizar la herramienta, por falta de experiencia hacia esta


Vemos que la mayoría del equipo a centrado su preocupación en el manejo de la tecnología nueva. Con felicitaciones hacia Juan por su rápido aprendizaje y dar ese empujoncito extra al equipo. De cara al siguiente sprint nadie espera tener de nuevo el mismo fallo, ya solventado durante la ejecución de este.


Las relaciones entre los miembros son cordiales y convenientes. El equipo de Juan con Laura ha demostrado entenderse muy bien para atacar de manera conjunta una tarea más grande que requiera fuerza de trabajo extensa. Por otro lado Pedro, Antonio y David han trabajado mejor en tareas pequeñas que requieran el trabajo de una persona única y puedan enfrentarse a ella en individual. En general han sido correctas y se espera y desea que sigan así.

Los procesos de daily standup, reparto de tareas en función de cuando se quede libre fuerza de trabajo y cuales son más prioritarias ha demostrado ser muy efectivo, esperamos seguir así. Al final del sprint empezamos a hacer como prueba reunión de fin de día. Se ve como una mejora positiva y se quiere implantar en la totalidad del siguiente sprint.


# Segundo Sprint

## Plan de Iteración
|                | Día 1                              | Día 2                        | Día 3                        | Día 4                     | Día 5                         |
|----------------|------------------------------------|------------------------------|------------------------------|---------------------------|-------------------------------|
| David Infante  | Diseño de clases                   | Diseño de clases             | Página de información        | Página de información     | Formulario modificar          |
| Laura Gómez    | Botón de barra y búsqueda          | Implementar diseño de clases | Implementar diseño de clases | Función de crear database | Función de borrado database   |
| Pedro Bonilla  | Botón "no funciona" en información | Sugerencias de búsqueda      | Sugerencias de búsqueda      | Sugerencias de búsqueda   | Botón de modificar            |
| Juan Ocaña     | Funciones de consulta              | Funciones de consulta        | Formulario crear             | Formulario crear          | Botón borrar (en información) |
| Antonio Martín | Marcador de servicio en mapa       | Formulario de incidencias    | Formulario de incidencias    | Botón de crear            | Función de modificar database |


## Sprint Review

En primer lugar vamos a comentar los resultados del sprint, pues se han conseguido realizar todas las historias de usuario propuestas, en ambos sprint se ha demostrado una medición muy correcta del tamaño de trabajo que el equipo es capaz de asumir.


|   ID | Título                                                | PH   |
| ---- | -------------------------------------------------     | ---- |
|    2 | Usuario - buscar servicios mediante un buscador       | 4    |
|   14 | Usuario - marcar si algo no funciona                  | 1,5  |
|   13 | Usuario - consultar información de un servicio        | 1,5  |
|   12 | Usuario - consultar si un servicio está en mal estado | 1,5  |
|   11 | Usuario - distintguir tipos de parque                 | 1,5  |
|   10 | Usuario - distintguir tipos de contenedores           | 1,5  |
|    7 | Administrador - eliminar información de un servicio   | 1    |
|    6 | Administrador - modificar información de un servicio  | 1    |
|    5 | Administrador - crear información de un servicio      | 2    |


Los novedades clave de esta iteración es la mejora de las capacidades de la aplicación. Principalmente, se ve que ahora existe un buscador, que sumado a las nuevas capacidades del administrardor para moderar el contenido que se ofrece a los usuarios, nos deja una aplicación perfectamente operativa. Esto es bastante importante ya que estamos lejos del punto de colapso que sucede cuando se añaden demasiadas funcionalidades a la aplicación. En esta iteración se ha añadido bastante valor al producto puesto que no solo tenemos las páginas de información de los servicios, sino que también podemos distinguir en la búsqueda parques, fuentes y contenedores. 

Para este sprint se han realizado estos incrementos mediante la tecnología usada previamente. En este sprint esta técnología se ha usado de manera más correcta dada la experiencia adquiridad por el equipo durante el primer sprint y el compromiso de los miembros por la calidad.

En esta iteración no hemos tenido apenas problemas, puesto que ya estabamos familiarizados con el software utilizado para su realización. Esto ha dejado una iteración en la que no se han tenido que resolver muchos inconvenientes.

Los StackeHolders y el Product Owner están muy contentos con el producto obtenido esta iteración, y ante el miedo de añadir más utilidades de las que son cómodamente manejables por el usuario, no añaden más contenido al product backlog. Tanto los StakeHolders como el Product Owner estan muy contentos con el trabajo realizado por el equipo. 


## Sprint Restrospective
