# Telecom X: Intelligence Churn Analysis
### Transformando datos en estrategias de retención de clientes

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458?logo=pandas)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-444444)
![Status](https://img.shields.io/badge/Project-Completed-green)

---

## Resumen Ejecutivo
Este proyecto aborda el desafío crítico de la **evasión de clientes (Churn)** en la industria de las telecomunicaciones. Mediante un flujo de trabajo de Ciencia de Datos (ETL + EDA), se analizaron los comportamientos de consumo y perfiles de usuario de **Telecom X** para identificar los factores que disparan la cancelación de servicios.

## Stack Tecnológico
* **Lenguaje:** Python 3.12.
* **Procesamiento:** Pandas (Limpieza de nulos, aplanamiento de JSON y tipado de datos).
* **Visualización:** Matplotlib & Seaborn (Análisis de tendencias y mapas de calor).
* **Entorno:** Google Colab (Cloud Computing).

## Arquitectura del Análisis
El desarrollo se dividió en fases técnicas rigurosas para asegurar la integridad de los insights:

1.  **Pipeline de Datos (ETL):** Aplanamiento de estructuras complejas, tratamiento de errores de casteo (`IntCastingNaNError`) y estandarización de métricas financieras.
2.  **Ingeniería de Características:** Creación de la métrica `Cuentas_Diarias` y traducción técnica de variables para accesibilidad del negocio.
3.  **Exploración Estadística (EDA):** Análisis de correlación de Pearson para validar hipótesis sobre cargos mensuales y tiempo de permanencia.



## Hallazgos de Alto Impacto
* **Tasa de Churn Baseline:** 25.72%.
* **Factor Contractual:** El modelo "Mes a Mes" es el principal predictor de fuga, con una tasa de abandono drásticamente superior a los planes anuales.
* **Ventana de Retención:** Los primeros **10 meses** son la etapa más crítica; superar este periodo reduce la probabilidad de evasión en un 60%.
* **Sensibilidad al Precio:** Clientes con facturaciones superiores a la mediana ($70.30) muestran una correlación positiva con la cancelación.

## Guía de Ejecución
1.  **Clonar:** `git clone https://github.com/lindlabs/TelecomX-Churn-Analysis.git`
2.  **Entorno:** Abrir el notebook `.ipynb` en Google Colab o Jupyter.
3.  **Dependencias:** `pip install pandas matplotlib seaborn`
4.  **Reproducción:** Ejecutar las celdas secuencialmente para observar la limpieza y generación de gráficas.

---

## Autor
**Lindbergh Paredes**
*Full Stack Developer & Systems Engineer*

> "Combinando la robustez de la ingeniería de sistemas con la agilidad del desarrollo web y el poder de los datos."

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/tu-perfil)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-lightgrey?style=flat&logo=github)](https://github.com/lindlabs)
