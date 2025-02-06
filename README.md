# 🪙 **CLASIFICADOR DE MONEDAS ANTIGUAS** 🏛️

¡Bienvenido al repositorio del **Clasificador de Monedas Antiguas**! Este proyecto tiene como objetivo clasificar monedas históricas según su período temporal utilizando técnicas de Machine Learning. A continuación, te explicamos cómo está estructurado y qué encontrarás en cada sección.

---

## 📚 **Índice**

1. [Fuente de los Datos](#-fuente-de-los-datos)
2. [Objetivo del Proyecto](#-objetivo-del-proyecto)
3. [Importancia de las Columnas](#-importancia-de-las-columnas)
4. [Preprocesamiento de Datos](#-preprocesamiento-de-datos)
5. [Selección del Modelo](#-selección-del-modelo)
6. [Entrenamiento y Evaluación](#-entrenamiento-y-evaluación)
7. [Mejora e Implementación](#-mejora-e-implementación)
8. [Estado del Proyecto](#-estado-del-proyecto)

---

## 📂 **Fuente de los Datos**

Los datos utilizados en este proyecto provienen del conjunto de datos **'Coin Images from the Portable Antiquities Scheme'**, disponible en [Kaggle](https://www.kaggle.com/segood). Este dataset fue compartido por [Sarah Good](https://www.kaggle.com/segood) y contiene imágenes e información detallada de monedas antiguas.

---

## 🎯 **Objetivo del Proyecto**

El objetivo principal es clasificar monedas antiguas en **7 períodos históricos** (según los establecidos ya en los datos, se podría ajustar según la datación que se tiene de los materiales):

- **Edad de Hierro** (Iron Age)
- **Griego y Romana Provincial** (Greek and Roman Provincial)
- **Romana** (Roman)
- **Bizantina** (Byzantine)
- **Alta Edad Media** (Early Medieval)
- **Medieval** (Medieval)
- **PosMedieval** (Post Medieval)

Utilizaremos características físicas, de diseño y metadatos para entrenar un modelo de Machine Learning que pueda predecir el período histórico de una moneda.

---

## 🔍 **Importancia de las Columnas**

- **Target (Período Histórico):** `broadperiod`
- **Características Físicas:** `length`, `width`, `thickness`, `diameter`, `weight`
- **Características de Diseño:** `observeDescription`, `reserveDescription`, `observeLegend`, `reverseLegend`, `mintmark`
- **Información Adicional:** `denominationName`, `rulerName`, `mintName`

---

## 🛠️ **Preprocesamiento de Datos**

Antes de entrenar el modelo, los datos deben ser preparados y limpiados. Aquí están los pasos clave:

1. **Limpieza de Datos:** Eliminar valores nulos, duplicados y corregir errores.
2. **Codificación de Variables Categóricas:** Transformar variables categóricas en formatos numéricos.
3. **Normalización/Estandarización:** Asegurar que todas las características estén en la misma escala.

---

## 🤖 **Selección del Modelo**

Se probarán varios algoritmos de clasificación (como Random Forest, SVM, Redes Neuronales, etc.) para determinar cuál ofrece el mejor rendimiento en la tarea de clasificación.

---

## 🏋️ **Entrenamiento y Evaluación**

Una vez seleccionado el modelo, se procederá a su entrenamiento. Luego, se evaluará su rendimiento utilizando métricas como:

- **Precisión**
- **Recall**
- **F1-Score**
- **Matriz de Confusión**

---

## 🚀 **Mejora e Implementación**

Después de la evaluación, se explorarán técnicas para mejorar el modelo, como:

- Ajuste de hiperparámetros.
- Selección de características.
- Uso de técnicas avanzadas como Grid Search o Cross-Validation.

Finalmente, el modelo se implementará para clasificar nuevas monedas 🪙📜.

---

## 🚧 **Estado del Proyecto**

¡Este proyecto está en proceso! 🛠️ Aún estoy trabajando en la implementación y mejora del modelo. 

---