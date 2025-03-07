# Análisis del Clima en Bilbao: 50 Años de Datos Meteorológicos

## 📊 [Ver Dashboard en Power BI](https://app.powerbi.com/reportEmbed?reportId=313c38e9-2057-4699-bc98-62a095a6f4e4&autoAuth=true&ctid=16a844d4-a6fb-4446-8873-1b1e40876fb5)

## 📝 Descripción del Proyecto
Este proyecto analiza 50 años de datos meteorológicos de Bilbao, explorando tendencias climáticas, patrones estacionales y cambios significativos en temperatura y precipitación. El análisis combina técnicas de web scraping, análisis de datos y visualización para proporcionar insights sobre el cambio climático a nivel local.

## 🎯 Objetivos
- Analizar tendencias históricas de temperatura y precipitación
- Identificar patrones estacionales y cambios climáticos
- Relacionar cambios locales con tendencias globales
- Visualizar datos meteorológicos de manera efectiva

## 🛠️ Metodología

### 1. Recolección de Datos
- Web scraping de datos históricos meteorológicos utilizando Python y BeautifulSoup
- Automatización del proceso de recolección mediante scripts personalizados
- Estructuración de datos en formato CSV para fácil manipulación
- Validación de datos durante la recolección

### 2. Limpieza y Preparación de Datos
- Detección y eliminación de valores duplicados para mantener la integridad de los datos
- Tratamiento de valores nulos mediante imputación con promedio mensual
- Creación de variables temporales (año, mes, estación) para análisis estacional
- Validación de consistencia y formato de datos
- Creación de tablas dimensionales para análisis en Power BI:
  - Tabla de meses con nombres en español
  - Tabla de estaciones del año

### 3. Análisis Exploratorio de Datos (EDA)
#### Análisis de Temperatura
- Análisis de tendencias en temperatura media, máxima y mínima
- Identificación de patrones estacionales mediante visualizaciones
- Detección de anomalías térmicas y eventos extremos
- Análisis de correlación entre variables de temperatura

#### Análisis de Precipitaciones
- Estudio de patrones de precipitación mensual y anual
- Identificación de períodos secos y húmedos
- Análisis de tendencias en intensidad de precipitaciones
- Correlación entre precipitación y temperatura

## 📈 Resultados Principales

### Tendencias de Temperatura
- Se observa una tendencia al aumento de la temperatura media a lo largo de los años
- Las temperaturas máximas muestran incrementos más pronunciados en verano
- Los inviernos presentan una variabilidad significativa en temperaturas mínimas

### Patrones de Precipitación
- Las precipitaciones muestran una distribución estacional clara
- Se identifican períodos de sequía y lluvias intensas
- Existe una correlación negativa entre temperatura y precipitación en verano

### Cambios Estacionales
- Los veranos tienden a ser más cálidos en las últimas décadas
- Los patrones de precipitación muestran cambios en su distribución anual
- Se observa una extensión de las temperaturas veraniegas hacia meses tradicionalmente más frescos

## 🌍 Relación con Tendencias Globales
- [Relacionar hallazgos locales con cambio climático global]
- [Mencionar similitudes con tendencias regionales]
- [Destacar particularidades locales]

## 📊 Visualización de Datos
El dashboard en Power BI incluye:
- Análisis temporal de temperaturas y precipitaciones
- Comparativas por décadas
- Patrones estacionales
- Correlaciones entre variables
- KPIs climáticos clave

<iframe title="Análisis Clima Bilbao - 50 años" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=313c38e9-2057-4699-bc98-62a095a6f4e4&autoAuth=true&ctid=16a844d4-a6fb-4446-8873-1b1e40876fb5" frameborder="0" allowFullScreen="true"></iframe>

## 🔍 Conclusiones
- Los datos muestran una clara tendencia al calentamiento en Bilbao
- Los patrones de precipitación están cambiando, con períodos más intensos
- Los cambios observados son consistentes con las tendencias globales de cambio climático
- Se recomienda continuar el monitoreo para futuras planificaciones urbanas

## 🛠️ Tecnologías Utilizadas
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebooks
- Power BI
- Web Scraping (BeautifulSoup)
- Git/GitHub

## 📚 Estructura del Repositorio
```
├── 01_Data_Collection/
│   └── weather_data.csv
├── 02_Data_Cleaning_Preparation_EDA/
│   └── weather_data_clean.csv
├── notebooks/
│   ├── 01_Web_Scraping.ipynb
│   └── 02_Data_Cleaning_Preparation_EDA.ipynb
├── src/
│   └── climate_scraper.py
└── README.md
```

## 🤝 Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cambios mayores.

## 📄 Licencia
Este proyecto está bajo la licencia MIT.

## ✉️ Contacto
[Tu información de contacto]

---
⭐️ Si este proyecto te resulta útil, ¡no dudes en darle una estrella!