#  <h1>  p_03-001 Analísis de Datos a Pruebas Universitarias Colombia  SaberPro (2018-2021) </h1> 

## Introducción

*El ICFES (Instituto Colombiano para la Evaluación de la Calidad de la Educación) realiza anualmente las Pruebas Saber Pro para conocer el desarrollo de las competencias de los estudiantes que están por finalizar sus carreras Universitarias.*<br>

Se pretende llevar a cabo un análisis de datos a los resultados de estas pruebas desde 2018 hasta 2021 teniendo en cuenta el perfil socioeconómico de cada estudiante suministrado por el ICFES. <br>

Para el desarrollo del proyecto se realiza:

**Analísis Exploratorío de Datos EDA.**<br>
**Creación de DataWarehouse.**<br>
**Visualización de datos.** <br>
<hr>

## Objetivos

* Establecer el desempeño de que tuvieron los estudiantes en las pruebas.<br>
* Generar analísis y visualizaciones del comportamiento de los datos en las pruebas.<br>
* Determinar que factores influyen más el desempeño de la prueba.<br>

<hr>

## Recursos implementados:

Python Version: 3.9<br>
Packages: pandas, numpy,  matplotlib, seaborn
<hr>

##  Analísis Exploratorío de Datos EDA

Se realiza un EDA a una tabla de datos [data_origen](https://www.datos.gov.co/Educaci-n/Resultados-nicos-Saber-Pro/u37r-hjmu) alojada en los repositorios de los datos abiertos del Gobierno de Colombia.  https://www.datos.gov.co/. <br>


### Limpieza de Datos
[preview](https://github.com/jospinoponce/EDA_ResultadoPruebasUniversitariasSaberPro/blob/main/Dataset/preview.md) de la tabla antes de realizar el EDA.. <br>
- Se eliminan  variables no relevantes al analisís.<br>
- Se realiza gestión de datos nulos para variables categoricas, numéricas.<br>
- Se da formato, ajustes a los tipos de variables presentes en el proyecto.<br> 

[Control de cambios](https://github.com/jospinoponce/EDA_ResultadoPruebasUniversitariasSaberPro/tree/main/Anexos/control_cambios) muestra detalladamente los cambios realizados en este proceso.
### Datos atípicos
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

### Interpretación de los datos

### Correlación de varibles

<hr>

## DataWarehouse
<hr>

## Concluciones

<hr>