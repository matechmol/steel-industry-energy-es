# ⚙️ Consumo de Energía en la Industria del Acero

Este proyecto analiza datos reales del consumo energético en la industria del acero utilizando técnicas de análisis de datos y modelos de regresión. El objetivo principal es comprender los factores que afectan el consumo de energía y construir un modelo predictivo.

## 📊 Descripción del Proyecto

El notebook realiza un análisis exploratorio de datos, limpieza y transformación de variables, y entrenamiento de modelos de regresión para predecir el consumo energético. Se aplican métricas como el **RMSE** y el **R²** para evaluar el rendimiento del modelo.

## 🧰 Tecnologías y Librerías Utilizadas

- Python 3.x
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn
- Statsmodels

## 📁 Estructura del Proyecto

- `steel_industry_energy_es.ipynb`: Notebook principal con todo el análisis.
- `steel_industry_data.csv`: Dataset con registros de consumo energético, temperatura, humedad, etc.

## 🧪 Pasos del Análisis

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

El modelo proporciona una estimación razonable del consumo de energía en base a variables como temperatura ambiente, hora del día, y condiciones operativas.

## 🚀 Cómo usar este repositorio

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu_usuario/consumo-energia-acero.git
   cd consumo-energia-acero
   ```

2. Instala las dependencias (usando `requirements.txt` si lo generas).

3. Ejecuta el notebook:

   Puedes abrir `steel_industry_energy_es.ipynb` en Jupyter Notebook o VSCode.

## 📌 Notas

- Asegúrate de tener el archivo `steel_industry_data.csv` en el mismo directorio que el notebook.
- Puedes adaptar el modelo con algoritmos más complejos como Random Forest o XGBoost para mejorar la precisión.

## 📃 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.