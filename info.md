PILA
Una pila es una estructura de datos de entradas ordenadas que solo se pueden introducir y eliminar por un extremos, llamado cima.
ejemplo: control Z

COLAS
Una cola es una estructura de datos cuyos elementos mantienen un cierto orden, de tal modo que solo se pueden añadir elementos por un extremo: final de la cola, y eliminar o extraer por el otro extremo: llamado frente
ejemplo: para controlar el flujo

LISTA ENLAZADA
Una lista enlazada es una colección o secuencia de elemetos dispuestos uno detrás de otro, en la que cada elemento se conecta al siguente por un "enlace". La idea básica consiste en contruir una lista, cuyos elementos, llamados nodos, se dividen en 2 partes: La informacion (dato), y la referencia (enlace), que apunta al siguente. Esto permite eliminar espacios de la lista en vez de solo vaciarlos comparado a un arreglo normal.
tipos: Simplemente enlazadas (1 enlace), Doblemente enlazadas (2 enlaces), Circular Simplemente enlazada (El ultimo enlace referencia al primero. 1 enlace), y, Circular doblemente enlazada (El primer enlace le hacce referencia al ultimo, y el ultimo al primero. 2 enlaces)
  DECLARACION NODO
    class nodo
    {
      int dato;
      nodo enlace;
      public nodo(int t)
      {.                                                                
        dato = t;
        enlace = null;
      }
    }
