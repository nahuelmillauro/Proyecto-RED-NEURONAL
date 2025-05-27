# Trabajo Práctico - Red Neuronal desde Cero

Este repositorio contiene el desarrollo completo de un trabajo práctico que consiste en analizar una base de datos, implementar una red neuronal manualmente utilizando distintas tecnologias como `sympy`, `numpy` y `pandas`, compararla con una versión en `scikit-learn` y reflexionar sobre el proceso.

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
- `calidad_manzana.csv`
- `calidad_manzana_limpia.csv`
- `manzanas_procesado.csv`

---

### 🤖 Parte 2 - Red Neuronal en Numpy
Se implementa una red neuronal desde cero:
- Arquitectura con capas ocultas.
- Funciones de activación (ReLU, Logistic, etc.).
- Entrenamiento con retropropagación y descenso por gradiente estocástico.
- Gráficos de pérdida y precisión.

📄 Archivos:
- `red_neuronal_numpy.ipynb`

---

### 🧪 Parte 3 - Red Neuronal con Scikit-learn
Se construye una red neuronal equivalente usando `scikit-learn` para comparar resultados:
- Mismos parámetros que la red de Numpy.
- Evaluación de performance, tiempos de ejecución y curvas.

📄 Archivos:
- `red_neuronal_sklearn.py`

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

- Python 
- Numpy
- Sympy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook
  
## 📬 Contacto

Realizado por:

- Nahuel Millauro  
- Lautaro Ávila Mena  
Tecnicatura en Programación Informática - UNSAM  
San Martín, Buenos Aires
