# Trabajo Practico Especial.

_Le traemos un informe sobre Python, en el mismo podra encontrar de que se trata, para que sirve, como usarlo, entre otros. Este informe esta escrito en un archivo con extension ".md" y escrito en "Markdown" como requisito minimo del trabajo especial._

## Informe sobre Python:

Python es un lenguaje de programación esencial para los informáticos en desarrollo web.  Es un lenguaje dinámico que puede ser interpretado en varias plataformas, esto permite la creación de sitios web y aplicaciones multiplataforma como: **iOS, Android, Windows o Mac**. Python cuenta con una sintaxis **limpia, clara y altamente legible**. 
Es conocido por su sencillez, este con pocas líneas de código se podrá programar algoritmos complejos con resultados satisfactorios. Es un lenguaje interpretado, lo cual da la posibilidad de ahorrar al informático mucho tiempo durante el desarrollo ya que no es necesario compilar ni enlazar. 
El intérprete puede usarse interactivamente, lo que facilita experimentar con características del lenguaje, escribir programas descartables o probar funciones cuando se hace desarrollo de programas de abajo hacia arriba.
Como se menciona anteriormente, el intérprete es utilizable de forma interactiva y permite crear y borrar con facilidad; Esto permite escribir programas compactos y legibles. Python es recomendable ya que los programas son mucho más cortos que sus programas equivalentes en C, C++ o Java por varios motivos:

* Los tipos de datos de alto nivel permiten expresar operaciones complejas en una sola instrucción.

* La agrupación de instrucciones se hace por sangría en vez de llaves de apertura y cierre.

* No es necesario declarar variables ni argumentos.

El intérprete de Python y su biblioteca estándar, están a disposición de quien lo necesite de forma binaria y de código fuente para las principales plataformas desde el sitio web, **htpp://www.python.org/**.
Es un lenguaje de programación el cual ofrece una fuerte estructura y soporte a programas grandes. Ofrece un chequeo de error más grande que *c*. Permite separar un programa en módulos los cuales pueden “reusarse” en otros programas; Posee una colección considerable de módulos en forma estándar, los cuales se pueden usar como base de programas para desarrolladores. Algunas de las cosas que estos módulos proveen son: Entrada/salida a archivos, llamadas al sistema, sockets, interfaz a sistemas de interfaces gráfica de usuario.
 
## Iteraciones:
Se denomina iteración a aquel conjunto de instrucciones que se encuentran acotadas por un bloque repetitivo de acciones indicadas a través de comandos indicadas en el lenguaje Python. Las instrucciones por excelencia en este lenguaje pertenecen a los bloques *for* y *while*. Estos bloques poseen indentación para reconocer el bloque como tal. 

Cuando iteramos sobre diccionarios, se pueden obtener al mismo tiempo la clave y su valor correspondiente usando el método *iteritems()* en python2, e *items()* en python3
.
Cuando se itera sobre una secuencia, se puede obtener el índice de posición junto a su valor correspondiente usando la función *enumerate()*
.
Para iterar sobre dos o más secuencias al mismo tiempo, los valores pueden emparejarse con la función *zip()*

Para iterar sobre una secuencia en orden inverso, se especifica primero la secuencia al derecho y luego se llama a la función *reversed()*

Para iterar sobre una secuencia ordenada, se utiliza la función *sorted()* la cual devuelve una nueva lista ordenada dejando a la original intacta.


##Elementos del lenguaje: 

Python fue diseñado para ser leído con facilidad. Una de sus características es el uso de palabras donde otros lenguajes utilizarían símbolos. Por ejemplo, los operadores lógicos ! , | | y &&, en Python se escriben not, or y and, respectivamente. Curiosamente el lenguaje Pascal es junto con COBOL uno de los lenguajes con muy clara sintaxis y ambos son de la década del 70. La idea del código claro y legible no es algo nuevo.El contenido de los bloques de código (bucles, funciones, clases, etc.) es delimitado mediante espacios o tabuladores, conocidos como indentación, antes de cada línea de órdenes pertenecientes al bloque. Python se diferencia así de otros lenguajes de programación que mantienen como costumbre declarar los bloques mediante un conjunto de caracteres, normalmente entre llaves {}.​ Se pueden utilizar tanto espacios como tabuladores para indentar el código, pero se recomienda no mezclarlos.

