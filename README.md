# World-Deaths-and-Causes-EDA

Análisis Exploratorio de Datos (EDA)
Este repositorio contiene el análisis exploratorio de datos realizado sobre un conjunto de datos que registra las muertes por países causadas por diferentes tipos de enfermedades, así como información sobre los años comprendidos entre 1990 y 2019. Además, se incorpora un segundo conjunto de datos que contiene la densidad de población de los continentes durante el mismo período de tiempo.

Descripción de los Datos

El conjunto de datos principal consiste en registros de muertes por país debido a distintos tipos de enfermedades, que hemos agrupado de la siguiente manera:

- Enfermedades Neurodegenerativas
- Enfermedades Infecciosas
- Enfermedades Nutricionales
- Enfermedades Cardiovasculares
- Trastornos Respiratorios
- Trastornos Neonatales
- Trastornos Mentales y de Conducta
- Enfermedades Crónicas No Transmisibles
- Lesiones y Traumatismos
- Trastornos Digestivos
- Otros

Se ha decidido hacer foco principalmente en las enfermedades infecciosas y cardiovasculares debido a su relevancia en el ámbito de la salud pública y la epidemiología.

Adicionalmente y, con el objetivo de facilitar el análisis, los países han sido agrupados en continentes: América, Asia, África, Europa y Oceanía.

Además, se cuenta con un segundo conjunto de datos que proporciona información sobre la densidad de población de los continentes durante el mismo período de tiempo (1990-2019).

Proceso de Limpieza y Preparación

El proceso de limpieza de datos incluyó:

Eliminación de valores nulos o faltantes.
Agrupación de países en continentes.
Agrupación de enfermedades en categorías concretas.


Durante el análisis, se plantean las siguientes hipótesis a validar:

Hipótesis 1: A mayor densidad de población, mayores muertes.

Se supone que la densidad de población puede estar relacionada con el número de muertes causadas por enfermedades. Esta hipótesis se investigará mediante un análisis de correlación entre la densidad de población y el número de muertes por enfermedad.

Hipótesis 2: Las muertes han descendido a lo largo de los años.

Se espera que con el avance en la medicina y la mejora de las condiciones sanitarias, el número de muertes haya disminuido a lo largo del tiempo. Esta hipótesis se evaluará mediante un análisis de tendencias a lo largo de los años.

Hipótesis 3: Las enfermedades infecciosas han disminuido a lo largo de los años.

Con los avances en vacunas y tratamientos, se espera que las enfermedades infecciosas hayan disminuido en frecuencia y mortalidad. Esta hipótesis se verificará mediante un análisis de tendencias específicamente para enfermedades infecciosas.

Hipótesis 4: Las enfermedades cardiovasculares han aumentado a lo largo de los años.

Dado el cambio en los estilos de vida y los factores de riesgo asociados, se supone que las enfermedades cardiovasculares pueden haber aumentado en prevalencia y mortalidad. Esta hipótesis se evaluará mediante un análisis de tendencias específicamente para enfermedades cardiovasculares.

Estructura del Repositorio

cause_of_deaths.csv: Contiene los datos sobre muertes por enfermedades.
evolucion_en_la_densidad_de_poblacion_de_cada_continente.csv: Contiene los datos sobre densidad de población por continente.
EDA_MUERTES_FINAL.ipynb: Jupyter Notebook que contiene el código y los pasos del análisis exploratorio de datos.


Resultados Esperados

Se espera que este análisis proporcione información útil sobre la relación entre la densidad de población, el número de muertes por enfermedad y las tendencias a lo largo del tiempo. Los resultados podrían ser relevantes para comprender mejor la evolución de la salud pública y para informar futuras investigaciones en el campo médico y epidemiológico.




