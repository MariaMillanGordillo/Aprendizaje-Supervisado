# Aprendizaje Supervisado: Regresión y Clasificación: Machine Learning

**Descripción:** Este repositorio contiene una serie de proyectos desarrollados como parte de la asignatura Aprendizaje Supervisado: Regresión y Clasificación:Machine Learning.

**Autores:** Carmen Lozano López, María Millán Gordillo y María Victoria Rodriguez del Corral.

## Contenido

### Proyecto 1: Predicción de Churn de Clientes

*   **Objetivo:** Predecir la probabilidad de que un cliente abandone la empresa (churn).
*   **Descripción:** Este proyecto aborda el problema clásico de la predicción de churn. Se realiza un análisis exploratorio exhaustivo para comprender mejor los datos.
*   **Análisis de Datos:** Se realiza un análisis exploratorio de los datos, mostrando estadísticas clave.
*   **Modelos:** Se han evaluado múltiples modelos de clasificación, probando cada uno con y sin Bagging. Además, se ha utilizado un Voting Classifier que combina varios de estos modelos. Los modelos evaluados incluyen:
    *   Gaussian Naive Bayes
    *   Random Forest Classifier
    *   XGBoost
    *   KNeighbors Classifier
    *   Linear Discriminant Analysis
    *   SVC
    *   Decision Tree Classifier

### Proyecto 2: Clasificación de Imágenes con Redes Neuronales

*   **Objetivo:** Clasificar imágenes del dataset CIFAR-10 utilizando una red neuronal.
*   **Descripción:** Se implementa una red neuronal para clasificar imágenes del dataset CIFAR-10.
*   **Modelos:** Probamos con distintas configuraciones:
    *   Capas Densas
    *   Capas Convolucionales
    *   Capas Convolucionales y MaxPooling
    *   Capas Convolucionales, MaxPooling y DropOut

### Proyecto 3: Clasificación de Texto y Análisis de Sentimientos

*   **Objetivo:** Clasificar las emociones expresadas en tweets.
*   **Descripción:** Se utiliza un dataset de Twitter para la clasificación de emociones mediante modelos de aprendizaje automático y redes neuronales.
*   **Preprocesamiento:** Se aplican técnicas de limpieza y normalización del texto, incluyendo la eliminación de stop words con NLTK, para mejorar la calidad de los datos y el rendimiento del modelo.
*   **Modelos:**
    *   Multinomial Naive Bayes
    *   Linear Discriminant Analysis
    *   Gaussian Naive Bayes
    *   Decision Tree Classifier
    *   Random Forest Classifier
    *   Red Neuronal Simple
    *   Red Neuronal Recurrente
    *   Red Neuronal con LSTM

### Proyecto 4: Regresión para la Predicción de Emisiones de CO2

*   **Objetivo:** Predecir las emisiones de CO2 de vehículos basándose en sus características.
*   **Descripción:** Se realiza un Análisis Exploratorio de Datos (EDA) para comprender la distribución y relaciones entre variables. Además, se prueban distintas estrategias de preprocesamiento, incluyendo la consideración o exclusión de valores atípicos.
*   **Modelos:**
    *   Linear Regression
    *   Decision Tree Regressor
    *   Random Forest Regressor
