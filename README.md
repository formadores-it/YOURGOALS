Arquitectura del proyecto y tecnología:
-El proyecto es de tipo Spring Starter Proyect, o Spring Boot. Utiliza los frameworks JPA+Hibernate para manejar y mapear los datos de la BBDD, que es de tipo persistente. Usa el contenedor de Tomcat Jasper que está integrado en la propia configuración del Spring boot
-Los .java se encuentran en src/main/java/com/formadoresit/gamifyalpha
-Las vistas se encuentran en src/main/webapp/WEB-INF/views
(En construcción...)


Para cargar el proyecto en Spring:
-En Spring: File>Open project from File System>Directory (elegir la carpeta destino que se encuentra en el proyecto de Gitlab)>Finish.

Para ejecutar el proyecto en Spring:
-Usar Run as>Spring Boot App.
-Ya no hace falta crear la Database, pero sí es necesario iniciar el servidor MySql.

Solución de errores:
-Spring da bastantes errores a la hora de cargar proyectos desde directorios. La forma más fácil de solucionarlos es: borrando la carpeta ".m2" que se encuentra normalmente en C/Users/{nombre de usuario}/.m2
-Otra forma de solucionar muchos errores es usar Alt+F5 en Spring y actualizar el proyecto Maven.
By Formadores IT
