# A2.3 — Comparación de modelos de clasificación con Iris

## Descripción

En esta actividad se utiliza la base de datos Iris para clasificar especies de flores a partir de las medidas de sus sépalos y pétalos.

Se entrenan y comparan cuatro modelos: Random Forest, Boosting, Support Vector Machine (SVM) y una red neuronal. El análisis incluye la evaluación de su desempeño y una reflexión sobre su complejidad, interpretabilidad y posibles riesgos de sobreajuste.

## Archivos

- Notebook `.ipynb`: código, análisis, entrenamiento y evaluación de los modelos.
- Archivo `.html`: versión del trabajo para consultar en el navegador.
- `iris.csv`: base de datos necesaria para reproducir el análisis.

## Evaluación

Los modelos se comparan mediante métricas de clasificación, matrices de confusión y curvas ROC. Para la red neuronal también se revisan las gráficas de exactitud y pérdida durante el entrenamiento.

## Cómo reproducir los resultados

1. Descarga el notebook y `iris.csv`.
2. Guarda ambos archivos en la misma carpeta.
3. Abre el notebook en Jupyter Notebook, JupyterLab o VS Code.
4. Instala las bibliotecas importadas al inicio del notebook. Para ejecutar la red neuronal también necesitas TensorFlow.
5. Verifica que la ruta de lectura corresponda a la ubicación de `iris.csv`.
6. Ejecuta las celdas en orden, desde la primera hasta la última.

Si utilizas Google Colab, sube también `iris.csv` y ajusta su ruta de lectura.

Para consultar el trabajo sin ejecutar el código, descarga el archivo `.html` y ábrelo en tu navegador.
