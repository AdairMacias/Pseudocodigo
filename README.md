# Pseudocodigo


#### Procedimiento: **Determinar el mayor de dos números (n1, n2)**
*Entrada:*
- n1 y n2 = Números arbitrarios

*Salida:*
1. Comparar el primer número (n1) frente al segundo (n2).
2. Si n1 > n2, el mayor es n1.
3. Si n1 < n2, el mayor es n2.



#### Procedimiento: **Determinar el mayor de tres números (n1, n2, n3)**
*Entrada:* 
- n1, n2 y n3 = Números arbitarios 

*Salida:* 
1. Comparar el primer número (n1) frente al segundo (n2) y frente al tercero (n3).
2. Si n1 > n2 y n1 > n3 entonces el número mayor es n1
3. Si lo anterior no es correcto entonces tengo que comparar si n2 > n3, si se cumple esta condición entonces el número mayor es n2.
4. Si n2 < n3, el número mayor es n3.



#### Procedimiento: **Determinar si un número es primo o no (A, n y n1)**
*Entrada:*
- A = Arreglo
- n = Número de elementos dentro del arreglo
- n1 = Número escogido arbitrariamente

*Salida:*
1. Dividir el número escogido (n1) entre 2, si resulta ser par (a excepción del 2), n1 no es un número primo.
2. Dividimos el número n1 entre los números previos a él y si es divisible entre alguno, tampoco es un número primo, si no lo es, se trata de un número primo.



#### Procedimiento: **Determinar si dos cadenas son palíndromas (c1, c2, n)**
*Entrada:*
- c1 y c2 = cadenas
- n = Elementos de cada cadena

*Salida:* 
1. Comparar elemento por elemento de cada cadena.
2. Si un elemento difiere de otro, la cadena no es políndroma.
3. Si todos los elementos de la cadena son iguales, la cadena es políndroma.



#### Procedimiento: **Determinar si "ant" es una subcadena de "Se han establecido antecedentes desde el siglo XIX" (c, sc, esc, ec, cec)**
*Entrada:*
- c = Cadena
- sc  = Subcadena
- esc = Elementos de la subcadena
- ec = Elementos de la cadena

*Salida:*
1. Comparar los elementos de la subcadena con los elementos de la cadena.
2. Si los elementos de la subcadena no se encuentran al comienzo, recorrer un elemento de la cadena y repetir el paso anterior.
3. Detenerse hasta que los elementos de la subcadena estén en la cadena o, en su defecto, llegar al final de la cadena.
