# Proyecto de Clasificación Supervisada: Predicción de Transacciones de Clientes

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un modelo de clasificación supervisada para predecir si un cliente realizará una transacción (1) o no (0). La predicción precisa de estas transacciones es crucial para optimizar campañas de marketing, mejorar la retención de clientes y maximizar las oportunidades de negocio.

## Contexto

El dataset utilizado en este proyecto proviene de la competencia de Kaggle "Santander Customer Transaction Prediction". Incluye 200 características anónimas y una variable objetivo que indica si un cliente realizó una transacción. Este dataset permite analizar y construir modelos predictivos que ayuden a identificar clientes potenciales para estrategias de marketing.

## Contenido del Proyecto

El proyecto incluye los siguientes pasos:

1. **Carga de Datos:** Lectura de los archivos CSV y transformación a DataFrames.
2. **Análisis Exploratorio de Datos (EDA):** Exploración detallada de las distribuciones de las variables, visualizaciones, y detección de valores faltantes, duplicados y atípicos.
3. **Preprocesamiento de Datos:** Limpieza y preparación de los datos, incluyendo la imputación de valores faltantes, manejo del desbalance de clases y estandarización.
4. **Selección y Entrenamiento de Modelos:** Prueba de varios algoritmos de clasificación (Regresión Logística, Random Forest, SVM) y selección del mejor modelo basado en métricas de evaluación.
5. **Evaluación y Validación:** Validación de los modelos utilizando técnicas como la validación cruzada y ajuste de hiperparámetros.

## Requisitos

- Python 3.x
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
