# Variables

### Definicion
Una variable en programacion es un objeto con un nombre al cual se le asigna un valor el cual puede ser modificado durante la ejecucion del programa.

Para definir una variable se tiene el operador de igualdad = , a la izquierda se pone el nombre de la variable y a la derecha el valor de este. En Python las variables se crear al momento en el cual se asigna su valor por primera vez.

Ejemplo

> x = 123\
> y = 456\
> z = "Hello world"

### Restricciones al definir variable 

En Python como en la mayoria de lenguajes de programacion se tiene con palabras o caracteres reservados que usa el lenguaje, por ejemplo los signos de operacion asi como nombres de funciones numeros represantativos de un valor o palabras com if, TRUE, etc. Estos caracteres o conjunto de caracteres se denominan palabras reservadas del lenguaje los cuales no se pueden usar como nombre de una variable, ya que daria error tratando de ejecutar la accion de la palabra y no asi como el valor de la variable.

Ejemplo

> 125 = 10 //ERROR, El programa tratara de encontrar la igualdad entre estos dos numeros\
> print()= 10 //ERROR, El programa no acepta signos para nombrar una variable\
> 21x = 10 //ERROR, No se puede iniciar el nombre de una variable con numeros\
> while = 10 //ERROR, Es una palabra reservada de Python

### Nombrar variables Python

Para nombrar varaibles en Python se puede usar los caracteres alfanumericos y el signo _ barra baja, siempre y cuando no viole las restriciones, Python podra diferenciar entre mayusculas y minusculas (key sensitive), podras usar numeros al nombrar variables siempre y cuando empieze por una letra.

Ejemplo

> var1 = 10\
> Var1 = 11\
> var2 = 12\
> var_3 = 13

> **Buenas Practicas**\
> Consejos para nombrar variables:
>    - Una variable tiene que ser entendible, es decir que el nombre tiene que tener relacion con el valor que contendra\
>      xyz = 1992 //Mal\
>      anio = 1992 //Bien
>    - Es mejor nombrar una variable larga entendible que una corta\
>      fechax = 1845 //Mal\
>      fechanacimiento = 1845 //Semi Bien\
>      alturay = 164 //Mal\
>      alturamujer = 164 //Semi Bien
>    - Evitar usar palabras iguales con diferencia en mayusculas\
>      fecha = 2015\
>      Fecha = 2018 // No es lo mismo que fecha lo cual puede producir una confuncion al usarla
>    - Se tiene dos formas practicas de escribir el nombre de una varaible compuesta:\
>      fechaNacimiento = 1985 //Bien\
>      fecha_nacimiento = 1985 //Bien\
>      alturaMujer = 164 //Bien\
>      altura_mujer = 164 //Bien
>    - No se pierde rendimento al usar mas caracteres al nombrar una variable, asi que si es necesario usar mas de dos palabras, se tiene que hacer.\
>      diferenciaHM = 15 //Mal\
>      diferencia_estatura_hombre_mujer = 15 //Bien\
>
>El nombrar variables depende de cada programador, estos son solo pautas de buenas practicas para que el trabajo del programador se mas facil, y que otros programadores puedan entender tu codigo, o tu mismo puedes entenderlo, asi que no es obligatorio seguir estas pautas.
