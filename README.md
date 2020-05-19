# Formato Evidencias Tutorías en Línea

![preview](https://raw.githubusercontent.com/BenKuso/Formato-Evidencias-Tutorias-Virtuales/master/images/Formato-tuto.png)

Una Planilla hecha en LaTeX, para el fácil llenado de evidencias, para que registres tus asesorías de forma más rápida y sencilla, con la capacidad de trabajarse on-line. Espero pueda servir como primer acercamiento de mucha gente a LaTeX y les sea útil a los compañeros del programa institucional de tutoría de pares.

## Características
  - Plantilla con datos fácilmente editables
  - Inserta imágenes con una sola línea de código
  - Edita en línea y descarga tu pdf


## Instalación

### 1 - Ingresa a Overleaf
Overleaf es un editor colaborativo de LaTeX on-line.
Ingresa a [Overleaf](https://www.overleaf.com/) y crea una cuenta (puedes hacerla con google).



### 2 - Obtener la plantilla

Abre el enlace de la [plantilla](https://www.overleaf.com/read/smxtdmkdqdgx).

Regresa al menú de tus proyectos, donde verás la plantilla.

![volver](https://raw.githubusercontent.com/BenKuso/Formato-Evidencias-Tutorias-Virtuales/master/images/back.png)

### 3 - Copiar proyecto para poder editar
Notarás que posees la plantilla en una vista protegida no editable. Ubica la sección de acciones en el proyecto y presiona "copy".  Esto agregará un nuevo proyecto llamado "Formato Tutorias (Copy)" que te pertenece, este ya lo puedes editar.

![copiar](https://raw.githubusercontent.com/BenKuso/Formato-Evidencias-Tutorias-Virtuales/master/images/copiar.png)

Por último, puedes renombrar este archivo. Abre el archivo (dando click sobre él). Verás que arriba del todo tiene su nombre, selecciona el lápiz que está al final y pon un nombre con el que lo ubiques. 

![renombrar](https://raw.githubusercontent.com/BenKuso/Formato-Evidencias-Tutorias-Virtuales/master/images/renombrar.png)

![nombrar](https://raw.githubusercontent.com/BenKuso/Formato-Evidencias-Tutorias-Virtuales/master/images/nombrar.png)

¡Listo!

Puedes dejar en tu lista de proyectos el original para repetir el paso anterior cada vez que quieras hacer un documento nuevo o bien, dejar listo uno propio en el que tengas listos ya tus datos. Las posibilidades de uso son muy grandes.

## Para empezar

### Datos personales

Ubica la línea 61 del documento, aquí empiezan las variables, aquellas no señaladas como variables son tus datos personales, que serán raramente editados, como tu nombre, tu ID, tu carrera, etc. Mientras que el resto serán los propios de la asesoría como la fecha y la materia.

![variables](https://raw.githubusercontent.com/BenKuso/Formato-Evidencias-Tutorias-Virtuales/master/images/variables.png)

Los datos se deben encontrar contenidos entre dos llaves, así que no las borres. La fecha tiene por defecto el comando \today que coloca la fecha actual al momento de compilar, pero puedes poner lo que gustes.
A partir de la línea 69 tienes los datos de tus tutorados, cuando sean muchos puedes poner los nombres o ID's en lista y recuerda separar uno de otro con \\\\ como si fueran comas

### Poniendo Imágenes

Tus evidencias serán imágenes, capturas de pantalla y demás. Para colocar una imágen, te he dejado preparado el comando \img.
En el menú de la izquierda ubica la carpeta llamada "Evidencias", da click derecho sobre ella y selecciona "Upload File", arrastra ahí todas tus imágenes.

![evidencias](https://raw.githubusercontent.com/BenKuso/Formato-Evidencias-Tutorias-Virtuales/master/images/evidencias.png)

Dirígete al final del documento, antes de la etiqueta de fin de documento (si no has modificado la plantilla, ve a la línea 124).
Aquí puedes empezar a poner imágenes de la siguiente forma
\img{nombredetuimagen}{tamaño}{descripción}
Reemplaza lo que está entre las llaves por lo que corresponda.
- Nombredetuimagen es el nombre que tiene tu imágen subida previamente a la carpeta - Evidencias.
- Tamaño es la escala, donde 1 es una proporción del 100% del tamaño de tu imágen, 0.5 sería 50%, 1.5 sería 150% etc.
- Descripción es el pie de la imágen, si no deseas poner nada puedes dejarla en blanco {}

En la descripción, si lo deseas, he preparado un comando (\link) para que puedas agregar enlaces a tus vídeos (en caso de que hayas grabado tu asesoría), esto se haría así...

![imagen](https://raw.githubusercontent.com/BenKuso/Formato-Evidencias-Tutorias-Virtuales/master/images/imagen.png)


## Por Último

###Compilar

Para compilar tu documento (generar el archivo pdf) sólo preciona las teclas Ctrl+Enter o presiona el botón verde que dice "Recompile"

###Descargar

Descarga tu documento en pdf presionando el botón de descarga ubicado sobre la visualización del pdf

![descargar](https://raw.githubusercontent.com/BenKuso/Formato-Evidencias-Tutorias-Virtuales/master/images/descargar.png)

Si tienes preguntas, puedes contactar conmigo en la pestaña [Issues](https://github.com/BenKuso/Formato-Evidencias-Tutorias-Virtuales/issues)
