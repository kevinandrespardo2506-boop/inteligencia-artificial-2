# K-means #
Algoritmo de aprendizaje no supervisado que agrupa datos sin etiquetar en $k$ grupos distintos (clusters). Asigna de forma iterativa cada punto al centroide más cercano según la distancia geométrica y luego recalcula la posición de los centroides con la media de sus miembros hasta estabilizarse.
# k-Nearest Neighbors (k-NN) #
Método supervisado simple y no paramétrico usado para clasificación o regresión. Para clasificar un nuevo dato, busca a sus $k$ vecinos más próximos en el espacio de características y le asigna la clase más frecuente por votación mayoritaria (o el promedio de valores si es regresión).
# Random Forest #
Modelo de ensamble supervisado que construye una multitud de árboles de decisión independientes durante el entrenamiento. Combina la técnica de bagging con la selección aleatoria de variables en cada nodo, agregando las predicciones de todos los árboles para reducir el sobreajuste y mejorar la precisión.
# AdaBoost (Adaptive Boosting) #
Algoritmo de ensamble secuencial que combina clasificadores débiles (usualmente árboles muy simples) para crear uno fuerte. En cada ronda entrena un nuevo modelo aumentando el peso de los ejemplos que el modelo anterior clasificó mal, obligando al algoritmo a enfocarse en los casos más difíciles.
# Almeida–Pineda Recurrent Backpropagation #
Extensión del algoritmo de retropropagación diseñada para redes neuronales recurrentes que convergen a un estado estacionario (fixed points). Permite calcular los gradientes de error directamente en el punto de equilibrio mediante álgebra matricial, evitando tener que desplegar la red a través del tiempo (BPTT).
# ALOPEX (Algorithm of Pattern Extraction) #
Método de optimización estocástico y libre de derivadas desarrollado para entrenar redes neuronales y procesar imágenes. Ajusta los pesos de las conexiones evaluando las correlaciones cruzadas entre pequeños cambios aleatorios en los pesos y las variaciones resultantes en la función de costo global.
# Backpropagation (Retropropagación) #
Algoritmo fundamental para entrenar redes neuronales supervisadas basado en la regla de la cadena del cálculo. Calcula el gradiente de la función de pérdida con respecto a cada peso desde la capa de salida hacia la de entrada, permitiendo que optimizadores como el descenso de gradiente actualicen los parámetros.
# Bootstrap Aggregating (Bagging) #
Metatécnica de ensamble diseñada para reducir la varianza y evitar el sobreajuste en modelos inestables. Genera múltiples subconjuntos de datos entrenables mediante muestreo aleatorio con reemplazo (bootstrap), entrena un modelo independiente en cada uno y promedia sus predicciones finales.
# CN2 Algorithm #
Algoritmo de inducción de reglas de clasificación que genera expresiones legibles del tipo "SI condición ENTONCES clase". Combina la búsqueda por haz (beam search) del algoritmo AQ para explorar el espacio de reglas con pruebas estadísticas de significancia (como chi-cuadrado) para evitar el sobreajuste frente a datos con ruido.
# Constructing Skill Trees (CST) #
Algoritmo de aprendizaje por refuerzo jerárquico (reinforcement learning) que extrae habilidades reutilizables a partir de trayectorias de demostración. Segmenta trayectorias continuas complejas en secuencias de metas intermedias y las organiza en una estructura de árbol, permitiendo al agente encadenar políticas aprendidas para resolver nuevas tareas.
