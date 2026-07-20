# Más Acciones y Escenas

Vamos a añadir más acciones y escenas a nuestro juego, para ello, vamos a utilizar los eventos y acciones que nos ofrece GBStudio.

## Actuadores (triggers)

Un actuador (trigger) es un elemento que podemos colocar en la escena, y que nos permite definir acciones y eventos cuando el jugador interactúa con él. Por ejemplo, podemos colocar un actuador en la escena, y definir que cuando el jugador lo toque, se reproduzca un sonido o se muestre un mensaje en pantalla.

Uno de los usos más comunes de los actuadores es para cambiar de escena, por ejemplo, cuando el jugador llega al final de un nivel, podemos colocar un actuador que cambie a la siguiente escena del juego.

### Añadir una nueva escena

Vamos a añadir una nueva escena a nuestro juego, para ello, vamos a la vista de _Montaje de escenas_ y pulsamos en el botón de añadir (+), en el menú de la izquierda, y seleccionamos la opción de _Escena_. Haz click en el espacio de trabajo para colocar la nueva escena, y en el panel de propiedades de la derecha, podemos modificar el nombre de la escena y otras propiedades.

Vamos a usar el el fondo llamado _mapa2_, que se encuentra en la carpeta _fondos_ de los recursos que hemos descargado para este taller. Para ello, seleccionamos la nueva escena y en el panel de propiedades de la derecha, seleccionamos el fondo _mapa2_ en la opción de _Fondo_.

<figure>
  <img src="/tallergbstudio/img/mapa2.png" alt="Segunda Escena" title="Segunda Escena" style="display: block; margin-left: auto; margin-right: auto; max-height: 450px;" />
  <figcaption>Figura 1: Segunda Escena</figcaption>
</figure>

!!! warning
    Recuerda establecer las propiedades de la escena correctamente, como el tipo de escena (Plataformas), la hoja de sprites del jugador y de establecer las colisiones de la escena.

### Cambiar de escena con un actuador

Vamos a utilizar un actuador; para ello, desde la primera escena, vamos a colocar un actuador en la parte derecha de la escena, para ello, pulsamos en el botón de añadir (+), en el menú de la izquierda, y seleccionamos la opción de _Accionador_. Una vez hecho esto, buscaremos en la escena el lugar donde queremos colocar el actuador, y haremos click para colocarlo. Una vez colocado, podemos modificar sus propiedades en el panel de propiedades de la derecha.

En las acciones, buscamos la pestaña de _al Entrar_ y añadimos una acción de tipo _cambiar escena a_, y seleccionamos la segunda escena que hemos creado. Esto permitirá que cuando el jugador toque el actuador, se cambie a la segunda escena del juego.

Además de que nos aparecerá un marcador azul en la segunda escena, donde podemos establecer el punto de aparición e incluso la dirección del jugador al entrar en la escena. Para ello, seleccionamos el marcador y en el panel de propiedades de la derecha, podemos modificar las propiedades del marcador, como la posición y la dirección del jugador al entrar en la escena.

Probemos esta nueva escena, y veremos que cuando el jugador toque el actuador, se cambiará a la segunda escena del juego.

<video width="450" height="300" autoplay loop style="display: block; margin-left: auto; margin-right: auto;">
  <source src="/tallergbstudio/videos/cambiaescena.webm" type="video/webm">
  Tu navegador no soporta el elemento de video.
  </source>
</video>
<span style="display: block; text-align: center; text-decoration: italic;">Figura 2: Video del juego con cambio de escena</span>

### Más acciones y eventos

Trata de Añadir más enemigos a este mapa y añadir la última escena que nos queda (_mapa3_), para ello, puedes usar los recursos que has descargado para este taller, y seguir los pasos que hemos visto en las secciones anteriores.

Se ha de añadir:

1. En el mapa2, 2 enemigos, uno en la parte izquierda y otro en la parte derecha del mapa, para ello, puedes usar el sprite _bee_ que hemos usado anteriormente.

2. En el _mapa3_, crea las colisiones y configura la escena, por último, añade un enemigo con el sprite _Bohwuencoopa_ que será el enemigo final del juego, y que al ser golpeado por el jugador, mostrará un mensaje de victoria en pantalla.

Sientete libre de añadir más enemigos y actuadores a las escenas, para hacer el juego más interesante y divertido. Recuerda que puedes usar los recursos que has descargado para este taller, y seguir los pasos que hemos visto en las secciones anteriores.
