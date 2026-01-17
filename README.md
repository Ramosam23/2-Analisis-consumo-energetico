# Análisis y Predicción del Consumo Energético

## Objetivo del proyecto
Analizar el comportamiento temporal del consumo energético a partir de datos históricos, identificando patrones estacionales, anomalías y dependencias temporales, y evaluando distintos enfoques de modelado predictivo para estimar el consumo futuro.

El proyecto tiene un enfoque **end-to-end**, abarcando:
- Exploración y limpieza de datos
- Análisis de series temporales
- Ingeniería de características
- Comparación de modelos predictivos
- Comunicación de resultados

## Enfoque metodológico
El análisis se desarrolló de forma incremental:

1. Exploración del consumo energético y detección de patrones temporales.
2. Agregación temporal y análisis de estacionalidad.
3. Construcción de un modelo baseline (naive).
4. Modelado supervisado mediante regresión lineal con variables rezagadas.
5. Implementación de un modelo SARIMA como enfoque avanzado de series temporales.
6. Comparación de desempeño entre modelos usando métricas cuantitativas.

## Modelos utilizados
- **Baseline (Naive)**: último valor observado.
- **Regresión lineal con rezagos**: consumo pasado como variables explicativas.
- **SARIMA**: modelo estadístico para capturar tendencia, estacionalidad y dependencia temporal.

## Estructura del proyecto

data/
├── raw/ # Datos originales sin modificar
├── processed/ # Datos limpios y preparados para análisis
└── external/ # Fuentes externas (si aplica)

notebooks/
├── Exploración y preparación de datos
├── Análisis temporal
├── Modelado y evaluación

models/
├── Modelos entrenados y resultados

reports/
├── Presentación final en PowerPoint



## Dataset
El dataset contiene registros históricos de consumo energético a nivel mensual, y se encuentra disponible en la carpeta `data/raw/`.  
Los datos procesados, listos para análisis y modelado, se almacenan en `data/processed/`.

## Herramientas utilizadas
- Python (pandas, numpy, statsmodels, scikit-learn, matplotlib)
- Jupyter Notebook
- PowerPoint (storytelling y comunicación de resultados)

## Resultados principales
- Se identificaron patrones estacionales claros en el consumo energético.
- Se detectaron anomalías puntuales en periodos específicos.
- El consumo energético mostró una fuerte dependencia temporal.
- El modelo SARIMA ofreció el mejor balance entre precisión e interpretación.

## Estado del proyecto
✅ Proyecto finalizado — listo para revisión y presentación en portafolio.
