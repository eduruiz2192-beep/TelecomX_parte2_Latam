# Telecom X Parte 2: Predicción de Evasión con Machine Learning

## Objetivo
En esta segunda fase, el objetivo fue construir modelos predictivos capaces de identificar a los clientes con riesgo de abandonar la empresa.

## Tecnologías y Técnicas
* **Balanceo de Clases:** Se utilizó **SMOTE** para equilibrar los datos (50/50) y evitar sesgos en el aprendizaje.
* **Estandarización:** Uso de `StandardScaler` para normalizar las escalas numéricas.
* **Modelado:** Se implementaron y compararon los modelos de **Regresión Logística** y **Random Forest**.

## Resultados
* **Modelo Ganador:** Random Forest con un **84% de exactitud (Accuracy)**.
* **Variable más influyente:** La antigüedad del cliente (Tenure) y los cargos mensuales.

## Conclusión
El modelo desarrollado permite a Telecom X anticiparse a la fuga de clientes, permitiendo aplicar estrategias de retención personalizadas antes de que se pierda el contrato.
