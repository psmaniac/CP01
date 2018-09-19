# Tipos de Datos

Antes de iniciar con los tipos, es necesario saber que son las variables mutables e inmutables.

### Tipos de datos inmutables
Estas son las variables cuyo contenido no se puede cambiar, modificar o actualizar, pero se puede asignar otro valor a este como cualquier varable.

Ejemplo
>  var = "hello world" // Esta variable es inmutable ya que no podemos cambiar solo la letra "h" con una "H"\
>  var = "Hello world" // Pero si podemos asignar otro valor a la variable var con la cadena "Hello world"

En el ejemplo anterior no se pudo cambiar solo una letra de la variable, sino que se tubo que cambiar todo el valor o contenido de este.
En esta categoria entra los siguentes tipos de datos:

**int**. Este tipo de datos engloba todos los numero enteros positivos y negativos con un rango de (-32768 a +32768).

Ejemplo
>  number = 123\
>  type(number)\
>  <type 'int'>

**long**. Este tipo de datos engloba todos los numero enteros de cualquier tamanio teniendo como limitante la memoria de la computadora, en Python para determinar un dato long se pone la letra **L** al final del valor, actualmetne en python 3.X no es necesario declarar este tipo de dato ya que maneja al igual que un int largo.

Ejemplo
>  number_long = 123456789L\
>  type(number_long)\
>  <type 'long'>

**float**. Este tipo de datos engloba todos los numero con decimales, tambien conocidos como numeros reales.

Ejemplo
>  number_float = 12.34\
>  type(number_float)\
>  <type 'real'>

**complex**. Este tipo de datos es una caracteristica particular de Python ya que no muchos lenguajes manejan este tipo de datos, engloba a aquellos numeros que tienen una parte imaginaria.

Ejemplo
>  number_complex = 3 + 3.2j\
>  type(number_complex)\
>  <type 'complex'>

**bool**. Este tipo de datos tambien llamado booleano, almacena dos valores: True(Verdadero) o 1(uno) y False(Falso) o 0(cero), estos valores son utilizados como resultados de operaciones logicas o binarias.

Ejemplo
>  boolean = True\
>  type(boolean)\
>  <type 'bool'>

**string**. Este tipo de datos engloba a los caracteres o conjunto de estos denominado texto, las cuales se asignan entre corchetes simples o dobles (",") o (',').

Ejemplo
>  text = "Hello world"\
>  text = 'Hello world'
>  type(text)\
>  <type 'str'>

**tuple**. Las tuplas son un conjunto de datos ordenados, las cuales siguen un orden empezando de 0 a n.

Ejemplo
>  var_tuple = (1, 2, 3, "a", "b", "c)\
>  type(var_tuple)
>  <type 'tuple
>  print(var_tuple[1])
>  2
>  print(var_tuple[4])
>  "b"

### Tipos de datos mutables

En este tipo de datos, los valores pueden ser modificado independientemente cada uno a diferencia de los inmutables que para cambiar el valor se debe cambiar todo, en este apartado se enfocara en las listas en Python y al igual que una tupla el indice de los elementos empieza en 0.

**list**. Para declarar una lista en Python se tiene dos opciones:

>  list_1 = \[1, 2, 3, "a", "b", "c"]\
>  list_2 = list(1, 2, 3, "a", "b", "c")\
>  print(list_1)\
>  \[1, 2, 3, 'a', 'b', 'c']\
>  print(list_1\[3])\
>  'a'
>  list_1\[3]= "hello"\
>  print(list_1\[3])\
>  'hello'

En una lista se puede cambiar el valor de un solo dato indicandole el indice o posicion del valor a reeemplazar, este tipo de variable tiene muchos metodos o funciones las cuales se puede aprobechar para el manejo de datos, las cuales se veran con mas detenimiento en metodos y funciones basicos en Python.

### Ejercicios 

Abrir el archivo [README.md](https://github.com/psmaniac/CP01/tree/master/lesson01/03_variables/Exercises) de la carpeta de ejercicios y realizar los ejercicios que indican cada uno, para asegurar sus respuestas puede usar Python en [Repl.it](https://repl.it/).


