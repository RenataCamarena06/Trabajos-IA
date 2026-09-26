# Proyecto — Consumo excesivo de alcohol en México

## Descripción

Este proyecto analiza la relación entre el consumo excesivo de alcohol y cuatro características de las entidades federativas de México: prevalencia de fumadores, estructura de edad, sobrepeso u obesidad y prevalencia de enfermedades.

Se exploran los datos de los 32 estados, se seleccionan variables explicativas y se comparan un modelo de regresión lineal y uno polinomial de grado 2. El análisis busca identificar asociaciones y evaluar qué modelo explica mejor las diferencias entre estados; no pretende establecer relaciones de causa y efecto.

## Archivos

- `P P1.625784.ipynb`: notebook con la exploración, los modelos, la evaluación y las conclusiones.
- `P P1.625784.html`: versión del trabajo para consultar en un navegador.
- `basededatosfinal.csv`: base de datos utilizada. Contiene un registro por entidad federativa y las variables analizadas.

## Cómo reproducir los resultados

1. Descarga los tres archivos de esta carpeta.
2. Abre `P P1.625784.ipynb` en VS Code o Jupyter.
3. Mantén `basededatosfinal.csv` en la misma carpeta que el notebook.
4. Ejecuta todas las celdas en orden, desde la primera hasta la última.

El notebook carga los datos con `pd.read_csv("basededatosfinal.csv")`. Para consultar el trabajo sin ejecutar el código, abre `P P1.625784.html` en un navegador.

## Datos y fuentes

La base de datos integra información sobre salud, hábitos y población por entidad federativa. El reporte documenta fuentes como ENSANUT, INEGI y el Anuario de Morbilidad de la Secretaría de Salud.

## Resultado general

La selección de características conservó la prevalencia de fumadores como variable explicativa. Tras comparar ambos modelos, el proyecto eligió la regresión lineal de grado 1 por su interpretación más sencilla y su desempeño similar al del modelo polinomial.

Los resultados muestran asociaciones a nivel estatal y deben interpretarse considerando que la base contiene únicamente 32 observaciones.
