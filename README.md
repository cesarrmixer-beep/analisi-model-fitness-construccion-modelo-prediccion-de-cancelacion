# Predicción de Cancelación de Clientes | Model Fitness

Proyecto de Data Science para predecir por qué canal un cliente cancela su membresía y reducir el churn.

### 🎯 Objetivo de Negocio
Reducir la tasa de cancelación (churn) identificando los canales y patrones de riesgo para aplicar estrategias de retención proactivas.

### 🛠️ Stack Tecnológico
- **Lenguaje:** Python, Pandas, NumPy
- **Visualización:** Matplotlib / Seaborn
- **Machine Learning:** Scikit-learn
- **Modelos evaluados:** Regresión Logística y Random Forest

### 📊 Proceso del Proyecto
1.  Limpieza de datos y Análisis Exploratorio (EDA)
2.  Ingeniería de variables
3.  Entrenamiento y comparación de modelos

### 📈 Resultados Clave
- **Mejor modelo:** LogisticRegression
- **Razón:** Tomando en cuenta las metricas metricas Precision y Recall,  el modelo LoggisticRegresion supera por una diferencia peqeuña pero notable, en Precision tenemos 87 contra 85 y en Recall tenemos 83 contra 82, lo cual nos dice que el modelo acerto de manera mas exacta en las preguntas clave, ¿que porcentage que se fue? , y ¿que porcentage logro detectar que se fue?
- **Insight de negocio:** Toamndo en cuenta los datos obtenidos, el cluster numero 1 es el que tiene el promedio mas alto de 'Churn', seguido del cluster 0, y en tercer lugar esta el cluster 2.
Si tomamos en cuenta el contract_period del cluster mas alto '1' es de 1.63 con un life_time de 1.8, y el contract_period del cluster mas bajo '4', podemos obcervar que curiosamente este es de 3.65 con u life_time de 12.7, los clientes estan fiemando contratos por periodos cortos, pero aun asi, la permanencia es prolongada en el caso dela cluster mas bajo, en ambos casos el cluster mas alto tiene un promedio de visitas de 1.2 mientras que el cluster mas bajo tiene 1.8, el cluster mas alto gasta un promedio extra al mes de 120.19 mientras que l cluster mas bajo llega a un promedio de 147.

### 🚀 Cómo ejecutarlo
