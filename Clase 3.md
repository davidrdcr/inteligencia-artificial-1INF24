
**Método Hill-Climbing**
Llega a un lugar, si sus vecinos son peores, se estanca ahí. Es codicioso. 

**Método Stochastic hill-climbing**
Escoje **aleatoriamente** el sucesor con probabilidad proporcional al aumento de la función objetivo. 

**Método Random-restart hill-climbing**
Ejecuta varias búsquedas a partir de varios estados iniciales escogidos aleatoriamente. 

**Método Simulated Annealing** Toman este 
Combina hill-climbing con caminos aleatorios.
Tenemos el problema y una función de schedule. La función de schedule es la temperatura. La temperatura está relacionado con qué tan probable es que escojamos vecinos malos. A medida que va avanzando es menos probable de que acepte vecinos malos. Ese decaimiento nosotros elegimos.
Primero generamos un nodo inicial. Si la temperatura es igual a cero, retorna lo que tiene. Escoje un sucesor aleatorio. Sin necesidad de crear un vecindario. Revisa su función objetivo, si el next tiene una función objetivo, Entonces el next se vuelve el current.

Temperatura inicial:
Factor de decaimiento de temperatura:
Máximo número de iteraciones maxlter:















**Algoritmos bioinspirados**

 - Particle Swarm Optimization: Conjunto de técnicas inspiradas en el comportamiento social de bandadas de aves, banco de peces y otros. 
 
 - Artificial Bee Colony: Conjunto de técnicas inspiradas por las actividades de una colonia de abejas. 
 
 Se optimiza la ubicación de las partículas 














 - Ant colony Optimization: Conjunto de técnicas inspiradas por las actividades de una colonia de hormigas.

Amplitud: Se busca la solución más cercana. Lo primero que se pierde acá es la memoria.  

Search problem tenía tres métodos (Resolve, Search_action, Goal_test). Con eso hacía la expanción de todo el árbol. 
G(n) costo del camino. En el arbol, todo nodo tiene una única ruta hacia la raíz. Si hay grafo tiene una sola 

La heurística mide el costo para llegar al objetivo. Si es cero, es porque ya llegué al objetivo.


No todas las heurísticas sirven.
Búsqueda en grafos.

¿Qué nodo de la frontera visito?. El que tenga menos función de evaluación.

Si f(n) = g(n), búsqueda de costo uniforme. 

h(n) = es estimado. Búsqueda voraz, codiciosa.

La búsqueda codiciosa expande el nodo en la frontera con menor h(n), o sea, el que parece que está más próximo al objetivo de acuerdo a la función heurística.

Algoritmo óptimamente eficiente: No hay otro mejor. 

Perdemos garantía de optimalidad. Podría haber un camino más corto. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExNjk5MzI3NjUsLTE5NjgzMDgxNjcsOD
Y2Njk0MjI2LC0xNTAzOTIzOTQyLC0xMzY5MTY2ODA4LC0zMjQ5
MDQwODgsMTYxNzc5OTk5MCwtNjAyMTQ2NzExXX0=
-->