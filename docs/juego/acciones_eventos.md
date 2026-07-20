# Acciones y Eventos

Vamos a comenzar a hacer nuestro algo más interactivo; tenemos nuestro jugador, y nuestro enemigo, pero no pasa nada, ya que no hemos definido ninguna acción para ellos. Para ello, vamos a utilizar los eventos y acciones que nos ofrece GBStudio.

Una de las características de GBStudio es que nos permite definir eventos y acciones para actores y elementos de la escena sin necesidad de codificar.

Todas las acciones y eventos que definamos para los actores y/o elementos de una escena, se ejecutarán en el orden en que los definamos, y podemos definir diferentes acciones y eventos para cada actor o elemento de la escena.

Todas las acciones y eventos que definamos, podemos verlo en la parte inferior derecha de la pantalla una vez este seleccionado el actor o elemento de la escena, en el apartado de _Eventos_ y _Acciones_. En este apartado podemos ver todos los eventos y acciones que hemos definido para el actor o elemento de la escena, y podemos modificarlos, eliminarlos o añadir nuevos eventos y acciones.

<figure>
  <img src="/tallergbstudio/img/eventosescena.png" alt="Eventos y Acciones" title="Eventos y Acciones" style="display: block; margin-left: auto; margin-right: auto; max-height: 450px;" />
  <figcaption>Figura 1: Eventos y Acciones de una escena</figcaption>
</figure>

### Definir un evento y acción para el jugador

Vamos a comenzar por hacer que el jugador comience del principio si es golpeado por un enemigo. 

Comenzamos seleccionando el actor del enemigo en la escena, y siguiendo los siguientes pasos:

1. En el panel de propiedades de la derecha, establecemos el grupo de colisión del enemigo a 1.
2. En la parte inferior tendremos una pestaña llamada _Al golpear_ y seleccionamos la opción de _jugador_. Esto nos permitirá definir una acción para el jugador cuando sea golpeado por el enemigo.
3. En este apartado añadiremos  una acción de tipo _actor->establecer posición a_, seleccionamos el actor del jugador, y establecemos la posición a X=0 Y=11.

Si probamos nuestro juego, veremos que cuando el jugador es golpeado por el enemigo, este vuelve a la posición inicial de la escena.

<video width="450" height="300" autoplay loop style="display: block; margin-left: auto; margin-right: auto;">
  <source src="/tallergbstudio/videos/colision.webm" type="video/webm">
  Tu navegador no soporta el elemento de video.
  </source>
</video>
<span style="display: block; text-align: center; text-decoration: italic;">Figura 2: Video del juego con colisiones</span>