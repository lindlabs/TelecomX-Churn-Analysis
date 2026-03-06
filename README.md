# Análisis de Evasión de Clientes (Churn) - Telecom X 🚀

## Descripción del Proyecto
Este proyecto consiste en un análisis de datos integral para identificar por qué los clientes de la compañía Telecom X cancelan sus servicios. A través de un proceso de ETL (Extracción, Transformación y Carga) y un Análisis Exploratorio de Datos (EDA), identificamos patrones críticos que permiten a la empresa tomar decisiones estratégicas para mejorar la retención.

## Tecnologías Utilizadas
* **Python 3.12**
* **Pandas**: Manipulación y limpieza de datos.
* **Matplotlib & Seaborn**: Visualización de datos y matrices de correlación.
* **Google Colab**: Entorno de desarrollo en la nube.

## Estructura del Análisis
1. **Limpieza de Datos**: Aplanamiento de JSON, manejo de valores nulos y conversión de tipos de datos (Object a Float64).
2. **Transformación**: Traducción de variables al español y creación de la métrica `Cuentas_Diarias`.
3. **EDA (Análisis Exploratorio)**: Visualización de la distribución de Churn y relación con variables categóricas (Contratos, Métodos de Pago).
4. **Análisis Estadístico**: Uso de `describe()` y matrices de correlación para validar hipótesis.

## Hallazgos Principales (Insights)
* **Tasa de Abandono**: 25.72%.
* **Contratos**: Los clientes con contrato "Mes a mes" representan el mayor riesgo de fuga.
* **Permanencia**: El riesgo de abandono es crítico durante los primeros 10 meses de antigüedad.

## Cómo Ejecutar el Proyecto
1. Clona este repositorio.
2. Abre el archivo `.ipynb` en Google Colab o Jupyter Notebook.
3. Asegúrate de tener instaladas las dependencias: `pip install pandas matplotlib seaborn`.
4. Ejecuta las celdas en orden secuencial.

---
**Autor:** Kleidex - Full Stack Developer & Systems Engineer
