# Proyecto de Predicción de Churn  
## Analítica y Modelado aplicando ASUM-DM

## Descripción del proyecto
Este proyecto analiza el fenómeno de fuga de clientes (customer churn) usando el dataset **Telco Customer Churn**.  
El objetivo es identificar los factores asociados al abandono y construir un modelo capaz de predecir el churn.  
El desarrollo sigue una versión resumida de la metodología **ASUM-DM**, adecuada para un proyecto académico de una semana.

---

## Objetivo analítico
Construir un modelo predictivo funcional y demostrar un proceso analítico completo que incluya:
- Exploración de datos (EDA)  
- Limpieza y preparación  
- Modelado inicial  
- Optimización del modelo  
- Resultados y conclusiones  

---

## Metodología ASUM-DM (versión resumida)

### **1. Business Understanding**
- Problema: alto abandono de clientes en telecomunicaciones.  
- Meta: identificar factores clave y predecir churn.  

### **2. Data Understanding**
- Revisión de estructura del dataset  
- Identificación de valores faltantes y datos erróneos  
- Visualizaciones iniciales  
- Obtención de hallazgos y patrones relevantes  

### **3. Data Preparation**
- Limpieza de datos inconsistentes  
- Conversión de variables categóricas  
- Normalización según necesidad del modelo  
- Selección de variables predictoras  

### **4. Modeling**
- Entrenamiento de un modelo base (p. ej. Regresión Logística o Árbol de Decisión)  
- Obtención de métricas iniciales  

### **5. Evaluation / Optimization**
- Ajuste de hiperparámetros  
- Comparación del desempeño antes vs. después  
- Justificación de cambios aplicados  

### **6. Deployment**
- Notebook funcional  
- Informe técnico en PDF  
- Presentación del proyecto  

---

## Estructura del repositorio

Proyecto-Churn
│
├── data/
│ └── telco_churn.csv
│
├── notebooks/
│ └── churn_project.ipynb
│
├── docs/
│ ├── informe_tecnico.pdf
│ └── bitacora_equipo.md
│
├── presentation/
│ └── pitch_churn.pdf / .pptx
│
└── src/
├── eda.py
├── preprocessing.py
├── model.py
└── evaluation.py

yaml
Copiar código

---

## Contenido del notebook
- EDA completo con más de 5 conclusiones reales  
- Preparación y transformación de datos  
- Modelo base entrenado  
- Optimización con hiperparámetros  
- Comparación de métricas  
- Interpretación de resultados  

---

## Roles del equipo

| Integrante | Rol | Actividades |
|-----------|------|-------------|
| **Carol** | Coordinación | Repositorio, documentación, revisión ASUM-DM |
| **Luis** | Data Understanding | EDA y visualizaciones |
| **Miguel** | Modelado | Construcción del modelo base |
| **Sneider** | Optimización | Ajuste de hiperparámetros y comparación de métricas |

---

## Bitácora del proyecto (1 semana)

### **Día 1**
- Creación del repositorio  
- Organización de carpetas  
- Descarga del dataset  

### **Día 2**
- EDA inicial  
- Gráficos y calidad del dato  

### **Día 3**
- Preparación de datos  
- Transformaciones  

### **Día 4**
- Entrenamiento del modelo base  

### **Día 5**
- Optimización y comparación  

### **Día 6**
- Elaboración informe PDF  

### **Día 7**
- Presentación final  

---

## Tecnologías utilizadas
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  
- Git y GitHub  

---

## Referencias
- Dataset Telco Customer Churn (IBM)  
- ASUM-DM Framework  
- Documentación de Scikit-learn  

---
