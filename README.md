# Consumo de Energía en la Industria del Acero

Este proyecto analiza datos reales del consumo energético en la industria del acero utilizando técnicas de análisis de datos y un modelo de regresión. El objetivo principal es comprender los factores que afectan el consumo de energía y construir un modelo predictivo.

## Descripción del Proyecto

El notebook realiza un análisis exploratorio de datos, limpieza y transformación de variables, y entrenamiento de un modelo de regresión para predecir el consumo energético. Se aplican métricas como el **RMSE** y el **R²** para evaluar el rendimiento del modelo.

## Tecnologías y Librerías Utilizadas

- Python 3.x
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn
- Statsmodels

## Estructura del Proyecto

- `steel_industry_energy_es.ipynb`: Notebook principal con todo el análisis.
- `steel_industry_data.csv`: Dataset con registros de consumo energético, fechas, factores de potencia reactiva, etc.

## Pasos del Análisis

1. **Carga de datos**  
   Lectura del archivo `.csv` y revisión de calidad de datos.

2. **Limpieza y transformación**  
   - Conversión de fechas
   - Ingeniería de variables (mes, hora, etc.)
   - Eliminación de columnas redundantes

3. **Visualización de datos**  
   - Análisis de correlaciones
   - Tendencias de consumo por hora y condiciones climáticas

4. **Modelado predictivo**  
   - Regresión lineal para predecir consumo energético
   - Evaluación del modelo con R² y RMSE

## 📈 Resultados

El modelo proporciona una estimación razonable del consumo de energía en base a variables como fecha, factores de potencia, y condiciones operativas.

## Autor

Mateo Chavez
