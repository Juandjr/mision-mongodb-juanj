# mision-mongodb-juanj

## Juan David Jiménez Romero

En esta actividad se realizo un bestiario digital el cual contiene la actividad en CRUD para la creacion del mismo como el ingreso de los datos y su busqueda, esto realizado por medio de MongoDB,
dado a que un bestiario es un libro donde se almacena la informacion de bestias/criaturas que un aventurero se vaya cruzando o que se tengan registros permitiendo tener un conocimiento de antemano sobre la criatura.

# Uso de los archivos

Para su uso se debe tener dentro de VSCode la extension de MongoDB para que al momento de abrir el archivo podamos ejecutarlo mediante el boton de ejecutar una vez que se tenga ingresado dentro de la base de datos de Mongo Atlas.

## crear_bd.mongodb

Al abrir el archivo (crear_bd.mongodb) aparecera dentro de la pestaña una opcion de play el cual al ejecutarse va a crear la base de datos "Bestiario" junto con la coleccion de "criaturas" que tiene un valor de "nivel_peligro" establecido de manera numerica con max y min.

## insertar_criaturas.mongodb

Al ejecutar el archivo (insertar_criaturas.mongodb) va a ingresar un registro por medio de db.criaturas.insertOne() y a continuacion va a ingresar otros 5 registros por medio de la funcion db.criaturas.insertMany() pero en caso de querer ejecutar unicamente un de las 2 funciones debe seleccionar todas las lineas de codigo que contenga la funcion junto al "use('bestiario')".

## read_criaturas.mongodb

En el momento de correr el archivo (read_criaturas.mongodb) este va a ejecutar todas las funciones, al igual que en insertar podemos unicamente ejecutar una funcion seleccionando la funcion que queramos ejecutar y al correr el archivo este mostrara la informacion.

## update_criaturas.mongodb

Al ejecutar el archivo (update_criaturas.mongodb) este va a agregar una habilidad a las criaturas que tengan el nombre de "Balatro" y otra funcion que permite aumentar en 1 el "nivel_peligro" de multiples criaturas que compartan un habitad. 
