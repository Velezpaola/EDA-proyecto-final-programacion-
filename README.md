# EDA-proyecto-final-programacion-
Proyecto final para la clase de Programacion en la Maestria en Ciencia de Datos de la Universidad de Sonora

## Analisis Exploratorio de Datos (Crimenes de odio en EUA)
Ana Paola Vélez Esquer

### Requerimientos para realizar el ejercicio
Para este ejercicio de creara un documento en Jupiter notebook para tabajar con Python, para esto es recomendable (mas no necesario) trabajar desde el ambiente de Anaconda ya que está disponible para ambientes Windows, macOS y Linux.

__[Aprende a instalar anaconda]https://www.aprendemachinelearning.com/instalar-ambiente-de-desarrollo-python-anaconda-para-aprendizaje-automatico/__

Ya que se cuenta con Anaconda lo primero es acceder a jupyter notebooks a travez de esta, seleccionando el boton "Launch" como se muestra a continuación.
![image](https://user-images.githubusercontent.com/82691330/144663637-662bc516-0e66-46b9-ba28-c97d790bb908.png)

Una vez accediendo se crea un archivo nuevo seleccionando en la esquina superior derecha la opcion "New" y posteriormente escogiendo abrir una notebook de python, como se muestra en la imagen.

![image](https://user-images.githubusercontent.com/82691330/144663841-a84b16ab-53a8-4219-bb91-812a074f22e2.png)

Y ya estamos listos para empezar.

### Descripción de los datos

Para el precente documento se utilizan los datos __[hate_crimes.csv](https://www.kaggle.com/fivethirtyeight/fivethirtyeight-hate-crimes-dataset?select=hate_crimes.csv)__ el cual contiene informacion de los crimene de odio vistos en EUA en el año 2016, utilizados para la creación del articulo __[Higher Rates Of Hate Crimes Are Tied To Income Inequality](https://fivethirtyeight.com/features/higher-rates-of-hate-crimes-are-tied-to-income-inequality/)__
de FiveThirtyEight.

Variable | Descripción
-------------|-----------------
state| Nombre del estado 
median_household_income | Media del ingreso familiar en el 2016
share_unemployed_seasonal | Proporcion de la poblacion desempleada (ajuste estacional) 2016
share_population_in_metro_areas | Porcentaje de la poblacion que vivia en areas metropolitanas en el año 2015
share_population_with_high_school_degree | Porcentaje de adultos de 25 años o mas que contaban con educacion preparatoria terminada en 2009
share_non_citizen | Proporcion de la pobalcion que no eran ciudadanos de EUA en el 2015
share_white_poverty | Proporcion de residentes blanco que vivian en pobreza en el 2015
gini_index | Indice de Gini (indicador de desigualdad) en el 2015
share_non_white | Proporcion de la poblacion no blanca en el 2015
share_voters_voted_trump | Porporcion de la poblacion que voto por Donal Trump para las elecciones del 2016
hate_crimes_per_100k_splc | Crimenes de odio por cada 100,000 habitantes (Southern Poverty Law Center, Nov. 9-18, 2016)
avg_hatecrimes_per_100k_fbi | Promedio anual de crimenes de odio por cada 100,000 habitantes (FBI, 2010-2015)
