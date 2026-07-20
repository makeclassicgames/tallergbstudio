# Actores

Un actor en GBStudio es una entidad que puede tener un comportamiento definido mediante eventos y acciones. Los actores pueden ser personajes jugables, enemigos, NPCs (personajes no jugables) u otros elementos interactivos en el juego.

Un actor puede tener diferentes propiedades, como su posición en la escena, su tamaño, su velocidad de movimiento y su comportamiento al interactuar con otros actores o con el jugador. Los actores también pueden tener animaciones asociadas a ellos, lo que les permite moverse y realizar acciones de manera más realista.

Los actores se añaden a las diferentes escenas del juego y pueden ser controlados mediante eventos y acciones definidas en el editor de GBStudio. Por ejemplo, podemos definir que un actor se mueva hacia la derecha cuando el jugador presione la tecla de flecha derecha, o que un enemigo ataque al jugador cuando se acerque a él.

Para añadir un actor a la escena, seleccionamos la escena a utilizar, y pulsamos en el botón de añadir (+), en el menú de la izquierda, y seleccionamos la opción de _Actor_. Una vez hecho esto, buscaremos en la escena el lugar donde queremos colocar el actor, y haremos click para colocarlo. Una vez colocado, podemos modificar sus propiedades en el panel de propiedades de la derecha.

!!! warning
    Los actores y los diferentes elementos de la escena tienen un espacio limitado, por lo que debemos tener cuidado de no saturar la escena con demasiados elementos, ya que esto puede afectar el rendimiento del juego y la experiencia del jugador. En la parte inferior de cada escena, podemos ver los indicadores de elementos en ella:
    <figure>
      <img src="/tallergbstudio/img/indicadores.png" alt="Indicadores de elementos en la escena" title="Indicadores de elementos en la escena" style="display: block; margin-left: auto; margin-right: auto; max-height: 350px;" />
      <figcaption>Figura 1: Indicadores de elementos en la escena</figcaption>
    </figure>

    * **A**: Actores: Indica el número de actores en la escena y el máximo permitido.
    * **S**: Mosaico: Indica el número de Tiles (mosaicos) en la escena y el máximo permitido.
    * **T**: Actuadores: indica el número de actuadores (Triggers) en la escena y el máximo permitido.

### Actores y Sprites

Un actor puede tener uno o varios sprites asociados a él, lo que le permite tener diferentes apariencias y animaciones en el juego. Por ejemplo, un actor puede tener un sprite para su apariencia normal, otro sprite para cuando está herido y otro sprite para cuando está muerto.

Vamos a añadir un actor que sea un enemigo; para ello, vamos a la escena y pulsamos en el botón de añadir (+), en el menú de la izquierda, y seleccionamos la opción de _Actor_. Una vez hecho esto, buscaremos en la escena el lugar donde queremos colocar el actor, y haremos click para colocarlo. Una vez colocado, podemos modificar sus propiedades en el panel de propiedades de la derecha.

El sprite a utilizar lo podrás encontrar con los recursos que has descargado para este taller, en la carpeta _sprites_, y lo puedes importar a GBStudio siguiendo los pasos mencionados en la sección de _Sprites y Animaciones_.

!!! note
    El archivo se llama _bee.png_, y contiene una sola animación, que es la de volar. Para asociar el sprite al actor, seleccionamos el actor en la escena y en el panel de propiedades de la derecha, seleccionamos el sprite _bee_ en la opción de _Sprite_.

Para este caso, usaremos las animaciones de tipo _Dirección Fija_, ya que el enemigo solo se moverá en una dirección, y no necesitamos que tenga animaciones para otras direcciones.

Una vez hecho esto, asociaremos el actor con un Sprite, para ello, seleccionamos el actor en la escena y en el panel de propiedades de la derecha, seleccionamos el sprite _bee_ en la opción de _Hoja de Sprite_. Esto permitirá que el actor tenga la apariencia y animaciones definidas en el sprite.



