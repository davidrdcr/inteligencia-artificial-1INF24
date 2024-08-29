
**Pasos para que un agente resuelva problemas**

**1. Formular el objetivo**

- asdsad

**2. Formulación del problema**

**- Estado inicial:** Es la situación inicial del problema.

**- Espacio de estados:** Es el conjunto de situaciones diferentes en el que puede estar el problema. El estado inicial, las acciones y el modelo de transición (función sucesor) determinan el espacio estados. El espacio estados puede estar representado con un grafo, donde los nodos representan estados y los arcos acciones.

**- Acciones:** Acciones que pueden ser realizadas desde un determinado estado s. Actions(s)

**- Modelo de transición:** Estados alcanzables desde un estado dado s con una determinada acción a. Se denota RESULTS(s, a)

**- Costo de camino:** Es una función que mide cuán costoso es un determinado camino para llegar a un nodo s desde el estado inicial g(s)

**3. Buscar la solución**
Encontrar la secuencia de acciones para llegar un objetivo

**5. Ejecutar la solución**

## EJEMPLOS

**Problema 1: Busqueda de ruta en mapa:**

AQUI VA LA IMAGEN PAGINA 7

**- Estados:** Todas las posibles ciudades son los estados
**- Estado inicial:** Ciudad de la que parto.
**- Acciones:** Moverse a  alguna ciudad vecina
**- Modelo de transición:** Mapa
**- Prueba de objetivo:** Verificar si se llegó a la ciudad objetivo.
**- Costo del camino:** Puede ser el tiempo, la distancia recorrida, etc.

**Problema 2: 8-puzzle:**

AQUI VA LA IMAGEN PAGINA 8

**- Estados:** Todas las configuraciones posibles de 8 números y un blanco.
**- Estado inicial:** Alguna configuración dada del puzzle. 
**- Acciones:** Movimientos del casillero blanco: Derecho, Izquierda, Arriba, abajo.
**- Modelo de transición:** NO ENTIENDO
**- Prueba de objetivo:** Verificar si el estado es el objetivo.
**- Costo del camino:** Cada acción cuesta 1. 

**Problema 3: 8-queens:**

AQUI VA LA IMAGEN PAGINA 8

**- Estados:** Vector de 8 números no repetidos (permutaciones). Cada elemento indica la fila en que se encuntra la reina en una columna.
**- Estado inicial:** Permutación aleatoria.
**- Acciones:** Intercambiar 2 elementos.
**- Modelo de transición:** NO ENTIENDO
**- Prueba de objetivo:** Verificar si la nueva permutación tiene reinas no atacadas. 
**- Costo del camino:** Cada acción cuesta 1. 




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5NTM3NDEzNDksLTExMzk0MDM4ODksLT
EyNjMxNjk4MjYsLTIwNDA4ODU5MzUsOTE4Nzg3MzQwLC0yMDQz
NTc4MzQ2LDEyMjU5Njg0OTgsLTEyNzQ3Nzg1MDksNDk3ODE4OD
EwXX0=
-->