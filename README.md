# proyectoCine

Proyecto con temática de cine programado en `HTML5`, `CSS3`, `Javascript` y `bootstrap`. Hecho por Alberto, Jose Antonio, Sergio y Adrian.

---
## ¿En qué consiste el proyecto?
Éste proyecto se basa en una aplicación del lado del cliente que nos provee de información sobre películas de cine, géneros, su reparto de actores, directores, etc.


## ¿Cómo ésta dividida ésta aplicación?
1. **Página de búsqueda(Alberto):** Contiene 4 funciones con las siguientes utilidades:
+ `devolverPelicula()`: deberá devolver todas las películas que tengan en su nombre o descripción, la cadena pasada al método.
+ `devolverPeliculaSimilar()`: deberá devolver las películas que sean similares a la indicada.
+ `peliculaPorActor()`: función que busca una película en la que aparece un actor concreto.
+ _Dos funciones extras definidas por el grupo_

2. **Página de edición(Adrian):** Contiene las siguientes funciones:
+ `validacion()`: debe validar todos los campos de una película, sin poder ser _nulos_, _undefined_ o vacíos.
+ `addUpdateActor()`: función que debe añadir un actor a una película. En caso de que ya esté, se actualiza, si no, se añade.
+ `addUpdateDirector()`: función que añade o actualiza al director de una película.
+ _funciones extra definidas por el grupo_

3. **Página de gestión de películas(Josan)**: Contiene las siguientes funciones:
+ `devolver10peliculas()`: devuelve las 10 películas con más personas trabajando en ella.
+ `mejorPelicula()`: debe obtener la mejor película de todas.
+ `ordenarPeliculas()`: debe ordenar las películas por puntuación o por fecha de emisión.
+ _funciones extras definidas por el grupo_

4. **Página del usuario(Sergio):** Contiene las siguientes funciones:
+ `votacionUsuario()`: debe contener una votación de un usuario con valor de 0 a 5 y especificar un comentario.
+ `obtenerPeliculasUsuario()`: obtener las películas que ha votado un usuario en concreto.
+ `obtenerListaUsuarios()`: obtener una lista de usuarios que hayan votado por películas similares al usuario.
+ _funciones extras definidas por el grupo_

## Tipos de datos
+ `Nombre` `Apellidos` `Género`
+ `Descripción` `Mes` `Año`
+ `Puntuación` `fecha_emisión` `Comentario` `Votación` 


## Clases
Se utilizan las siguientes clases:

+ `Peliculas`
+ `Actor`
+ `Director`
+ _añadir más..._
