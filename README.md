# AutoVisionClust

Este repositorio contiene tres proyectos que exploran diferentes técnicas de aprendizaje automático aplicadas al análisis de imágenes y datos financieros. Cada proyecto se centra en una tecnología específica: Detección de Anomalías con Autoencoders, Vision Transformers y técnicas de clustering.

## Estructura del Repositorio

### 1. Detección de Anomalías en Series Temporales
**Carpeta:** `/Anomaly Detection`
- Implementación de autoencoders para detectar anomalías en series temporales financieras
- Dataset: SPX (S&P 500)
- Características principales:
  - Arquitectura de autoencoder denso
  - Acumulación de gradientes
  - Detección de anomalías basada en error de reconstrucción
  - Visualización de series temporales y anomalías

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
  - Implementación desde cero de BFR
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
git clone https://github.com/RicardoLoperaV/AutoVisionClust
cd AutoVisionClust
```

## Uso

Cada proyecto tiene su propio notebook Jupyter con instrucciones detalladas:

1. `/Anomaly Detection/Anomaly_Detection.ipynb`
2. `/Leaf Disease Classification/Leaf_Disease_Classification.ipynb`
3. `/Credit Card Customer Data/clustering_techniques.ipynb`

## Resultados

- **Anomaly Detection:** Detecta eficazmente anomalías en series temporales financieras utilizando autoencoders
- **Vision Transformers:** Alcanza alta precisión en la clasificación de enfermedades en hojas
- **Clustering:** Identifica segmentos claros de clientes con características distintivas

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abra un issue primero para discutir qué le gustaría cambiar.


## Contacto

Ricardo Lopera - [@Ricardo Esteban Lopera Vasco](https://www.linkedin.com/in/ricardo-esteban-lopera-vasco/) - rloperav@unal.edu.co

Link del proyecto: [https://github.com/username/AutoVisionClust](https://github.com/username/AutoVisionClust)