# 📊 Entregable 1: Análisis de Complejidad Algorítmica

## Tabla Comparativa de Complejidades

| Complejidad | Analogía Personal | Patrón de Código | Situación en Software Real |
| :--- | :--- | :--- | :--- |
| **O(1)** | Tomar un chocolate de una caja sabiendo su posición exacta. | Acceso directo por índice: `lista[5]` | Consultar si un usuario está conectado por su ID. |
| **O(log n)** | Buscar un nombre en una agenda física abriéndola a la mitad. | División sucesiva (Búsqueda binaria). | Buscar un producto en un catálogo ordenado. |
| **O(n)** | Leer una lista de súper de arriba a abajo. | Un solo ciclo `for`. | Calcular el total de una factura. |
| **O(n log n)** | Organizar libros dividiéndolos en grupos y luego mezclándolos. | Dividir y mezclar (Merge Sort). | El ordenamiento de datos en Excel. |
| **O(n²)** | 10 personas intercambiando tarjetas entre todas. | Ciclos anidados (`for` dentro de `for`). | **El error de Daniel:** Comparar todo contra todo. |
| **O(2ⁿ)** | Probar todas las combinaciones de un candado. | Recursión doble. | Ataques de fuerza bruta a contraseñas. |

---

## 🧠 Reflexión
**¿Cuál fue la analogía que más te ayudó a entender y por qué?**

La analogía de **la fiesta de los desconocidos (O(n²))** fue la más clara. Explica por qué el sistema de DataStream Inc. colapsó: al duplicar los datos, el trabajo no se duplicó, sino que se elevó al cuadrado, haciendo que el hardware fuera irrelevante ante la ineficiencia del código.
