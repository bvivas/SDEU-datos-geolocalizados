# Datos Geolocalizados - SDEU

Práctica de Datos Geolocalizados de la asignatura Sistemas Distribuidos, Empotrados y Ubicuos, EPS-UAM.  
Basado en [phaya - Real Life Analytics](https://github.com/phaya/real-life-analytics).  

En este proyecto se analizan los datos relativos a los trayectos realizados por los taxis en la ciudad de Nueva York durante el 14 de enero de 2013, extrayéndose conclusiones acerca de los hábitos de movilidad de esta población (trayectos más frecuentes, horas punta, lugares más demandados...). Por otra parte, se buscan los Starbucks más frecuentados de la ciudad en función de los viajes previamente analizados.

![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white) ![RStudio](https://img.shields.io/badge/RStudio-4285F4?style=for-the-badge&logo=rstudio&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

- [Instalación](#instalación)
- [Datasets](#datasets)
- [Ejecución](#ejecución)
- [Créditos](#créditos)

## Instalación

Será necesario tener R instalado y un IDE donde se puedan visualizar los resultados (probado con RStudio).  

Se utilizarán los siguientes paquetes:  
```
install.packages("tidyverse")
install.packages("cowplot")
install.packages("hexbin")
install.packages("lubridate")
install.packages("prettydoc")
install.packages("scales")
```

## Datasets

Los datasets del proyecto deberán ir dentro de un directorio `/data`.

- [Taxis NYC](https://www.dropbox.com/s/3px4xtwb0z9r2n2/trip_data_2013-01-14.csv?dl=1): contiene todos los trayectos en Taxi realizados en la ciudad de Nueva York durante el día 14 de enero de 2013.  
*Tamaño: 73.4 MB*
- [Starbucks NYC](https://www.dropbox.com/s/043ake4u0q6xe05/All_Starbucks_Locations_in_the_US_2013.csv?dl=1): contiene la coordenadas de los Starbucks que había en Nueva York en el año 2013.  
*Tamaño: 3.9 MB*

## Ejecución

Será necesaio crear el directorio `/data` e introducir ahí los ficheros de datos. Una vez hecho, se podrá ejecutar el notebook `nyc_taxi.Rmd` para obtener de nuevo los resultados.

## Créditos
[Belén Vivas García](https://github.com/bvivas)  
[Martín Salinas Antón](https://github.com/MartinSalinas98)  
[phaya - Real Life Analytics](https://github.com/phaya/real-life-analytics) (base)
