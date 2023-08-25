# README

<h1 align="center"> ventajas y desventajas en la inversion de cryptomonedas</h1>

<p align ="center" width="100%">
    <img width="60%" src="image\cripto.png">
</p>

*[Índice](#índice)

*[Descripción del proyecto](#descripción-del-proyecto)

*[Características de la aplicación y demostración](#Características-de-la-aplicación-y-demostración)

*[Acceso al proyecto](#acceso-proyecto)

*[Tecnologías utilizadas](#tecnologías-utilizadas)


*[Personas-Desarrolladores del Proyecto](#personas-desarrolladores)


*[Conclusión](#conclusión)

# descripción-del-proyecto
muy a menudo tenemos la necesidad de representar nuestro conjunto de datos en un diagrama o un dibujo representativo ,centrarse mas en el analisis , pues el proceso de EDA precede al modelamiento, se formula supuestos o hipotesis .este proyecto esta involucrado en encontrar objetos bajo analisis : las ventajas y desventajas cuando iniciamos en invertir en un activo En el mercado actual hay más de 10.000 criptomonedas, cada una de ellas con sus peculiaridades. Ahora bien, todas las criptomonedas tienen aspectos en común, como la tendencia a registrar repentinos picos (y caídas) de valor. Los precios dependen principalmente de la oferta de monedas  y de la demanda por parte de los compradores. Esta dinámica de oferta y demanda puede generar importantes beneficios. asi como encontrar algunas desventajas como : no tener una politica de reembolso o cancelacion, ataques a las tecnologias de blockcain donde se registren las  transacciones .

# Características-de-la-aplicación-y-demostración

- primero realice la carga de los datos mediante una API , se hizo la extraccion de datos de una funcion  a traves de python ,en los primeros dataset  se especifican la lista de criptomonedas,plataforma de activos y direccion de contrato , en el primer dataframe se encontro duplicados por la variable name , asi que se trabajara con los ids_criptomoneda para analisis , se concatena dataframes en el cual estan los datos generales de las criptomonedas , realizamos un analisis univariante , descripcioon estadistica , se realiza el barplots  ,en escala logaritmica(se tiene una mejor visualizacion) se encuentra la metrica : capitalizacion de mercado , volumen ,volatilidad (desviacion estandar). 



<p align ="center" width="100%">
    <img width="60%" src="image\Anotación 2023-08-25 173244.png">
</p>
   
- Analisis : se comienza a analizarel dataframe ce criptomonedas , se observa una distribucion normal en las variables : rango de capitalizacion de mercado (no tiene outliers) , cambio en porcentage de precio de 24hr,cambio en porcentaje de capitalizacion de mercado de 24hr , se encontro que la criptomoneda bitcoin tiene el mayor precio, capitalizacion de mercado , volumen total , en analisis multivariado realizado se encontro que 9 variable guardan una correlacion perfecta , ejemplo capitalizacion de mercado y valoracion totalmente diluida(en detalle en el notebook) en categorias criptograficas layer 1 es la categoria mas grande por capitalizacion de mercado , en intercambios activos hay 8 de ellos que tiene una mayor puntuacion de confianza

 <p align ="center" width="100%">
    <img width="60%" src="image\Anotación 2023-08-25 173244_2.png">
</p>

- respecto a la fecha con mayor precio , capitalizacion de mercado , analizamos en particular a la criptomoneda bitcoin donde registra su mayor precio en dolares el 11 de setiembre del 2021. y para la tecnologia binance-smart-chain registra precio el 29 de setiembre del mismo año . las cripto bitcoin y ethereum estan en su mayor pporcentaje en las empresas coinbase global , meitu , mogo inc.


 <p align ="center" width="100%">
    <img width="60%" src="image\newplot.png">
</p>

# personas-desarrolladores

 - Yesica Milagros Leon Ccahuana


# acceso-proyecto
 
  - link de notebook completo: https://colab.research.google.com/drive/1OMGun3n4lPjhc6Zz4sq5rUdTaA-RlGRd?usp=sharing
  - link de dashboard del proyecto : https://drive.google.com/drive/folders/1ii7TG9ESNpx3oe4zM8OREc3r5peV808k?usp=sharing

# paquetes-usados

    - ploty
    - pandas 
    - matplotlib.pyplot 
    - seaborn 
    - numpy 
    - plotly.express 

# conclusión


- La capitalización de mercado es una métrica útil para comparar el valor total de las criptomonedas.es una estimación de su valor total de acuerdo con su precio de mercado actual.

- suministro circulante y suministro total tiene correlacion perfecta
 ,bajo 24hr y alto 24hr tiene correlacion perfecta
precio actual y alto 24hr tiene corrrelacion perfecta,
precio actual y bajo 24hr tiene corrrelacion perfecta,
capitalizacion de mercado y valoracion totalmente diluida tiene correlacion perfecta,
precio actual y cambio precio 24 hr tiene correlacion negativa muy fuerte,
capitalizacion de mercado y cambio de capitalizacion de mercado 24 hr tiene correlacion negativa muy fuerte,
capitalizacion de mercado y volumen total tiene correlacion muy fuerte,
minimo historico y precio actual tiene una correlacion fuerte,
se puede concluir que hay variables que pueden ser reemplazadas por otras cuando existen una correlacion fuerte o muy fuerte

- binance , byspot , huobit , kraken ,kucoin bitfinex, binance_us , gdax intercambios de activos con un puntaje de confianza mayor
tranquil_finance ,sushis_wap_avalanche , baryon network , mm-finance-arbitrum con mayor rango de confianza


- el 11 de setiembre del 21 la criptomoneda bitcoin tuvo su mayor precio de 67617.015545 usd mientras que hoy 25 de agosto del 23 se registra el precio 26102.469492 en dolares

- en intercambio binance se registramn el volumen_chart hace 14 dias el 18 de agosto se registra mayor volumen_chart

- Los intercambios de derivados para criptomonedas: por ejemplo Bybit es una plataforma especializada dedicada únicamente a los mercados de derivados. Está en el mercado desde 2018. Los derivados son una parte esencial de cualquier mercado, ya sea el mercado de valores, el mercado de divisas o el mercado de criptomonedas. Los comerciantes pueden utilizar varias estrategias para especular o mitigar sus pérdidas mediante cobertura. 

