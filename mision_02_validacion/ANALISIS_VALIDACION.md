# Validación: ¿Por qué es preferible implementar la validación de datos a nivel de Base de Datos (con JSON Schema) en lugar de hacerlo únicamente en el código de la aplicación (backend)?
Esto es asi debido a que permite tener documentado en un archivo mas corto de lineas la infomacion de las validaciones de esta manera ya se tiene un archivo especifico donde se pueda revisar estos valores, en caso de hacerlo solo en la aplicacion puede llegar a ser un poco dificultoso en caso de perdida de los datos saber como estaba compuesto la coleccion.

# Relaciones 1-a-1: Explicaste la ficha_veterinaria como una relación 1-a-1 embebida. ¿Por qué crees que este fue un buen enfoque? ¿Bajo qué circunstancias hubieras preferido modelarla como referenciada (en su propia colección)?
Para la primera pregunta pienso que fue un buen enfoque debido a que no es mucha informacion la que pide ademas que evita llamar a otras colecciones o tener que vincularlas y prefiriria unicamente ponerla en su propia coleccion en un posible caso que multiples colecciones requieran esa informacion porque hay no se deberia llamar al de criaturas sino al de la ficha veterinaria en un posible caso de que haya un registro en otra coleccion de veterinaria.

# Relaciones 1-a-N: En tu modelo, usaste dos tipos de relaciones 1-a-N:

## Guardián -> Inventario (Embebida)
## Guardián -> Criaturas (Referenciada) 

# Justifica por qué cada decisión de modelado (embebida vs. referenciada) fue la correcta para cada caso.
En el caso de inventario este era necesario debido a que viendo que un inventario es algo unico del usuario este debe de tenerlo en su propia coleccion, en cambio las criaturas como son entidades independientes con sus propios valores este se le trabaja mejor referenciada ademas que trabaja bajo el id unico.