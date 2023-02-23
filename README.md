<center> <h1> EDA Pruebas Universitarias Colombia  SaberPro (2018-2021) </h1></center>

## Introducción <br>

*El ICFES (Instituto Colombiano para la Evaluación de la Calidad de la Educación) realiza anualmente las Pruebas Saber Pro para conocer el desarrollo de las competencias de los estudiantes que están por finalizar sus carreras Universitarias.*<br>

Se busca realizar un análisis a los datos que contienen los resultados de estas pruebas desde 2018 hasta 2021 teniendo en cuenta el perfil socioeconómico de cada estudiante. <br>

La fuente de los datos es una [tabla](https://github.com/jospinoponce/EDA_ResultadoPruebasUniversitariasSaberPro/tree/main/Dataset) 
. Tiene las variables **MOD_RAZONA_CUANTITAT_PUNT, MOD_COMUNI_ESCRITA_PUNT,  MOD_LECTURA_CRITICA_PUNT, MOD_COMPETEN_CIUDADA_PUNT,** y **MOD_INGLES_PUNT**. Representan el número de respuestas acertadas por cada estudiante en un rango de 0-300 y en las competencias de **Razonamiento Cuantitativo, Comunicación Escrita, Lectura critica, Competencia Ciudadana** e **Inglés**.<br>


Para evalúar las competencias mencionadas se implementa el desempeño numérico que establece el Icfes. De 1 a 4 (*siendo 1 el más bajo*) por medio de la relación a continuacíon. El desempeño en el área de ingles es  -A1, A1, B1 hasta B2 (*siendo 0.5 el más bajo*)
 <br> 
 

| **Razonamiento cuantitativo,  lectura crítica  competencia ciudadana** |               |        **Inglés**       |               |     |
|:----------------------------------------------------------------------:|:-------------:|:-----------------------:|:-------------:|:---:|
|                         **Preguntas Correctas**                        | **Desempeño** | **Preguntas Correctas** | **Desempeño** |     |
|                                 185-300                                |       4       |         200-300         |       B2      |  4  |
|                                 150-184                                |       3       |         180-199         |       B1      |  3  |
|                                 116-149                                |       2       |         146-179         |       A2      |  2  |
|                                  0-115                                 |       1       |         123-145         |       A1      |  1  |
|                                                                        |               |          0-122          |      -A1      | 0.5 |

*[fuente](https://www.icfes.gov.co/)*

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