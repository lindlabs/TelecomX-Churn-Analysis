#  Telecom X: Intelligence Churn Analysis
### Transformando datos en estrategias de retención de clientes

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458?logo=pandas)
![Status](https://img.shields.io/badge/Project-Completed-green)

---

##  Resumen Ejecutivo
Este proyecto aborda el desafío crítico de la **evasión de clientes (Churn)** en la industria de las telecomunicaciones. Mediante un flujo de trabajo de Ciencia de Datos (ETL + EDA), se analizaron los comportamientos de consumo y perfiles de usuario de **Telecom X** para identificar los factores que disparan la cancelación de servicios.

##  Stack Tecnológico
* **Lenguaje:** Python 3.12.
* **Procesamiento:** Pandas (Limpieza de nulos, aplanamiento de JSON y tipado de datos).
* **Visualización:** Matplotlib & Seaborn (Análisis de tendencias y mapas de calor).

##  Arquitectura del Análisis y Resolución de Problemas
El desarrollo se enfocó en superar inconsistencias en los datos para obtener métricas fiables:

1.  **Pipeline de Datos y Debugging:** Se superaron errores críticos de tipo `IntCastingNaNError` mediante un proceso de limpieza profunda de valores nulos y estandarización de tipos de datos (`object` a `float64`), asegurando que la base de datos fuera apta para el análisis matemático.
2.  **Estandarización:** Se transformó la variable "Abandono" de formato texto a binario (0 y 1), permitiendo el cálculo de la tasa de evasión y correlaciones estadísticas.
3.  **Ingeniería de Características:** Creación de la métrica `Cuentas_Diarias` para entender el impacto económico diario por usuario.



##  Hallazgos de Alto Impacto (Resultados Solucionados)
* **Tasa de Churn Identificada:** 25.72%.
* **Factor Contractual:** El modelo "Mes a Mes" es el principal predictor de fuga; se recomienda incentivar la migración a planes anuales para estabilizar los ingresos.
* **Ventana de Retención:** Los primeros **10 meses** son la etapa más crítica; superar este periodo reduce drásticamente la probabilidad de evasión.

##  Guía de Ejecución
1.  **Clonar:** `git clone https://github.com/lindlabs/TelecomX-Churn-Analysis.git`
2.  **Entorno:** Abrir el notebook `.ipynb` en Google Colab o Jupyter.
3.  **Dependencias:** `pip install pandas matplotlib seaborn`

---

##  Autor
**Lindbergh Paredes**
*Full Stack Developer & Systems Engineer*

> "Ingeniería orientada a datos: Identificando problemas, construyendo soluciones."

