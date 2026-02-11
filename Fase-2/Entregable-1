
 Fragmento 1:
   =================================================
   |Función verificar_estatus(transaccion):
   |tasa = 0.02
   |monto_final = transaccion['monto'] * (1 + tasa)
   |RETORNAR monto_final > 1000
   =================================================

        Hipotesis: O(1).
            -Razonamiento: Se aplican operaciones secuenciales (Regla 1).
             No existen ciclos ni recursión. El tiempo de ejecución es constante e independiente del tamaño de la entrada.
                 -Conclusión: O(1) Constante.

 Fragmento 2: 
   ===================================================
   |Función buscar(lista, objetivo):
   |Para cada elemento en lista:
   |     SI elemento == objetivo: RETORNAR Verdadero
   ===================================================

          -Hipotesis: O(n)
              -Razonamiento: Existe un loop simple que recorre la lista de principio a fin, se realizan "n" comparaciones.
                    -Conclusión: O(n) Lineal.

 Fragmento 3:
   ===================================================
   |Para cada i en lista:
   |Para cada j en lista:
   |     SI i != j Y lista[i] == lista[j]: Duplicado()
   ===================================================

          -Hipotesis: O(n^2).
              -Razonamiento: Aplicamos la Regla 2 de Operaciones Anidadas. Un ciclo de "n" iteraciones contiene otro ciclo de "n" iteraciones. n x n = n^2
                    -Conclusion:  O(n^2) Cuadrática.

 Fragmento 4:
   ________________
  | mientras n > 1:
  | n = n / 2
  |imprimir(n)
  -----------------

          -Hipotesis:  O(\log n).
               -Razonamiento: Aplicamos la Regla 4 de division repetida. El tamaño del problema se reduce a la mitad en cada iteración.
                     -Conclusion: O(\log n) Logarítmica.

Fragmento 5:
   __________________________________
  | Para cada x en lista: imprimir(x)
  | Para cada y en lista: imprimir(y)
  -----------------------------------

          -Hipotesis:Parecía O(n^2) por ver dos loops.
                -Razonamiento: Aplicamos la Regla 1 de la Suma. Los loops no están anidados, sino uno tras otro. O(n) + O(n) = O(2n). Por la Regla 3, ignoramos la constante 2.
                      -Conclusion: O(n) Lineal.

Fragmento 6:
    ________________________
    |Para cada i en lista:
    |j = n
    |mientras j > 1:
    |    j = j / 2
    ________________________

          -Hipotesis: O(n \log n)
                -Razonamiento: El ciclo interno reduce "j" a la mitad en cada paso, lo cual es O(\log n).
                      -Conclusion: O(n \log n) Linealítmica

