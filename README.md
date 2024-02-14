<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 


# Análisis de Siniestros Viales en Buenos Aires (2016-2021)

## Introducción

Este proyecto se centra en el análisis de los siniestros viales en la Ciudad Autónoma de Buenos Aires, con el objetivo de comprender mejor las dinámicas detrás de estos incidentes que afectan significativamente la seguridad y el bienestar de los ciudadanos. A través de un exhaustivo análisis de datos, buscamos identificar patrones, tendencias y factores de riesgo asociados a los siniestros viales para informar y guiar la implementación de políticas públicas y estrategias de prevención eficaces.

## Objetivo y Alcance

El proyecto tiene como objetivo principal analizar los datos de siniestros viales ocurridos en Buenos Aires entre 2016 y 2021, con el fin de:

- Identificar las tendencias temporales y geográficas de los siniestros.
- Caracterizar las víctimas y participantes en términos demográficos y roles en los incidentes.
- Evaluar los factores de riesgo y las condiciones bajo las cuales ocurren los siniestros.
- Proponer recomendaciones basadas en datos para la reducción de siniestros viales.

## Estructura del Repositorio

El repositorio está organizado de la siguiente manera para facilitar el acceso y la comprensión de los análisis realizados:

```
├── EDA.ipynb                # Jupyter Notebook con el Análisis Exploratorio de Datos
├── ETL.ipynb                # Jupyter Notebook con el proceso de Extracción, Transformación y Carga
├── README.md                # Documentación del proyecto
│
│
├── dashboard                # Dashboard de Power BI
│  └── dashboard.pbix
│  
│   
│
└── data                     # Datos utilizados y generados en el proyecto
    ├── homicidios.xlsx      # Dataset original
    └── homicidios_clean.xlsx  # Dataset limpio y procesado
```

## Tech Stack

El proyecto se desarrolló utilizando las siguientes tecnologías y herramientas:

- **Python**: Para el procesamiento y análisis de datos, con librerías como `pandas` para la manipulación de datos y `matplotlib`/`seaborn` para la visualización.
- **Jupyter Notebook**: Como entorno de desarrollo para el análisis exploratorio de datos (EDA) y el proceso ETL.
- **Power BI**: Para la creación de dashboards interactivos que permiten visualizar los hallazgos y tendencias de los datos analizados.
- **Excel**: Para la gestión inicial de los datasets y como formato de archivo para los datos procesados.

## Flujo de Trabajo

1. **Extracción, Transformación y Carga (ETL)**: Procesamiento inicial de los datos para limpiar, normalizar y preparar para el análisis.
2. **Análisis Exploratorio de Datos (EDA)**: Investigación profunda de los datos para identificar patrones, tendencias y anomalías.
3. **Visualización y Dashboards**: Desarrollo de visualizaciones de datos y un dashboard interactivo en Power BI para comunicar los hallazgos de manera efectiva.
4. **Análisis y Recomendaciones**: Basado en los hallazgos del EDA y las visualizaciones, se formulan recomendaciones dirigidas a mejorar la seguridad vial en Buenos Aires.

Incorporando los hallazgos del Análisis Exploratorio de Datos (EDA) en la sección del README, el reporte final se estructura de la siguiente manera:



## Hallazgos Principales del Análisis Exploratorio de Datos

### Análisis Descriptivo General
Nuestro análisis inicial abarcó 687 registros únicos, proporcionando una visión profunda de la problemática de los siniestros viales en Buenos Aires. Este conjunto de datos reveló:

- Una predominancia de víctimas masculinas con una edad media de aproximadamente 39.7 años.
- Una distribución geográfica variada que subraya la existencia de áreas con una alta concentración de siniestros.
- Una diversidad en los tipos de participantes involucrados, incluyendo peatones, pasajeros, y diversos tipos de vehículos.

### Evolución Temporal y Patrones
El análisis temporal destacó:

- Un pico de siniestros y víctimas en 2018, seguido por una notable disminución en 2020, posiblemente influenciada por la pandemia de COVID-19.
- Patrones estacionales y diarios, con una concentración de siniestros en los meses de verano y diciembre, y un aumento durante las primeras horas de la mañana.

### Distribución Geográfica y Análisis Espacial
La visualización geoespacial permitió identificar:

- Zonas de riesgo dentro de la ciudad, especialmente en ciertas comunas y avenidas principales.
- La importancia de focalizar intervenciones de infraestructura y campañas de seguridad vial en áreas con alta incidencia de siniestros.

### Caracterización de Víctimas y Participantes
Se observó:

- Una alta incidencia de siniestros viales entre motociclistas y peatones, destacando la necesidad de estrategias de prevención dirigidas a estos grupos vulnerables.
- La necesidad de revisar y mejorar la infraestructura vial y promover campañas de concienciación para la seguridad de todos los usuarios de la vía.

### Naturaleza y Factores de Riesgo de los Siniestros
El análisis iluminó:

- La relevancia del tipo de calle en la incidencia de siniestros, siendo las avenidas las más afectadas.
- La relación entre la hora del día y la ocurrencia de siniestros, señalando un riesgo aumentado en las primeras horas de la mañana.

## Conclusiones y Recomendaciones

A partir de este análisis, recomendamos:

1. **Implementación de Políticas de Seguridad Vial Dinámicas**: Adaptación de estrategias a las tendencias temporales y cambios en el comportamiento social y la movilidad.
2. **Fortalecimiento de la Infraestructura en Puntos Críticos**: Mejora en la señalización, iluminación y diseño de vías en zonas de alta incidencia.
3. **Promoción de la Educación y Concienciación**: Incremento en las campañas de seguridad vial dirigidas a conductores jóvenes, motociclistas y peatones.
4. **Fomento de la Investigación y el Análisis de Datos Continuo**: Uso de la recolección y análisis de datos en tiempo real para ajustar políticas públicas según sea necesario.

Este estudio subraya la importancia de una colaboración intersectorial para enfrentar la problemática de los siniestros viales, con un enfoque en salvar vidas y crear un entorno urbano más seguro para todos.



<hr>  

<div align="center">
    <img src="./img/hero.jpg" alt="hero" style="width: 200px; height: auto; border-radius: 50%;">
    <h3>Andres Castaño</h3>
    <p>Data Scientist Associate | Geological Engineer</p>
    <a href="https://github.com/FeRsOmBrA" target="_blank">
        <img alt="GitHub" src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github" />
    </a>
    <a href="https://www.linkedin.com/in/ferney-castano/" target="_blank">
        <img alt="LinkedIn" src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin" />
    </a>
</div>
