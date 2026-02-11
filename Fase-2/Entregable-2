                                  Tabla comparativa con los cálculos de operaciones para cada caso


A continuación, se demuestra la diferencia de rendimiento calculando el número aproximado de operaciones que realiza cada función para encontrar el objetivo.
======================================================================================================================================================
| Escenario (Tamaño n) | Posición del Objetivo | Operaciones Función A (O(n)) | Operaciones Función B (O(n^2))        | Impacto                     |
| Pequeño (n=100)      | Posición 50           | "51" operaciones             | \approx "5,051" operaciones           | 100 veces más lento         |
| Mediano (n=10,000)   | Posición 5,000        | 5,001 operaciones            | \approx "50,005,001" operaciones      | 10,000 veces más lento      |
| Masivo (n=1,000,000) | Última Posición       | 1,000,000 operaciones        | \approx 1,000,000,000,000" (1 Billón) | 1 Millón de veces más lento |
=====================================================================================================================================================


2. El Espejismo de la Funcionalidad.
Dos códigos pueden retornar el mismo resultado correcto ("funcionar") pero tener costos distintos. 
La Función B realiza un trabajo redundante al reiniciar un ciclo interno completo por cada elemento del ciclo externo. 

El peligro real es que, con pocos datos (ej. 100 elementos), la diferencia es de milisegundos y es imperceptible para el humano. 
Sin embargo, la complejidad matemática no perdona: al escalar a millones de datos, el crecimiento cuadrático transforma esos milisegundos en horas o días de procesamiento.
Un código que no escala es, en la práctica profesional, un código roto.


3. Propuesta de Detección en Código Real.
Para evitar que algoritmos ineficientes como la "Función B" lleguen a producción:

1.  **Code Review Estricto:** Buscar patrones de "bucles anidados" (`for` dentro de `for`) y exigir una justificación si recorren la misma colección de datos.
2.  **Pruebas de Estrés (Stress Testing):** No validar solo con 10 datos de prueba. Ejecutar tests automatizados con n=100,000 que fallen si la función tarda más de 200ms.
3.  **Análisis Estático:** Usar herramientas (linters) que alerten sobre complejidad ciclomática alta.

