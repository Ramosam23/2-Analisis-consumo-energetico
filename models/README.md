# Models – Modelos Entrenados

Esta carpeta está destinada a almacenar modelos entrenados y artefactos derivados del proceso de modelado.

## Estado actual

En este proyecto, los modelos (baseline, regresión con rezagos y SARIMA) fueron **entrenados y evaluados directamente en el notebook**, sin persistir archivos de modelos serializados (`.pkl`, `.joblib`, etc.).

Esto se decidió porque:
- El objetivo del proyecto es **demostrativo y analítico**, no de despliegue en producción.
- El foco está en la comparación de enfoques y en la interpretación de resultados.

## Uso futuro

En una extensión del proyecto, esta carpeta podría incluir:
- Modelos guardados para reutilización.
- Versiones de modelos entrenados con distintos parámetros.
- Artefactos asociados a pipelines de modelado.

