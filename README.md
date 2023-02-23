<center> <h1> EDA Pruebas Universitarias Colombia  SaberPro (2018-2021) </h1></center>

## Introducción <br>

*El ICFES (Instituto Colombiano para la Evaluación de la Calidad de la Educación) realiza anualmente las Pruebas Saber Pro para conocer el desarrollo de las competencias de los estudiantes que están por finalizar sus carreras Universitarias.*<br>

Se pretende llevar a cabo un análisis de datos a los resultados de estas pruebas desde 2018 hasta 2021 teniendo en cuenta el perfil socioeconómico de cada estudiante suministrado por el ICFES. <br>

Para el desarrollo del proyecto se realiza:
- Data Enginery

**Data Cleaning**<br>
**EDA**<br>
**Creación de DataWarehouse**<br>
**Dashboard** <br>


 

<hr>

## Objetivos

* Establecer el desempeño de que tuvieron los estudiantes en las pruebas.<br>
* Generar analísis y visualizaciones del comportamiento de los datos en las pruebas.<br>
* Determinar que factores influyen más el desempeño de la prueba.<br>
* Validar si el contexto socioeconomico influye en el buen desempeño de las pruebas.<br>
<hr>

## Recursos implementados:
DataSource: [ICFES_origen](https://www.datos.gov.co/Educaci-n/Resultados-nicos-Saber-Pro/u37r-hjmu) <br>
Python Version: 3.9<br>
Packages: pandas, numpy,  matplotlib, seaborn
<hr>

## Data Cleaning
- Se eliminan  variables no relevantes al analisís.<br>
- Se realiza gestión de datos nulos para variables categoricas, numéricas.<br>
- Se da formato a las columnas del dataframe. 
<hr>

## Datos atípicos
- Se grafica la distribución de las variables numéricas más representativas.
- Se usa metodología 3 Sigma para detección de outliers.

<img src="Anexos/_src/image_1.png" width="700" height="350px"> 

<hr>

## EDA
- Se generan nuevas variables, correspondientes al desempeño general. 
- Se grafican las variables categoricas.
- Se grafican las variables numericas.<br>



*variables categoricas*

<img src="Anexos/_src/image_2.png" width="600" height="400px">
<img src="Anexos/_src/image_3.png" width="600" height="200px">




<img src="Anexos/_src/image_4.png" width="900" height="1600px">

<hr>

## Correlación de varibles

<hr>


## Concluciones

<hr>