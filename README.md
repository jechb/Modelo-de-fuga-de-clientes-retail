# Modelo de Fuga de Clientes - Retail

Proyecto de Data Science enfocado en la predicción del churn (fuga de clientes) en un contexto retail, utilizando técnicas de Machine Learning y análisis de impacto económico.

---

## Objetivo del Proyecto

Desarrollar un modelo predictivo que permita identificar clientes con alta probabilidad de abandonar la tienda, permitiendo generar estrategias de retención basadas en datos.

---

## Enfoque Metodológico

El proyecto sigue un pipeline estructurado de ciencia de datos:

1. Limpieza y validación de datos
2. Análisis exploratorio (EDA)
3. Construcción de variable objetivo (Churn basado en RFM)
4. Feature Engineering
5. Modelado con:
   - Logistic Regression
   - Random Forest
6. Evaluación con métricas de clasificación
7. Análisis de calibración
8. Simulación de impacto económico

---

## Resultados Principales

- ROC-AUC: ~0.85
- Modelo mejor calibrado: Logistic Regression
- Variables más relevantes:
  - Recency
  - Total Orders
  - Total Sales
- LA simulación económica mostró un potencial impacto positivo al aplicar una estrategia de retención sobre el top percentil de riesgo.

---

## Librerias utilizadas

- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib / Seaborn

## Framework de validación y evaluación del modelo
- Pipeline y ColumnTransformer
- Curvas ROC y calibración
- Evaluación económica del modelo

---

## Principales Insights

- La recencia de compra es el predictor más fuerte del abandono.
- Clientes con baja frecuencia y bajo monto de compra presentan mayor probabilidad de churn.
- La calibración del modelo permite interpretar probabilidades como riesgo real.
- El modelo permite optimizar campañas de retención reduciendo costos innecesarios.

---

## Posibles Mejoras Futuras

- Implementar validación temporal
- Optimización de hiperparámetros
- SHAP para mayor interpretabilidad
- Integración con modelo de segmentación

---

## Contexto

Dataset ficticio utilizado con fines académicos (Kaggle).
---

## Autor

Jose Chamorro Barredo 
Chile  
Proyecto desarrollado en el contexto de Diplomado en Data Science.
