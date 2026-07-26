# 🎮 Video Game Sales Prediction
# 🎮 Predicción de Ventas de Videojuegos

An end-to-end Machine Learning project for predicting global video game sales using regression models, feature engineering, and exploratory data analysis.

Proyecto completo de Machine Learning para predecir las ventas globales de videojuegos utilizando modelos de regresión, ingeniería de características y análisis exploratorio de datos.

---

# 🇺🇸 English

## 📌 Project Overview

This project presents an end-to-end Machine Learning pipeline for predicting global video game sales using regression models and feature engineering.

The objective is to estimate the **global sales** of a video game based on several features, including:

- Console
- Genre
- Publisher
- Developer
- Release date

The project follows a complete Machine Learning workflow, from data preprocessing and exploratory analysis to model training, evaluation, and feature importance analysis.

---

## 📂 Dataset

**Source:** VGChartz 2024 Video Game Dataset

The dataset contains information about thousands of video games, including:

- Console
- Genre
- Publisher
- Developer
- Release date
- Regional sales
- Global sales (target variable)

**Target Variable:** `total_sales`

---

## 🛠️ Machine Learning Workflow

- Data Understanding
- Data Cleaning
- Missing Value Handling
- Feature Engineering
- Categorical Encoding
- Exploratory Data Analysis (EDA)
- Train/Test Split
- Linear Regression
- Log-Transformed Linear Regression
- Random Forest Regressor
- Feature Importance Analysis

---

## ⚙️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📈 Model Performance

| Model | MAE | RMSE | R² |
|------|------:|------:|------:|
| Linear Regression | 0.3519 | 0.7894 | 0.0804 |
| Linear Regression (Log Transformation) | 0.3064 | 0.7947 | 0.0680 |
| **Random Forest Regressor** | **0.2903** | **0.7205** | **0.2339** |

Among the evaluated models, the **Random Forest Regressor** achieved the best predictive performance.

---

## 📊 Feature Engineering

The preprocessing pipeline includes:

- Removing irrelevant features
- Removing data leakage variables
- Handling missing values
- Date conversion
- Extracting release year and month
- Frequency Encoding
- One-Hot Encoding

---

## 📉 Most Important Features

According to the Random Forest model, the most influential variables were:

- Release Year
- Developer
- Publisher
- Release Month
- Console
- Genre

---

# 🇪🇸 Español

## 📌 Descripción del Proyecto

Este proyecto presenta un pipeline completo de Machine Learning para predecir las ventas globales de videojuegos utilizando modelos de regresión y técnicas de ingeniería de características.

El objetivo es estimar las **ventas globales** de un videojuego a partir de características como:

- Consola
- Género
- Publicadora
- Desarrolladora
- Fecha de lanzamiento

El proyecto sigue un flujo completo de Machine Learning, desde el preprocesamiento y análisis exploratorio de los datos hasta el entrenamiento, evaluación e interpretación del modelo.

---

## 📂 Dataset

**Fuente:** VGChartz 2024 Video Game Dataset

El conjunto de datos contiene información sobre miles de videojuegos, incluyendo:

- Consola
- Género
- Publicadora
- Desarrolladora
- Fecha de lanzamiento
- Ventas por región
- Ventas globales (variable objetivo)

**Variable objetivo:** `total_sales`

---

## 🛠️ Flujo de Trabajo

- Comprensión de los datos
- Limpieza de datos
- Tratamiento de valores faltantes
- Ingeniería de características
- Codificación de variables categóricas
- Análisis Exploratorio de Datos (EDA)
- División en entrenamiento y prueba
- Regresión Lineal
- Regresión Lineal con transformación logarítmica
- Random Forest Regressor
- Análisis de importancia de variables

---

## ⚙️ Tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📈 Rendimiento de los Modelos

| Modelo | MAE | RMSE | R² |
|------|------:|------:|------:|
| Regresión Lineal | 0.3519 | 0.7894 | 0.0804 |
| Regresión Lineal (Transformación Logarítmica) | 0.3064 | 0.7947 | 0.0680 |
| **Random Forest Regressor** | **0.2903** | **0.7205** | **0.2339** |

De los modelos evaluados, **Random Forest Regressor** obtuvo el mejor desempeño predictivo.

---

## 📊 Ingeniería de Características

Durante el preprocesamiento se realizaron las siguientes tareas:

- Eliminación de variables irrelevantes
- Eliminación de variables con *data leakage*
- Tratamiento de valores faltantes
- Conversión de fechas
- Extracción del año y mes de lanzamiento
- Frequency Encoding
- One-Hot Encoding

---

## 📉 Variables Más Importantes

Según el modelo Random Forest, las variables con mayor influencia fueron:

- Año de lanzamiento
- Desarrolladora
- Publicadora
- Mes de lanzamiento
- Consola
- Género

---

## 📜 License / Licencia

This project is licensed under the **MIT License**.

Este proyecto se distribuye bajo la **Licencia MIT**.