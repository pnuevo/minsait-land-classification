# minsait-land-classification
Hace unas semanas participamos, Jorge Galán Gómez, Ángeñ Fombellida de la Fuente y yo (Pablo Nuevo Tapioles)
en el reto MINSAIT LAND CLASSIFICATION del #Dataton  UniversityHack2020 de GRUPO CAJAMAR. 
El reto consistía en el desarrollo de un modelo de clasificación de suelo a partir de imágenes proporcionadas por el 
satélite Sentinel II del servicio Copernicus de la Agencia Espacial Europea. 
La principal dificultad a la que nos enfrentamos fue que el  fichero de datos estaba muy desbalanceado, 
ya que casi el 90% de los datos pertenecían a la misma clase, y el 10% restante se encontraba distribuido entre las demás. 
Para solucionar esto, probamos con algunas técnicas de balanceo de datos como SMOTE. 
Sin embargo, el resultado no mejoraba mucho y el tiempo de ejecución era muy elevado. 
Al final, decidimos crear un conjunto de datos balanceado para evaluar el modelo y ajustar 
los metaparámetros en función de estos resultados.
