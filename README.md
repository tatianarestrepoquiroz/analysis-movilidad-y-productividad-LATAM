📊 Movilidad urbana y productividad económica en ciudades de LATAM

📌 ¿De qué trata este proyecto?

Este proyecto analiza la relación entre movilidad urbana (congestión vehicular) y productividad económica (PIB per cápita) en ciudades de América Latina durante 2024–2025.

El objetivo es evaluar si existe una relación entre mayores niveles de congestión y menores niveles de productividad, bajo un enfoque tipo consultoría estratégica.

📂 ¿Qué contiene este repositorio?

📓 Notebook principal

Analysis-Movilidad urbana y productividad económica en ciudades de LATAM.ipynb

Incluye:

Limpieza y estandarización de datos

Extracción y filtrado por año

Integración de datasets (movilidad + PIB)

Análisis exploratorio (EDA)

Visualizaciones estratégicas

Conclusiones y recomendaciones

📈 Visualizaciones incluidas en el análisis

El notebook contiene los siguientes gráficos clave:

1️⃣ Histograma

Permite analizar la distribución del PIB per cápita y entender:

Concentración de ciudades en determinados rangos

Asimetría en los datos

Posibles valores extremos

2️⃣ Boxplot

Utilizado para:

Identificar valores atípicos (outliers)

Analizar la dispersión de los datos

Comparar la variabilidad entre ciudades

Este gráfico es clave para detectar desigualdades estructurales entre ciudades.

3️⃣ Gráfico de barras comparativo

Permite comparar ciudades seleccionadas en términos de:

Nivel de congestión

PIB per cápita

Este gráfico facilita identificar visualmente qué ciudades combinan:

Alta congestión

Productividad económica más baja

Lo que apoya la priorización estratégica.

📊 Hallazgos principales

No se evidencia una correlación fuerte y lineal entre mayor PIB per cápita y mayor congestión.

Existen ciudades con congestión alta y productividad media o baja.

Bogotá y Lima presentan combinación de alta congestión y presión estructural sobre movilidad.

Se identifican outliers que sugieren que la planificación urbana e inversión en transporte influyen más que el nivel económico por sí solo.

🧪 Metodología

Limpieza y transformación de datos con pandas

Agregación por ciudad–año

Integración mediante INNER JOIN

Análisis exploratorio (EDA)

Identificación de outliers

Visualización con matplotlib y seaborn

🚀 ¿Cómo reproducir el análisis?

Abrir el notebook.

Ejecutar todas las celdas en orden (Run All).

El notebook ya incluye la carga de datasets.

No se requieren archivos adicionales.
