## Data – Consumo Energético

Esta carpeta contiene los datos utilizados en el proyecto Análisis y Predicción del Consumo Energético.
La organización de los datos sigue buenas prácticas de ciencia de datos, separando claramente los datos originales de los datos procesados utilizados en el análisis y el modelado.

### Estructura de la carpeta
raw/

Contiene los datos originales, sin ningún tipo de modificación / no versionado debido a tamaño del archivo.
Estos archivos se utilizan exclusivamente como fuente de entrada.
No deben ser alterados manualmente.

processed/
Contiene los datos limpios y transformados / no versionado debido al tamaño del archivo

Incluye:
- Conversión y estandarización de la variable temporal.
- Tratamiento de valores faltantes.
- Verificación y eliminación de valores inválidos.
- Estos datos son los utilizados directamente en el análisis exploratorio y en los modelos predictivos.

external/

Carpeta reservada para fuentes de datos externas o complementarias
(por ejemplo, datos climáticos, calendarios o información contextual).

En este proyecto no se incorporaron fuentes externas adicionales, por lo que la carpeta se mantiene vacía de forma intencional.

### Fuente del dataset

El dataset original utilizado en este proyecto corresponde a:

**Individual household electric power consumption Data Set**  
Fuente: UCI Machine Learning Repository  
https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption

### Nota importante

Los datasets originales y procesados no se incluyen en el repositorio debido a las limitaciones de tamaño de GitHub.

Para reproducir el análisis:

- Descargar el dataset desde la fuente original.

- Colocarlo en la carpeta data/raw/.

- Ejecutar el notebook de exploración y preparación de datos para generar el dataset procesado.

