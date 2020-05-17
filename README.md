# Classificador binario de imagenes miscroscópicas en vivo para el disgnóstico de Cancer de Esófago

Se utiliza Perceptrón lineal para realizar una clasificación binaria de un subconjunto de imagenes provenientes del Data Challenge by Mauna Kea 
(Link of the challenge : https://challengedata.ens.fr/participants/challenges/11/)

Para este clasificador se utilizaron solamente las imagenes de tejido sano y las imágenes de tejido con displasia/cáncer.
De manera que el conjuntode datos está formdado por 1,469 imágenes de tejido sano (clase 0)  y 3,594 imágenes de displasia/cáncer (clase 1).Las imagenes originales fueron reducidas de 519x521 pixeles a 260x260 para reducir el tiempo y la memoria requeridos para el procesamiento. El conjunto de imagenes utilizadas están disponibles en https://drive.google.com/open?id=1olGkDPm4mpOil7YvyCvVjA5kSck-SClh

El archivo ClasesImagenes.csv contiene una tabla donde se identifica el nombre de cada imagen y la clase a la que pertenece.





