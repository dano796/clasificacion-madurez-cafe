# Clasificación de la Madurez de Granos de Café usando Redes Neuronales Convolucionales con PyTorch

## Descripción del proyecto

Este proyecto implementa **Redes Neuronales Convolucionales (CNN)** con **PyTorch** para clasificar la madurez de granos de café a partir de imágenes. La clasificación del nivel de madurez es esencial en la industria cafetera para garantizar la calidad del grano de café. El repositorio incluye dos cuadernos (`rnc_pytorch_cafe.ipynb` y `despliegue_rnc_pytorch_cafe.ipynb`), un documento PDF con la metodología y resultados, y dos conjuntos de datos, uno para entrenamiento y otro para prueba.

## Etapas de desarrollo

El proyecto se desarrolló en las siguientes etapas:

1. **Recolección de Datos**: Para el entrenamiento del modelo se utilizó el conjunto de datos [**Cherry Coffee Bean Dataset**](https://zenodo.org/records/14271151) disponible en Zenodo. Este conjunto de datos contiene imágenes de granos de café en diferentes etapas de madurez (verde, pinton, maduro, sobremaduro y seco). Además, se incluyó un conjunto de datos adicional para prueba (`futuro.zip`).
2. **Preprocesamiento**: Las imágenes se procesaron (redimensión, conversión en matriz NumPy y normalización) para la correcta interpretación de los datos hacia el modelo.
3. **Diseño de la CNN**: Se diseñó una red neuronal convolucional en PyTorch, con capas de convolución, batch normalization, pooling, flatten y dropout.
4. **Entrenamiento**: El modelo se entrenó usando el conjunto de datos de entrenamiento, ajustando hiperparámetros para mejorar la exactitud del modelo.
5. **Evaluación**: Se evaluó el modelo con el conjunto de datos de prueba, analizando métricas como precisión y pérdida.
6. **Despliegue**: Se implementó un flujo para cargar el modelo entrenado y realizar predicciones en nuevas imágenes.

El documento PDF (`CLASIFICACIÓN DE LA MADUREZ DE GRANOS DE CAFÉ USANDO REDES NEURONALES CONVOLUCIONALES CON PYTORCH.pdf`) detalla la metodología, arquitectura del modelo, entrenamiento y resultados.

## Características

- **Clasificación de Madurez**: Identifica etapas de madurez (verde, pinton, maduro, sobremaduro y seco) de granos de café mediante imágenes.
- **Conjuntos de Datos Incluidos**: Incluye datos de entrenamiento y prueba para reproducir los experimentos.
- **Implementación en PyTorch**: Código modular para entrenamiento y despliegue del modelo.
- **Documentación Completa**: El PDF proporciona un análisis detallado de la metodología y resultados.

## Resultados
**Modelo no optimizado:**
- Pérdida: 0.4167 (CrossEntropyLoss) tras 30 épocas.
- Precisión: 90.71%
- Desempeño: En el conjunto de imágenes de prueba el modelo no optimizado acertó 17 de 20 predicciones.

**Modelo optimizado:**
- Pérdida: 0.1866 (CrossEntropyLoss) tras 30 épocas.
- Precisión: 93.44%
- Desempeño: En el conjunto de imágenes de prueba el modelo optimizado acertó 20 de 20 predicciones.

El modelo optimizado, con una tercera capa convolucional, normalización por lotes y dos capas densas mostró una convergencia más rápida 
y mejor generalización, reduciendo los errores de clasificación.

---

### Desarrollado por
- Daniel Ortiz Aristizábal
- Felipe Torres Montoya
- Samuel Betancur Muñoz

### Inteligencia Artificial - Universidad Pontificia Bolivariana
