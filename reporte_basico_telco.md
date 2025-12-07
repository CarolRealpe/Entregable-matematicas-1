# Reporte Inicial --- Telco Customer Churn (Procesamiento Básico)

Este documento cubre únicamente los requerimientos solicitados:

-   Descargar y almacenar el dataset\
-   Ubicarlo en `/data/raw/`\
-   Evaluar calidad de datos\
-   Identificar nulos, duplicados y tipos\
-   Reportar problemas iniciales

------------------------------------------------------------------------

## 1. Descarga y Almacenamiento del Dataset

El archivo **WA_Fn-UseC\_-Telco-Customer-Churn.csv** fue descargado
desde Kaggle y almacenado correctamente.

**Ubicación sugerida en el proyecto:**

    /data/raw/WA_Fn-UseC_-Telco-Customer-Churn.csv

------------------------------------------------------------------------

## 2. Estructura del Dataset (Shape)

-   **Filas:** 7043\
-   **Columnas:** 21

------------------------------------------------------------------------

## 3. Tipos de Datos Detectados

``` text
customerID           object
gender               object
SeniorCitizen        int64
Partner              object
Dependents           object
tenure               int64
PhoneService         object
MultipleLines        object
InternetService      object
OnlineSecurity       object
OnlineBackup         object
DeviceProtection     object
TechSupport          object
StreamingTV          object
StreamingMovies      object
Contract             object
PaperlessBilling     object
PaymentMethod        object
MonthlyCharges       float64
TotalCharges         object
Churn                object
```

------------------------------------------------------------------------

## 4. Valores Nulos

El archivo no contiene nulos explícitos, pero **TotalCharges incluye
valores vacíos representados como texto**, que generarán nulos al
convertir a numérico.

------------------------------------------------------------------------

## 5. Filas Duplicadas

-   **Duplicados:** 0

------------------------------------------------------------------------

## 6. Problemas Iniciales Identificados

1.  **`TotalCharges` está como texto (object)\
    Debe convertirse a numérico.**

2.  **Al convertir `TotalCharges` aparecerán NaNs**, indicando registros
    con problemas en esa columna.

3.  **`customerID` no aporta información analítica**, ya que es solo un
    identificador.

4.  **Dataset limpio en duplicados**, no requiere depuración por este
    lado.

------------------------------------------------------------------------

## 7. Conclusión

El dataset está completo y bien estructurado, salvo por el problema
común de `TotalCharges`, que requiere corrección. 