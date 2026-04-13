## Análisis de Datos - Estaciones de servicio

---

El objetivo de este proyecto es realizar un análisis exploratorio y preprocesamiento de un conjunto de datos real sobre estaciones de servicio.

Información obtenida desde archivo CSV, aplicando técnicas de limpieza, transformación y análisis de datos para preparar el dataset para futuros modelos de Machine Learning.


---
### Objetivos

- Analizar la estructura del dataset
- Detectar y tratar valores faltantes
- Transformar variables (tipos de datos)
- Visualizar la distribución de los datos
- Estudiar la correlación entre variables
- Aplicar técnicas de preprocesamiento
- Generar análisis automático con AutoViz

---

### ¿Qué problema se resuelve?

El dataset original presenta problemas típicos de datos reales:

- Valores numéricos almacenados como texto
- Presencia de valores nulos
- Variables heterogéneas
- Falta de normalización

Este proyecto deja los datos listos para su uso en modelos de aprendizaje automático.

---

### Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- AutoViz
- Jupyter Notebook

---

### Flujo de trabajo
1. Carga y exploración inicial del dataset
2. Limpieza de datos (tratamiento de valores faltantes, conversión de tipos)
3. Análisis exploratorio (visualización, estadísticas descriptivas)
4. Preprocesamiento (normalización, codificación)
5. Análisis automático con AutoViz
6. Conclusiones y recomendaciones para futuros modelos de Machine Learning
7. Documentación y presentación de resultados

---
### Resultados principales
- Los precios de gasolina y gasóleo presentan una distribución similar
- Existe una fuerte correlación positiva (~0.93) entre ambas variables
- La gasolina presenta precios generalmente superiores al gasóleo

---
### Aplicación de Machine Learning
Este dataset puede utilizarse para construir modelos de regresión que permitan predecir el precio del carburante en función de variables como ubicación, tipo de estación o características del servicio.

---
### Estructura del proyecto

```
PyDataProject/
├── petrolStationsApp.ipynb                      # Jupyter Notebook para análisis y preprocesamiento
├── gii32_act1_precios_carburantes_24.csv        # Dataset con precios de carburantes
└── README.md                                    # Este archivo 😄
```

---

### Autora

 👨‍💻     [Anabel Díaz](https://github.com/rubiwan)

---

### Aprendizajes clave
- Trabajo con datasets reales y su limpieza
- Importancia del preprocesamiento en ML
- Análisis exploratorio de datos (EDA)
- Uso de herramientas automáticas como AutoViz