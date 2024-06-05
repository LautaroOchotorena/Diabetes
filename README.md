# Diabetes
Se trata de **predecir** la diabetes en base al nivel de glucosa, insulina, edad, número de embarazos, etc.

Primero consta de un **análisis** del [dataset](https://github.com/LautaroOchotorena/Diabetes/blob/master/diabetes.csv) para el luego armado de los **modelos predictivos**.

## Modelos utilizados:

1. Redes neuronales.

2. Boosting con árboles de decisión.

3. SVM lineal (con polynomial features)

4. SVM con Kernel RBF

5. Regresión Logística.

6. Ensamble (Votting) utilizando el modelo de boosting y regresión logística.

## Resultados

Al tratarse de una enfermedad se priorizó tener una buena recall.

| Modelo       | Precisión | Recall | ROC AUC |
|--------------|--------|-----------|---------|
| Red Neuronal    | 0.68   | 0.78      | 0.88    |
| Boosting     | 0.68   | 0.81      | 0.92    |
| SVM lineal     | 0.69  | 0.75      | 0.88    |
| SVM con RBF     | 0.67   | 0.75      | 0.88    |
| Regresión Logística     | 0.78   | 0.84      | 0.89    |
| Ensamble (Votting)     | 0.72   | 0.84      | 0.92    |

## ¿Cómo ver el proyecto?

Hay **tres maneras**:

1. El archivo [Diabetes](https://github.com/LautaroOchotorena/Diabetes/blob/master/Diabetes.ipynb) contiene la nootebook en donde se puede visualizar el código y los resultados obtenidos.

2. Se puede chequear el [Colab](https://colab.research.google.com/drive/1POTSqMkTs5cnioWX-Asejc1yMX1R39QO?usp=sharing).

3. Descargarse el archivo [Diabetes](https://github.com/LautaroOchotorena/Diabetes/blob/master/Diabetes.ipynb) y ejecturalo en un env con el siguiente código:

En la consola, navega a la carpeta y corra:

    ```bash
    pip install -r requirements.txt
    ```

Esto instalará todas las dependencias necesarias.

Para la visualización de los árboles de decisión requiere la instalación de graphviz.