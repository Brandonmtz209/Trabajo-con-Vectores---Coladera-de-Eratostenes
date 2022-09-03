# Trabajo-con-Vectores---Coladera-de-Eratostenes
La coladera de Eratóstenes) Un entero primo es cualquier entero que es divisible sólo entre él mismo y
entre 1 La coladera de Eratóstenes es un método para encontrar números primos. Opera como sigue:
    a) Cree un arreglo con todos los elementos inicializados a 1 (verdadero). Los elementos del arreglo que
      tengan subíndices primos permanecerán en 1. Los demás elementos del arreglo en algún momento
      se establecerán a cero.
    b) Comenzando por el subíndice 2 (el subíndice 1 debe ser primo), cada vez que se encuentre un ele-
      mento del arreglo que sea 1, haga un ciclo por el resto del arreglo y establezca a cero todos los
      elementos cuyo subíndice sea un múltiplo de dicho subíndice. Para el subíndice 2, todos los elemen-
      tos por encima de 2 que sean múltiplos de 2 se establecerán a cero (los subíndices 4, 6, 8, 10, etc.);
      en el caso del subíndice 3, todos los elementos por encima de 3 que sean múltiplos de 3 se establece-
      rán a cero (subíndices 6, 9, 12, 15, etc.); y así sucesivamente.
Terminado este proceso, los elementos del arreglo que aún estén establecidos a 1 indicarán que el subíndice es un
número primo, así que podrán imprimirse. Escriba un programa con un arreglo de 1000 elementos que determine
e imprima los números primos entre 1 y 999. Ignore el elemento O del arreglo.