**Uso de variables**: Las variables se definen de forma dinámica, lo que significa que no se tiene que especificar cuál es su tipo de antemano y puede tomar distintos valores en otro momento, incluso de un tipo diferente al que tenía previamente. Se usa el símbolo = para asignar valores.
**Condicionales**: Una sentencia condicional (if) ejecuta su bloque de código interno sólo si se cumple cierta condición. Se define usando la palabra clave if seguida de la condición, y el bloque de código. Condiciones adicionales, si las hay, se introducen usando elif seguida de la condición y su bloque de código. Todas las condiciones se evalúan secuencialmente hasta encontrar la primera que sea verdadera, y su bloque de código asociado es el único que se ejecuta. Opcionalmente, puede haber un bloque final (la palabra clave else seguida de un bloque de código) que se ejecuta sólo cuando todas las condiciones fueron falsas.
**Bucle for**: El bucle for es similar a foreach en otros lenguajes. Recorre un objeto iterable, como una lista, una tupla o un generador, y por cada elemento del iterable ejecuta el bloque de código interno. Se define con la palabra clave for seguida de un nombre de variable, seguido de in, seguido del iterable, y finalmente el bloque de código interno. En cada iteración, el elemento siguiente del iterable se asigna al nombre de variable especificado.
**Bucle while**: El bucle while evalúa una condición y, si es verdadera, ejecuta el bloque de código interno. Continúa evaluando y ejecutando mientras la condición sea verdadera. Se define con la palabra clave while seguida de la condición, y a continuación el bloque de código interno
**Listas y tuplas**: Para declarar una lista se usan los corchetes [], en cambio, para declarar una tupla se usan los paréntesis (). En ambas los elementos se separan por comas, y en el caso de las tuplas es necesario que tengan como mínimo una coma.
Tanto las listas como las tuplas pueden contener elementos de diferentes tipos. No obstante las listas suelen usarse para elementos del mismo tipo en cantidad variable mientras que las tuplas se reservan para elementos distintos en cantidad fija.
Para acceder a los elementos de una lista o tupla se utiliza un índice entero (empezando por "0", no por "1"). Se pueden utilizar índices negativos para acceder elementos a partir del final.
Las listas se caracterizan por ser mutables, es decir, se puede cambiar su contenido en tiempo de ejecución, mientras que las tuplas son inmutables ya que no es posible modificar el contenido una vez creada.
**Conjuntos**: Los conjuntos se construyen mediante set(items) donde items es cualquier objeto iterable, como listas o tuplas. Los conjuntos no mantienen el orden ni contienen elementos duplicados.
Se suelen utilizar para eliminar duplicados de una secuencia, o para operaciones matemáticas como intersección, unión, diferencia y diferencia simétrica.
**Funciones**: definicion:

La ejecución de una función introduce una nueva tabla de símbolos usada para las variables locales de la función. Más precisamente, todas las asignaciones de variables en la función almacenan el valor en la tabla de símbolos local; así mismo la referencia a variables primero mira la tabla de símbolos local, luego en la tabla de símbolos local de las funciones externas, luego la tabla de símbolos global, y finalmente la tabla de nombres predefinidos. 

Así, no se les puede asignar directamente un valor a las variables globales dentro de una función (a menos se las nombre en la sentencia global), aunque si pueden ser referenciadas.
La primer sentencia del cuerpo de la función puede ser opcionalmente una cadena de texto literal; esta es la cadena de texto de ocumentación de la *función* o *docstring* (cadena de documentaciòn).

Los parámetros reales (argumentos) de una función se introducen en la tabla de símbolos local de la función llamada cuando esta es ejecutada; así, los argumentos son pasados por valor (dónde el valor es siempre una referencia a un objeto, no el valor del objeto).
Cuando una función llama a otra función, una nueva tabla de símbolos local es creada para esa llamada.
La definición de una función introduce el nombre de la función en la tabla de símbolos actual.

La palabra reservada *def* se usa para *definir funciones*. Debe seguirle el nombre de la función y la lista de parámetros formales entre paréntesis. Las sentencias que forman el cuerpo de la función empiezan en la línea siguiente, y deben estar con sangría.

También es posible definir funciones con un número variable de argumentos. 
Hay tres formas que pueden ser combinada:

*Argumentos con valores por omiciòn*
     
 *Palabras claves como argumento*

 *Lista de argumentos arbitrarios*


Todos los ejemplos compartían algo en común: realizaban una tarea concreta (presentar información en pantalla), pero no devolvían ningún valor al ser invocadas.

##info issues
Ya conoces algunas funciones en Python que devuelven valores. Por ejemplo, recuerda la función int(), que convertía una cadena de caracteres en un número entero, o la función len(), que devolvía la longitud de una cadena.

Los valores que devuelven las funciones pueden ser capturados y esto típicamente se hace asignando una variable, pudiendo formar parte de una expresión numérica.

