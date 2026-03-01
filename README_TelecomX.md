# 📊 Telecom X -- Análisis de Fuga de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Análisis%20de%20Datos-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Estado](https://img.shields.io/badge/Proyecto-Finalizado-success)

------------------------------------------------------------------------

## 📌 Descripción del Proyecto

Este proyecto desarrolla un proceso completo de **ETL (Extracción,
Transformación y Carga)** y **Análisis Exploratorio de Datos (EDA)** con
el objetivo de identificar los factores que influyen en la **fuga de
clientes (churn)** en una empresa del sector telecomunicaciones (Telecom
X).

El análisis busca comprender las causas estructurales del abandono y
proponer **estrategias basadas en datos** para mejorar la retención y el
valor del cliente en el tiempo.

------------------------------------------------------------------------

## 🎯 Objetivos de Negocio

-   Identificar patrones asociados a la evasión de clientes\
-   Generar visualizaciones estratégicas para apoyar la toma de
    decisiones\
-   Proponer recomendaciones accionables para reducir la tasa de
    abandono\
-   Establecer una base analítica para futuros modelos predictivos

------------------------------------------------------------------------

## 🛠 Metodología

### 1️⃣ Extracción de Datos

-   Carga del dataset desde repositorio externo\
-   Validación de estructura y tipos de variables

### 2️⃣ Limpieza y Transformación

-   Tratamiento de valores nulos\
-   Estandarización de variables categóricas\
-   Conversión de tipos de datos\
-   Ingeniería de variables relevantes

### 3️⃣ Análisis Exploratorio (EDA)

-   Análisis de correlaciones\
-   Segmentación por antigüedad\
-   Comparación por tipo de contrato\
-   Impacto del método de pago\
-   Evaluación de servicios adicionales\
-   Análisis de cargos mensuales

### 4️⃣ Modelado Predictivo (Preliminar)

-   Modelo de regresión logística\
-   Evaluación mediante curva ROC\
-   Análisis de desempeño del modelo

------------------------------------------------------------------------

## 🔎 Principales Hallazgos

### 1️⃣ La Antigüedad es el Principal Factor de Riesgo

Los clientes durante los primeros seis meses presentan una probabilidad
significativamente mayor de abandono.

> El ciclo temprano del cliente es la ventana crítica de intervención.

### 2️⃣ Fricción en el Método de Pago

El método **Cheque Electrónico** presenta la tasa de abandono más
elevada (\~45%).

### 3️⃣ Alta Volatilidad en Contratos "Mes a Mes"

Los clientes sin compromiso de largo plazo muestran mayor propensión a
cancelar.

### 4️⃣ Relación entre Cargos Mensuales y Fuga

Los clientes con mayores cargos mensuales presentan mayor probabilidad
de abandono.

### 5️⃣ Servicios Adicionales como Anclas de Retención

Servicios como Soporte Técnico, Seguridad en Línea y Backup reducen la
probabilidad de fuga.

### 6️⃣ Perfil Digital y Facturación Electrónica

Los clientes con facturación electrónica muestran mayor tasa de
abandono.

------------------------------------------------------------------------

## 🚀 Recomendaciones Estratégicas

-   Programa de retención temprana\
-   Incentivos para pago automático\
-   Migración hacia contratos anuales\
-   Estrategia de bundling de servicios

------------------------------------------------------------------------

## 🧰 Tecnologías Utilizadas

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Seaborn\
-   Scikit-Learn\
-   Jupyter Notebook

------------------------------------------------------------------------

## 📂 Estructura del Repositorio

📁 telecomx-churn-analysis\
├── TelecomX_Analysis.ipynb\
├── dataset.csv\
├── README.md\
└── images/

------------------------------------------------------------------------

## 👤 Autor

Proyecto desarrollado como ejercicio aplicado de análisis de datos y
estrategia de negocio.
