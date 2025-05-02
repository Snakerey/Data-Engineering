# Proyecto: Análisis de Soporte al Cliente en Twitter

Este proyecto forma parte de mi portafolio en Ingeniería de Datos. Analiza 100,000 mensajes entre clientes y agentes de marcas como Apple, Amazon y Uber en Twitter.

El objetivo es identificar patrones clave de interacción, tiempo de respuesta y sentimiento con un enfoque práctico y visual.

---

## 🧩 Estructura del Proyecto

```
soporte-twitter/
├── Proyecto_1 v1.1.ipynb         # Notebook principal con análisis completo
├── Proyecto_1 v1.1.html          # Versión exportada en HTML para visualización web
├── resumen_sesiones.csv          # Métricas por sesión de conversación
├── resumen_sentimiento.csv       # Datos con análisis de sentimiento por tweet
├── twcs_sample_100k.csv          # Dataset base (100,000 tweets de soporte)
└── README.md                     # Descripción del proyecto
```

---

## 🚀 Técnicas aplicadas

- Limpieza y transformación de datos con pandas
- Cálculo de tiempo de respuesta entre clientes y agentes
- Análisis de sentimiento con VADER (NLTK)
- Visualización de actividad por hora, día y sesiones
- Identificación de outliers y patrones de respuesta lenta

---

## 📌 Resultados clave

- +68% de respuestas en menos de 1 hora
- Mediana de respuesta: 16 minutos
- Se identifican outliers de +700 días
- Visualización de sesiones más largas y clientes críticos

---

## 📁 Dataset original

- Fuente: [Customer Support on Twitter - Kaggle](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter)
- Muestra utilizada: `twcs_sample_100k.csv`

---

Este proyecto puede integrarse en sistemas de priorización de tickets, automatización de soporte o análisis de churn de clientes.