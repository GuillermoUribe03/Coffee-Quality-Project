# Predicción de la Calidad del Café Arábica mediante Machine Learning

**Grupo G6** — Guillermo Mejía Uribe, Víctor Restrepo, Daniel Duque Rivera  
**Curso:** Modelos y Simulación II  
**Universidad:** Universidad de Antioquia

---

## Descripción del proyecto

Este proyecto explora si es posible estimar el puntaje total de catación (_Total Cup Points_) del café Arábica utilizando únicamente metadatos agrícolas (país de origen, altitud, método de procesamiento, defectos y humedad), descartando variables sensoriales que no están disponibles para el productor antes de una catación oficial.

Se evaluaron seis modelos de regresión (Ridge, KNN, Random Forest, Gradient Boosting, MLP y SVR) sobre 1310 muestras del Coffee Quality Institute, empleando validación cruzada anidada e intervalos de confianza bootstrap.

---

## Estructura del repositorio

| Archivo                                 | Descripción                                                                                                                            |
| --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| `coffee_quality_final_V2.ipynb`         | Notebook principal con todo el código del proyecto (EDA, preprocesamiento, entrenamiento, reducción de dimensionalidad y conclusiones) |
| `Articulo-ProyectoPrediccionCafeML.pdf` | Reporte final en formato artículo IEEE que documenta todo el desarrollo del proyecto                                                   |
| `README.md`                             | Este archivo, con instrucciones para interactuar con el repositorio                                                                    |

---

## Instrucciones de ejecución

### Requisitos previos

Para ejecutar el notebook, necesita un entorno con Python 3.8 o superior y las siguientes librerías:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `kagglehub`
- `scipy`

### Opción 1: Ejecutar en Google Colab

1. Abrir [Google Colab](https://colab.research.google.com/)
2. Seleccionar **"Subir notebook"** y cargar el archivo `coffee_quality_final_V2.ipynb`
3. Ejecutar todas las celdas en orden (**Runtime → Ejecutar todo**)
4. El notebook descargará automáticamente el dataset desde Kaggle utilizando `kagglehub`

> **Nota:** La primera ejecución puede tardar varios minutos debido a la descarga del dataset y a los procesos de validación cruzada y búsqueda de hiperparámetros.

## Video de sustentación

El resumen del proyecto, elaborado por los tres integrantes del grupo, está disponible en el siguiente enlace:

🔗 **[Video de sustentación - Proyecto Café ML](https://www.youtube.com/watch?v=VOUTYDveoUE)**
