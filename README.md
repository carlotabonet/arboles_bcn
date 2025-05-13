# Árboles de Barcelona

## Descripción
Análisis del arbolado urbano de Barcelona con datos abiertos del Ayuntamiento:
- https://opendata-ajuntament.barcelona.cat/data/ca/dataset/arbrat-zona
- https://opendata-ajuntament.barcelona.cat/data/ca/dataset/arbrat-viari
- https://opendata-ajuntament.barcelona.cat/data/ca/dataset/arbrat-parcs

## Estructura
- **notebooks/**: Código Python para procesamiento
- **data/**: 
 - `/raw`: Datos originales (arbrat_2025.csv, arbrat_parcs.csv, arbrat_zones.csv)
 - `/clean`: Datos procesados (arbres_clean.csv)
- **output/**: Visualizaciones generadas

## Metodología
1. Unificación de datasets
2. Limpieza de datos
3. Visualizaciones exploratorias
4. Preparación para Power BI

## Principales hallazgos
- Barcelona cuenta con más de 224,000 árboles
- El plátano es la especie predominante (19.9%)
- Los distritos con más árboles son Sant Martí y Sants-Montjuïc
- Solo el 15.4% tienen fecha de plantación registrada

## Tecnologías
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Power BI

