# Primera escena

Vamos a empezar por el principio, creando la primera escena de nuestro juego de plataformas para Game Boy y Game Boy Color.

Una escena es un nivel o pantalla del juego donde se desarrollan los eventos y la acción. En esta sección, aprenderás a crear una nueva escena, y aprender como interactuar con esta.

Dede la vista de Montaje de escenas, haz click en el botón _Añadir escena_ para crear una nueva escena. Esto nos mostrará un marcador en el espacio de trabajo, para que indiques donde quieres colocar la nueva escena. Haz click en el espacio de trabajo para colocar la escena.

<figure>
  <img src="/tallergbstudio/img/nuevaescena.png" alt="Primera escena" title="Primera escena" style="display: block; margin-left: auto; margin-right: auto; max-height: 350px;" />
  <figcaption>Figura 1: Primera escena creada</figcaption>
</figure>

Con esto ya tenemos nuestra primera escena creada; si ejecutamos el juego en el emulador, veremos que la escena aparece en pantalla, pero no hay nada más que un fondo y una flecha que corresponde al jugador; vemos que podemos moverlo por la pantalla, pero no hay nada más que hacer.

## Configuración de la escena

Si hacemos click en la escena, podemos ver que en el panel de propiedades aparecen las propiedades de la escena. Aquí podemos cambiar el nombre de la escena, el fondo, la música y otras propiedades.

Vamos a ver algunas de estas propiedades:

* **Nombre de la escena**: Podemos cambiar el nombre de la escena para identificarla fácilmente. Por ejemplo, podemos llamarla "Escena 1" o "Nivel 1".
* **Tipo de Escena**: Podemos seleccionar el tipo de escena para definir el comportamiento del jugador y algunas propiedades de la escena. Por ejemplo, podemos seleccionar "Plataformas" para que el jugador pueda saltar y moverse por la escena. Veremos más adelante en detalle esta propiedad y cómo afecta al comportamiento del jugador y la escena.
* **Fondo**: Podemos seleccionar un fondo para la escena. Esto nos permite cambiar el aspecto visual de la escena y darle un estilo único. Podemos seleccionar un fondo de los recursos del proyecto.
* **Sprite jugador**: Podemos seleccionar el sprite del jugador para la escena. Esto nos permite cambiar el aspecto del jugador y darle un estilo único. Podemos seleccionar un sprite de los recursos del proyecto.
* **Paletas**: Podemos seleccionar las paletas de colores para la escena. Esto nos permite cambiar los colores de los sprites y el fondo de la escena. Podemos seleccionar paletas de los recursos del proyecto; para los diferentes entornos de ejecución (Game Boy/Game Boy Color, Game Boy Player, etc.) podemos seleccionar diferentes paletas para cada uno de ellos.

## Tipos de escena

Vamos a ver los diferentes tipos de escena que podemos seleccionar en GBStudio:

* **Plataformas**: Este tipo de escena permite al jugador moverse y saltar por la escena, interactuando con plataformas y obstáculos. Es el tipo de escena más común para juegos de plataformas.

* **Vista Cenital 2D**: Este tipo de escena permite al jugador moverse en todas las direcciones, como en un juego de rol o aventura. El jugador puede interactuar con objetos y personajes en la escena.

* **Aventura Gráfica**: Este tipo de escena permite al jugador interactuar con objetos y personajes en la escena, resolviendo puzzles y avanzando en la historia del juego. Es ideal para juegos de aventura y narrativa.

* **MataMarcianos (Shot'emup)**: Este tipo de escena permite al jugador disparar a enemigos y esquivar obstáculos, como en un juego de disparos. Es ideal para juegos de acción y arcade.

* **Logo**: Esta tipo de escena permite mostrar un logo o imagen al inicio del juego, antes de que comience la acción. Es ideal para mostrar el logo del desarrollador o del juego.