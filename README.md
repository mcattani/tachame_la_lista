# Tachame la Lista!

Se trata de un programa del estilo *to-do list* (lista de tareas) que escribí para una amiga que estaba buscando una app muy simple para gestionar tareas. 

La información se almacena en una base de datos **sqlite3**  que consta de 4 campos:

1. **ID**: Único por cada entrada.
2. **"Completado"**:  Que es un valor booleano (verdadero/falso) para indicar si el elemento de la lista ha sido completado o no. 
3. **Título**: Nombre que le asignamos a la tarea.
4. **Contenido**: Dentro de cada tarea se puede guardar más información. Por ejemplo si agregamos una tarea que sea *"Ir al supermercado"* podemos además agregar información respecto de la compra que tenemos que hacer. Si la entrada posee "contenido" el mismo aparecerá en un panel lateral al hacer click sobre la tarea. 

Se reproducen sonidos cada vez que una ítem de la lista se marca como "realizado" y también cuando se completa la lista entera o se borran todos los elementos.

Más información en: [https://thenerdyapprentice.blogspot.com/](https://thenerdyapprentice.blogspot.com/) 