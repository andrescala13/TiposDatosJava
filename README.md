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
* Accesible desde otras instancias de clase
* Su ciclo de vida termina cuando no se necesita mas
* Mientras exista al menos una referencia activa en la zona de datos esta se mantendrá.
* Tan pronto cuando no hayan mas referencias, la zona se considera no utilizada y se procede a su destrucción por parte del Garbage Collector.
* Un tipo referenciado puede no referenciar nada -> null 
* new: instanciación de una clase. Reserva una dirección de un área de memoria.

### Variable de referencia
* Caracteriza una instancia de clase , es decir la dirección donde esta el objeto.
* Contiene la direccion de un objeto, cuyo valor por defecto es null.
* Durante una prueba e igualdad entre dos variables por referencia, son las direcciones de los objetos que se compara, y no el contenido de los objetos en si mismos.
* Cuando se usa una referencia como argumento de un método es la direccion del obejto lo que se pasa, y no el objeto en si mismo.
