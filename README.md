# AutoVisionClust

Este repositorio contiene tres proyectos que exploran diferentes técnicas de aprendizaje automático aplicadas al análisis de imágenes y datos. Cada proyecto se centra en una tecnología específica: Autoencoders, Vision Transformers y técnicas de clustering.

## Estructura del Repositorio

### 1. Autoencoders para Análisis de Imágenes
**Carpeta:** `/Autoencoders`
- Implementación de autoencoders para compresión y reconstrucción de imágenes
- Dataset: MNIST Fashion
- Características principales:
  - Arquitectura de encoder-decoder
  - Reducción de dimensionalidad
  - Visualización de reconstrucciones
  - Análisis del espacio latente

### 2. Vision Transformers para Clasificación de Enfermedades
**Carpeta:** `/Leaf Disease Classification`
- Clasificación de enfermedades en hojas de yuca usando Vision Transformers
- Dataset: Cassava Leaf Disease Classification (Kaggle)
- Características principales:
  - Implementación de ViTBase16
  - Data augmentation avanzado
  - Entrenamiento en TPU
  - Métricas de rendimiento y validación

### 3. Técnicas de Clustering para Segmentación de Clientes
**Carpeta:** `/Credit Card Customer Data`
- Análisis de clientes mediante técnicas de clustering
- Dataset: Credit Card Customer Data
- Características principales:
  - Implementación de K-means
  - Análisis DBSCAN
  - Evaluación mediante coeficiente Silhouette
  - Visualización de clusters

## Requisitos

```python
# Dependencias principales
numpy>=1.19.2
pandas>=1.2.4
torch>=1.8.0
tensorflow>=2.4.1
scikit-learn>=0.24.2
matplotlib>=3.3.4
seaborn>=0.11.1
```

## Instalación

```bash
git clone https://github.com/username/AutoVisionClust.git
cd AutoVisionClust
pip install -r requirements.txt
```

## Uso

Cada proyecto tiene su propio notebook Jupyter con instrucciones detalladas:

1. `/Autoencoders/autoencoder_analysis.ipynb`
2. `/Leaf Disease Classification/Leaf_Disease_Classification.ipynb`
3. `/Credit Card Customer Data/clustering_techniques.ipynb`

## Resultados

- **Autoencoders:** Logra una reconstrucción efectiva de imágenes con una reducción significativa de dimensionalidad
- **Vision Transformers:** Alcanza alta precisión en la clasificación de enfermedades en hojas
- **Clustering:** Identifica segmentos claros de clientes con características distintivas

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abra un issue primero para discutir qué le gustaría cambiar.

## Licencia

Este proyecto está bajo la Licencia MIT - vea el archivo `LICENSE.md` para más detalles.

## Contacto

Ricardo Lopera - [@username](https://twitter.com/username) - email@example.com

Link del proyecto: [https://github.com/username/AutoVisionClust](https://github.com/username/AutoVisionClust)