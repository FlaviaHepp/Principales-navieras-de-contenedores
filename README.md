# 🚢 Análisis de las Mayores Navieras de Contenedores del Mundo

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre las 30 mayores navieras de contenedores del mundo, clasificadas por capacidad de flota en TEU (Twenty-foot Equivalent Unit), según datos de Alphaliner (febrero 2024).

El análisis se centra en comparar capacidad operativa, cuota de mercado, número de barcos y alianzas, utilizando visualizaciones estáticas e interactivas para comprender la estructura y concentración del sector marítimo global.

## 🎯Objetivos del proyecto

- Analizar la distribución de capacidad (TEU) entre las principales navieras.
- Comparar la cuota de mercado de cada empresa.
- Estudiar la relación entre:
- Número de barcos
- Capacidad total (TEU)
- Participación de mercado
- Identificar niveles de concentración del sector.
- Explorar características cualitativas como alianzas y sedes corporativas.

## 🌍Contexto del sector

El transporte marítimo de contenedores es un pilar del comercio internacional.
En enero de 2022, MSC superó a Maersk como la naviera con mayor capacidad por primera vez desde 1996, marcando un cambio estructural en el liderazgo del sector.

📌 Comprender esta industria es clave para:
- Análisis económico global
- Supply chain & logística
- Comercio exterior
- Estudios de competencia y concentración de mercado

## 📊Dataset

Fuente: Alphaliner
Fecha: Febrero 2024
Observaciones: 30 compañías
Formato: CSV

Variables principales:
- Rank: Posición en el ranking mundial
- Company name: Nombre de la naviera
- Headquarters: Sede central
- TotalTEU: Capacidad total de la flota (TEU)
- Ships: Número de barcos
- Marketshare: Cuota de mercado (%)
- Alliance: Alianza marítima
- Notes: Observaciones relevantes

📌 El dataset no presenta valores nulos ni duplicados significativos.

## 🔍Metodología

1️⃣ Inspección y limpieza de datos

- Revisión de estructura y tipos de datos.
- Estadísticos descriptivos.
- Verificación de valores nulos y duplicados.

2️⃣ Análisis Exploratorio (EDA)

📦 Capacidad y cuota de mercado

Gráficos de barras de:
- Capacidad total (TEU)
- Cuota de mercado (%)
- Gráficos circulares para visualizar concentración del mercado.

🚢 Flota

- Comparación del número de barcos por compañía.
- Análisis horizontal y vertical para mejorar legibilidad.

📊 Distribuciones

- Histogramas de variables numéricas.
- Análisis de dispersión y asimetría.

🔗 Correlaciones

Matriz de correlación entre:

- TEU
- Número de barcos
- Cuota de mercado

🏢 Variables categóricas

Distribución por:

- Sede (Headquarters)
- Alianzas marítimas
- Conteos y gráficos de frecuencia.

3️⃣ Análisis textual

- WordCloud basado en nombres de compañías para visualización exploratoria.
- Uso de Counter para frecuencias de términos.

## 📈Principales hallazgos

- El mercado presenta alta concentración, con pocas navieras controlando gran parte de la capacidad global.
- Existe una fuerte correlación positiva entre:
- Número de barcos
- Capacidad total (TEU)
- Cuota de mercado
- Las alianzas juegan un rol clave en la competitividad del sector.
- El tamaño de flota no siempre crece proporcionalmente al número de barcos, reflejando diferencias tecnológicas y de eficiencia.

## 🛠️Tecnologías y Librerías

- Python
- Pandas / NumPy
- Matplotlib
- Seaborn
- Plotly Express
- WordCloud

## 📁Estructura del proyecto

├── The largest shipping lines in the world.csv
├── 1.py
└── README.md

## 🚀Posibles extensiones

- Análisis de concentración (Índice Herfindahl-Hirschman).
- Evolución histórica del ranking por año.
- Comparación pre y post pandemia.
- Dashboard interactivo (Power BI / Tableau / Dash).
- Integración con datos de comercio internacional.

## 👤Autor

Flavia Hepp
Proyecto de análisis de datos aplicado a logística, comercio internacional y transporte marítimo.
