# Clasificación del Dataset IRIS usando k-Nearest Neighbors (kNN)

Autor: Manuel Eugenio Morocho Cayamcela  

## 📌 Descripción general

Este proyecto implementa un flujo completo de **Aprendizaje Supervisado** para la **clasificación del dataset IRIS**, utilizando el algoritmo **k-Nearest Neighbors (kNN)**.  
El notebook cubre desde la carga de datos y análisis exploratorio hasta el entrenamiento, evaluación del modelo y análisis de la importancia de las características.

El objetivo es **comprender el proceso completo de clasificación**, así como garantizar que los resultados sean **reproducibles**.

---

## 🧪 Dataset

- **Nombre:** IRIS
- **Fuente:** Dataset clásico de Machine Learning
- **Archivo utilizado:** `iris.csv`
- **Clases:**  
  - Iris-setosa  
  - Iris-versicolor  
  - Iris-virginica  

- **Características:**
  - SepalLength
  - SepalWidth
  - PetalLength
  - PetalWidth

---

## 🛠️ Requisitos del entorno

### 🔹 Versión recomendada de Python
```bash
Python >= 3.9
```

### 🔹 Librerías necesarias

Ejecuta el siguiente comando para instalar todas las dependencias:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## 📂 Estructura del proyecto

```
.
├── Supervised_Learning_Clasificación_de_IRIS_con_kNN.ipynb
├── iris.csv
└── README.md
```

---

## 🚀 Paso a paso para replicar el experimento

### 1️⃣ Clonar o descargar el proyecto

Asegúrate de que el archivo `iris.csv` se encuentre en el mismo directorio que el notebook.

---

### 2️⃣ Importación de librerías

El notebook inicia con la importación de las librerías necesarias:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

---

### 3️⃣ Carga del dataset

Se carga el archivo `iris.csv` usando `pandas` y se verifica su estructura:

- Dimensiones del dataset
- Tipos de datos
- Valores nulos

---

### 4️⃣ Análisis Exploratorio de Datos (EDA)

Se realizan las siguientes tareas:

- Visualización de las primeras filas
- Estadísticas descriptivas
- Gráficos de dispersión
- Visualización de relaciones entre variables
- Análisis de la distribución de las clases

---

### 5️⃣ Preparación de los datos

- Separación de variables independientes (**X**) y variable objetivo (**y**)
- División del dataset en:
  - Conjunto de entrenamiento
  - Conjunto de prueba
- Normalización / escalado de características (si aplica)

---

### 6️⃣ Entrenamiento del modelo kNN

- Selección del valor de **k**
- Entrenamiento del clasificador `KNeighborsClassifier`
- Ajuste del modelo con los datos de entrenamiento

---

### 7️⃣ Evaluación del modelo

Se evalúa el rendimiento utilizando:

- Accuracy
- Matriz de confusión
- Reporte de clasificación (precision, recall, f1-score)

---

### 8️⃣ Análisis de importancia de características

Aunque kNN no genera importancia de variables de forma nativa, el notebook incluye:

- Análisis comparativo de características
- Visualización gráfica de la relevancia de variables
- Identificación de las **dos características más importantes**

---

### 9️⃣ Visualizaciones finales

- Gráficos para interpretación del modelo
- Representación visual de los resultados
- Análisis interpretativo de las predicciones

---

## 📊 Resultados

- El modelo logra una **alta precisión** en la clasificación de las especies de IRIS.
- Se confirma que las características relacionadas con los **pétalos** son las más discriminantes.
- El enfoque es adecuado como introducción al Aprendizaje Supervisado.

---

## 🔁 Reproducibilidad

Para garantizar resultados reproducibles:

- Se utiliza una **semilla aleatoria (`random_state`)** fija al dividir los datos.
- Se especifican explícitamente las librerías requeridas.
- El dataset utilizado es el mismo en todas las ejecuciones.

---

## 🧠 Conclusiones

Este notebook demuestra de forma práctica:

- El flujo completo de un problema de clasificación
- La aplicación de kNN en un dataset real
- La importancia del análisis exploratorio previo
- Buenas prácticas para experimentos reproducibles

---

## 📚 Uso académico

Este material puede ser utilizado en:
- Cursos de Machine Learning
- Introducción a Ciencia de Datos
- Aprendizaje Supervisado
- Prácticas guiadas o tareas individuales

---

## ✍️ Autor

**Manuel Eugenio Morocho Cayamcela**  
PhD – Artificial Intelligence & Networks  
