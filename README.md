##Telecom X - Predicción de Cancelación (Churn) 

## Descripción del Proyecto
Este proyecto forma parte de mi rol como Analista Junior de Machine Learning .. El objetivo principal es desarrollar modelos predictivos robustos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios (Churn), permitiendo a la empresa tomar decisiones proactivas de retención.

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Lenguaje:** Python
* **Entorno:** Google Colab
* **Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Logistic Regression, Random Forest), Imbalanced-Learn (SMOTE)

## 🧠 Estructura del Proyecto
1. **Preparación de Datos:** Limpieza final, One-Hot Encoding, verificación de proporciones y balanceo de clases sintético mediante SMOTE. Normalización de datos para modelos sensibles a la escala.
2. **Correlación y Selección:** Análisis exploratorio dirigido para identificar los atributos más correlacionados con el Churn (ej. Tiempo de contrato y Gastos).
3. **Modelado Predictivo:** Entrenamiento y comparación de dos algoritmos:
   * *Regresión Logística* (usando datos estandarizados).
   * *Random Forest* (modelo basado en árboles, sin estandarizar).
4. **Evaluación:** Uso de métricas clave de clasificación (Accuracy, Precision, Recall, F1-Score) y Matrices de Confusión.
5. **Interpretación de Variables:** Extracción de la importancia de características y coeficientes para entender el "por qué" de las predicciones del modelo.

