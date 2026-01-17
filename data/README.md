# Data – Consumo Energético

Esta carpeta contiene los datos utilizados en el proyecto **Análisis de Consumo Energético**.  
Los datos están organizados siguiendo buenas prácticas de análisis de datos, separando los archivos originales de los datos procesados utilizados para el modelado.

## Estructura

- **raw/**
  - Contiene los datos originales, sin ningún tipo de modificación.
  - Estos archivos se utilizan únicamente como fuente de entrada.

- **processed/**
  - Contiene los datos limpios y transformados.
  - Incluye agregaciones temporales y variables derivadas utilizadas para el análisis y el modelado.

- **external/**
- Esta carpeta está reservada para fuentes de datos externas o complementarias (por ejemplo, datos climáticos, calendarios, información geográfica).

- En este proyecto no se utilizaron fuentes externas adicionales, por lo que la carpeta se mantiene vacía de forma intencional.

## Nota importante

Los datos en la carpeta `raw/` no deben ser modificados.  
Cualquier transformación, limpieza o ingeniería de variables se guarda en `processed/` para asegurar trazabilidad y reproducibilidad del análisis.
