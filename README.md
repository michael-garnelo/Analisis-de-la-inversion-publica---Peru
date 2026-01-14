#  Análisis y Visualización de la Inversión Pública en el Perú

## Descripción del proyecto
Este proyecto tiene como objetivo analizar los datos de los proyectos de
inversión pública en el Perú, identificando patrones relevantes según
nivel de gobierno, función y distribución territorial. El análisis se
enfoca en transformar datos abiertos en información comprensible que
pueda apoyar iniciativas de visualización y análisis de datos sociales.

##  Fuente de datos
Los datos utilizados provienen del portal de Datos Abiertos del
Ministerio de Economía y Finanzas (MEF), específicamente del conjunto
**“Seguimiento de Proyectos de Inversión”**.  
Se trabajó principalmente con el dataset correspondiente al año 2024,
por ser el último disponible de forma completa.

🔗 https://datosabiertos.mef.gob.pe/dataset/seguimiento-de-proyectos-de-inversion

## Herramientas utilizadas
- **Python** (pandas, plotly) para exploración y análisis inicial
- **SQL Server** para el modelado y organización de los datos
- **Power BI** para la visualización y construcción de dashboards
- **Google Colab** como entorno de trabajo

##  Metodología
1. Exploración y limpieza inicial de los datos utilizando Python.
2. Selección de variables relevantes y definición del nivel de análisis.
3. Modelado de los datos bajo un esquema de tipo estrella (Kimball).
4. Desarrollo de visualizaciones y dashboards en Power BI para comunicar
   los resultados de forma clara.


##  Visualización de resultados
Se desarrollaron dashboards en Power BI que permiten analizar la
distribución de la inversión pública por función, nivel de gobierno y
territorio, facilitando la interpretación de los datos para públicos
tanto técnicos como no técnicos.

*(Ver carpeta `images/powerbi/`)*

##  Modelado de datos
El proyecto incluye un modelo de datos tipo estrella (Kimball), el cual
sirvió como base para la construcción de los dashboards y el análisis en
Power BI.

*(Ver carpeta `images/modelado/`)*

##  Conclusiones
El análisis permitió identificar patrones relevantes en la asignación de
la inversión pública, destacando la concentración de proyectos en
determinadas funciones y regiones. Este enfoque evidencia el potencial
de los datos abiertos para apoyar proyectos de transparencia,
visualización y análisis social.


## 👤 Autor
Michael Garnelo
