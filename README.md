 Estimación del Número de Clusters en K-Means

*Métodos Implementados
1. Método del Codo: Evalúa la reducción de la inercia para diferentes valores de *k*.
2. Coeficiente de Silueta: Mide la calidad de la separación entre clusters.

*Uso
1. Clonar repositorio: `git clone [URL]`
2. Ejecutar script: `python optimal_k.py`
3. Interpretar gráficas generadas (`elbow_silhouette_plot.png`).

* Resultados
- Dataset Iris: 
  - *k óptimo*: 3 (coincide con las 3 especies de flores).
  - Gráficas muestran claridad en la selección de *k*.

* Referencias
Tibshirani, R., et al. (2001). "Estimating the number of clusters via the Gap Statistic". [citation:8]
2. Murtagh, F. (2014). "A survey of recent advances in hierarchical clustering algorithms". [citation:5]
3. Scikit-learn Documentation. "KMeans and Silhouette Score". [citation:9]
