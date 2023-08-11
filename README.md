# Clasificador binario de imágenes miscroscópicas en vivo para el disgnóstico de Cancer de Esófago

El presente repositorio se refiere a un curso sobre el Perceptrón, impartido en colaboración con el [Colegio de Matemáticas Bourbaki](https://www.colegio-bourbaki.com/).

Se utiliza Perceptrón lineal para realizar una clasificación binaria de un subconjunto de imágenes provenientes del [Data Challenge by Mauna Kea](https://challengedata.ens.fr/participants/challenges/11/).

Para este clasificador se utilizaron solamente las imágenes de tejido sano y las imágenes de tejido con displasia/cáncer.
De manera que el conjuntode datos está formado por 1,469 imágenes de tejido sano (clase 0)  y 3,594 imágenes de displasia/cáncer (clase 1).

Las imágenes originales fueron escaladas de 519x521 pixeles a 260x260 para reducir el tiempo y la memoria requeridos para el procesamiento. El conjunto de imágenes utilizadas están disponibles en el archivo comprimido [CarpetaImagenes.zip](https://drive.google.com/file/d/1Abi4hjl5djn8X75YCcMXL5htq7iqf7VY/view?usp=sharing), fuera de este repositorio.

Por su parte, el archivo ClasesImagenes.csv, que se ubica en la carpeta Datos de éste repositorio, contiene una tabla donde se identifica el nombre de cada imagen y la clase a la que pertenece.





