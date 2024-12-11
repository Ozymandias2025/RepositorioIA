# TEMA 1 - INTRODUCCION
## CONTENIDOS
### ANÁLISIS EXPLORATORIO DE DATOS
Existen algunas recomendaciones para realizar un EDA. Entre ellas están:
* Verificar la cantidad de clases.
* Verificar datos faltantes y outliers.
* Verificar el tipo de datos que componen el dataset.
* Analizar histogramas de las features, entre otros.

Los modelos no pueden ser entrenados por un mismo conjunto de datos. Para esto, un 30% del conjunto de datos se usa para evaluar el modelo, y el otro 70% del conjunto se usa para entrenar el modelo. La selección se debe hacer aleatoria.

### PRINCIPALES TIPOS DE APRENDIZAJE DE IA
* APRENDIZAJE SUPERVISADO:

Es como aprender con un maestro. En este enfoque, el modelo se entrena utilizando un conjunto de datos que incluye tanto las entradas (características) como las salidas correctas (etiquetas). El objetivo es que el modelo aprenda a mapear las entradas a las salidas correctas para poder hacer predicciones precisas sobre datos nuevos.

Ejemplo 1 (de clasificación):
Imagina que quieres crear un modelo que pueda distinguir entre fotos de perros y gatos. Tienes un conjunto de fotos, cada una etiquetada como "perro" o "gato". Usando este conjunto de datos etiquetado, el modelo aprende a reconocer patrones en las imágenes que corresponden a cada categoría.

Ejemplo 2 (de regresión):
Supongamos que deseas predecir el precio de una casa basándote en características como el tamaño, el número de habitaciones y la ubicación. Tienes un conjunto de datos donde cada casa tiene estas características y su precio correspondiente. El modelo aprende a predecir el precio de una casa nueva basándose en estos datos.

* APRENDIZAJE NO SUPERVISADO:

Es como explorar un nuevo terreno sin un mapa. Aquí, el modelo se entrena con un conjunto de datos sin etiquetas, y el objetivo es descubrir patrones o estructuras ocultas dentro de los datos.

Ejemplo 1 (de clustering):
Imagina que tienes una gran cantidad de datos de clientes y quieres segmentarlos en diferentes grupos basados en comportamientos de compra similares. El algoritmo de clustering puede agrupar a los clientes en segmentos como "compradores frecuentes", "compradores ocasionales", etc., sin saber de antemano cuántos o qué tipo de grupos encontrar.

Ejemplo 2 (de reducción de dimensionalidad):
Supongamos que tienes un conjunto de datos con muchas características y quieres simplificarlo para visualizarlo o para mejorar la eficiencia del modelo. Algoritmos como PCA (Análisis de Componentes Principales) pueden reducir el número de dimensiones mientras retienen la mayor parte de la variabilidad en los datos.

* APRENDIZAJE POR REFUERZO:

Es como aprender mediante ensayo y error. En este enfoque, un agente aprende a tomar decisiones secuenciales interactuando con un entorno. El agente recibe recompensas o penalizaciones basadas en las acciones que toma, y su objetivo es maximizar la recompensa total a lo largo del tiempo.

Ejemplo 1 (juegos):
Un agente de aprendizaje por refuerzo puede aprender a jugar un videojuego (como ajedrez o un juego de arcade) desde cero. El agente prueba diferentes estrategias y recibe recompensas por ganar puntos o penalizaciones por perder vidas. Con el tiempo, el agente mejora sus estrategias para maximizar su puntuación.

Ejemplo 2 (robótica):
Imagina un robot que debe aprender a caminar. Al principio, el robot puede caerse mucho, pero cada vez que da un paso exitoso, recibe una recompensa. A través de muchos intentos y errores, el robot aprende a caminar de manera estable.