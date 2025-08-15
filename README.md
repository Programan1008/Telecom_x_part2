# 📊 Proyecto TelecomX Parte 2 — Predicción de Evasión de Clientes (Churn part2)

## 📝 Descripción del Proyecto
Este proyecto forma parte de la actividad final del módulo de **Análisis de Datos y Machine Learning** del programa de certificación en Ciencia de Datos de **Alura Latam y Oracle**.  
El objetivo principal es **analizar el comportamiento de clientes de una empresa de telecomunicaciones** y construir un modelo predictivo capaz de identificar aquellos con mayor probabilidad de abandonar el servicio (**Churn**).

---

## 🎯 Objetivos
1. Realizar un **proceso ETL** (Extracción, Transformación y Carga) de los datos.
2. Efectuar una **limpieza y tratamiento de valores faltantes**.
3. Desarrollar un **Análisis Exploratorio de Datos (EDA)** para identificar patrones y correlaciones.
4. Construir modelos de **Machine Learning** para predecir la evasión de clientes.
5. Extraer **conclusiones y recomendaciones de negocio** para reducir el churn.

---

## 📂 Estructura del Proyecto
- **1️⃣ Importación de Librerías y Datos**  
  Carga del dataset original y librerías necesarias para análisis y modelado.
  
- **2️⃣ Limpieza y Preprocesamiento**  
  - Tratamiento de valores nulos y duplicados.  
  - Conversión de variables categóricas a numéricas (One-Hot Encoding).  
  - Escalado de variables numéricas.

- **3️⃣ Análisis Exploratorio (EDA)**  
  - Visualizaciones para identificar patrones relevantes.  
  - Análisis de correlaciones entre variables.  
  - Identificación de factores clave relacionados con el churn.

- **4️⃣ Modelado Predictivo**  
  - Modelos evaluados: **Logistic Regression**, **Random Forest**, **Gradient Boosting**.  
  - Uso de **StratifiedKFold** y **GridSearchCV** para optimizar hiperparámetros.  
  - Métricas de evaluación: Accuracy, Precision, Recall, F1-score, ROC-AUC.

- **5️⃣ Resultados y Conclusiones**  
  - Factores más influyentes en el churn.  
  - Recomendaciones estratégicas.

---

## 📊 Dataset
- **Fuente:** Proporcionado por el curso (TelecomX dataset).
- **Observaciones:** 7,043 clientes, con variables demográficas, de uso y facturación.
- **Variable objetivo:** `Churn` (0 = No se fue, 1 = Se fue).

---

## 🚀 Principales Resultados
- Los **clientes con contrato mensual** presentan una **probabilidad significativamente mayor de churn**.
- Los **cargos mensuales altos** son un factor de riesgo importante.
- Clientes sin servicios adicionales como **seguridad online o soporte técnico** tienden a abandonar más.
- El **Random Forest optimizado** fue el modelo con mejor desempeño (AUC > 0.85).

---

## 💡 Conclusiones y Recomendaciones
- **Fidelización:** Implementar programas de recompensas y descuentos para clientes con contrato mensual.
- **Incentivos a largo plazo:** Promocionar planes anuales o bianuales con beneficios exclusivos.
- **Servicios de valor agregado:** Ofrecer paquetes de bajo costo como soporte técnico o seguridad online para aumentar la retención.
- **Monitoreo constante:** Aplicar el modelo predictivo periódicamente para identificar clientes en riesgo y tomar medidas preventivas.

---

## 🛠️ Tecnologías Utilizadas
- **Lenguaje:** Python 3.13
- **Librerías principales:**  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Entorno:** Google Colab

---

## 📌 Cómo Ejecutar el Proyecto
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Programan1008/Telecom_x_part2.git
