📊 Predicción de Ventas 2025 – Cadena de Ópticas

Este proyecto analiza el comportamiento histórico de ventas de una cadena de ópticas en México (2022–2024) y desarrolla un modelo predictivo capaz de estimar las ventas por sucursal para el año 2025.
Incluye análisis exploratorio, limpieza profunda, ingeniería de características, modelado de series de tiempo y validación.

🚀 Objetivo del Proyecto

Identificar patrones y tendencias en ventas mensuales.
Evaluar el impacto de descuentos, promociones y características de sucursales.
Detectar outliers y anomalías.
Construir un modelo de series de tiempo (Holt-Winters) para proyectar ventas en 2025.
Generar visualizaciones claras y un dashboard final.

📂 Estructura del Proyecto
📁 data
- datos_limpios.csv       
     
📁 notebooks
- Proyecto_Mas_Vision.ipynb

📁 reports
- Presentacion_Proyecto Mas Vision.pptx  
- Dashboard_PowerBI_Capturas.pdf    
- Predicciones_2025.csv              

🔍 Metodología
1. Limpieza y Procesamiento

Normalización de tipos de datos
Imputación de valores faltantes
Consolidación de información por sucursal
Creación de tabla calendario

2. Análisis Exploratorio (EDA)

Tendencias de ventas 2022–2024
Identificación de estacionalidad
Análisis de correlaciones
Detección de outliers con IQR y z-score

3. Modelado

Análisis de tendencia y estacionalidad
Pruebas de distintos enfoques de forecasting
Selección del modelo de suavizado exponencial Holt-Winters (aditivo/multiplicativo según el caso)
Validación usando train-test split temporal y métricas de error (por ejemplo, MAE / RMSE)

4. Predicción 2025

Proyección de ventas mensuales por sucursal
Visualización de tendencia esperada
Exportación de resultados a CSV

🛠️ Tecnologías utilizadas

-Python
-pandas 
-numpy
-statsmodels
-scikit-learn
-matplotlib 
-seaborn

-Power BI
-Power Query
-Medidas DAX
-Dashboard interactivo

-Jupyter Notebook

📈 Resultados Principales

Se identificó una estacionalidad marcada en ciertos meses clave.
Algunas sucursales presentan patrones atípicos influenciados por promociones y descuentos.
El modelo Holt-Winters mostró mejor desempeño que otros enfoques probados, logrando errores de predicción razonables sobre el conjunto de validación.
Las predicciones 2025 permiten planificar inventarios y metas de ventas con anticipación a nivel sucursal.

📌 Conclusión

El proyecto demuestra el ciclo completo de un análisis profesional de series de tiempo aplicado a un negocio real: desde datos crudos hasta insights accionables y predicciones útiles para la toma de decisiones.
La solución puede integrarse en un pipeline de forecasting mensual para actualizar las proyecciones conforme se obtienen nuevos datos.
