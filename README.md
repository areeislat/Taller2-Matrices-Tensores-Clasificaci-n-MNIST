# Taller 2 — Matrices, Tensores y Clasificación con MNIST

Asignatura: Machine Learning (MLY1101)  
Estudiante: Areliz Isla  
Fecha: 20-08-2026

## Descripción
Proyecto didáctico que explora estructuras de datos (matrices y tensores) aplicadas a imágenes del conjunto MNIST y compara estrategias de clasificación multiclase (One-vs-One vs One-vs-Rest). Incluye además una sección sobre generación y eliminación de ruido usando KNN.

## Contenido
- `MLY1101_001V_T02_IslaAreliz.ipynb` — Notebook con todo el desarrollo:
  - Parte 1: exploración de X como vectores, matrices y tensor (70000, 28, 28), visualizaciones.
  - Parte 2: comparación OvO vs OvR con un clasificador base (SGDClassifier) usando N_TRAIN = 10000.
  - Parte 3: generación de imágenes con ruido y experimentos de eliminación de ruido (KNN).
  - Resultado final: inclusión de una imagen propia para evaluación (tal como pide la consigna).

## Resultados principales
- División de datos: primeras 60.000 observaciones para entrenamiento y últimas 10.000 para prueba.
- Comparación OvO vs OvR (ejecución de ejemplo en el notebook con N_TRAIN = 10 000):
  - OvO — Accuracy ≈ 0.9089; tiempo de entrenamiento ≈ 5.51 s; tiempo de predicción ≈ 2.80 s.
  - OvR — Accuracy ≈ 0.8546; tiempo de entrenamiento ≈ 16.12 s; tiempo de predicción ≈ 0.45 s.
- Conclusión breve: OvO obtuvo mayor precisión en el experimento, mientras que OvR fue más lento de entrenar pero más rápido en predicción en este caso y con este clasificador base.

## Requisitos
- Python 3.8+  
- Paquetes (principales): scikit-learn, numpy, pandas, matplotlib
- Recomendado: ejecutar en entorno con suficiente RAM (MNIST entero) o usar Google Colab.

Instalación rápida:
```bash
pip install numpy pandas matplotlib scikit-learn
