# Analisis noSQL JuanJ
## NoSQL vs. SQL: ¿Por qué un modelo de documentos como MongoDB es más adecuado para el "Bestiario Digital" que un modelo relacional estricto como el que usaste en la tarea anterior? 

Para actividades donde no sea necesario tener un entorno tan delimitado por reglas yo prefiriria realizar uso de mongodb debido a que este es mas flexible con sus datos debido a que la creacion de estas es mas rapida y no toca especificar el valor de cada uno a no ser casos concretos siendo que para este bestiario es bastante util para las relaciones que tienen con los valores de tipo array que pueden contener multiples valores y no tenemos que realizar otra tabla con su conexion para este mismo funcionamiento como seria en una base de datos SQL.

## Tipos de NoSQL: MongoDB es una base de datos orientada a documentos. Investiga y describe brevemente otro tipo de base de datos NoSQL (ej: Clave-Valor, Columnar, Grafo) y propón un escenario donde ese tipo sería más útil que MongoDB.

Una de estas bases de datos que seria mejor usar en vez de mongodb seria Graph DB el cual es una BD de grafos que almacenan nodos y aristas con propiedades, optimizadas para consultas de relaciones y recorridos (traversals). Siendo que esta enfocado a grafos seria erroneo usar otra BD noSQL que no sea este para actividades que sean con Grafos.

## Casos de Estudio: Basándote en el material de referencia y tu propia investigación, menciona una aplicación del mundo real (ej: una red social, una plataforma de e-commerce) que utilice MongoDB y explica por qué su elección fue acertada.

En mi caso una aplicacion de esto podria ser alguna pagina web que se quiera almacenar la informacion de los usuarios para la configuracion de su perfil unicamente debido a que este no va a tener mayor utilidad que guardar su informacion personal y presentarla en la pagina algo asi como alguna red social o Blog.