### Wheather Ohio

Los datos provienen del aeropuerto de ohio ![link](https://www.ncei.noaa.gov). Los datos son principalmente datos historicos de temperatura, precipitaciones, velocidad y dirección del viento.

El problema de prediccion de tiempo se enmarco dentro de framework de forecasting. Usando muchas variables de dias anteriores para hacer variables nuevas. Sin embargo se ha encontrado que estas variables están muy correlacionadas y no aportan mucha información novedosa. 
Entonces lo que se ha hecho es simplemente coger datos del dia anterior al  que se quiere predecir.
Tambien, revisando los residuos de las predicciones se ha encontrado un patrón. Hay una tendencia en la que los errores  son consistentemente mas altos en los meses de invierno que en verano.

Este video muestra una implementación interesante del problema. ![Link](https://app.dataquest.io/c/93/m/99991/portfolio-project%3A-predicting-the-weather-using-machine-learning/1/project-overview)
	- Tiene una manera interesante de ir haciendo de hacer el problema. testea de forma muy rapida  con una funcion adhoc. 
	-Testea bien los residuos