# Tarea 2 "Algoritmos, Redes y Equidad"

### Integrantes:
* Valentina Alarcón
* Santiago Haberle
* José Miguel Zapata

## El código
La tarea fue realizada en un Jupyter Notebook de Google Colab. El contenido se divide en lo siguiente:

1. Un pequeño estudio de los datos: cantidades, porcentajes.
2. Pre-procesamiento del dataset: Se eliminaron algunas columnas que se consideraron no relevantes, y se modificó el contenido de otras. Esto con el principal objetivo de facilitar su procesamiento en el resto del trabajo.
3. Entrenamiento de modelos (+ selección de mejores parámetros) 'Árbol de Decisión', 'Random Forest' y KNN.
4. En la sección Random Forest se incluye un breve estudio de threshold óptimo, pero este no será usado ni se le da mayor importancia.
5. Evaluación de sesgo: Independencia, Separación y Suficiencia.
6. Mitigación de sesgo: Pre, In y Post-procesamiento. En general se suele primero intentar mitigar los atributos sensibles por separado. Luego se intenta con ambos a la vez.
7. Combinación de mitigación.

## Cómo correr el código
En primer lugar, es de alta importancia agregar el dataset 'MBA.csv' a la parte de 'contents' de colab.

Luego, dado que todo se encuentra de manera secuencial, basta con correr el código para observar los resultados.

Tener un poco de paciencia! Algunos entrenamientos tardan un poco.

NOTA: Hay algunas líneas hacia el final dedicadas a reiniciar el entorno de ejecución. Esto es por algunos problemas que se generaban por Tensorflow. Si estas líneas por algún motivo no funcionaran, y apareciera un error asociado a ello, se debería reiniciar el entorno de ejecución manualmente.
