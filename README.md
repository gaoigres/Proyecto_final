# 📘 Modelo de machine learning para la detección de vulnerabilidades financieras

## 📑 Índice  
- [1. Descripción general](#1-descripción-general)  
- [2. Objetivo del proyecto](#2-objetivo-del-proyecto)  
- [3. Dataset](#3-dataset)  
- [4. Metodología](#4-metodología)  
- [5. Resultados clave](#5-resultados-clave)  
- [6. Principales insights](#6-principales-insights)  
- [7. Discusión](#7-discusión)  
- [8. Limitaciones](#8-limitaciones)  
- [9. Conclusiones](#9-conclusiones)  

---

## 1. Descripción general
Este repositorio contiene el desarrollo de un sistema predictivo de clasificación multiclase para estimar vulnerabilidades financireas en el ámbito bancario usando datos públicos y PyCaret.

## 2. Objetivo del proyecto
Construir un modelo replicable y automatizado que clasifique bancos en cinco niveles de riesgo.

## 3. Dataset
Panel mensual 2010–2025 con 2256 observaciones, 12 bancos y 14 indicadores financieros.

## 4. Metodología
Pipeline completo: preprocesamiento, score prudencial, clasificación, AutoML PyCaret, tuning, stacking, validación temporal y SHAP.

## 5. Resultados clave
- Modelo final: Stacking/Voting Ensemble  
- Accuracy: 0.9271  
- Heatmap con ciclos de riesgo y heterogeneidad entre bancos.

## 6. Principales insights
- Ciclos financieros claros.  
- Mora + ROA como señales críticas.  
- Modelos de árboles capturan mejor la complejidad.

## 7. Discusión
El modelo es transparente, granular y altamente replicable.

## 8. Limitaciones
No cubre todos los indicadores prudenciales; no incorpora macro variables.

## 9. Conclusiones
El proyecto muestra que es posible construir un modelo predictivo de clasificación multiclase capaz de estimar el nivel de riesgo prudencial de las entidades bancarias utilizando únicamente información pública y técnicas modernas de aprendizaje automático. 
