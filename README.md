# Modelación del Aprendizaje con Inteligencia Artificial
---

Este repositorio contiene distintos proyectos realizados en la clase **Modelación del Aprendizaje con Inteligencia Artificial**, cuyo objetivo es comprender a mayor profundidad el comportamiento y funcionamiento de algoritmos de *Machine Learning* para aprendizaje supervisado y no supervisado. Entre estos algoritmos destacan la regresión lineal, regresión logísitca y K-Means.  

## 📁 Estructura del repositorio

```
Proyecto-01/
│   Proyecto01_Notebook_A01286569_A0128754.ipynb
│   Proyecto01_ReporteTecnico_A01286569_A01286754.pdf

Proyecto-02/
│   Proyecto02_KMeans_PCA-A01286569_A01286440_A01286754.ipynb
│   Proyecto02_KMeans_PCA-A01286569_A01286440_A01286754.pdf

TC2034-Actividad01-A01286569/
│   regresionlineal.ipynb
│   regresionlogistica.ipynb

TC2034-Actividad03-A01286569/
│   TC2034-Actividad03-A01286569.ipynb

.gitignore
README.md
```

Cada carpeta contiene materiales específicos dependiendo del tipo de entrega:

- **Proyectos (Proyecto-01 y Proyecto-02):** incluyen tanto el *notebook* de desarrollo como su respectivo **reporte técnico en PDF**, donde se documenta la metodología, resultados y conclusiones.
- **Actividades (TC2034-ActividadXX):** contienen únicamente implementaciones en notebook enfocadas en la comprensión práctica de los algoritmos.

---

## 📊 Descripción de contenido

### 🔹 Actividad 01 — Regresión lineal y logística

En esta actividad se implementan modelos de aprendizaje supervisado:

- **Regresión lineal:** utilizando el dataset de *housing prices* para predecir precios de viviendas.
- **Regresión logística:** aplicada al dataset de *breast cancer* para clasificar tumores como benignos o malignos.

El modelo de clasificación logra un desempeño sólido, reflejado en la matriz de confusión:

```
               precision    recall  f1-score   support

tumor benigno       0.98      0.99      0.98        89
tumor maligno       0.98      0.96      0.97        54

     accuracy                           0.98       143
    macro avg       0.98      0.98      0.98       143
 weighted avg       0.98      0.98      0.98       143
```

---

### 🔹 Actividad 03 — K-Means clustering

Se implementa el algoritmo de **K-Means** en dos etapas:

1. Uso de datos sintéticos generados con `make_blobs` para entender el comportamiento del algoritmo.
2. Aplicación a un dataset real de *teen mental health*, con el objetivo de agrupar usuarios en función de sus hábitos sociales y uso de redes sociales.

---

### 🔹 Proyecto 01 — Regresión logística (implementación manual)

Se desarrolla una implementación manual de regresión logística y se evalúa en:

- Dataset de *housing prices* (adaptado para clasificación).
- Dataset de **Telco Customer Churn**, para predecir si un cliente abandona o permanece en el servicio.

---

### 🔹 Proyecto 02 — K-Means + PCA (implementación manual)

Se implementa el algoritmo de **K-Means desde cero** y se combina con **PCA** para reducción de dimensionalidad.

El modelo se aplica a un dataset de *customer segmentation*, considerando variables como:

- Edad
- Ingreso
- Frecuencia de compra
- Uso de cupones
- Cantidad de productos adquiridos
- Recencia de compra

El objetivo es identificar grupos de clientes con comportamientos similares.

---

## 📈 Enfoque de aprendizaje

En ambos proyectos se realiza una comparación entre:

- Implementaciones manuales
- Modelos de la librería `scikit-learn`

Esto permite comprender no solo el uso de los algoritmos, sino también su funcionamiento interno y diferencias prácticas.

Además, se exploran distintas métricas y técnicas de evaluación, como:

- Matriz de confusión (precision, recall, f1-score)
- Método del codo
- Silhouette score
- Adjusted Rand Index (ARI)

Estas herramientas permiten analizar la calidad de los modelos y tomar decisiones informadas sobre su desempeño.

---

Este repositorio refleja un enfoque práctico y teórico hacia el aprendizaje automático, priorizando la comprensión profunda de los algoritmos más allá de su simple implementación.