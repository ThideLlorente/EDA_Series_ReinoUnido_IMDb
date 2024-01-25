## EDA - ¿Qué tipo de serie gusta más al público general?

### Autore
>Thide E. Llorente Llorente, para The Bridge

### Fecha
>25 de enero de 2024

### Librerías empleadas
>numpy

>pandas

>selenium

>time

>matplotlib

>seaborn

### Recursos utilizados
>Apuntes proporcionados por el profesor Alberto Romero

>Resolución de dudas por parte de los profesores Alberto Romero y Antonio Macorra

>Visual Studio Code

>Stack Overflow para resolución de dudas

>debugging de Python

### Datos utilizados
> Datos obtenidos de la página web de IMDb (https://www.imdb.com/), usando la ténica de web scraping.

### Descripción del proyecto

Mi Análisis Exploratorio de Datos (EDA) pretende responder a una hipotética pregunta de negocio en relación con cuáles son las características de las series (en cuanto a formato —serie o miniserie—, público al que se dirige —mayores de 12 años, mayores de 16 años o para todos los públicos— y género —comedia, suspense o drama—) mejor valoradas.
Concretamente, parto de la idea de que una productora de Reino Unido quiere producir una serie y quiere saber cuáles han sido las características más repetidas en las series, así como las características de las series mejor valoradas, en este último siglo. Para ello, he tomado datos de la página web de IMDb (https://www.imdb.com/), de las series producidas en Reino Unido del año 2000 en adelante, usando la ténica de web scraping.

Mi proyecto ha constado de cinco fases principales, que se corresponden con los Notebooks recogidos en la carpeta ``EDA_Thide.zip``
1)	**Delimitación de los criterios de inclusión y extracción de las URL de las series que cumplían dichos criterios**. Se puede consultar en el documento ``FASE_1_Extraer_URL.ipynb``
2)	**Extracción de los datos de cada una de esas series y elaboración del DataFrame**. Se puede consultar en el documento ``FASE_2_Extraer_Datos.ipynb``
3)	**Limpieza del DataFrame con los datos de las series**. Se puede consultar en el documento ``FASE_3_Limpiar_df.ipynb``
4)	**Análisis de los datos del DataFrame**. Se puede consultar en el documento ``main.ipynb``
5)	**Extracción de conclusiones**. Se puede consultar en ``Presentación_EDA_Thide.pdf`` y en ``Memoria_EDA_Thide.pdf``
