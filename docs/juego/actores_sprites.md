# Actores y Sprites

En GBStudio, los actores y sprites son elementos que se pueden agregar a una escena para representar personajes, enemigos, objetos y otros elementos interactivos en el juego. Los actores son entidades que pueden tener comportamientos y acciones definidas, mientras que los sprites son imágenes que representan visualmente a los actores.

En esta sección, aprenderemos cómo importar y utilizar actores y sprites en nuestras escenas, así como cómo definir sus propiedades y comportamientos.

## Actores

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

## Sprites

Un sprite es una imagen que representa visualmente a un actor en la escena. Los sprites pueden ser estáticos o animados, y debe tener un tamaño mínimo de 16x16px; además, de que cada frame del sprite (en caso de ser animado) debe ser múltiplo de 16px. Los sprites se pueden crear utilizando herramientas de edición de imágenes, como GIMP o Photoshop, y luego se pueden importar a GBStudio como recursos del proyecto.

Un Sprite para Game Boy, debe tener los siguientes colores:

*  Color 0: #071821 <span style="background-color: #071821; color: #ffffff;">(Color de fondo)</span>
*  Color 1: #86c06c <span style="background-color: #86c06c; color: #000000;">(Color de primer plano)</span>
*  Color 2: #e0f8cf <span style="background-color: #e0f8cf; color: #000000;">(Color de segundo plano)</span>
*  Color 3: #65ff00 <span style="background-color: #65ff00; color: #000000;">(Color transparente)</span>

### Importar un sprite a GBStudio

Para importar un sprite a GBStudio, simplemente copia el archivo de imagen del sprite en la carpeta _assets/sprites_ del proyecto. Asegúrate de que el archivo cumpla con los requisitos de tamaño y color mencionados anteriormente.


!!! note
    Recuerda que al inicio de esta sección, has descargado un zip, los sprites los puedes encontrar en la carpeta _sprites_  del mismo, y los puedes importar a GBStudio siguiendo los pasos mencionados anteriormente.

### Crear animaciones para un sprite

Vamos a un apartado importante de los sprites, que es la posibilidad de crear animaciones para ellos. Esto nos permite dar vida a nuestros personajes y enemigos, y hacer que se vean más realistas y atractivos.

Recuerda que cada frame de la animación debe tener un tamaño de 16x16px. Por ejemplo, si queremos crear una animación de caminar para un personaje, podemos crear varios frames que muestren al personaje moviendo las piernas y los brazos mientras camina. Luego, podemos definir la velocidad de la animación y el orden de los frames para que se reproduzca correctamente.

Para ello, vamos a abrir la vista de _sprites_ que encontrarás en la parte superior izquierda de la ventana de GBStudio. Esto abrirá la ventana de _sprites_, donde podemos ver todos los sprites disponibles en el proyecto.

<figure>
  <img src="/tallergbstudio/img/ventanasprites.png" alt="Ventana de Sprites" title="Ventana de Sprites" style="display: block; margin-left: auto; margin-right: auto; max-height: 450px;" />
  <figcaption>Figura 2: Ventana de Sprites</figcaption>
</figure>

Cada Sprite puede tener una hoja de animación; que se compone de varias animaciones, y cada animación puede tener varios frames. Para crear una animación para un sprite, seleccionamos el sprite en la ventana de _sprites_, y veremos en la parte inferior de la ventana, las animaciones y los correspondientes Frames del Sprite.


