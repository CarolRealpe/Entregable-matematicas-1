# Entregable-matematicas-1
# Predicción de Churn de Clientes  
## Proyecto Integral de Analítica y Modelado de Datos  
### Aplicando la metodología ASUM-DM

---

## Descripción general del proyecto

Este proyecto tiene como objetivo analizar, modelar y optimizar un sistema de predicción de fuga de clientes (customer churn) utilizando el dataset **Telco Customer Churn**.  
El trabajo se desarrolla siguiendo la metodología **ASUM-DM**, una guía estructurada para proyectos de ciencia de datos que cubre desde la comprensión del problema hasta la comunicación de resultados.

El proyecto incluye:
- Una exploración detallada de los datos (EDA)  
- Evaluación de la calidad de los datos  
- Construcción de un modelo base  
- Optimización del modelo mediante ajuste de parámetros  
- Elaboración de un informe técnico en PDF  
- Un notebook completo y reproducible  
- Una presentación tipo *elevator pitch*  
- Bitácora y planeación del equipo de trabajo  

---

## Objetivo analítico

Desarrollar un modelo capaz de predecir si un cliente abandonará el servicio (churn), identificando:
- Los factores más relevantes del comportamiento de fuga  
- El desempeño del modelo antes y después de la optimización  
- Conclusiones prácticas para una empresa de telecomunicaciones  

---

## Preguntas clave del proyecto

1. ¿Cuáles son los factores demográficos o de servicio más asociados al churn?  
2. ¿Qué variables presentan mayor correlación con el abandono del cliente?  
3. ¿Qué modelo de clasificación permite obtener mejores métricas con bajo costo computacional?  
4. ¿Qué ajustes de optimización mejoran significativamente el rendimiento del modelo?  
5. ¿Qué conclusiones analíticas pueden apoyar la toma de decisiones de retención de clientes?  

---

## Metodología utilizada: ASUM-DM

Este proyecto sigue las fases de ASUM-DM:

### **1. Business Understanding**  
- Definición del problema  
- Objetivos del negocio  
- Necesidades analíticas  

### **2. Data Understanding**  
- Exploración inicial  
- Evaluación de calidad  
- Identificación de variables críticas  
- Visualizaciones y primeros hallazgos  

### **3. Data Preparation**  
- Limpieza de datos  
- Transformaciones  
- Codificación de variables categóricas  
- Normalización cuando corresponde  

### **4. Modeling**  
- Selección del algoritmo  
- Entrenamiento del modelo inicial  
- Evaluación de métricas base  

### **5. Evaluation & Optimization**  
- Comparación del modelo optimizado con el modelo inicial  
- Justificación de los ajustes realizados  
- Selección final del modelo  

### **6. Deployment**  
- Entrega del notebook  
- Informe PDF  
- Presentación ejecutiva  
- Opcional: Dashboard  

### **7. Feedback**  
- Conclusiones finales  
- Reflexiones sobre el proceso  
- Recomendaciones  

---

## 🗂 Estructura del repositorio
Proyecto-Churn-ASUMDM
│
├── data/
│ └── telco_churn.csv
│
├── notebooks/
│ └── churn_project.ipynb
│
├── docs/
│ ├── informe_tecnico_ASUMDM.pdf
│ └── bitacora_equipo.pdf
│
├── presentation/
│ └── elevator_pitch_churn.pptx
│
└── README.md


---

## Contenido del Notebook

El notebook contiene:

### EDA completo
- Análisis de nulos  
- Detección de anomalías  
- Distribuciones  
- Gráficos de churn  
- Relación entre variables  
- Más de 5 conclusiones basadas en evidencia  

### Preparación de datos
- Limpieza  
- Imputación  
- One-hot encoding  
- Selección de variables  

### Modelado
- Regresión logística (modelo base)  
- Árbol de decisión (si se requiere comparación)  

### Optimización
- Ajuste de hiperparámetros como:  
  - `C`, `max_iter` (Logistic Regression)  
  - `max_depth`, `criterion` (Decision Tree)  
- Comparación antes / después  

### Resultados finales
- Interpretación de métricas  
- Elección del mejor modelo  

---

## Equipo de trabajo

| Nombre  | Rol principal | Responsabilidades |
|---------|---------------|-------------------|
| **Carol Realpe** | Coordinación general | Repositorio, ASUM-DM, informe técnico |
| **Luis ______**  | Data Understanding | EDA, visualizaciones y hallazgos |
| **Miguel ______** | Modelado | Modelo base y replicabilidad |
| **Sneider ______** | Optimización | Ajuste de hiperparámetros y comparación |

---

## Bitácora de trabajo del equipo

### **Día 1**
- Creación del repositorio  
- Descarga del dataset  
- Plantilla inicial del notebook  

### **Día 2–3**
- Análisis exploratorio (EDA)  
- Limpieza y preparación de datos  

### **Día 4**
- Modelado base  

### **Día 5**
- Optimización del modelo  
- Evaluación comparativa  

### **Día 6**
- Elaboración del informe PDF  

### **Día 7**
- Construcción de la presentación  
- Revisión final  

---

## 🛠 Tecnologías utilizadas

- **Python 3.x**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-learn**  
- **Jupyter Notebook**  
- **Git & GitHub**  

---

## Referencias

- Dataset oficial: Telco Customer Churn  
- IBM Sample Data Sets  
- Documentación Scikit-learn  
- ASUM-DM Framework  

---

## Estado final del proyecto
Este proyecto cumple los requisitos del **Desafío Integral de Análisis, Modelado y Optimización de Datos**, demostrando la aplicación práctica del ciclo ASUM-DM desde el análisis exploratorio inicial hasta la comunicación de resultados.


