# Bitácora de Trabajo del Equipo  
## Proyecto: Análisis y Predicción de Churn  
**Fecha de inicio:** 06/12/2025  
**Fecha de entrega:** 15/12/2025  

---

## Integrantes del Equipo
- **Carol** – Líder del proyecto  
- **Luis** – Análisis de calidad de datos  
- **Miguel** – EDA y visualizaciones  
- **Sneider** – Limpieza e ingeniería de datos  

---

## Objetivo de la Bitácora
Registrar de manera organizada todas las actividades, tareas, responsabilidades y avances del equipo durante el desarrollo del proyecto, como parte del proceso estructurado con la metodología **ASUM-DM**.

---

# Roles y Responsabilidades del Equipo

## **Carol — Líder del Proyecto**
- Crear y organizar el repositorio en GitHub.
- Definir la estructura final de carpetas del proyecto.
- Redactar el archivo README y mantenerlo actualizado.
- Gestionar y consolidar la bitácora del equipo.
- Asegurar que cada entregable esté correctamente ubicado en el repositorio.
- Coordinar reuniones pequeñas del equipo y revisar avances diarios.
- Unificar notebook, informe técnico y presentación antes de la entrega final.
- Mantener coherencia metodológica con ASUM-DM.

---

## **Luis — Responsable del Dataset**
- Buscar, descargar y verificar el dataset oficial de Telco Customer Churn.
- Almacenar correctamente la data en `/data/raw/`.
- Realizar una descripción inicial del dataset (columnas, tipos, tamaño, etc.).
- Evaluar la calidad de los datos:
  - Registros nulos  
  - Duplicados  
  - Tipos incorrectos  
  - Valores inconsistentes
- Documentar los problemas detectados para que Sneider los solucione.
- Guardar un **reporte inicial del dataset** en `/docs/reporte_dataset.md` o `/docs/reporte_dataset.pdf`.

---

## **Miguel — Especialista en EDA**
- Crear el notebook del EDA en `/notebooks/EDA_churn.ipynb`.
- Realizar el análisis exploratorio completo:
  - Distribuciones de variables
  - Tablas estadísticas
  - Gráficos relacionados al churn
  - Matriz de correlación
  - Comparaciones entre clientes que se van y los que permanecen
- Redactar un mínimo de cinco conclusiones basadas en evidencia.
- Identificar variables clave para el modelado.
- Exportar gráficos para el informe técnico.
- Guardar versiones preliminares enriquecidas del dataset si es necesario.

---

## **Sneider — Limpieza e Ingeniería de Datos**
- Realizar limpieza completa del dataset según problemas encontrados por Luis:
  - Imputación de datos faltantes  
  - Eliminación o revisión de duplicados  
  - Corrección de tipos de datos  
  - Normalización cuando corresponda
- Ingeniería de características (feature engineering):
  - Codificación de variables categóricas (one-hot encoding o label encoding)
  - Transformación de columnas relevantes (ej: convertir `TotalCharges` a numérico)
  - Creación de variables derivadas si aportan valor al modelo
- Exportar el dataset limpio a `/data/processed/churn_clean.csv`.
- Documentar todas las transformaciones realizadas.
- Preparar el dataset final para ser usado en el modelado.


---

# 2. Plan de Trabajo (06–15 de diciembre)

| Fecha | Actividad | Responsable | Estado |
|-------|-----------|-------------|--------|
| **06 dic** | Crear repositorio y estructura | Carol | Completado |
| **06 dic** | Subida del dataset | Luis | Completado |
| **07 dic** | Evaluación de calidad del dataset | Luis | En proceso |
| **07 dic** | Crear notebook inicial | Miguel | En proceso |
| **08 dic** | Realizar EDA preliminar | Miguel | Pendiente |
| **09 dic** | Limpieza y codificación de datos | Sneider | Pendiente |
| **10 dic** | Dataset procesado | Sneider | Pendiente |
| **11 dic** | Modelado inicial | Carol + Sneider | Pendiente |
| **12 dic** | Optimización del modelo | Carol | Pendiente |
| **13 dic** | Redacción del informe PDF | Carol | Pendiente |
| **14 dic** | Ensayo presentación | Todo el equipo | Pendiente |
| **15 dic** | Entrega final del proyecto | Todo el equipo | Pendiente |

---

# 3. Indicaciones Importantes
- El notebook debe ser reproducible desde cero.  
- El EDA debe generar **mínimo 5 conclusiones útiles**.  
- La optimización debe mostrar comparaciones antes/después.  
- El informe PDF debe documentar cada fase de ASUM-DM.  
- La bitácora debe actualizarse hasta el 15 de diciembre.

---

# 4. Estado Actual del Proyecto
- Repositorio creado  
- Carpetas principales listas  
- Bitácora inicial registrada  
- Dataset seleccionado  
- EDA, limpieza y modelado por iniciar  

---

> **Esta bitácora se actualizará diariamente hasta el cierre del proyecto.**

