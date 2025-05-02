# 📊 Análisis de Soporte al Cliente en Twitter

Proyecto desarrollado como parte de mi portafolio en Ingeniería de Datos. Analiza más de 100,000 mensajes reales en Twitter entre usuarios y cuentas oficiales de soporte de marcas como Apple y Amazon.

## 🎯 Objetivos

- Identificar patrones de comportamiento en atención al cliente.
- Analizar tiempos de respuesta, sentimiento y sesiones de conversación.
- Extraer insights para mejorar la experiencia del usuario y detectar áreas críticas.

## 🧰 Tecnologías utilizadas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- NLTK (VADER)
- WordCloud
- Jupyter Notebook

## 📁 Dataset

[Customer Support on Twitter – Kaggle](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter)  
Se utilizó una muestra de 100,000 registros (`twcs_sample_100k.csv`).

## 📈 Análisis realizado

- Limpieza y transformación de datos (tiempo, autores, fechas).
- Cálculo de tiempo de respuesta y análisis de outliers.
- Clasificación de sentimiento con VADER.
- Visualización: distribución horaria, días, sentimientos, sesiones y nubes de palabras.
- Agrupación por sesiones (ventana de 30 minutos).
- Exportación de resultados clave a CSV.

## 📊 Resultados destacados

- **Media real de respuesta**: ~1.8 horas (sin outliers).
- **Sentimiento general**: Mayoría neutral, con casos críticos bien segmentados.
- **Clientes con más mensajes negativos** identificados.
- **Top sesiones** de conversación analizadas y visualizadas.
- **Exportación de resultados** para dashboards o modelos adicionales.

## 🧠 Posibles extensiones

- Modelado de churn o satisfacción basada en sentimiento y tiempos de respuesta.
- Entrenamiento de bots de atención con base en clasificaciones reales.
- Integración en dashboards interactivos en Power BI o Streamlit.

## 📂 Estructura

```
proyecto-soporte-cliente/
├── Proyecto_1.ipynb
├── Proyecto_1.html
├── resumen_sesiones.csv
├── resumen_sentimiento.csv
├── README.md
```

## 👤 Autor

**Reinaldo Alejo**  
📧 [Tu correo]  
🔗 [Tu LinkedIn]
