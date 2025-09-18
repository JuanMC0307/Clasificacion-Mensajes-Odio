# Crear el contenido del README.md en formato markdown para el proyecto de clasificación de mensajes de odio

readme_content3 = """# 💬 Clasificación de Mensajes de Odio  

Este proyecto corresponde a una actividad grupal del máster en Inteligencia Artificial y tiene como objetivo desarrollar un modelo de **clasificación de mensajes de odio**, aplicando técnicas de aprendizaje automático sobre un dataset de comentarios etiquetados.  

📚 **Tabla de Contenidos**  
- 🧠 ¿Qué incluye este proyecto?  
- 🔍 Análisis realizado  
- 💻 Tecnologías y librerías utilizadas  
- 🚀 Resultados  
- ⚙️ Cómo ejecutar este proyecto  

---

## 🧠 ¿Qué incluye este proyecto?  
✅ Carga y exploración del dataset `out.csv`  
✅ Análisis exploratorio de datos (**EDA**) con visualizaciones  
✅ Distribución de variables de texto y etiquetas  
✅ Cálculo de correlaciones entre variables  
✅ Preparación de la variable objetivo `label`  
✅ Entrenamiento de modelos de clasificación supervisada  
✅ Evaluación de métricas de desempeño  

---

## 🔍 Análisis realizado  

1. **EDA (Exploratory Data Analysis)**  
   - Se analizaron distribuciones de variables textuales (conteo de palabras positivas/negativas).  
   - Se evaluó la correlación entre variables numéricas.  
   - Se verificó que la variable objetivo **label** está bien balanceada.  

2. **Definición de etiquetas**  
   - `0`: Ira  
   - `1`: Alegría  
   - `2`: Tristeza  
   - `3`: Miedo  
   - `4`: Sorpresa  
   - `5`: Disgusto  
   - `6`: Neutral  

3. **Modelado de clasificación**  
   - Entrenamiento de clasificadores supervisados sobre las variables.  
   - Evaluación de desempeño con métricas estándar.  

---

## 💻 Tecnologías y librerías utilizadas  

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🚀 Resultados  

📊 El proyecto permitió:  
- Comprender la distribución de variables textuales relacionadas con mensajes de odio.  
- Definir un conjunto de clases emocionales como objetivo de la clasificación.  
- Probar clasificadores y evaluar su rendimiento en términos de precisión y equilibrio entre clases.  

---

## ⚙️ Cómo ejecutar este proyecto  

1. Clona este repositorio en tu máquina:  
   ```bash
   git clone https://github.com/usuario/Clasificacion-Mensajes-Odio.git
