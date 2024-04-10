# Incendios Forestales México 2015-2023 | Python | Data Science
![image](https://github.com/Valamca/Fires_Mexico_2015-2023/assets/129345721/3c0f9b0a-3f47-4b12-a86c-2f225b5a73d4)
<ul align = center>

<img src="https://img.shields.io/badge/_Python-f7e172?style=flat&logo=python" />
  <img src="https://img.shields.io/badge/_Jupyter_Notebook-767677?style=flat&logo=jupyter"/>
  <img src="https://img.shields.io/badge/_Pandas-e00484?style=flat&logo=pandas"/>
  <img src="https://img.shields.io/badge/_scikit-learn-f89a36?style=flat&logo=scikit-learn"/>
  
</ul>

## Descripción: 📄
  El presente proyecto muestra el procedimiento para calcular con herramientas de análisis y ciencia de datos, aquellos registros en que las causas de los incendios son desconocidas,
  convirtiendolo en un procedimiento de clasificación. <br>
  De la misma manera, este set de datos será compartido en la plataforma de **Kaggle** para observar a mas personas conseguir diferentes soluciones al mismo problema.

  Enlace: [Forest Fire Registry of Mexico](https://www.kaggle.com/datasets/valamcortes/forest-fire-registry-of-mexico)
  
### Obtención de datos: 💾
Los datos fueron obtenidos del set de datos abiertos proporcionados por CONAFOR <br>
Fuente Original: 
<a href="https://snif.cnf.gob.mx/datos-abiertos/" target="_blank">CONAFOR, 2024</a>

## Configuración del ambiente: 💻 

En este proyecto se emplearon los siguientes programas:

Exploración Inicial: <br>
- Microsoft Excel

Análisis de datos: <br>

- Visual Studio Code<br>
  Para empezar, se puede utilizar cualquier entorno de Python, tan sólo asegúrate que sea una versión 3.X, el base para este proyecto es Jupyter Notebook aunque tu puedes usar el Notebook de tu preferencia como: Google Colab,    Anaconda, DeepNote, Azure, entre otros.<br>
  También necesitarás instalar algunas librerías de Python que son esenciales para este proyecto, como: <br>
  - Pandas 
  - Numpy 
  - Matplotlib
  - Scikit-learn
  - Seaborn

Base de datos: <br>
- Microsoft SQL Server

Visualización de resultados: <br>
- Power BI
  
## Procedimiento: ✔️

Este proyecto de Ciencia de Datos se llevó a cabo en varias etapas diseñadas para garantizar la precisión y la eficacia. <br>

### 1.- Inspección de Datos:<br> <br>
La primera etapa implicó una inspección exhaustiva de los datos, durante la cual se exploró la estructura y la composición de los datos. <br>

Para este caso en particular debido a que el archivo original es un .CSV, fue utilizado Excel para una primera exploración. 

![image](https://github.com/Valamca/Fires_Mexico_2015-2023/assets/129345721/0a0b5c84-bdcb-4434-897c-d7546a9b2615)

El uso de tablas dinámicas es una excelente herramienta para realizar exploraciones rápidas de datos.

![image](https://github.com/Valamca/Fires_Mexico_2015-2023/assets/129345721/9a077033-f897-4934-8c37-5a93ce6c9897)


### 2.- Limpieza de Datos: <br>
Tras la inspección inicial, se realizó una limpieza de datos integral. Este proceso incluyó la normalización de los datos, la sustitución de valores y otros procedimientos necesarios para garantizar la validez de los datos para los análisis posteriores. <br>

Para la limpieza de datos se opto por usar Python con Notebooks de Jupiter, esto debido a que el siguiente paso del análisis de datos es dependiente de este mismo.

![image](https://github.com/Valamca/Fires_Mexico_2015-2023/assets/129345721/1dd9e99c-b19e-417e-a668-f94a7eb68c68)

### 3.- Implementación de Machine Learning: <br>
Una vez limpios los datos, se implementaron modelos de Machine Learning para predecir los datos faltantes. Esto permitió la conformación de un conjunto de datos válido y completo para el análisis de datos.


### 4.- Consolidación de Datos: <br>
Los datos se consolidaron posteriormente en una base de datos relacional. Para los propósitos de este proyecto, se optó por SQL Server debido a su integración sencilla con Power Apps.

![image](https://github.com/Valamca/Fires_Mexico_2015-2023/assets/129345721/8629749a-f17f-437f-b846-6cab29e13551)

### 5.- Creación de un Tablero de Control:<br>
Finalmente, se creó un tablero de control en Power BI para visualizar los resultados obtenidos a través de este procedimiento.

![image](https://github.com/Valamca/Fires_Mexico_2015-2023/assets/129345721/9d890f5d-3cb0-492a-bb04-e14257aedcb4)

El Panel de control puede ser encontrando en la siguiente dirección:
<a href="https://app.powerbi.com/view?r=eyJrIjoiNjZlYTM0ZmYtOTBiMS00OWMwLThjNmMtOGFjYzAyYmE0NjkxIiwidCI6IjAzMGU5NTFkLTZlZmQtNDJmNS04NDI3LWJhYjYzMmNmODAxMCIsImMiOjR9&pageName=ReportSection" target="_blank">Incendios Forestales 2015-2023</a>

## Conclusiones: 💡

Este proyecto de Ciencia de Datos ha demostrado ser un ejercicio exhaustivo y valioso en el manejo y análisis de datos. A través de una serie de pasos cuidadosamente diseñados, desde la inspección y limpieza de datos hasta la implementación de modelos de Machine Learning y la consolidación de datos, logrando transformar un conjunto de datos crudos en información significativa y utilizable.<br>
La integración exitosa con SQL Server y Power Apps ha permitido una visualización efectiva de los resultados, lo que facilita la interpretación y el uso de los datos. El tablero de control creado proporciona una representación visual intuitiva de los resultados obtenidos.
  
**Desarrollador** :wink: 

 <img src="https://avatars.githubusercontent.com/u/129345721?v=4" width=115>
 
 **Francisco Valam Cortes**  <br>[<sub>GitHub</sub>](https://github.com/ValamCA) <img src="https://i.postimg.cc/hPxhb2YB/icons8-github-50.png" width =16>
 <br>[<sub>Linkedin </sub> ](https://www.linkedin.com/in/franciscovalamca/)<img src="https://i.postimg.cc/C5LJHycc/icons8-linkedin-48.png" width =16 ><br>
 [<sub>Twitter</sub>](https://twitter.com/FNiggalam)<img src="https://i.postimg.cc/xTrL2ND9/icons8-twitter-48.png" width =16 ><br>
