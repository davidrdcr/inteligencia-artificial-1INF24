
**Método Hill-Climbing**
Llega a un lugar, si sus vecinos son peores, se estanca ahí. Es codicioso. 

**Método Stochastic hill-climbing**
Escoje **aleatoriamente** el sucesor con probabilidad proporcional al aumento de la función objetivo. 

**Método Random-restart hill-climbing**
Ejecuta varias búsquedas a partir de varios estados iniciales escogidos aleatoriamente. 

**Método Simulated Annealing**
Combina hill-climbing con caminos aleatorios.
Tenemos el problema y una función de schedule. La función de schedule es la temperatura. La temperatura está relacionado con qué tan probable es que escojamos vecinos malos. A medida que va avanzando es menos probable de que acepte vecinos malos. Ese decaimiento nosotros elegimos.
Primero generamos un nodo inicial. Si la temperatura es igual a cero, retorna lo que tiene. Escoje un sucesor aleatorio. Sin necesidad de crear un vecindario. Revisa su función objetivo, si el next tiene una función objetivo, Entonces el next se vuelve el current.

**Algoritmos bioinspirados**

 - Particle Swarm Optimization: Conjunto de técnicas inspiradas en el comportamiento social de bandadas de aves, banco de peces y otros. 
 
 - Artificial Bee Colony: Conj
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTk1NDA3NjE4NSwtNjAyMTQ2NzExXX0=
-->