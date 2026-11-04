# Clasificación de la prioridad de accidentes de tránsito en la Ciudad de México

## Descripción

Este proyecto compara modelos de aprendizaje automático para clasificar accidentes de tránsito de la Ciudad de México según su prioridad: BAJA, MEDIA o ALTA.

Se analizan 30,655 registros correspondientes a 2024. Para realizar la clasificación se consideran el tipo de evento, el tipo de intersección, la presencia de semáforo y el día de la semana.

## Objetivo

Evaluar qué tan bien distintos modelos identifican las tres categorías de prioridad, considerando especialmente las dificultades para reconocer las clases menos frecuentes.

## Modelos utilizados

- Regresión logística.
- Análisis discriminante lineal (LDA).
- Árbol de decisión con poda.
- Random Forest.
- Support Vector Machine (SVM).
- Red neuronal.

## Archivos

- Notebook `.ipynb`: preparación de datos, entrenamiento, evaluación y comparación de modelos.
- Reporte `.pdf`: explicación del análisis, resultados y conclusiones.
- `basededatosp2.csv`: base de datos utilizada en el proyecto.

## Evaluación

Los datos se dividen en conjuntos de entrenamiento y prueba. Se utilizan validación cruzada, matrices de confusión y métricas como exactitud, precisión, recall, F1 y ROC-AUC para comparar los modelos.

El análisis considera el desbalance entre las categorías, ya que una exactitud alta puede coexistir con una baja detección de los accidentes de prioridad MEDIA y ALTA.

## Cómo reproducir los resultados

1. Descarga el notebook y `basededatosp2.csv`.
2. Guarda ambos archivos en la misma carpeta.
3. Abre el notebook en Jupyter Notebook, JupyterLab o VS Code.
4. Instala las bibliotecas importadas en el código. La red neuronal requiere TensorFlow.
5. Verifica que la ruta de lectura del CSV corresponda a su ubicación.
6. Ejecuta las celdas en orden, desde la primera hasta la última.

También puedes utilizar Google Colab, cargando la base de datos y ajustando su ruta de lectura.

## Consulta del trabajo

Abre el reporte PDF para consultar el análisis y las conclusiones sin ejecutar el código.

## Alcance

Los resultados permiten explorar patrones en los registros analizados. El desempeño debe interpretarse considerando el desbalance de clases y la información disponible; el modelo no ha sido validado para asignar prioridades en situaciones reales de emergencia.
