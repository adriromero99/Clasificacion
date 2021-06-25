# Clasificación de flores con LDA y QDA

El objetivo del presente trabajo es estudiar y comparar las clasificaciones que se obtienen al
utilizar **Linear Discriminant Analyisis (LDA) y Quadratic Discriminant Analysis (QDA)**. Para
ello se clasificarán las observaciones de flores del set de datos iris en 3 grupos: setosa, versicolor
y virginica, a partir de mediciones realizadas sobre la longitud y el ancho de los pétalos y de los
sépalos de las flores.

El desarrollo del trabajo estará dividido en tres secciones:

- **Explicación de LDA y QDA:** se explicarán brevemente los clasificadores para poder
comprender sobre qué fundamentos se basan las secciones siguientes.

- **Análisis inicial:** se analizará el set de datos que se utilizará a lo largo del trabajo y el
cumplimiento de las hipótesis que suponen los modelos de LDA y QDA. Además se buscará
qué features son mejores para lograr una clasificación óptima.

- **Clasificación y análisis de métricas:** se utilizarán distintos clasificadores para clasificar
a las observaciones y para cada uno de ellos se evaluarán las métricas de accuracy, precision,
recall y se utilizarán técnicas de resampleo como validación cruzada (cross-validation).
