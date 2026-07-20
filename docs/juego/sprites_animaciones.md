# Sprites y Animaciones

En GBStudio, los sprites son elementos que se pueden agregar a una escena para representar personajes, enemigos, objetos y otros elementos interactivos en el juego. Los Sprites pueden ser estáticos o animados, y se pueden importar desde archivos de imagen externos o crear directamente en GBStudio utilizando el editor de sprites incorporado.

En esta sección, aprenderemos cómo importar y utilizar sprites en GBStudio, así como cómo crear animaciones para ellos y asociarlos a actores en la escena.


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
  <figcaption>Figura 1: Ventana de Sprites</figcaption>
</figure>

Cada Sprite puede tener una hoja de animación; que se compone de varias animaciones, y cada animación puede tener varios frames. Para crear una animación para un sprite, seleccionamos el sprite en la ventana de _sprites_, y veremos en la parte inferior de la ventana, las animaciones y los correspondientes Frames del Sprite.

### Sprite del Jugador

Vamos a centrarnos en el sprite del jugador, que es el personaje principal del juego. Este sprites tiene varias animaciones, como caminar y saltar, y cada animación tiene varios frames que muestran al personaje en diferentes posiciones y movimientos.

<figure>
  <img src="/tallergbstudio/img/playersprt.png" alt="Sprite del Jugador" title="Sprite del Jugador" style="display: block; margin-left: auto; margin-right: auto; max-height: 450px;" />
  <figcaption>Figura 2: Sprite del Jugador</figcaption>
</figure>

Podemos observar que el sprite tiene varias animaciones, como caminar y saltar, y cada animación tiene varios frames que muestran al personaje en diferentes posiciones y movimientos. Cada animación tiene 3 frames.

Vamos a crear la animación en GBStudio; para ello, vamos a la vista de _sprites_ y en la parte derecha, seleccionaremos el tipo de animaciones que queremos añadir. Como nuestro juego es de tipo plataformas, seleccionaremos el tipo de _jugador de plataformas_.

!!! note
    Dependiendo del tipo de juego que estemos creando y del comportamiento que queremos dar, podemos seleccionar diferentes tipos como:

    * **Dirección Fija**: Solo una dirección, como un juego de disparos en 2D.
    * **Dirección Fija + Movimiento**: Una dirección fija, pero con movimiento, como un juego de disparos en 2D.
    * **Direcciones Horizontales**: Solo permite movimiento horizontal, como un juego de desplazamiento lateral.
    * **Direcciones Horizontales + Movimiento**: Permite movimiento horizontal, pero con movimiento, como un juego de desplazamiento lateral.
    * **Cuatro direcciones**: Permite visualizar en 4 direcciones, como un juego de rol en 2D.
    * **Cuatro direcciones + Movimiento**: Permite visualizar en 4 direcciones, pero con movimiento, como un juego de rol en 2D.
    * **Jugador de plataformas**: Permite visualizar en 2 direcciones, salto y escalada pero con movimiento, como un juego de plataformas en 2D.
    * **Cursor**: Permite visualizar un cursor en la pantalla, como un juego de estrategia en 2D.

Una vez seleccionado el tipo de animación, podemos ver que se han creado varias animaciones para el sprite del jugador, como caminar y saltar. Cada animación tiene varios frames que muestran al personaje en diferentes posiciones y movimientos.

Veamos como crear cada animación:

1. Selecciona la animación como por ejemplo _mover derecha_.
2. Haz click en el botón de _añadir frame_ para añadir un nuevo frame a la animación.
3. Selecciona el frame que quieres añadir a la animación desde la hoja que has importado; recuerda que cada frame debe tener un tamaño de 16x16px. Por lo que se seleccionarán con el ratón 2 fragmentos de 8x16px, para formar un frame de 16x16px.
4. Con el ratón centra donde quieres en el frame que aparezca el personaje, y haz click para añadirlo a la animación.

Repite este proceso para cada una de las animaciones que quieras crear para el sprite del jugador, como caminar y saltar. Una vez que hayas creado todas las animaciones, podemos asociarlas al actor del jugador en la escena.

### Asociar una animación al jugador

Para nuestro juego, vamos a asociar la animación de caminar al actor del jugador en la escena. Para ello, desde la vista de _Montaje de escenas_ seleccionamos el actor del jugador en la escena, y en el panel de propiedades de la derecha, seleccionamos el sprite que hemos creado con las animaciones. El propio motor establecerá las animaciones correspondientes a cada acción del jugador, como caminar y saltar, según el tipo de animación que hayamos seleccionado para el sprite.

Prueba ahora tu juego y verás que el jugador se mueve y salta con las animaciones que hemos creado. Esto le da un aspecto más realista y atractivo al juego, y hace que la experiencia del jugador sea más divertida y emocionante.

<video width="450" height="300" autoplay loop style="display: block; margin-left: auto; margin-right: auto;">
  <source src="/tallergbstudio/videos/videojuego.webm" type="video/webm">
  Tu navegador no soporta el elemento de video.
  </source>
</video>
<span style="display: block; text-align: center; text-decoration: italic;">Figura 3: Video del juego con animaciones</span>