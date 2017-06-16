## Proyecto-FADA
## Punto 1
# Solucion Ingenua
Tiene complejidad de O(2^n*n), es un arbolo con 2^n nodos y en cada nodo hace 2n iteracciones por lo que tenemos algo de la forma
2*(2^n)*n que es igual a O(2^n*n)  
# Solucion Voraz
Tiene complejidad de O(n logn) debido al metodo de ordenamiento, la parte en la que seleccionamos los procesos se ejecuta en n, no es optimo para todos los casos  
# Solucion Dinamica
Tiene complejida de O(n^2), la primer parte es ordenar de acuerdo a la hora de inicio, la segunda parte es recorrer todos los procesos "i" y ver cuál es mejor proceso elegido con anterioridad "j" para concatenar la solucion de j con i.  
## Punto 2
# Solucion Ingenua  
Complejidad desconocida
# Solucion Dinamica  
Complejidad O(m^2*n) donde m es igual a la cantidad de libros y n igual a la cantidad de escritores.
