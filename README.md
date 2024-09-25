# Parcial1DS
## Daniel Rojas Groihs-1010117986
PREGUNTA 1
1. Si el vector funcionará como un arreglo estático, al alcanzar su capacidad máxima e intentar agregar un nuevo elemento, no habría espacio disponible en la memoria asignada. Entonces para continuar almacenando elementos, el vector asigna un nuevo bloque de memoria más grande y copia los elementos existentes a esta nueva ubicación.
   Al reservar un espacio de memoria desde un principio, sería poco eficiente ya que se podría desperdiciar memoria si no se utiliza, además de que manejar varias ubicaciones de memoria llegaría a complicar la implementación. Si se separara un espacio fijo en la memoria para futuros elementos podría causar que la memoria no se utilice de forma útil. Con el resize, se ajusta el tamaño del vector dependiendo de las necesidades reales.
2. El vector es más eficiente que la lista, pero en ciertos casos. Un vector permite acceso rápido a los elementos, ya que están almacenados en memoria adyacente. Pero la lista será más eficiente en casos en los que se necesite realizar una inserción o eliminación de elementos, porque permitirá utilizar punteros al nodo que se necesite, pero para acceder a cierto elemento será más complicado porque primero deberá recorrer toda la lista; aunque la lista requiere más memoria debido a que se utiliza un puntero adicional por cada nodo.
