# Processed Data – Consumo Energético

Esta carpeta contiene los datos procesados y preparados para el análisis exploratorio avanzado y el modelado predictivo.

## Transformaciones realizadas

A partir del dataset original, se aplicaron los siguientes pasos de preparación:

- Combinación de las columnas `Date` y `Time` en una única variable temporal (`Datetime`).
- Conversión del campo temporal a formato `datetime`.
- Reordenamiento de columnas, priorizando la variable temporal.
- Tratamiento de valores faltantes mediante interpolación temporal, adecuada para series de tiempo.
- Verificación de valores negativos y duplicados.
- Preparación de los datos para permitir agregaciones temporales (diaria y mensual) realizadas      posteriormente dentro del análisis, sin alterar el dataset base procesado.Esto con el fin de:
  - Reducir ruido de alta frecuencia.
  - Facilitar la identificación de patrones estacionales.
  - Preparar los datos para modelos de predicción temporal.

## Uso de estos datos

Los datos contenidos en esta carpeta se utilizan para:

- Análisis de tendencias y estacionalidad.
- Ingeniería de características temporales (lags).
- Entrenamiento y evaluación de modelos predictivos:
  - Modelo baseline (naive).
  - Regresión lineal con rezagos.
  - Modelo SARIMA.

Estos archivos representan la versión **final y validada** de los datos para el modelado.
