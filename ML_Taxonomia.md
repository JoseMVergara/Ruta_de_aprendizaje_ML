
# **Clasificación / Taxonomía de los modelos de Machine Learning - Estrategía e Innovación de TI**

![Supervised vs unsupervised](https://i.ytimg.com/vi/mKTD8X4iokQ/maxresdefault.jpg)

## **Aprendizaje supervisado (supervised learning):**
El aprendizaje supervisado es uno de los tipos más comunes de aprendizaje automático. En este tipo de aprendizaje, se proporciona al modelo un conjunto de entrenamiento etiquetado que incluye tanto las entradas como las salidas deseadas. El objetivo es que el modelo aprenda a generalizar y predecir la salida deseada para nuevos datos.

Si bien el operador conoce las respuestas adecuadas, el algoritmo reconoce patrones en los datos, aprende de las observaciones y produce predicciones, el algoritmo predice y es corregido por el operador; este proceso se repite hasta que el algoritmo alcanza un alto nivel de precisión.

 - Aplican lo aprendido en el pasado en los datos nuevos.
 - Realizan predicciones sobre los valores de salida.
 - Comparan la salida con la correcta y prevista, encontrando errores para modificar el modelo.

Ejemplo: Un ejemplo de aprendizaje supervisado es un modelo de regresión lineal que se entrena para predecir el precio de una casa en función de su tamaño, ubicación y otros factores.

### **Regresión:**
Cuando usamos regresión, el resultado es un número. Es decir, el resultado de la técnica de machine learning que estemos usando será un valor numérico, dentro de un conjunto infinito de posibles resultados.

Aquí van algunos ejemplos de regresión:

    - Predecir por cuánto se va a vender una propiedad inmobiliaria
    - Predecir cuánto tiempo va a permanecer un empleado en una empresa
    - Estimar cuánto tiempo va a tardar un vehículo en llegar a su destino
    - Estimar cuántos productos se van a vender


### **Clasificación:**
Cuando usamos clasificación, el resultado es una clase, entre un número limitado de clases. Con clases nos referimos a categorías arbitrarias según el tipo de problema.

Por ejemplo, si queremos detectar si un correo es spam o no, sólo hay 2 clases. Y el algoritmo de machine learning de clasificación, tras darle un correo electrónico, tiene que elegir a qué clase pertenece: spam o no-spam. Hay muchos más ejemplos, por supuesto:

    - ¿comprará el cliente este producto? [sí, no]
    - ¿tipo de tumor? [maligno, benigno]
    - ¿subirá el índice bursátil? IBEX mañana [sí, no]
    - ¿es este comportamiento una anomalía? [sí, no]
    - ¿nos devolverá este cliente un crédito? [sí, no]
    - ¿qué deporte estás haciendo? tal y como lo detectan los relojes inteligentes [caminar, correr, bicicleta, nadar]
    - ¿obtendrá una historia un número alto de visitas en un agregador de noticias? [sí, no]

## **Aprendizaje no supervisado:**
El aprendizaje no supervisado es un tipo de aprendizaje automático en el que no se proporcionan etiquetas de salida al modelo. El objetivo es descubrir patrones o relaciones en los datos de entrada. Los modelos de aprendizaje no supervisados se utilizan para tres tareas principales: agrupamiento y reducción de dimensionalidad. 

Ejemplo: Un ejemplo de aprendizaje no supervisado es un modelo de agrupamiento que se utiliza para segmentar una base de datos de clientes en grupos con similares características demográficas y de comportamiento de compra.

### **Agrupamiento o clusterización:**
El agrupamiento es una técnica de minería de datos que agrupa datos sin etiquetar basándose en sus similitudes o diferencias. Los algoritmos de agrupamiento se utilizan para procesar objetos de datos sin clasificar en grupos representados por estructuras o patrones en la información. 

Ejemplo: Un ejemplo de agrupamiento es un modelo de clustering que se utiliza para agrupar textos similares en un corpus de document

### **Reducción de dimensionalidad:**
En este tipo de aprendizaje no supervisado, el objetivo es reducir la cantidad de características o dimensiones en los datos, mientras se intenta preservar la información importante.

Aunque más datos suelen dar lugar a resultados más precisos, también pueden afectar el rendimiento de los algoritmos de aprendizaje automático (por ejemplo, el sobreajuste) y también pueden hacer difícil visualizar los conjuntos de datos. La reducción de dimensionalidad es una técnica utilizada cuando el número de características o dimensiones en un determinado conjunto de datos es demasiado alto. Reduce el número de entradas de datos a un tamaño manejable, al mismo tiempo que preserva la integridad del conjunto de datos tanto como sea posible. Se utiliza comúnmente en la etapa de preprocesamiento de datos 

## **La principal diferencia entre el aprendizaje supervisado y el no supervisado: datos etiquetados**

La principal distinción entre los dos enfoques es el uso de conjuntos de datos etiquetados. En términos simples, el aprendizaje supervisado utiliza datos de entrada y salida etiquetados, mientras que un algoritmo de aprendizaje no supervisado no lo hace.

En el aprendizaje supervisado, el algoritmo "aprende" del conjunto de entrenamiento haciendo predicciones iterativas sobre los datos y ajustándose para la respuesta correcta. Aunque los modelos de aprendizaje supervisado suelen ser más precisos que los modelos de aprendizaje no supervisado, requieren una intervención humana previa para etiquetar adecuadamente los datos. Por ejemplo, un modelo de aprendizaje supervisado puede predecir cuánto tiempo durará su viaje en función de la hora del día, las condiciones climáticas, etc. Pero primero, tendrás que entrenarlo para que sepa que la lluvia prolonga el tiempo de conducción.

Por otro lado, los modelos de aprendizaje no supervisado trabajan solos para descubrir la estructura inherente de los datos no etiquetados. Tenga en cuenta que aún requieren cierta intervención humana para validar las variables de salida. Por ejemplo, un modelo de aprendizaje no supervisado puede identificar que los compradores en línea a menudo compran grupos de productos al mismo tiempo. Sin embargo, un analista de datos necesitaría validar que tiene sentido para un motor de recomendación agrupar la ropa de bebé con un pedido de pañales, compota de manzana y vasos con boquilla.

## **Otras diferencias clave entre el aprendizaje supervisado y el no supervisado**

 - **Metas:** En el aprendizaje supervisado, la meta es predecir resultados para nuevos datos. Ya sabes de antemano el tipo de resultados que esperar. Con un algoritmo de aprendizaje no supervisado, la meta es obtener insights de grandes volúmenes de nuevos datos. La propia inteligencia artificial determina lo que es diferente o interesante en el conjunto de datos.
- **Aplicaciones:** Los modelos de aprendizaje supervisado son ideales para la detección de correo no deseado, el análisis de sentimientos, la predicción del clima y los precios, entre otras cosas. Por otro lado, el aprendizaje no supervisado es una buena opción para la detección de anomalías, los motores de recomendación, las personas de clientes y la imagen médica.

- **Complejidad:** El aprendizaje supervisado es un método simple para el aprendizaje automático, típicamente calculado a través del uso de programas como R o Python. En el aprendizaje no supervisado, se necesitan herramientas potentes para trabajar con grandes cantidades de datos no clasificados. Los modelos de aprendizaje no supervisado son computacionalmente complejos porque necesitan un gran conjunto de entrenamiento para producir los resultados deseados.

- **Desventajas:** Los modelos de aprendizaje supervisado pueden ser tardados en entrenarse y las etiquetas para las variables de entrada y salida requieren experiencia. Mientras tanto, los métodos de aprendizaje no supervisado pueden tener resultados increíblemente inexactos a menos que haya intervención humana para validar las variables de salida.