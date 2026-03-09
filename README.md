# 📉 Predicción de Churn - Telecom X

Este proyecto busca predecir la cancelación de clientes (Churn) para la empresa **Telecom X** utilizando técnicas de Machine Learning. El objetivo principal es identificar a los clientes en riesgo para aplicar estrategias de retención proactivas.

## Resumen del Proyecto

El flujo de trabajo incluyó:
- **Limpieza de datos:** Tratamiento de duplicados y variables irrelevantes.
- **Ingeniería de variables:** Codificación One-Hot y escalado con `StandardScaler`.
- **Balanceo de datos:** Aplicación de **SMOTE** para corregir el desbalance de clases.
- **Modelado:** Comparación entre Regresión Logística y Random Forest.

## Resultados 

El modelo seleccionado fue la **Regresión Logística** debido a su alto desempeño en la métrica de negocio más crítica:

| Métrica | Resultado |
| :--- | :--- |
| **Exactitud (Accuracy)** | 76.72% |
| **Exhaustividad (Recall)** | **68.72%** |

> **Insight principal:** Los contratos mensuales y el servicio de fibra óptica son los principales disparadores de fuga, mientras que la antigüedad del cliente (tenure) actúa como el mayor factor de retención.

---
Realizado con ❤️ por Lucía Jantus
