# Salesforce Pipeline Analysis

Este proyecto es un **análisis de oportunidades de ventas** basado en un dataset de Salesforce, usando Databricks y pandas para exploración y visualización. Incluye un mini dashboard interactivo para filtrar datos por propietario de oportunidades (Owner).

## 📂 Archivos del proyecto

- `Salesforce pipeline.ipynb` – Notebook principal con análisis y dashboard.  
- `ProductPipelineUSA.csv` – Dataset de ejemplo de Salesforce.

## 🔹 Objetivos del análisis

1. Explorar la **distribución de oportunidades por etapa (Stage)**.  
2. Analizar **montos totales y promedio** por Stage y por Producto.  
3. Evaluar el **desempeño de los representantes (Owner)** en Pipeline y Contract Amount.  
4. Construir un **dashboard interactivo** para visualizar KPIs y métricas clave.

## 🔹 Tecnologías utilizadas

- **Databricks Free Edition**  
- **Python** (pandas, matplotlib, seaborn)  
- **PySpark** para carga y preprocesamiento seguro de datos
- **Widgets de Databricks** para filtrado interactivo

## 🔹 Cómo ejecutar el proyecto

1. Abrir `Salesforce pipeline.ipynb` en Databricks.  
2. Asegurarse de que el dataset CSV esté en `data/ProductPipelineUSA.csv`.  
3. Ejecutar todos los bloques del notebook.
4. Interactuar con el widget `Owner` para filtrar oportunidades.  

## 🔹 Resultados esperados

- Visualizaciones de distribución de oportunidades por Stage.  
- Montos totales de Pipeline y Contract por Stage y Producto.  
- Tabla de desempeño de cada Owner.  
- Dashboard interactivo que permite exploración rápida de los datos.

---
