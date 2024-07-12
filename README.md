# INF-398-TALLER3
Archivos del taller3

Declaración ética:

Se declara por parte de los integrantes Natalia Barraza y Cristian Marín que este trabajo es un trabajo original, no usa código extraido de otra persona, por otro lado si hubo uso de Chatgpt para la creación de las funciones que se usaron para el procesamiento de texto, dado el desconocimiento del manejo de este, de estudió al respecto en diversas fuentes (se adjuntan links al final) y luego se plantearon ideas, pero por la ignorancia de librerías y funciones para llevar a cabo estas ideas se implementaron con chatgpt.

División del trabajo:

Cristian Marín: Elección de modelos a entrenar, desarrollo del código de entrenamiento de los modelos.

Natalia Barraza: Preprocesamiento de datos, implementación código de método de ensamble de mayor votación.

Observación:

El entrenamiento de todos los modelos demora app entre 1,5 y 2 horas, la parte de voting demora app 15 minutos, por lo que en el repositorio se adjunta predicciones realizadas de cada modelo y archivo comparativo para observar como cambia f1 según el modelo y parámetro elegido (este archivo se muestra como df al final del código).
La parte del voting, si se quisiera confirmar los resultados, se puede ejecutar sin necesidad de ejecutar la celda anterior con los demás modelos. 

Links fuentes: 
1)https://arnaudunjo.com/es/2021/04/25/machine-learning-modelo-clasificador-de-textos-en-python/
2)https://www.arsys.es/blog/clasificaciontextos-python-jupyternotebooks 

Los modelos entrenados se quisieron adjuntar pero estos pesaban mucho (en particular randomforest y voting entre 500 mb y 2 gb)
