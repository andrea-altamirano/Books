# DETECTOR DE LIBROS 

*Por Andrea Guillermina Ramirez Altamirano*

## ¿Cómo ejecutar el código? 

Para poder ejecutar iniciar el proceso para poder utilizar este código es necesario posicionarte en la pantalla inicial y presionar en el archivo que se muestra en la imagen. 

<img src="IMAGEN.png" width="500">

Una vez abierto el documento, entraras a una nueva pantalla donde podrás presionar un nuevo botón para visualizar los procesos en Google Colab. 

<img src="IMAGEN.png" width="500">

Una vez estando en el entorno de trabajo de google asegurate de estar utilizando en tu entorno de ejecución la GPU T4. Esto lo revisas en Entorno de ejecución/ Cambiar tipo de entorno de ejecución / Seleccionar GPU T4. 

<img src="IMAGEN.png" width="500">
<img src="IMAGEN.png" width="500">

Para continuar, debes estar conectado a Google Colab y dar en ejecutar todo, hay un total de ocho celdas de las cuales siete se ejecutaran.

La primera solo copiara el reposito de GitHub
<img src="IMAGEN.png" width="500">

En la segunda encontraremos la descarga de las librerias
<img src="IMAGEN.png" width="500">

Para la tercera celda es dónde hacemos uso de una dataset previamente descargada de Roboflow con las caracteristicas buscadas para este proyecto. 
<img src="IMAGEN.png" width="500">

En la cuarta y quinta celdas encontraremos la carga del modelo utilizado para este proyecto y el entrenamiento a realizar. 
<img src="IMAGEN.png" width="500">

En la seis y siete se trabaja con los resultados obtenidos en base al entrenamiento realizado anteriormente. 
<img src="IMAGEN.png" width="500">

NOTA: Para poder ver los distintos resultados se debe de cambiar el numero que esta entre los corchetes de la celda siete.

Al final vemos un fragmento de código que esta comentado, ese código puede ser utilizado en Visual Studio, se necesita una Webcam, lenguaje en Python, el archivo best generado en Google Colab y un instador para Ultralytics que encontraras en la parte ded abajo. 

<img src="IMAGEN.png" width="500">
<img src="IMAGEN.png" width="500">
(Buscar los tres puntos al costado para descargr el archivo best.pt)

*Colocar en la terminal de Visual Studio lo siguiente:*
& "C:\Users\ruta_modificar" -m pip install ultralytics opencv-python
