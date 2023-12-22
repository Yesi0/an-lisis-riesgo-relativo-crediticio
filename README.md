# 📊 Análisis de Riesgo Crediticio - Banco "Super Caja"

## 🌐 Contexto

En un entorno de tasas de interés decrecientes, el banco "Super Caja" ha visto un aumento en la demanda de créditos. El proceso manual actual para evaluar las solicitudes de préstamo ha resultado ineficiente y lento, provocando un cuello de botella en el equipo de análisis de crédito y retrasando la toma de decisiones.

## 🎯 Objetivo

Este proyecto se centra en la automatización y mejora del análisis de crédito a través de técnicas avanzadas de análisis de datos. El fin es aumentar la precisión en la evaluación del riesgo crediticio, lo que permitirá al banco tomar decisiones más informadas y reducir la incidencia de préstamos incobrables.

## 📝 Descripción del Proyecto

Se desarrolló un modelo de scoring crediticio para categorizar a los solicitantes de crédito en diferentes niveles de riesgo basándose en su probabilidad de incumplimiento. Se ha incorporado una métrica de pagos atrasados existente para mejorar la predicción de riesgos.

## 🔧 Herramientas Utilizadas

- **SQL con BigQuery**: Para consultas y manejo de datos.
- **Looker Studio**: Para visualizaciones de datos.
- **Python**: Para el modelado estadístico y evaluación de modelos.

## ⚙️ Proceso de Análisis

1. **Extracción de Datos**: Se realizaron consultas complejas en BigQuery.
2. **Visualización de Datos**: Se crearon dashboards interactivos en Looker Studio.
3. **Modelado Estadístico**: Se construyó un modelo de regresión logística en Python.
4. **Evaluación del Modelo**: Se evaluó mediante la matriz de confusión.

## 📈 Resultados

El modelo predictivo ha identificado eficazmente los siguientes patrones:

- 🚀 **Edad y Monto del Préstamo**: Existe una correlación positiva entre la edad de los clientes y el monto total de préstamo concedido, indicando que clientes mayores tienden a recibir préstamos de montos mayores.
-💳 **Uso del Crédito y Ratio de Deuda**: Los gráficos revelan una fuerte correlación positiva entre el ratio de deuda y el monto del préstamo, sugiriendo que clientes con mayores niveles de deuda son más propensos a tener préstamos más grandes.
- 📊 **Matriz de Confusión**: El análisis de la matriz de confusión indica una alta precisión del modelo en la identificación de verdaderos negativos, aunque con un número considerable de falsos positivos, lo que implica una tendencia del modelo a sobreestimar el riesgo de incumplimiento.
- El modelo de clasificación desarrollado ha demostrado ser efectivo en la identificación de clientes con alto riesgo de incumplimiento, lo que ha optimizado la estrategia de aprobación de créditos del banco.


Estos insights están ayudando a "Super Caja" a mejorar sus estrategias de concesión de crédito y a establecer políticas más efectivas para la gestión de riesgos.

## Dashboard 

<img width="256" alt="image" src="https://github.com/Yesi0/an-lisis-riesgo-relativo-crediticio/assets/125078076/7ff1fca3-b2fb-4b0b-b1a4-d5eb96bcc6e2">

## Matriz de confusión y Regresión Logística
[Link aqui](https://colab.research.google.com/drive/1o4LRiQBxte7LHp_mUgafNl-JLKR9Z9ZS?usp=sharing)
