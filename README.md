# 📈 Proyecto: Predicción de Fuga de Clientes

## 1. Descripción del Problema

El objetivo de este proyecto es desarrollar un modelo de Machine Learning capaz de predecir qué clientes de una empresa de telecomunicaciones tienen una alta probabilidad de cancelar su contrato (churn). Identificar a estos clientes de forma proactiva permite a la empresa ofrecerles incentivos para que se queden.

## 2. Dataset

El dataset utilizado es "Telco Customer Churn" de Kaggle. Contiene información demográfica de los clientes, los servicios que han contratado, y si finalmente abandonaron la empresa o no.

[Enlace al Dataset en Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 3. Metodología

El proyecto sigue el siguiente ciclo de vida de Machine Learning:
1.  **Análisis Exploratorio de Datos (EDA):** Limpieza, análisis y visualización de los datos para entender las variables.
2.  **Ingeniería de Características:** Creación de nuevas variables y preprocesamiento para los modelos.
3.  **Modelado:** Entrenamiento y comparación de diferentes algoritmos (p. ej., Regresión Logística, Random Forest, XGBoost).
4.  **Evaluación:** Medición del rendimiento de los modelos con métricas apropiadas como F1-Score y AUC-ROC.

## 4. Cómo Ejecutar el Proyecto

1. Clonar el repositorio: `git clone https://github.com/RobertoGPAI/prediccion-fuga-clientes.git`
2. Instalar dependencias: `pip install -r requirements.txt` (crearemos este archivo más adelante).

## 5. Stack Tecnológico

* Python
* Pandas
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook