# ❤️ Heart Attack Prediction: Machine Learning Workflow

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange?style=for-the-badge&logo=scikit-learn)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Descripción del Proyecto
Este proyecto se enfoca en la creación de un sistema de clasificación binaria para predecir la probabilidad de ataques cardíacos basándose en indicadores clínicos y fisiológicos. El flujo de trabajo abarca desde el **Análisis Exploratorio de Datos (EDA)** hasta la implementación de modelos de aprendizaje supervisado.

> **Nota:** Este notebook fue preparado originalmente para el Machine Learning Bootcamp de **Global AI Hub** (Live Stream en YouTube).

---

## 📊 Diccionario de Datos
El dataset contiene atributos críticos para la salud cardiovascular. A continuación, se detallan las variables clave:

| Variable | Descripción | Valores / Unidades |
| :--- | :--- | :--- |
| **Age** | Edad del paciente | Años |
| **Sex** | Género | 1 = Masc; 0 = Fem |
| **CP** | Tipo de dolor de pecho | 1: Angina típica, 2: Atípica, 3: No-anginal, 4: Asintomático |
| **Trtbps** | Presión arterial en reposo | mm Hg |
| **Chol** | Colesterol sérico | mg/dl |
| **Fbs** | Azúcar en sangre en ayunas | 1: > 120 mg/dl; 0: <= 120 |
| **Rest_ecg** | Resultados electrocardiográficos | 0: Normal, 1: Anomalía ST-T, 2: Hipertrofia ventricular |
| **Thalachh** | Frecuencia cardíaca máxima | bpm |
| **Exng** | Angina inducida por ejercicio | 1: Sí; 0: No |
| **Oldpeak** | Depresión del ST inducida por ejercicio | Medida numérica |
| **Slp** | Pendiente del segmento ST pico | 0: Ascendente, 1: Plano, 2: Descendente |
| **Caa** | Número de vasos principales | Rango (0-4) |
| **Thall** | Resultado de prueba de talio | 0 a 3 |
| **Target** | **Variable Objetivo** | **0: Menor riesgo; 1: Mayor riesgo** |

---

## 🚀 Fases del Proyecto

### 1. Exploración y Visualización (EDA) 🔍
* **Inspección Estadística:** Análisis de tendencia central y dispersión de los datos.
* **Análisis de Correlación:** Uso de mapas de calor para identificar variables con mayor impacto en el riesgo cardíaco.
* **Distribuciones:** Visualización de `Age`, `Trtbps` y `Chol` mediante histogramas y boxplots para detectar sesgos.

### 2. Ingeniería de Características (Feature Engineering) 🛠️
* **Limpieza de Datos:** Identificación y manejo de valores nulos o inconsistentes.
* **Tratamiento de Outliers:** Manejo de valores atípicos en presión arterial y colesterol para mejorar la calidad del modelo.
* **Codificación y Escalado:** Transformación de variables categóricas (Encoding) y estandarización de variables numéricas (Scaling).

### 3. Modelado y Evaluación 🤖
Se implementaron y compararon los siguientes modelos de clasificación:
* **Logistic Regression** (Línea base).
* **K-Nearest Neighbors (KNN)**.
* **Decision Tree**.

La evaluación se centró en métricas de precisión y recall para determinar la capacidad del modelo en identificar casos de alto riesgo.

---

## 📈 Trabajo Futuro (Roadmap)
Para mejorar el rendimiento del sistema, se proponen las siguientes etapas:
- [ ] **Hyperparameter Tuning:** Aplicar `Grid Search` o `Random Search` para optimizar parámetros.
- [ ] **Modelos Avanzados:** Probar con ensambles como **Random Forest**, **XGBoost** o **Gradient Boosting**.
- [ ] **Explicabilidad (XAI):** Implementar valores **SHAP** para interpretar las decisiones del modelo de forma clínica.

---

## 🔗 Recursos
* **Dataset:** [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
* **Librerías principales:** Pandas, Numpy, Scikit-learn, Seaborn, Matplotlib.

---
