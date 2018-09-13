# Operaciones Extras en Python

Para hacer operaciones mas complejas en Python se dispone de diferentes funciones o expreciones extras (Se hablara con mas claridad las funciones en los siguentes temas.) para realizar estas operaciones, como ser potencia, raiz cuadrada, logaritmo entre otras.

## Division

> ![python](https://github.com/psmaniac/CP01/blob/master/lesson01/02_extra_operations/div.jpg)

En la division se tiene varias partes las cuales python nos facilita en obtener el resultado de estas, para diferentes propositos.

### Cociente de una division

El cociente de una division es la parte entera del resultado de la division, en Python se calcula con el operador // el cual nos devolvera  un valor entero sin decimales.

Ejemplo

  > 1545 // 15\
  > 103
  
  > 51 // 7\
  > 7

### Resto de la division

Esta es una de las funciones mas llamativas en programacion ya que muchos algoritmos trabajan con el resto de las divisiones, en Python se calcula mediante el operador %, al igual que el cociente este nos devolvera un valor entero sin decimales.

Ejemplo

  > 1545 % 15\
  > 0
  
  > 51 % 7\
  > 2

### Funcion integrada divmod()

Esta funcion tiene como parametros dos datos, el dividendo y el divisor, separados por una coma, esta funcion devuelve una dupla el cual es el cociente y el resto.

Ejemplo

  > divmod(1545, 15)\
  > (103, 0)
  
  > divmod(51, 7)\
  > (7, 2)
  
## Potencia y Raiz

> ![python](https://github.com/psmaniac/CP01/blob/master/lesson01/02_extra_operations/potencia.png)

Hay una relacion muy estrecha entre la potencia enesima y la raiz enesima de una variable, la raiz enesima de una variable es la inversa de la potencia enesima de la misma variable, esto nos indica que si queremos hallar la raiz cuadrada de un numero simplemente tenemos que elevarlo a 1/2 o su equivalente 0.5, en Python para calcular la potencia se tiene al siguiente operador ** el cual nos devolvera el resultado de la potencia.

Ejemplo potencia

  > 2 ** 5\
  > 32
  
  > 6 ** 4\
  > 1296
  
 Ejemplo raiz

  > 25 ** 0.5  o  25 ** (1/2)\
  > 5
  
  > 729 ** (1/3)\
  > 9
  
### Funcion de potencia
  
Esta funcion realiza lo mismo que el operador ** , el cual nos devuelve la potencia del primer valor con respecto al segundo. En Python se tiene esta funcion como pow().

Ejemplo

  > pow(2, 5)\
  > 32
  
  > pow(25, 0.5)  o  pow(25, (1/2))\
  > 5
  
### Ejercicios 

Abrir el archivo [README.md](https://github.com/psmaniac/CP01/blob/master/lesson01/02_extra_operations/Exercices/README.md) de la carpeta de ejercicios y realizar los ejercicios que indican cada uno, realizar los ejercicios en [Repl.it](https://repl.it/) usando Python como lenguaje.
