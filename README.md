# Análisis de Clustering: Comparación entre K-means y GMM

Este proyecto implementa y compara dos técnicas de clustering no supervisado (K-means y GMM). El análisis incluye la determinación del número óptimo de clusters, visualización de resultados y evaluación mediante métricas como Davies-Bouldin y coeficiente de silueta.

## Contenido del proyecto

- Análisis exploratorio de datos
- Preprocesamiento y normalización
- Clustering con K-means
- Clustering jerárquico con visualización de dendrograma
- Modelo de mezcla de Gaussianas (GMM)
- Comparación de resultados entre ambos modelos
- Visualización de clusters en espacio reducido (PCA)

## Resultados
El análisis comparativo entre K-means y GMM muestra que K-means produjo clusters más compactos y con mayor separación para este conjunto de datos, con un coeficiente de Davies-Bouldin de [valor] frente a [valor] para GMM. Esto sugiere que la estructura de los datos se ajusta mejor a clusters de forma esférica.

![Visualización de clusters](ruta-a-imagen-guardada.png)

## Tecnologías utilizadas

- Python 3.x
- Pandas y NumPy para manipulación de datos
- Scikit-learn para implementación de algoritmos de clustering
- Matplotlib y Seaborn para visualización
- Yellowbrick para evaluación y visualización de clusters

## Cómo usar este proyecto

1. Clona este repositorio
2. Instala las dependencias: `pip install -r requirements.txt`
3. Abre el notebook `Proyecto_Python_Clustering.ipynb` con Jupyter
4. Ejecuta las celdas para replicar el análisis

## Dependencias

Todas las bibliotecas necesarias están listadas en `requirements.txt`

## Licencia

Este proyecto está licenciado bajo [MIT License](LICENSE).
