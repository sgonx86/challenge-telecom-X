# Telecom X – Predicción de Cancelación de Clientes


# Sobre el desafio

Telecom X enfrenta una alta tasa de cancelación de clientes y busca anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios. Como parte del equipo de Machine Learning, tu misión es construir un pipeline robusto que permita predecir la cancelación (churn) con alta precisión.

# Objetivos del Proyecto

- Preparar y preprocesar los datos para modelado.
- Realizar análisis exploratorio y selección de variables relevantes.
- Construir y entrenar modelos predictivos de clasificación.
- Evaluar el rendimiento de los modelos con métricas adecuadas.
- Interpretar los resultados y extraer insights estratégicos.
- Proponer acciones basadas en los factores que influyen en la cancelación.

# Preparación de los datos

- Seliminaron columnas irrelevantes como identificadores únicos (customerID) y columnas redundantes (account.Charges.Total).
- Se codificaron variables categóricas mediante One-Hot Encoding para variables con múltiples categorías y binarización para variables binarias.
- Se verificó la proporción de clientes que cancelaron (Churn) para evaluar posibles desbalances.
- Se recomendó aplicar técnicas de balanceo.
- Se consideró la normalización de variables para modelos sensibles a escala

# Análisis exploratorio y selección de variables

- Se visualizó la matriz de correlación para identificar relaciones significativas con la variable objetivo (Churn).
- Se investigaron variables específicas como Tiempo de contrato y Gasto mensual en relación a la cancelación, usando gráficos como boxplots y scatter plots.
- Se seleccionaron variables con mayor relevancia para alimentar los modelos predictivos.

# Modelado predictivo

- Se dividió el conjunto de datos en entrenamiento y prueba con una proporción de 70%-30%.
- Se entrenaron al menos dos modelos distintos para comparar desempeño (Arbol de decision, Random Fores)
- Se consideró la normalización para modelos sensibles y no para modelos basados en árboles.
- Se evaluó el rendimiento con métricas

# Importancia de las variables

Las variables más influyentes para predecir la cancelación son:
-Tenure (tiempo como cliente)
-Tipo de contrato (ej. mensual, anual)
-Cargos mensuales
-Tipo de servicio de internet
-Facturación sin papel
Estas variables fueron identificadas mediante la importancia calculada por los modelos, especialmente Random Forest.
Su comprensión permite tomar decisiones estratégicas para mitigar la cancelación.

# Conclusiones y recomendaciones estratégicas

- Focalizar campañas de retención en clientes nuevos o con contratos mes a mes.
- Ofrecer incentivos para contratación anual o bianual, mejorando la fidelización.
- Revisar y ajustar planes de precios para mejorar la percepción de valor y reducir cancelaciones por costos.
- Personalizar la experiencia según el tipo de servicio contratado, mejorando la satisfacción.
- Promover la facturación digital y comunicación proactiva para fortalecer el vínculo con el cliente.

# Como ejecutar este analisis de datos
Clonar este repositorio (si aplica) o descargar el archivo .ipynb y los archivos .json
Asegurarse de tener Python y las bibliotecas requeridas instaladas
Abrir y ejecutar el notebook TelecomX_LATAM.ipynb en un entorno Jupyter (como Jupyter Lab, Jupyter Notebook clásico, o Google Colab). Las celdas deben ejecutarse en orden.

  
