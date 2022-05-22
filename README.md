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
    <li><a href="#Ejecución">Ejecución</a></li>
    <li><a href="#Datos-Obtenidos">Datos obtenidos</a></li>
    <li><a href="#Video">Video</a></li>
    <li><a href="#Recursos">Recursos</a></li>
    <li><a href="#Licencia">Licencia</a></li>
  </ol>
</details>

## Descripción
Con esta práctica se pretende aprender a identificar los datos relevantes para un proyecto analítico y usar las herramientas de integración, limpieza, validación 
y análisis de las mismas sobre el conjunto de datos Red Wine Quality (https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009).
El conjunto de datos contiene muestras de vino donde se recogen los valores de diferentes variables fisicoquimicas.

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
