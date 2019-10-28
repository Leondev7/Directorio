# RESPUESTA #

Lo primero de todo agradecerte que hayas hecho la prueba y la hayas enviado, sabemos que la gente trabaja sus 8 horas y luego el llegar a casa es una hora o menos con suerte, y no hay muchas ganas de hacer nada cuando llegas a casa; así que muchas gracias por dedicarle tiempo.

Ahora queríamos dedicar un poco de tiempo a enumerar los fallos o carencias que creemos que hayas tenido en el código para que puedas solucionarlas y mejorar en el futuro

## DOCUMENTACION ##

No hay nada de documentación, ni en formato de un README del propio 
proyecto ni en comentarios en las propias clases. Si una persona nueva 
llega al proyecto lo deseable es que no tenga que hacer ingeniería 
inversa para saber lo que hace cada cosa

## PATRÓN MVP ##

No hay ningún tipo de arquitectura en la parte de vista de la 
aplicación, ni MVVM ni MVP ni MVVM. La lógica del código está en las
Activity así como la descarga de datos.

## PATRÓN REPOSITORIO ##

No hay separación entre el código propio de la vista (Activity) con el 
código de recogida de datos

## GITIGNORE ##

El proyecto no tiene archivo .gitignore y por lo tanto al hacer el
commit se están subiendo los archivos autogenerados de la carpeta build 

## ERRORES ##

Cuando tienes un error en la carga de datos, no realizas ninguna gestión
 del swiper y se queda ahí colgando, no permitiendo recargar la página 
 otra vez.

Al obtener el listado de películas en Dialog de carga aparece 
"Obteniendo Usuarios".

En el enunciado de la prueba pedíamos ordenar las películas por voto, 
no hemos visto ningún tipo de organización en la lista.

## ECHAMOS EN FALTA ##

Echamos de menos la falta de uso de Kotlin, ya que tenemos varias partes
del proyecto en este lenguaje y sería recomendable al menos conocerlo.

El uso de la versión 25 de Android cuando la última ya es la 29.

No borrar en las dependencias la librería de Picasso si no vas a 
utilizar realmente en el proyecto.


## COSAS QUE NOS HAN GUSTADO ##

El uso de Retrofit y OKHttp, ya que son las dos librerías más extendidas
para las comunicaciones de red

El uso de Butterknife para la inyección de los componentes de vista

El uso de Glide y de CircleImageView para la gestión de las imágenes

# RESUMEN # 

Esta prueba realmente se trata de ver cómo una persona organiza el 
código cuando tiene total libertad : utlización de patrones de diseño, 
Clean Architecture, programación funcional, programación reactiva, 
separación de conceptos, principios SOLID, etc...
 
Para nosotros lo realmente importante son los tres puntos iniciales: 
Documentación, MVP y REPOSITORIO; ya que permiten definir la 
arquitectura de la aplicación y un código organizado.