# Sampling_Distribution_in_Python

### Nombre del proyecto

Distribuciones muestrales como ayuda didáctica en la impartición de la asignatura de Estadística y Probabilidad en el Colegio de Ciencias y Humanidades

### Objetivos

El programa desarrollado tiene el objetivo de tener una ayuda didática en la impartición del tema de Distribuciones Muestrales, que es parte de la Unidad II del segundo curso de Estadística y Probabilidad. Esta unidad tiene el nombre de Estimadores e introducción a la inferencia estadística y ayuda a que el alumno se apropie de los siguientes aprendizajes:

* Inspecciona el comportamiento de la media y de la proporción muestrales como variables aleatorias, obtenidas por medio de la simulación física y/o computacional, dentro del contexto de un problema o una investigación y en términos de tendencia, dispersión y distribución.

* Infiere que los estimadores media y proporción se distribuyen de manera aproximadamente normal, al trabajar con muestras grandes.

* Construye las distribuciones muestrales para la media y la proporción, bajo las condiciones del Teorema del Límite Central y a partir de la expresión para estandarizar la distribución normal.

### Problema que resuelve

Por lo general los modulos del software de enseñanza de estadñsística en materia de distribuciones muestrales que existen en el mercado, solo realizan la aproximación frecuencial de estas. La fala de un software que realice todas las muestras posibles de una población dada es evidente. Por lo anterior, es importante tener herramientas computacionales para que el alumno pueda apropiarse del aprendizaje de como realizar una distribución muestral ya que aun en una población de tamaño pequeño obtener todas las muestras posibles de dicha población es una tarea ardua y compleja para el alumno. El programa desarrollado resuelve esta parte y con ayuda de una secuencia didáctica adecuada, este programa es de gran ayuda para el alumno.

### Mención sobre los lenjuage(s) utilizado(s)

Se utilizó el lenguaje de programación **Python**, aunque se pretende en un futuro realizar el programa en lenguaje de programación **Julia**, lo anterior por la eficiencia para el manejo de datos de este último lenguaje de programación.

### Argumentación sobre la elección de este lenguaje

Python permite que los desarrolladores sean más productivos, ya que pueden escribir un programa de Python con menos líneas de código en comparación con muchos otros lenguajes. Python cuenta con una gran biblioteca estándar que contiene códigos reutilizables para casi cualquier tarea.

### Descripción de lo que se está simulando, ejemplo básico de su funcionamiento en general e instrucciones de uso

El presente programa toma los datos de una población dada (del tipo cuantitativa) mediante la lectura de un archivo tipo CSV, para después realizar todas las muestras posibles de tamaño n=2, 3, 4, 5 a elección del usuario como se muestra en la siguiente figura:

![](https://github.com/temocbzc/Sampling_Distribution_in_Python/blob/main/Img%201.JPG)

Como se puede observar en la anterior figura, las muestras realizadas se pueden guardar en un archivo tipo CSV para otro tratamiento que pueda realizar el alumno, o bien calcular las medias muestras de cada una de las muestras y graficar su distribución:

![](https://github.com/temocbzc/Sampling_Distribution_in_Python/blob/main/Img%202.JPG)

El programa como se puede observar en las figuras anteriores, es una aplicación con ventanas, por lo cual su funcionamiento es muy intuitivo y por el momento no se necesitaria un instructivo de uso.

### Tema que ayuda a comprender

Distribuciones Muestrales

### Justificación de cómo ayuda al alumno a comprender el tema

Como se menciono en apartados anteriores, la justificación de realizar un programa en Python es la falta de un software que realice todas las muestras posibles de una población dada. Por lo anterior es importante tener herramientas de este estilo para que el alumno pueda aprender a realizar distribuciones muestrales. Este software desarrollado se puede escalar a realizar muestras de tamaño más grandes y para encontrar espacios muestrales de experimentos con muestreos con reemplazo y repetitivos (diagramas de árbol).

Si estas en la disposición de ayudar a mejorar el codigo de programación o bien a sugerir opciones de adición al programa, estas cordialmente invitado a realizarlo y así poder contar con una herramienta más robusta para la enseñanza de la Estadística y Probabilidad, que puede ser utilizado en otras escuelas de bachillerato o incluso a nivel superior.