# Tipos de Datos

Antes de iniciar con los tipos, es necesario saber que son las variables mutables e inmutables.

### Tipos de datos inmutables
Estas son las variables cuyo valor no se puede cambiar, modificar o actualizar su contenido, pero como variable se puede asignar otro valor a este.

Ejemplo
>  var = "hello world" // Esta variable es inmutable ya que no podemos cambiar solo la letra "h" con una "H"\
>  var = "Hello world" // Pero si podemos asignar otro valor a la variable var con la cadena "Hello world"

En el ejemplo anterior no se pudo cambiar solo una letra de la variable, sino que se tubo que camniar toda la variable siendo esta un nuevo valor asignado a la variabel var.

En esta categoria entra los siguentes tipos de datos:

**int**. Este tipo de datos engloba todos los numero enteros positivos y negativos con un rango de (-32768 - 32768).

Ejemplo
>  number = 123\
>  type(number)\
>  <type 'int'>

**long**. Este tipo de datos engloba todos los numero enteros de cualquier tamanio teniendo como limitante la memoria de la computadora, en Python para determinar un dato long se pone la letra **L** al final del valor.

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

**bool**. Este tipo de datos tambien llamado booleano, almacena dos valores: True(Verdadero) y False(Falso), estos valores son utilizados como resultados de operaciones logicas o binarias.

Ejemplo
>  boolean = True\
>  type(boolean)\
>  <type 'bool'>
