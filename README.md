# COPA
COPA is programming language for maths. COPA es un lenguaje de programacion orientado a las matematicas.

COPA es un lenguaje de programacion creado para plasmar i ejecutar ecuaciones.
La sintaxis es muy simple pero el concepto sobre el que se basa es algo extraño pero entendible i muy util.
Este lenguaje de programacion es un experimento, no aseguro su perfecto desenpeño ni diseño, lo hice en solo 2 dias y otros 2 para retocar "script:" :).

SINTAXIS:
Es muy simple, la linea siempre se debe acabar con ":", doble punto.
Puedes ingresar 3 tipos de datos y luego escribir el valor, "n" numero, "$" variable, "c" comando son los tipos de datos
Eje: "n1 n2 c+:" -> 1 + 2

Las variables de convirten en el numero que almacenan.
Eje: (la variable 12, es igual a 3) "$12 n2 c-:" -> 3 - 2

Puedes poner tantos comandos quieras.
Eje: "n1 n2 c+ c1>0 n3 c-:" -> ( 1 + 2 ) - 3

En este lenguaje se usan las lineas, que son como stacks en los que puedes poner datos i sacarlos, las operaciones siempre sogen los datos de la linea de trabajo 0 i el resultado en la 1.

No confundir las lineas en si que pueden ser como por ejemplo 5, con las lineas de trabajo, LTA, que son las que de todas las existentes nosotros elegimos como las LTA0 y LTA1.

Luego esta el punto, vamos que el punto en el que estamos en la linea o stack.

las variables son variables normales, cada una con un numero.

los numeros binarios es decir, 0 o 1, son en realidad n%2, donde n=ElNumero.

Comandos existentes:

"+" la suma, normal 

"-" la resta, normal

"*" la multiplicacion, normal

"/" la division, normal

"%" el resto de la division, normal

"n=" si dos numeros son iguales

"b=" si dos numeros binarios son iguales

"<" menor<mayor, resultado 0 o 1

">" mayor>menor, resultado 0 o 1

"<=" menor o igual

">=" mayor o igual

"and"

"or"

"xor"

"not"

"var" "n1 n2 cvar :" n1:el dato a poner en la variable n2:variable a poner los datos

"0>1" mover un numero de la LTA0 a LTA1

"1>0" mover un numero de la LTA1 a LTA0

"rm0" elimina un numero en la LTA0

"rm1" elimina un numero en la LTA1

"cp0" duplica un numero de en la LTA0

"cp1" duplica un numero de en la LTA1

"if" si el numero binario es 1 permitira ejecutar el comando posterior, si es 0 para la ejecucion de esa linea.

"cc" es para refrescar sin hacer nada

"script" para ejecutar un script de copa (script.copa), se indiga solo en nombre "script", automaticamente pone el ".copa"

"conf" para abrir la configuracio, es guiada no es nada compleja, el resto de la configuracion esta editando el archivo copaconf.conf

"exit" para salir del programa




