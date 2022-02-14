# predicciones_ventas
Predecir las ventas de productos
El proyecto tiene por objeto predecir las ventas de diferentes tipo de outlets que distribuyen ciertos productos y tienen una ubicación específica.
Para la depuración de datos se decidió trabajar con una base sin datos de vacíos (eliminar NaN)y rellenar los datos cuando fue posible (rellenar con la mediana). 
Los gráficos presentados ayudaron al análisis de la distribución de los datos y conocer la relación entre las variables (variable dependiente vs variables independientes)
Con los Boxplot lo que se buscó es comparar entre outlets y tipos de outlest para ver cuáles son los que más venden y que variables pueden estár relacionadas. 
Los algoritmos con los que se trabajó fueron KNN Regressor y RandomForestRegressor, teniendo un score de 0.67 y 0.92 respectivamente. 
