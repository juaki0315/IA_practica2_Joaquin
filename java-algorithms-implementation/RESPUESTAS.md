1. ¿Qué variable representa la lista ABIERTA?

    La lista abierta en la clase AStar está representada por la variable OpenSet que almacena los posible candidatos que  seran evaluados.

2. ¿Qué variable representa la función g?

    La funcion g esta representada por la variable gScore que recoge el coste desde el comienzo hasta el final del mejor cmaino

3. ¿Qué variable representa la función f?

    La funcion f esta representada por la variable fScore que recoge el coste desde cualquier punto dado hasta el destino. 

4. ¿Qué método habría que modificar para que la heurística representara la distancia aérea entre vértices?

    Habría que modificar el metodo heuristicCostEstimate() ya que este actualmente solo devuelve 1. 

5. ¿Realiza este método reevaluación de nudos cuando se encuentra una nueva ruta a un determinado vértice? Justifique la   respuesta.

    El método que realiza la reevaluacion con nuevas rutas es compare(), que compara los costes de fScore.