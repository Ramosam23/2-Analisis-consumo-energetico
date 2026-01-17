
# Notebooks – Análisis de Consumo Energético

Esta carpeta contiene los notebooks que documentan de forma secuencial
el análisis exploratorio, la preparación de datos y el modelado predictivo
del consumo energético.

El flujo de trabajo sigue una estructura lógica, desde la comprensión
del problema hasta la evaluación de modelos.

## Notebooks incluidos

### 01_EDA_Consumption_Energy.ipynb
Exploración inicial del dataset y preparación de los datos para análisis
temporal. Incluye:

- Comprensión del problema y definición de preguntas de análisis.
- Limpieza y validación de datos.
- Análisis de patrones temporales.
- Identificación de estacionalidad y anomalías.
- Agregación temporal para facilitar el modelado.

### Modelado predictivo
Dentro del mismo notebook se desarrollan y comparan distintos enfoques
de predicción del consumo energético:

- Modelo baseline (naive).
- Regresión lineal con variables rezagadas.
- Modelo SARIMA para capturar tendencia y estacionalidad.

Cada modelo es evaluado utilizando métricas cuantitativas (MAE y RMSE),
así como mediante comparación visual entre valores reales y predichos.

## Enfoque del análisis

El análisis prioriza:

- Interpretabilidad de los resultados.
- Comprensión del comportamiento temporal del consumo.
- Comparación progresiva de modelos, desde simples hasta más robustos.

Este enfoque permite justificar técnicamente la elección del modelo final
y sentar bases sólidas para futuros proyectos de mayor complejidad.
