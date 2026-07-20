# Música y Sonido

A la hora de trabajar con Game Boy o Game Boy Color, es importante tener en cuenta que el hardware de estas consolas tiene limitaciones en cuanto a la cantidad de canales de audio que se pueden utilizar al mismo tiempo. En el caso de la Game Boy, solo se pueden reproducir 4 canales de audio simultáneamente, lo que limita la complejidad de las melodías y los efectos de sonido que se pueden usar en el juego.

### Música

GBStudio nos permite añadir música a nuestro juego, para ello, podemos utilizar archivos de música en formato .mod o .s3m. Estos archivos se pueden crear utilizando herramientas de edición de música, como MilkyTracker o OpenMPT, y luego se pueden importar a GBStudio como recursos del proyecto.

Para importar un archivo de música a GBStudio, simplemente copia el archivo de música en la carpeta _assets/music_ del proyecto. Asegúrate de que el archivo cumpla con los requisitos de formato mencionados anteriormente.

### Reproducir música en una escena

Para reproducir música en una escena, seleccionamos la escena a utilizar, y en el panel de eventos de la parte inferior derecha, en la pestaña de _Al iniciar_, añadimos una acción de tipo _Reproducir música_, y seleccionamos el archivo de música que hemos importado previamente. Esto permitirá que la música se reproduzca automáticamente cuando se inicie la escena.

Prueba a añadir música a la primera escena de nuestro juego, utiliza el ejemplo que incluye GBStudio que se llama _template.mod_.

### Editor de música

GBStudio también incluye un editor de música integrado, que nos permite crear y editar música directamente dentro del programa. Para acceder al editor de música, se realizará desde la vista de _música_, que se encuentra en la parte superior izquierda de la ventana de GBStudio. Esto abrirá la ventana del editor de música, donde podemos crear y editar música utilizando diferentes instrumentos y efectos.

<figure>
  <img src="/tallergbstudio/img/editormusica.png" alt="Editor de Música" title="Editor de Música" style="display: block; margin-left: auto; margin-right: auto; max-height: 450px;" />
  <figcaption>Figura 1: Editor de Música</figcaption>
</figure>

## Efectos de sonido

GBStudio nos permite añadir efectos de sonido a nuestro juego, para ello, podemos utilizar archivos de sonido en formato .wav o .ogg. Estos archivos se pueden crear utilizando herramientas de edición de audio, como Audacity o FL Studio, y luego se pueden importar a GBStudio como recursos del proyecto.

Para importar un archivo de sonido a GBStudio, simplemente copia el archivo de sonido en la carpeta _assets/sounds_ del proyecto.  Asegúrate de que el archivo cumpla con los requisitos de formato.

!!! info "Formatos de Sonido compatibles"
    * Formato: .wav (8bits mono), VGM o SAV.
    * Duración: Menos de 3.64 segundos.


Además, GBStudio permite emitir efectos de sonido utilizando el sintetizador de audio integrado, que nos permite crear efectos de sonido directamente dentro del programa. Para ello, podemos utilizar la acción de tipo _Reproducir efecto de sonido_, y seleccionar el efecto de sonido que queremos reproducir.

!!! info "Efectos de Sonido integrados"
    GBStudio incluye varios efectos de sonido integrados, que podemos utilizar en nuestro juego. Estos efectos de sonido se pueden encontrar en la carpeta _assets/sounds_ del proyecto, y se pueden reproducir utilizando la acción de tipo _Reproducir efecto de sonido_.

    * **Pitido**: Permite definir un pitido de tono y duración específicos.
    * **Tono**: Permite definir un tono de frecuencia y duración específicos.
    * **Ruido**: Permite definir un ruido de duración específica.

Prueba a poner varios efectos de sonido en la última escena al golpear el enemigo final, para ello, puedes utilizar los efectos de sonido integrados que incluye GBStudio, o crear tus propios efectos de sonido utilizando el editor de música integrado.