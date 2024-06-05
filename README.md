# Diabetes
Se trata de **predecir** la diabetes en base al nivel de glucosa, insulina, edad, número de embarazos, etc.

Primero consta de un **análisis** del [dataset](https://github.com/LautaroOchotorena/Diabetes/blob/master/diabetes.csv) para el luego armado de los **modelos predictivos**.

## Modelos utilizados:

1. Redes neuronales.

2. Boosting con árboles de decisión.

3. SVM lineal (con polynomial features)

4. SVM con Kernel RBF

5. Regresión Logística.

6. Ensamble utilizando el modelo de redes neuronales, SVM y regresión logística.

## Resultados

| Modelo       | Precisión | Recall | ROC AUC |
|--------------|--------|-----------|---------|
| Redes Neuronales    | 0.85   | 0.88      | 0.90    |
| Modelo 2     | 0.80   | 0.85      | 0.87    |
| Modelo 3     | 0.82   | 0.83      | 0.88    |
| Modelo 4     | 0.87   | 0.89      | 0.91    |
| Modelo 5     | 0.83   | 0.84      | 0.86    |

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