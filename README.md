# Proyecto: Análisis Exploratorio de Datos Bancarios (EDA_Banco_Python)

## Descripción

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) para identificar factores que influyen en la suscripción de productos bancarios por parte de los clientes. Para ello, se trabajan datos de campañas de marketing bancario y detalles sociodemográficos y financieros de los clientes.

---

## Estructura del Repositorio

EDA_Banco_Python/
│
├── README.md
├── data/
│ └── raw/
│ ├── bank-additional.csv
│ ├── customer-details.xlsx
│ └── DataProject_Proyecto EDA con Python.docx
│
└── notebooks/
└── EDA_Banco.ipynb


- `data/raw/`: Contiene los archivos originales proporcionados para el análisis.
- `notebooks/`: Contiene el notebook Jupyter con el análisis exploratorio, visualizaciones y conclusiones.
- `README.md`: Documento con descripción y guía del proyecto.

---

## Contenido del Proyecto

### 1. Datos Utilizados

- **bank-additional.csv**: Datos de campañas de marketing con información sobre contactos, resultados y características de la campaña.
- **customer-details.xlsx**: Datos sociodemográficos y financieros de los clientes.
- **Documento de proyecto**: Detalles y planificación del análisis.

### 2. Procesamiento y Limpieza

- Carga y unión de los datasets mediante la columna ID.
- Limpieza de datos, incluyendo manejo de valores nulos y conversión de tipos.
- Preparación de variables para análisis estadístico.

### 3. Análisis Exploratorio

- Estadísticas descriptivas generales para entender la distribución de los datos.
- Análisis bivariado y multivariado para identificar relaciones entre variables numéricas y categóricas con la variable objetivo (suscripción).
- Agrupación y segmentación de variables clave (edad, ingresos, número de hijos, contacto, historial de campañas anteriores, etc.).
- Visualizaciones con gráficos de barras y mapas de calor para facilitar la interpretación.

### 4. Conclusiones

- Identificación de variables con mayor influencia en la suscripción al producto bancario.
- Recomendaciones para campañas futuras basadas en los hallazgos.

---

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/tu_usuario/EDA_Banco_Python.git

2. Instalar las dependencias necesarias (recomendado usar entorno virtual):

pip install pandas numpy matplotlib seaborn openpyxl

3. Abrir el notebook notebooks/EDA_Banco.ipynb en Jupyter Notebook o JupyterLab para ejecutar y revisar el análisis.

Autor
Nacho Palomino

Notas
Este proyecto se realiza como parte del curso de Análisis de Datos y está orientado a demostrar habilidades en limpieza de datos, análisis exploratorio, visualización y redacción de informes.