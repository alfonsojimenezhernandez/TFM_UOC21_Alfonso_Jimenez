# TFM_UOC21_Alfonso_Jimenez
Previsión de la demanda en empresas del sector retail  Alfonso Jiménez Hernández Proyecto Final Máster Universitario en Ciencia de Datos (Data Science) en  Área de ciencia de datos en el ámbito industrial
La entrega consta:

1.	Los ficheros que se proporcionan al inicio de la  practica:
•	01_Ventas.xlsx
•	02_Promos.xlsx
•	03_Stock.xlsx
•	04_PrevisionesEmpresa.xlsx
2.	Notebook 01_Analisis_Explotaroio.ipynb 
Parte inicial del desarrollo de la practica. Contiene todas las partes propias de un proyecto de machine learning previas al modelado.
Las salidas que proporciona este notebook son:
•	MODELAR_FINAL.csv: Archivo que se utiliza para realizar la etapa de modelado y extracción de conclusiones en los notebook 02 y 03.
•	Previsiones_Filtrado.csv: Ficheros tratados correspondiente al fichero 04_PrevisionesEmpresa. Sirve como back-up.
•	Promociones_Filtrado.csv: Fichero tratado correspondiente al fichero 02_Promos. Sirve como back-up.
3.	Notebook 02_Modelado.ipynb 
Contiene la etapa final de Feature Engineering, la etapa de modelado conclusiones y cálculo de costes. Las salidas que proporciona este notebook son:
Metricas_pred.csv: Fichero de métricas que contiene todas las métricas de todos los productos por modelo. Estas métricas son generadas con el conjunto test que son los datos que el modelo no ha usado para entrenar ni validar.
•	prediciones_fin_24_05.csv: Fichero que contiene todas las prediciones por modelo y producto de los diferentes modelos con el conjunto de test.
•	Metricas_val_24_05.csv: Fichero de métricas que contiene lás metricas de los productos por modelo. Estás metricas son generadas con el conjunto de validación que son los datos que usa el modelo para extraer la mejor solución.
•	prediciones_val_20_05.csv: Fichero que contiene las prediciones realizadas con el conjunto de validación por los diferentes modelos.
•	Costes_24_05.csv: Fichero que contiene los costes diarios por producto del modelo que predice mejor la demanda y los costes diaros de la empresa tradicional
•	Gráfico dinámico donde se expone la solución del Coste del modelo vs Coste de la predición tradicional (Apartado 11 Calculo de Costes)(En este notebook no se aprecia y solo se puede observar en google colab) por tanto generamos un notebook para la salida.
 
4.A	Dashboard_Reducción_de_Costes_Sol1.
Contiene la salida del notebook 2 para visualizar los costes del modelo frente a los costes de la predición tradicional. El gráfico se puede ver tanto en el notebook como en el html. Esto se genera debido a que  el renderizado del gráfico dinamico en colab es diferente que en Anaconda.
4.B	Dashboard_Comparación Modelo_Sol1
Contiene la salida del notebook 2 para visualizar las predicciones de los diferentes modelos
	
5.	Notebook 03_Modelado_Filtrado.ipynb y 03_Modelado_Filtrado.html.
Contiene la etapa de Feature Engineering para el cálculo de nuevas carácterísticas para periodos donde ha habido demanda, la etapa de modelado, conclusiones y cálculo de costes. Las salidas que proporciona este notebook son:

•	Metricas_pred_filtrado_25_05.csv: Fichero de métricas que contiene todas las métricas de todos los productos por modelo. Estas métricas son generadas con el conjunto test que son los datos que el modelo no ha usado para entrenar ni validar.
•	prediciones_fi_25_05n.csv: Fichero que contiene todas las prediciones por modelo y producto de los diferentes modelos con el conjunto de test.
•	Metricas_val_filtrado_25_05.csv: Fichero de métricas que contiene lás metricas de los productos por modelo. Estás metricas son generadas con el conjunto de validación que son los datos que usa el modelo para extraer la mejor solución.
•	prediciones_val_filtrado_25_05.csv: Fichero que contiene las prediciones realizadas con el conjunto de validación por los diferentes modelos.
•	costes_filtrado_25_05.csv: Fichero que contiene los costes diarios por producto del modelo que predice mejor la demanda y los costes diaros de la empresa tradicional
•	Gráfico dinámico donde se expone la solución del Coste del modelo vs Coste de la predición tradicional (Apartado 11 Calculo de Costes)
6.A	Dashboard_Reducción_de_Costes_Sol2.
Contiene la salida del notebook 3 para visualizar los costes del modelo frente a los costes de la predición tradicional. El gráfico se puede ver tanto en el notebook como en el html. Esto se genera debido a que  el renderizado del gráfico dinamico en colab es diferente que en Anaconda.
6.B	Dashboard_Comparación Modelo_Sol2
Contiene la salida del notebook 3 para visualizar las predicciones de los diferentes modelos


La mayoría de los csv son escrituras back-ups debido al alto volumen de computación que se necesita para llevar a cabo todo el proceso de modelado. Se encuentran en el fichero z
