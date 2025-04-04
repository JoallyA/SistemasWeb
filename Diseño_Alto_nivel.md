# Objetivo
Este documento de diseño plantea una solucion propuesta para implementar un sistema en backend que cumpla con los requerrimientos del cliente.

## Caso de uso a soportar
A continuacion se enlistan los casos de uso que aplican al sistema solicitado.  

**Usuario no registrado**   
Puede visualizar el contenido del curso    

**Usuario registrado (Alumno)**   
Puede revisar el curso    
Acceder a ejercicios y exámenes
Revisar calificaciones personales   
Tener registro de “ruta ideal”    

**Administrador**   
Puede generar usuarios y cursos    
Identificar actividades entregadas    
Ver el rendimiento de los alumnos (individual y en grupo)  

**Profesor**   
Puede revisar el contenido del curso    
Visualizar las respuestas de los alumnos    
Dar retroalimentación al alumno

## Fuera de alcance  
Los siguientes casos de uso no están contemplados como casos de uso en este sistema, esto no limita las capacidades del sistema.  
* Los alumnos pueden enviarse mensajes entre ellos.
* Los alumnos pueden personalizar su perfil.
* Se pueden agregar diferentes cursos, no solo cursos enfocados a matematicas.

## Solucion
Se propone utilizar Moodle para el curso, dado que ofrece las funcionalidades requeridas, como el inicio de sesión de usuarios, la gestión de perfiles, el envío de actividades y materiales de estudio, así como la posibilidad de facilitar la comunicación entre profesores y alumnos.    
Adicionalmente, se sugiere desplegar el sistema en AWS. Aunque en un principio la plataforma no manejará un gran volumen de usuarios, cursos o ubicaciones geográficas, AWS ofrecería la flexibilidad necesaria para escalar y ajustar el sistema en caso de un aumento en la demanda, garantizando así la estabilidad y evitando posibles fallos.
