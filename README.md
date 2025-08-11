# Proyecto: Análisis Exploratorio de Datos Bancarios (EDA_Banco_Python)

## Descripción

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) para identificar factores que influyen en la suscripción de productos bancarios por parte de los clientes. Para ello, se trabajan datos de campañas de marketing bancario y detalles sociodemográficos y financieros de los clientes.

---

## Estructura del Repositorio

```plaintext
EDA_Banco_Python/
│
├── README.md
├── data/
│   └── raw/
│       ├── bank-additional.csv
│       ├── customer-details.xlsx
│       └── DataProject_Proyecto EDA con Python.docx
│
└── notebooks/
    └── EDA_Banco.ipynb
```

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

 🔎 Conclusión final sobre el análisis bivariado de las variables (numéricas y categóricas):

Ante el análisis realizado de las variables numéricas y categóricas con su influencia en la suscripción, podemos afirmar que los siguientes
grupos, características y segmentaciones deben ser incluidas en la realización de próximas campañas con el objetivo de suscripción, 
al aumentar su tasa de éxito. Cabe destacar que otros grupos, características o segmentaciones pueden ser relevantes para una segunda campaña,
pues aunque tengan menor tasa de éxito que los incluidos en la primera campaña, podremos obtener mayor número de suscripciones realizando 
una segunda campaña:

🎯 Grupos, segmentaciones y características de la Campaña "Éxito Garantizado":

1. Cuanto más larga sea la llamada, más probabilidad existirá de convertirla en suscripción.
2. Establecer un rango óptimo de contactos por cliente de entre 3 y 6. Si el cliente no se ha suscrito tras los 6 contactos, eliminar. 
En caso de que no se haya suscrito y el número de contactos sea inferior a 6, seguir contactando. No exceder en ningún caso los 6 contactos.
3. Si el cliente ya ha sido contactado, no deben pasar más de 30 días en volverse a producir el siguiente contacto.
4. Segmentación por edad: de 65 años en adelante. 
5. Segmentación por Profesiones: 'Student' y 'Retired'.
6. Segmentación por Estado Civil: 'Solteros'.
7. Segmentación por Nivel Educativo: 'University Degree', 'Professional Courses' e 'Illiterate'.
8. La forma de contactar al cliente debe ser por 'cellular'.
9. Clientes con el Resultado de la campaña anterior 'Success'.
10. Clientes sin historial de impagos ('default' = 0).

---

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/tu_usuario/EDA_Banco_Python.git
```

2. Instalar las dependencias necesarias (recomendado usar entorno virtual):

pip install pandas numpy matplotlib seaborn openpyxl

3. Abrir el notebook notebooks/EDA_Banco.ipynb en Jupyter Notebook o JupyterLab para ejecutar y revisar el análisis.

Autor
Nacho Palomino