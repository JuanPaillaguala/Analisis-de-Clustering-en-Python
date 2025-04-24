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
El análisis comparativo entre K-means y GMM muestra que K-means produjo clusters más compactos y con mayor separación para este conjunto de datos. Esto sugiere que la estructura de los datos se ajusta mejor a clusters de forma esférica.

![Gráfico de siluetas](https://github.com/user-attachments/assets/331c1513-04cc-4690-9624-ec1a72f6cc4a)

![Gráfico de cluster (GMM) con PCA](https://github.com/user-attachments/assets/412bbec6-2b67-46bb-b1ef-fa2d7e626617)

## Tecnologías utilizadas

- Python 3.12.7
- Pandas y NumPy para manipulación de datos
- Scikit-learn para implementación de algoritmos de clustering
- Matplotlib y Seaborn para visualización
- Scikit-learn y Yellowbrick para evaluación y visualización de clusters

## Dependencias

Todas las bibliotecas necesarias están listadas en `requirements.txt`

## Licencia

Este proyecto está licenciado bajo [MIT License](LICENSE).
