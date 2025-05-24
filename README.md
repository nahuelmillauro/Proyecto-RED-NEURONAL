# Trabajo Práctico - Red Neuronal desde Cero

Este repositorio contiene el desarrollo completo de un trabajo práctico que consiste en analizar una base de datos, implementar una red neuronal manualmente utilizando `numpy`, compararla con una versión en `scikit-learn` y reflexionar sobre el proceso.

## 📁 Estructura del proyecto

### 🧠 Parte 1 - Análisis de la Base de Datos
Se realiza un análisis exploratorio completo sobre un dataset de clasificación:
- Descripción de columnas.
- Correlaciones entre variables.
- Evaluación de la factibilidad para entrenar una red neuronal.
- Detección y tratamiento de outliers.
- Transformaciones necesarias (normalización, codificación, etc.).

📄 Archivos:
- `analisis_exploratorio.ipynb`
- `base_datos.csv`

---

### 🤖 Parte 2 - Red Neuronal en Numpy
Se implementa una red neuronal desde cero:
- Arquitectura con múltiples capas ocultas.
- Funciones de activación (ReLU, Sigmoid, etc.).
- Entrenamiento con retropropagación y descenso por gradiente estocástico.
- Gráficos de pérdida y precisión.

📄 Archivos:
- `red_neuronal_numpy.py`
- `entrenamiento_numpy.ipynb`
- `graficos_numpy.png`

---

### 🧪 Parte 3 - Red Neuronal con Scikit-learn
Se construye una red neuronal equivalente usando `scikit-learn` para comparar resultados:
- Mismos parámetros que la red de Numpy.
- Evaluación de performance, tiempos de ejecución y curvas.

📄 Archivos:
- `red_neuronal_sklearn.py`
- `entrenamiento_sklearn.ipynb`
- `comparacion_numpy_vs_sklearn.ipynb`

---

### 📝 Parte 4 - Conclusión Final
Reflexión sobre el proceso completo:
- ¿Qué se aprendió?
- Ventajas y desventajas de construir desde cero vs usar librerías.
- Observaciones sobre resultados y performance.

📄 Archivo:
- `conclusiones.md`

---

## 🛠 Tecnologías utilizadas

- Python 3
- Numpy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook
