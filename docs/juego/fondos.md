# Fondos

Habrás observado que en la sección de propiedades de la escena, podemos seleccionar un fondo para la escena. Esto nos permite cambiar el aspecto visual de la escena y darle un estilo único. Podemos seleccionar un fondo de los recursos del proyecto.

Un fondo, es una imagen que se muestra en la parte posterior de la escena, detrás de los sprites y objetos. Los fondos pueden ser estáticos o animados, y pueden tener diferentes tamaños y resoluciones.

Un fondo en Game Boy debe tener una resolución de 160x144 píxeles, y puede tener hasta 4 colores diferentes (en el caso de Game Boy Color, se pueden utilizar hasta 32 colores diferentes). Los fondos se pueden crear utilizando herramientas de edición de imágenes, como GIMP o Photoshop, y luego se pueden importar a GBStudio como recursos del proyecto.

Un fondo para Game Boy, debe tener los siguientes colores:

* Color 0: #071821. <span style="background-color: #071821; color: #ffffff;">(Color de fondo)</span>
* Color 1: #306850. <span style="background-color: #306850; color: #ffffff;">(Color de primer plano)</span>
* Color 2: #86c06c. <span style="background-color: #86c06c; color: #000000;">(Color de segundo plano)</span>
* Color 3: #e0f8cf. <span style="background-color: #e0f8cf; color: #000000;">(Color de tercer plano)</span>

### Importar un fondo a GBStudio

Vamos a importar un fondo a GBStudio para utilizarlo en nuestra escena. Para ello, sigue estos pasos:

1. Desde GbStudio, en la parte superior derecha haz click en el botón abrir carpeta de recursos. Esto abrirá la carpeta de recursos del proyecto en tu explorador de archivos.
2. En la carpeta _assets/backgrounds_, copia el archivo de imagen del fondo que quieras utilizar. Asegúrate de que el archivo tenga una resolución de 160x144 píxeles y cumpla con los requisitos de color mencionados anteriormente.

Una vez hecho esto, ya podemos utilizarlo en nuestras escenas como fondo.

### Seleccionar un fondo para la escena

Por último, vamos a seleccionar el fondo que acabamos de importar para nuestra escena. Para ello, sigue estos pasos:

1. Haz click en la escena que quieras modificar para ver sus propiedades en el panel de propiedades.
2. En la sección de propiedades de la escena, busca la opción _Fondo_ y haz click en el botón de selección de fondo.
3. Se abrirá una ventana con los fondos disponibles en el proyecto. Selecciona el fondo que acabas de importar y haz click en _Aceptar_.

<figure>
  <img src="/tallergbstudio/img/escenaconfondo.png" alt="Escena con fondo" title="Escena con fondo" style="display: block; margin-left: auto; margin-right: auto; max-height: 350px;" />
  <figcaption>Figura 1: Escena con fondo</figcaption>
</figure>