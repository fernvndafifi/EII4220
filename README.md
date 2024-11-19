# PROYECTO FINAL (GRUPO 31) - EII4220: ANÁLISIS DESCRIPTIVO Y PREDICTIVO SOBRE LOS TIROTEOS FATALES POR POLICÍAS EN ESTADOS UNIDOS

Este repositorio contiene un análisis de los tiroteos fatales ocurridos en Estados Unidos, enfocado en los incidentes involucrando a la policía. El proyecto está compuesto por diferentes archivos que permiten analizar, visualizar y explorar los datos relacionados con estos eventos, con el fin de identificar patrones, tendencias y posibles áreas de mejora en las políticas de seguridad pública.

### Archivos del Proyecto

#### 1. **Análisis de Tiroteos Fatales en EE.UU..pbix**
   - Este archivo es un informe interactivo creado en Power BI, que proporciona visualizaciones detalladas de los datos de tiroteos fatales. El informe incluye gráficos, mapas y tablas para facilitar el análisis de las tendencias de estos incidentes a lo largo del tiempo y por diversas variables.

#### 2. **EII4220_Proyecto.ipynb**
   - Este archivo es un cuaderno de Jupyter Notebook que contiene el código Python utilizado para procesar y analizar los datos de tiroteos fatales. Incluye limpieza de datos, análisis estadístico y generación de visualizaciones utilizando librerías como `pandas`, `matplotlib` y `seaborn`.

#### 3. **cities-of-USA-info.xlsx**
   - Este archivo de Excel contiene información geográfica y demográfica de las ciudades de EE.UU. que puede ser utilizada para enriquecer el análisis de los tiroteos fatales. La base de datos incluye detalles como población, estado, y otras características relevantes de las ciudades.

#### 4. **fatal-police-shootings-agencies.xlsx**
   - Este archivo de Excel contiene información sobre las agencias de policía involucradas en los tiroteos fatales. Incluye detalles como el nombre de la agencia, su ubicación y otros factores relacionados con las fuerzas de seguridad.

#### 5. **fatal-police-shootings-data.xlsx**
   - Este archivo de Excel es el conjunto principal de datos que contiene los incidentes de tiroteos fatales ocurridos en EE.UU., detallando información sobre cada evento, como la fecha, la ubicación, la raza de las víctimas, las circunstancias del tiroteo y las agencias de policía involucradas.

### Requisitos

Para ejecutar el análisis y el código, asegúrate de tener los siguientes requisitos:

- **Python 3.x** (se recomienda la versión 3.7 o superior).
- Librerías de Python:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  
Instalar las dependencias:
```bash
pip install pandas numpy matplotlib seaborn
```

- **Power BI Desktop** (para abrir y explorar el archivo `.pbix`).

### Instrucciones de Uso
1. Abrir el Informe Interactivo en Power BI
Para explorar las visualizaciones detalladas de los tiroteos fatales, abre el archivo Análisis de Tiroteos Fatales en EE.UU..pbix en Power BI Desktop. El informe interactivo incluye gráficos, mapas y tablas para facilitar el análisis de las tendencias a través del tiempo y por diferentes variables.

2. Ejecutar el Código en Jupyter Notebook
Abre el archivo EII4220_Proyecto.ipynb en un entorno de Jupyter (como Google Colab) para ejecutar el análisis en Python. El cuaderno contiene los pasos necesarios para:

    - Cargar los datos,
    - Limpiar los datos,
    - Realizar análisis descriptivo y predictivo, y
    - Generar visualizaciones.

3. Para usar Google Colab, simplemente sube el archivo al entorno y ejecuta las celdas correspondientes.

4. Explorar los Datos en Excel
Los archivos .xlsx se pueden abrir con Microsoft Excel o cualquier otra aplicación compatible. Estos archivos contienen información relevante sobre las ciudades de EE.UU., los departamentos de policía y los detalles de los incidentes de tiroteos fatales.

### Clonación del Repositorio
Si deseas obtener una copia local del repositorio, puedes clonarlo usando el siguiente comando en tu terminal:

   ```bash
   git clone https://github.com/fernvndafifi/EII4220.git
