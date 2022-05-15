# MachineLearning_mean
 AirbnB es una plataforma de negocios que ha cambiado la forma de viajar de las personas y se presenta como un negocio tanto para las personas que ofrecen sus servicios como para los clientes, por eso la importancia de  estudiar su comportamiento y poder predecri resultados, en nuestro caso usaremos modelos de Machine Learning para predecir el precio de una propiedad.
 El dataset que usamos es extraído de Airbnb mediante técnicas de scraping.
Dentro de las opciones recomiendo utilizar el extract (“Only the 14780 selected records”).
El objetivo es obtener un modelo capaz de predecir el precio del alquiler, cuya variable objetivo es el Precio
Haremos uso de librerias como 
numpy  
pandas  

 matplotlib.pyplot  
  matplotlib.colors import ListedColormap
%matplotlib inline
 os
  seaborn as sns
from matplotlib import pyplot as plt
 matplotlib.ticker as ticker
 
 Lenguaje Python

# Con esta Práctica se intenta:
TRATAMIENTO DE LOS DATOS
a. Análizar un dataset con información real, lo que conlleva un mayor tiempo a la hora de hacer el procesado de los datos, ya que como es sabido, basura que entra bausra que sale.
   para ello, hemos descartados características que no influyen de manera significativa usando la intución y la matriz de correlación
   se han intentado manejar outliers, observados mediante diagramas de boxplot e histográmas.
B. Imputación de missing values: usando la moda en las variables númericas y cualitativas
c. Categorízamos variables cualitativas.
DIVISIÓN TRAIN Y TEST 
para evaluar la capacidad predictiva del modelo y poder hacer una estimación del error .
ESTANDARIZACIÓN Y ESCALADO DE VARIABLES 
Usamos el StandardScaler 
USAMOS CROSSVALIDATION
Para encontrar los mejores valores 
APLICAMOS MODELOS
