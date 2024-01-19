
# MaaS-demand-in-Madrid
Soluciòn al problema de kaggles
Objetivo de la competición
Se te proporciona información histórica sobre los viajes realizados en e-motos en Madrid durante el período de enero a septiembre de 2022. El objetivo es desarrollar un modelo que prediga, con la mayor precisión posible, el número de viajes por clúster durante el resto de 2022 (octubre-diciembre).
Para ellos nos han proporcionado 2 archivos
1. Train.csv
2. sample_submission.csv

Como parte de la prediccion he usado un archivo adicioal del clima en madrid para el año 2022 el nombre del archivo es :

1. export_weather.csv

Para abordar la soluciòn he seguido los siguientes pasos:

1. Analisis exploratorio de datos
2. use el sample_submission.csv para hacer la predicciones del modelo usabdo como test
3. use el export_weather.csv para complementar datos
4. Merge de Datasets 
    1. Merge con train (num_viajes)
    2. weather_train
    3. test (para predicciones reales) con weather_test
5.Split de los datos
6.Entrenamiento del split usando modelo de Gradient Boosting Regressor con parámetros específicos
7. Prediccion Real
8. Preparaciòn de archivo de envio de la predicion
