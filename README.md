# Clasificación de la Madurez de Granos de Café usando Redes Neuronales Convolucionales con PyTorch

![Granos de Café](https://www.ocu.org/-/media/ocu/seo/alimentaci%C3%B3n/caf%C3%A9/cafe-vamos-al-grano%201.jpg?la=es-es&rev=ebbf57dd-7b6d-4bf9-8422-8eee2ab73acc&h=338&w=600&hash=0853E5BAD2B7F51DEAB856211D5E1A78&mw=960)

https://www.ocu.org/-/media/ocu/seo/alimentaci%C3%B3n/caf%C3%A9/cafe-vamos-al-grano%201.jpg?la=es-es&rev=ebbf57dd-7b6d-4bf9-8422-8eee2ab73acc&h=338&w=600&hash=0853E5BAD2B7F51DEAB856211D5E1A78&mw=960

## Descripción del Proyecto

Este proyecto implementa **Redes Neuronales Convolucionales (CNN)** con **PyTorch** para clasificar la madurez de granos de café a partir de imágenes. La clasificación de la madurez es esencial en la industria cafetalera para garantizar la calidad del producto. El repositorio incluye dos cuadernos Jupyter (`rnc_pytorch_cafe.ipynb` y `despliegue_rnc_pytorch_cafe.ipynb`), un documento PDF con la metodología y resultados, y conjuntos de datos para entrenamiento y prueba.

**El proyecto se desarrolló en las siguientes etapas:**

1. **Recolección de Datos**: Se recopilaron imágenes de granos de café en diferentes etapas de madurez (verde, maduro, sobremaduro). Los conjuntos de datos para entrenamiento y prueba están incluidos en el repositorio.
2. **Preprocesamiento**: Las imágenes se procesaron (normalización, aumento de datos) para mejorar el rendimiento del modelo.
3. **Diseño de la CNN**: Se diseñó una red neuronal convolucional en PyTorch, optimizada para clasificar las imágenes según la madurez de los granos.
4. **Entrenamiento**: El modelo se entrenó usando el conjunto de datos de entrenamiento, ajustando hiperparámetros para maximizar la precisión.
5. **Evaluación**: Se evaluó el modelo con el conjunto de datos de prueba, analizando métricas como precisión y pérdida.
6. **Despliegue**: Se implementó un flujo para cargar el modelo entrenado y realizar predicciones en nuevas imágenes.

El documento PDF (`CLASIFICACIÓN DE LA MADUREZ DE GRANOS DE CAFÉ USANDO REDES NEURONALES CONVOLUCIONALES CON PYTORCH.pdf`) detalla la metodología, arquitectura del modelo, experimentos y resultados.

## Características

- **Clasificación de Madurez**: Identifica etapas de madurez (verde, maduro, sobremaduro) de granos de café mediante imágenes.
- **Conjuntos de Datos Incluidos**: Incluye datos de entrenamiento y prueba para reproducir los experimentos.
- **Implementación en PyTorch**: Código modular para entrenamiento y despliegue del modelo.
- **Documentación Completa**: El PDF proporciona un análisis detallado de la metodología y resultados.

---

### Desarrollado por
- Daniel Ortiz Aristizábal
- Felipe Torres Montoya
- Samuel Betancur Muñoz
### Inteligencia Artificial - Universidad Pontificia Bolivariana
