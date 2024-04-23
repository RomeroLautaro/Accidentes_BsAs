Siniestros viales en la Ciudad Autónoma de Buenos Aires, Argentina

## Introducción

Asumimos el rol de un Data Analyst, formando parte del equipo de OBSERVATORIO DE MOVILIDAD Y SEGURIDAD VIAS (OMSV). Que se encarga de llevar adelante la Secretaria de Transporte del Gobiernos de Buenos Aires (CABA).

El rol consiste en generar infirmacion Util para las autoridades locales, lo cual le ayude a tomar decisiones y conciencia de las victimas que sufren siniestros viales ocurrido en CABA. Lo cual vamos a llevar adelante el trabajo con unos dataset de los periodos 2016-2021.

El producto final conlleva una realizar Analisis de datos, realizar conclusiones y presentar un dashboard interactivo que interprete la informacion y el analisis.


## Contexto

Los siniestros viales, también conocidos como accidentes de tráfico o accidentes de tránsito, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos. Estos incidentes pueden tener consecuencias que van desde daños materiales hasta lesiones graves o fatales para los involucrados.

Los siniestros viales son una preocupación importante debido al alto volumen de tráfico y la densidad poblacional. Estos incidentes pueden tener un impacto significativo en la seguridad de los residentes y visitantes de la ciudad, así como en la infraestructura vial y los servicios de emergencia.
Actualmente, según el censo poblacional realizado en el año 2022, la población de CABA es de 3121707 de habitantes. 

## Datos

Para este proyecto se trabajó con la Bases de Víctimas Fatales en Siniestros Viales que se encuentra en formato de Excel y contiene dos pestañas de datos:

HECHOS: que contiene una fila de hecho con id único y las variables temporales, espaciales y participantes asociadas al mismo.
VICTIMAS: contiene una fila por cada víctima de los hechos y las variables edad, sexo y modo de desplazamiento asociadas a cada víctima. Se vincula a los HECHOS mediante el id del hecho.

## Tecnologías utilizadas

Para la elaboración de este proyecto se utilizó Python y Pandas para los procesos de extracción, transformación y carga de los datos, como así también para el análisis exploratorio de los datos. En el siguiente apartado se describen los resultados del análisis. Finalmente, para la construcción de un dashboard interactivo se utiliza Power BI

## ETL y EDA

Se realizó un proceso de extracción, transformación y carga de los datos (ETL), tanto de "HECHOS" como "VÍCTIMAS", donde se estandarizaron nombres de las variables, se analizaron nulos y duplicados de los registros, se eliminaron columnas redundantes o con muchos valores faltantes, entre otras tareas. Una vez finalizado este proceso se procedió a unir los dos conjuntos en uno solo denominado.
Luego procedió a realizar un análisis exploratorio exahustivo (EDA), con la finalidad de encontrar patrones que permitan generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales.

## Análisis de los Datos


## KPI

En función de lo analizado en el punto anterior, se plantearon tres objetivos en relación a la disminución de la cantidad de víctimas fatales de los siniestros viales, desde los cuales se proponen tres indicadores de rendimiento clave o KPI.

Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior*

Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior*

## Conclusiones y recomendaciones

Entre los años 2016 a 2021 se registraron 750 víctimas fatales en accidentes de tránsito. La mayor cantidad de las víctimas se registraron durante la semana. En cuanto a la franja horaria, ocurre entre las 5 y las 8 de la mañana, pero durante los fines de semana. Diciembre es el mes que resulta con el máximo de fallecimientos en el período analizado.

La Mayor víctimas fatales fueron de sexo masculino. El vehiculo del cual tiene mayor participacion en un accidente son las motos. Los homicidios ocurrió en algún punto de las avenidas de CABA

Finalmente, para el segundo semestre del año 2021, se cumplió con el objetivo de bajar la tasa de homicidios en siniestros viales, pero no se cumplieron los objetivos de reducir la cantidad de accidentes mortales en motociclistas.

Recomendaciones

Impulsar el equipamiento total de los elementos de seguridad, lo cual podria ayudar a prevenir muertes
Realizar campañas de seguridad vial entre los días viernes a lunes, intensificando particularmente en el mes de Diciembre.
Dirigir las campañas de seguridad hacia el sexo masculino, especialmente en cuanto a conducción en moto.
Exigir la reducir las velocidades para todos los vehiculos en las avenidas en horarios picos.
