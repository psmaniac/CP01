# Operaciones logicas y binarias

Como se menciono en la leccion anterior los datos booleanos son datos que pueden tener dos valores True y False que indica el valor logico al evaluar una expresion, estos valores se identifica como:

> True: Verdadero, 1\
> False: Falso, 0

En Python tambien se tiene la palabra reservada not el cual invierte el valor booleano.\

Los elementos que dan valores False en Python son: None, 0 (Entero o flotante), False, Variables en forma de colecciones vacias (Tuplas, Listas, Cadenas y Diccionarios) y otros que veremos mas adelante.

## Operaciones logicas de comparacion

En general se tiene seis operadores de comparacion en Pyhton las cuales son:

  * \>   (mayor que)
  * \>=  (mayor igual que)
  * <   (menor que)
  * <=  (menor igual que)
  * ==  (igual que)
  * !=  (diferente que)

En todos los casos nos devolvera una respuesta como True y False.

Ejemplos

> 8 > 4               //True\
> 10 < 45             //False\
> 9 == 9              //True\
> 'Hello' == 'Hello'  //True\
> 5 > 5               //False\
> 5 >= 5              //True\
> \[5, 6, 4] == \[5, 6, 4] //True
> \[5, 6, 4] == \[5, 4, 6] //False

## Operaciones de evaluacion logica

Las operaciones de evaluacion son and y or las cuales evaluan sentecias de True y False tambien se encuentra la expresion not el cual devuelve la inversa de la sentencia.

