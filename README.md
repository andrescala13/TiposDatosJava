# TIPOS DE DATOS EN JAVA

## JVM (Java Virtual Machine)

* Realice una gestion eficiente de la memoria.
* Distribuye la memoria en dos zonas: stack(pila) y heap(montón)

![RAM](/modelo/ram.jpeg "RAM") 

### Stack
* Se almacenan variables locales, llamadas a metodos(parametros y resultados), variables primitivas, referencias a objetos del heap.
* Memoria estática.

### Heap
* Gestionado por el Garbage Collector
* Espacio de memoria en tiempo de ejecucion donde se registran los objetos.
* Memoria dinamica.
* No posee estructura de asignacion de espacios.

### Variable
* Contenedor de memoria donde se almacena informacion.
* En java se declara con un tipo que se conservara durante todo su ciclo de vida en el interior de la app.
* La variable debe tener un nombre.
* Existen de tipo primitivo y referenciado.


## PRIMITIVOS
* Contenedores de tamaño especifico que almacenan valores y no tienen metodos.
* Ejemplos: bolean, char, byte, short, long, float, double.

### REFERENCIADOS
* Almacenan las referencias a los datos.
* Estos datos se escriben en una zona de memoria llamada heap.