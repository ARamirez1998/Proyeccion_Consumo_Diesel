# Proyeccion_Consumo_Diesel

# Objeto:
Modelo de Predicción del Consumo de Diésel en Unidades de Transporte Público.

# Descripción:
Este proyecto tiene como objetivo desarrollar un modelo predictivo capaz de estimar el consumo de diésel por hora, utilizando datos históricos de consumo y variables asociadas a su comportamiento. Se enmarca en una necesidad operativa de optimizar la planificación del abastecimiento y uso del combustible en una entidad o sistema que depende de este insumo para su funcionamiento continuo.

# Fase 1 - Análisis Exploratorio y Limpieza de Datos:
En esta fase se abordaron las siguientes actividades:

1. Carga y comprensión del dataset original: conteniendo datos de consumo de diésel por hora.

2. Análisis exploratorio de datos (EDA): se estudiaron patrones temporales, tendencias, estacionalidad y anomalías.

3. Limpieza de datos: manejo de valores nulos, detección y tratamiento de outliers, conversión de formatos y verificación de la consistencia de los datos.

4. Visualización: gráficos de líneas, histogramas y diagramas de caja para representar y entender la distribución del consumo.

# Fase 2 - Feature Engineering y Modelado Predictivo:
En esta fase se avanzó con:

1. Generación de nuevas variables: como hora del día, día de la semana, mes, y posibles variables de rezago.

2. Codificación de variables categóricas: en caso de que existan.

3. Selección de características relevantes: se descartaron variables irrelevantes o redundantes para mejorar el desempeño del modelo.

4. Entrenamiento de modelos de regresión: se probaron algoritmos como:

    - LinearRegression

    - DecisionTreeRegressor

    - RandomForestRegressor

    - GradientBoostingRegressor

5. Evaluación del desempeño: mediante métricas como RMSE, MAE y R² para seleccionar el modelo más adecuado.

# Aplicaciones:

El sistema desarrollado permitirá:

1. Predecir el consumo de diésel por hora, facilitando la toma de decisiones sobre logística y abastecimiento.

2. Optimizar recursos y evitar sobrecostos, reduciendo tanto el desabastecimiento como el exceso de combustible almacenado.

3. Planificar operaciones de forma eficiente, especialmente en sistemas de transporte, plantas eléctricas o industrias que requieren un suministro continuo de diésel.

4. Adaptarse dinámicamente a la demanda futura, gracias a un modelo que aprende de los datos históricos y se ajusta a nuevas tendencias.
