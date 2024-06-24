# iic2440-t2

El archivo de la tarea con todas las funciones se llama ```Tarea2.ipynb```, además, hay 3 archivos con datos de prueba, los cuales son: ```datos_p2.txt```: datos de prueba para la pregunta 2, es el mismo ejemplo dado en el repositorio de la tarea. ```datos_p3.txt``` y ```datos_p3_2.txt```: todos archivos con datos y consultas para la pregunta 3. 

Para cada una de las preguntas se creó un apartado al final del notebook para realizar pruebas. La primera no necesita de archivos ya que se conecta a la base de datos de Neo4J la cual está hosteada en Neo4J AuraDB, una plataforma para montar bases de dato Neo4J en la nube. En la segunda y tercera pregunta se especifica el formato que deben tener los archivos para su correcta ejecución, y en caso de querer probar con otro archivo, subirlo a Google Colab y correr lo siguiente:
```
data, b, A, L, M = readFile3('nombre_archivo.txt')
print(inputArista(A, L, M))
```
