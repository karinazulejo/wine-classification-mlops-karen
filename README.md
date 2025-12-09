# Wine Classification – MLOps Pipeline
Autora: Karen Espejo Herrera

## 1. Descripción general
Este proyecto implementa un flujo completo de Machine Learning para clasificar la variedad de vino a partir de sus características químicas. Incluye análisis exploratorio, preprocesamiento, modelado supervisado y registro del experimento siguiendo buenas prácticas MLOps.

## 2. Dataset
El dataset proviene del repositorio UCI ML y contiene 178 muestras con 13 características químicas y una variable objetivo (clase).

## 3. Flujo de trabajo
1. Exploración inicial del dataset  
2. Análisis de correlaciones  
3. Evaluación de outliers  
4. Preprocesamiento (conversión de tipos, escalamiento)  
5. Modelado con RandomForest dentro de un Pipeline  
6. Evaluación del modelo con métricas avanzadas  
7. Registro del modelo con MLflow  
8. Predicción final de muestras nuevas
## Arquitectura del pipeline

![Arquitectura del pipeline](assets/Clasificacion%20de%20vinos.png)

## 4. Resultados
- Accuracy: 1.0  
- F1 Weighted: 1.0  
- Predicciones finales:
  - Muestra 1 → Clase 1
  - Muestra 2 → Clase 2

## 5. Conclusiones
El proyecto demuestra un flujo profesional y reproducible basado en buenas prácticas de ciencia de datos y MLOps.

## 6. Estructura recomendada
/
├── README.md  
├── Wine_Classification_Karen.ipynb  
├── requirements.txt  
└── evidencias/  

