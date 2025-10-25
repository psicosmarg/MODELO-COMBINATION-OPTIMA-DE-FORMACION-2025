# Modelo Predictivo para Optimizar la Efectividad de la Formación (Datos Robustos)

**Proyecto:** 8 \| **Autores:** Gutierrez Fernandez, Jesus Osmar y Marcelo Porcayo, Tonancy Lizahaya \| **Estado:** Finalizado

## 1. Contexto y Objetivo del Proyecto

Este proyecto simula una consultoría para "Global Secure Insurance", una aseguradora global. El objetivo es analizar datos robustos (500 empleados) para entender cómo factores demográficos (edad, educación) impactan la efectividad de diferentes modalidades de formación (En línea vs. Presencial) y construir un modelo predictivo para optimizar el diseño instruccional.

## 2. Preguntas Clave del Análisis

-   ¿Cómo influyen la **edad** y el **nivel educativo** en la efectividad (`puntaje_post_formacion`) de las modalidades de formación **En línea vs. Presencial**?
-   ¿Podemos construir un modelo preciso para predecir el resultado de la formación y guiar las decisiones de diseño?

## 3. Metodología Aplicada

Se utilizó un dataset simulado robusto (500 filas). La metodología incluyó: \* **Análisis Exploratorio de Datos (EDA)** detallado para identificar patrones e interacciones. \* **Construcción y Validación de un Modelo Predictivo** (Regresión Lineal v2.0) utilizando `tidymodels`, incorporando la calificación inicial (`puntaje_pre_formacion`) como predictor clave.

## 4. Hallazgo Principal

El análisis reveló que la formación **En línea** es consistentemente efectiva en todas las edades, mientras que la **Presencial** es superior para empleados jóvenes pero su ventaja disminuye con la edad. El **puntaje inicial** es el predictor más fuerte del resultado final. El modelo v2.0 final demostró **alta precisión** (R² ≈ 0.75, Error Promedio ≈ 3.2 puntos), validando su utilidad.

## 5. Estrategia Propuesta (ROI)

Se desarrolló un prototipo funcional del **"Simulador de Efectividad v2.0"** (aplicación R Shiny) impulsado por el modelo predictivo. Esta herramienta permite: 1. Predecir la calificación final esperada para diferentes perfiles y modalidades. 2. Optimizar el diseño de cursos y la asignación de modalidades. 3. Justificar las inversiones en formación basándose en predicciones de impacto.

## 6. Entregable Público

El reporte visual completo (en inglés), que incluye los hallazgos clave y una **demostración en video** del "Simulador de Efectividad", se puede consultar en la siguiente página web:

[**Visualizar el Reporte Interactivo Completo aquí**](https://psicosmarg.github.io/MODELO-COMBINATION-OPTIMA-DE-FORMACION-2025/)
