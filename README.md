# Trabajo de modelos

En este repositorio se encuentran todos los pipelines junto a los archivos que se utilizaron para el desarrollo de este proyecto. 

## Datasets
Esta es una carpeta donde se tienen los archivos que se utilizaron en el trabajo 
1. dataset.csv: Es el dataset que se usa en el entrenamiento de los modelos, ya que es el resultado de la transformación que se le hace al dataset original para que solo contenga datos numéricos. 
2. DatosReales.csv: Es el dataset que se utiliza para evaluar el rendimiento de cada uno de los modelos después de ser entrenados. Es una combinación de datos reales tomados por nosotros y una elaboración de datos ficticios realizados a partir del análisis de los datos.
3. heart_2020_cleaned.csv: Es la base de datos original que encontramos en Kaggle. Es la que utilizamos para visualizar los datos. En base en este archivos se transforma el dataset para que solo tenga datos numéricos.[enlace](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)

## Modelos
 Esta es una carpeta donde se tienen los modelos que se entrenaron y se hizo la validación de los mismos con los datos reales para ver su rendimiento.
 
 ## Proceso de ejecución
 Los pasos para obtener los resultados esperados en la ejecución de los archivos es la siguiente:
 
 1. heart-disease-data-visualization, ya que es allí donde se explica detallamente el contenido del dataset original con sus variables, si hay datos faltantes, valores atípicos y demás. Además de hacer un análisis de cada una de las variables del dataset.
 2. transformacion-dataset, porque es en este donde se transforma el dataset original para que este solo contenga datos numéricos
 3. Ejecutar el archivo de cada uno de los modelos.
 4. Ejecutar Validación_modelos para verificar si los modelos tienen un buen rendimiento. 