longitud = len('La casa de la pradera')

Esta instrucción asignaría el valor numérico 21 a la variable longitud.

Los valores que devuelven las funciones no tienen que ser necesariamente numéricos.

Voy a mostrarte cómo hacer para que una función devuelva un valor. Crearemos una que admita como argumento un número natural y que devuelva la suma de todos los naturales que hay hasta él inclusive. Es decir, si, por ejemplo, le facilitamos como argumento un 5, nos devuelva la suma:

1 + 2 + 3 + 4 + 5 = 15

Podríamos hacer un algoritmo para realizar el cálculo empleando un bucle, pero no va ser necesario. Si recordáis las enseñanzas en la escuela, hay una fórmula directa para calcular la suma de todos los términos de una progresión aritmética de diferencia uno:

sp=\frac{n(n+1)}{2}

Ya estamos en condiciones de crear nuestra función:

Abre IDLE o el intérprete interactivo y escribe el siguiente código:

>>> def sumaprogresion(n):
       sp=n*(n+1)//2
       return sp


##Funciones que retornan
En Python, es posible (al igual que en la gran mayoría de los lenguajes de programación), llamar a una función dentro de otra, de forma fija y de la misma manera que se la llamaría, desde fuera de dicha función:

def funcion(): 
    return "Hola Mundo" 
 
def saludar(nombre, mensaje='Hola'): 
    print mensaje, nombre 
    print mi_funcion()

Sin embargo, es posible que se desee realizar dicha llamada, de manera dinámica, es decir, desconociendo el nombre de la función a la que se deseará llamar. A este tipo de acciones, se las denomina llamadas de retorno.

Para conseguir llamar a una función de manera dinámica, Python dispone de dos funciones nativas: locals() y globals().

Ambas funciones, retornan un diccionario. En el caso de locals(), éste diccionario se compone -justamente- de todos los elementos de ámbito local, mientras que el de globals(), retorna lo propio pero a nivel global.
Durante una llamada de retorno, el nombre de la función, puede no ser el indicado. Entonces, siempre que se deba realizar una llamada de retorno, es necesario comprobar que ésta exista y pueda ser llamada.

if nombre_de_la_funcion in locals(): 
    if callable(locals()[nombre_de_la_funcion]): 
        print locals()[nombre_de_la_funcion]("Emilse")

El operador in, nos permitirá conocer si un elemento se encuentra dentro de una colección, mientras que la función callable() nos dejará saber si esa función puede ser llamada.

## Impresiones de pantalla
Opción 1

El primero de ellos es PyAutoGUI, un módulo multiplataforma para automatizar tareas. Podemos capturar la pantalla con tres líneas de código.

    import pyautogui
    # Capturar pantalla.
    screenshot = pyautogui.screenshot()
    # Guardar imagen.
    screenshot.save("screenshot.png")

PyAutoGUI utiliza internamente Pillow, una de las librerías de manejo de imagenes más populares del lenguaje, por lo que screenshot es una instancia de PIL.Image.Image.

    # Mostrar imagen.
    screenshot.show()

Para capturar únicamente una porción de la pantalla, empleamos el parámetro region, una tupla con la estructura (X, Y, Ancho, Alto).

    # Capturar una porción de la pantalla.
    screenshot = pyautogui.screenshot(region=(50, 50, 400, 300))

La forma más sencilla de instalar el módulo junto a todas sus dependencias es vía pip.

pip install pyautogui

Para poder ejecutar correctamente PyAutoGUI en Linux, además, deben instalarse las siguientes dependencias.
Opción 2

Otro paquete similar a PyAutoGUI es AutoPy, un toolkit de automatización plataforma escrito en C. Su API es mucho más elegante, simple y agradable que la del módulo anterior, pero por el momento soporta únicamente Python 2 (razón por la cual pasa a ser la opción número dos).

Capturar la pantalla es igualmente de sencillo:

    import autopy
    screenshot = autopy.bitmap.capture_screen()
    screenshot.save("screenshot.png")

La función capture_screen puede tomar una región determinada de la pantalla, con la estructura ((X, Y), (Ancho, Alto)).

    screenshot = autopy.bitmap.capture_screen(((50, 50), (400, 300)))



Bibliografía:
http://docs.python.org.ar/tutorial/pdfs/TutorialPython2.pdf
http://docs.python.org.ar/tutorial/2/datastructures.html
https://es.wikipedia.org/wiki/Python
https://librosweb.es/libro/python/capitulo-2/estructuras-de-control-de-flujo.html
