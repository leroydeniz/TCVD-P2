# Práctica 2
Tipología y Ciclo de Vida de los Datos<br/>
Máster en Ciencia de Datos<br/>
Universitat Oberta de Catalunya <br/>

<!-- Tabla de contenidos -->
<details>
  <summary>Indice</summary>
  <ol>
    <li><a href="#Descripción">Descripción</a></li>
    <li><a href="#Miembros-del-equipo">Miembros del equipo</a></li>
    <li><a href="#Ficheros-del-código-fuente">Ficheros del código fuente</a></li>    
    <li><a href="#Librerias">Librerias</a></li>
    <li><a href="#Librerías-de-gráficos">Librerias de gráficos</a></li>
    <li><a href="#Conjunto-de-datos">Conjunto de datos</a></li>
    <li><a href="#Video">Video</a></li>
    <li><a href="#Recursos">Recursos</a></li>
    <li><a href="#Licencia">Licencia</a></li>
  </ol>
</details>

## Descripción
Con esta práctica se pretende aprender a identificar los datos relevantes para un proyecto analítico y usar las herramientas de integración, limpieza, validación 
y análisis de las mismas sobre el conjunto de datos Red Wine Quality

## Miembros del equipo
El equipo esta integrado por: 
* Leroy Deniz Pedreira
* David Muñoz Bertrán

## Ficheros del código fuente
El proyecto se estructura de la siguiente manera: <br/>
* **TCVD-P2/:** Raíz del proyecto <br/>
* **TCVD-P2/datasets/:** Directorio donde esta almacenado el conjunto de datos con el que se realizara la practica <br/>

## Librerias
El script hace uso de las siguientes librerias:

 * pandas
  ```sh
  import pandas as pd # Pandas para manejo de datasets
  ```
 * numpy
  ```sh
  import numpy as np # Importar Numpy para manejo de vectores
  ```
 * scipy
  ```sh
  from scipy import stats # Scipy para utilizar funciones de detección de outliers
  ```
  * math
  ```sh
  import math # math para funciones matemáticas
  ```
  * skim
  ```sh
  from skimpy import skim # para visualizar datos estadísticos de un dataset
  ```
  * KBinsDiscretizer
  ```sh
  from sklearn.preprocessing import KBinsDiscretizer # Importa librería para discretizar usando k-Means
  ```
  * statsmodels
  ```sh
  import statsmodels.api as sm # Permite aplicar el logaritmo a las variables de cara a normalizar
  ```


## Librerías de gráficos
  * pyplot
  ```sh
  import matplotlib.pyplot as plt
  ```
  * style
  ```sh
  from matplotlib import style
  ```
 * seaborn
  ```sh
  import seaborn as sns
  ```

## Conjunto de datos
El dataset con el que se realiza la práctica se puede visualizar/descargar desde:

https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

El conjunto de datos contiene muestras de vino donde se recogen los valores de diferentes variables fisicoquimicas.


## Recursos
Calvo M., Subirats L., Pérez D. (2019). Introducción a la limpieza y análisis de los datos. Editorial UOC.
Conover, W. J., Johnson, M. E. and Johnson M. M. (1981). A comparative study of tests for homogeneity of variances, with applications to the outer continental shelf biding data. Technometrics, 23(4), 351-361.
Fligner, M.A. and Killeen, T.J. (1976). Distribution-free two-sample tests for scale. ‘Journal of the American Statistical Association.’ 71(353), 210-213.
Jason W. Osborne (2010). Data Cleaning Basics: Best Practices in Dealing with Extreme Scores. Newborn and Infant Nursing Reviews; 10 (1): pp. 1527-3369.
Jiawei Han, Micheine Kamber, Jian Pei (2012). Data mining: concepts and techniques. Morgan Kaufmann.
Levene, H. (1960). In Contributions to Probability and Statistics: Essays in Honor of Harold Hotelling, I. Olkin et al. eds., Stanford University Press, pp. 278-292.
Megan Squire (2015). Clean Data. Packt Publishing Ltd.
OpenIntro Statistics: Fourth Edition by David Diez, Mine Çetinkaya-Rundel, Christopher Barr https://amzn.to/3vVcwa4.
Peter Dalgaard (2008). Introductory statistics with R. Springer Science & Business Media.
Team, D. S. (2020, 15 diciembre). ¿Qué es una Matriz de Correlación? DATA SCIENCE. Recuperado 14 de mayo de 2022, de https://datascience.eu/es/matematica-y-estadistica/que-es-una-matriz-de-correlacion/
Tutorial de Github https://guides.github.com/activities/hello-world.
Wes McKinney (2012). Python for Data Analysis. O’Reilley Media, Inc.

## Licencia
