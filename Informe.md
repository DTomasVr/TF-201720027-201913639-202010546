# Informe Trabajo Final 
### Complejidad Algoritmica

### Alumnos
- Palacios Jauregui, Kalid.
- Postigo Tuesta, Enrique Daniel.
- Villafuerte Ramirez, Diego Tomas.

### Profesor
- Canaval Sanchez, Luis Martin

### Ciclo
2022-01

## Introducción
En el siguiente informe se detallara la elaboracion de una representacion de un distrito de la ciudad de Lima, más especificamente el distrito de Miraflores y sus alrededores, como un grafo.
Partiendo de esta base añadiremos valores a los pesas de las aristas, considerando su localización y el  posible tráfico de la zona considerando la hora.
Para la elaboracion de este trabajo se tuvieron en cuenta varias herramientas practicadas en clase por ejemplo el caso de:
 ###### Djisktra
  >Sirve para encontrar el Page 2 camino de coste mínimo desde un nodo origen a todos los demás nodos del grafo
 ##### Breadth First Search or BFS
  >Algoritmo de búsqueda para lo cual recorre los nodos de un grafo, comenzando en la raíz (eligiendo algún nodo como elemento raíz en el caso de un grafo), para          luego explorar todos los vecinos de este nodo
 ##### Iterative Deepening Search(IDS) 
   >Es una estrategia iterativa de búsqueda de gráficos que aprovecha la integridad de la estrategia Breadth-First Search (BFS) pero usa mucha menos memoria en cada      iteración (similar a la búsqueda en profundidad)
 
## Elaboración

>Para poder realizar la representacion del distrito de miraflores y sus respectivas intersecciones, primero se tuvo que delimitar el area trabajada, luego la digitación de las calles que se encuentran en esta area, y por ultimo realizar la lista de Adyaciencia de las intersecciones, todo se trabajo en Archivos .Txt como se ha venido trabajando a lo largo del ciclo.
>Luego de obtener todos estos datos manualemente se tuvo que hayar cada cordenada, es por eso que se utilizó la libreria geopy para luego transformarlas con una funcion posterior a coordenadas X,Y
 
 ## Interfaz Grafica
 
 Despues de recibir la asesoria del profesor para poder realizar esta interfaz, asi mismo la graficación de los nodos, se utilizó la carpeta brindada "tfbase"
 
 ## Conclusiones
  
>La divison de trabajo y un trabajo organizado con tareas designadas para cada uno es muy importante para trabajos de este tipo que almacenan cantidades         significativas de datos
>Despues de implementar el algoritmo de Perlin Noise se puede resumir que para lo buscado (Simular trafico en las calles)
>Los algoritmos aprendidos, durante el ciclo (-djisktra,implementacion de bfs,implementacion de ids)
