# Challenge RappiCard
Caso de negocio Rappi: Detección de fraude

Para este caso de negocio contamos con información sobre transacciones con tarjeta de crédito de un Banco Comercial. Los objetivos son (1) crear estrategias de negocio para el banco basadas en el análisis de esta información y (2) crear un modelo para la detección de transacciones fraudulentas.

El Data Set con el que contamos contiene información sobre transacciones: fecha y hora de la transacción, monto, tipo de establecimiento y ciudad en donde se llevó a cabo, cashback, si fue aceptada o rechazada y si la transacción fue catalogada como fraudulenta o no. También hay información sobre los clientes: género, línea de crédito, intereses, características de su celular, si es cliente premium y un ID único.

Esta notebook se divide en tres partes. En la parte (1) hacemos un análisis exploratorio de los datos. En la parte (2) clasificamos a los clientes de acuerdo con un score que definimos como la razón entre el total de sus gastos al mes y su límite de crédito, y discutimos las implicaciones para el negocio. En la parte (3) desarrollamos y validamos un modelo Random Forest para la detección de fraude.

Instrucciones.

Para correr el notebook basta con escribir en csv_path = "_ _ _" la ruta del archivo "ds_challenge_data_2022.csv".

La PPT "Rappi_BTB_v2" presenta los resultados del análisis.


