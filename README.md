Modelo Predictivo para Estimar el Precio de las Viviendas en Iowa, EE.UU. y Bogotá, Colombia

Descripción del Proyecto

Una empresa está interesada en desarrollar un modelo predictivo para estimar el precio de las viviendas en el estado de Iowa, EE.UU., utilizando diversas características de las propiedades. Para ello, se dispone de un conjunto de datos con 2,930 registros que incluyen múltiples atributos de las viviendas.

Adicionalmente, se replicó el mismo procedimiento para un conjunto de datos sobre viviendas en Bogotá, Colombia, con el objetivo de analizar el mercado inmobiliario en esta ciudad y evaluar la aplicabilidad del modelo en diferentes contextos.

El objetivo principal de este proyecto es construir modelos de regresión que permitan predecir el precio de las viviendas y sirvan de apoyo en la toma de decisiones relacionadas con inversiones inmobiliarias en ambas ubicaciones.

Fuentes de Datos

Iowa, EE.UU.: Conjunto de datos con 2,930 registros sobre propiedades en el estado de Iowa.

Bogotá, Colombia: Conjunto de datos con información sobre viviendas en la capital colombiana.

Una descripción detallada de cada característica de las propiedades se encuentra en la fuente original del dataset.

Proceso de Desarrollo

El proceso de desarrollo del modelo predictivo incluyó las siguientes etapas:

Exploración y Preprocesamiento de Datos:

Análisis de valores faltantes y tratamiento de los mismos.

Conversión de variables categóricas en formatos adecuados.

Detección y eliminación de valores atípicos según la distribución de las variables.

División del Conjunto de Datos:

Separación de los datos en conjuntos de entrenamiento y prueba.

Selección y Entrenamiento del Modelo:

Evaluación de distintos modelos de regresión, incluyendo regresión lineal, regresión polinómica, KNN y Random Forest.

Optimización de hiperparámetros para mejorar el desempeño del modelo.

Evaluación del Modelo:

Comparación del desempeño de los modelos mediante métricas de evaluación.

Análisis de los resultados obtenidos y ajuste del modelo seleccionado.

Resultados y Predicciones

Iowa, EE.UU.

Tras el entrenamiento del modelo Random Forest, se generó un DataFrame con los valores reales y las predicciones:


Bogotá, Colombia

El análisis de los datos de Bogotá evidenció una alta dispersión en variables como precio_venta, habitaciones, baños y administración. Se aplicaron técnicas de imputación con la mediana para algunas variables, aunque esto puede no capturar completamente la variabilidad en cada zona y tipo de propiedad.

Se entrenó el modelo Random Forest y se analizaron las predicciones, encontrando que factores como el tipo de propiedad, el sector y el estrato influyen en la precisión del modelo. Los resultados indicaron que la variabilidad en los datos de Bogotá requería ajustes adicionales para mejorar la estimación de precios.

Conclusión

El modelo entrenado en Iowa ofrece predicciones que pueden ser utilizadas para evaluar el valor de propiedades en ese estado. En el caso de Bogotá, la dispersión de los datos sugiere que se deben considerar estrategias adicionales para mejorar la precisión del modelo.

Las mejoras futuras pueden incluir la optimización de hiperparámetros adicionales, la incorporación de más características en el análisis y la aplicación de técnicas avanzadas de modelado.
