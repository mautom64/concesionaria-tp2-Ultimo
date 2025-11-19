# concesionaria-tp2-Ultimo
Este proyecto es una aplicación desarrollada en Java, utilizando Spring Boot, Maven y Lombok, pensada para manejar de forma simple una lista de vehículos dentro de una concesionaria. Permite cargar autos y motos, mostrarlos, buscar modelos y ordenarlos según distintos criterios.

La aplicación cuenta con una interfaz que define las acciones principales del sistema y una clase encargada de administrar la lista de vehículos. Desde ahí se pueden agregar vehículos nuevos, mostrar el listado completo, identificar el más caro y el más barato, buscar modelos que contengan una letra o palabra específica y ordenar los vehículos por precio o por un orden natural ya definido.

Para procesar los datos, se utiliza la API de Streams, que facilita tareas como filtrar, buscar y ordenar información. También se emplea un TreeSet cuando se necesita obtener la lista ordenada automáticamente. Lombok ayuda a mantener el código más limpio generando automáticamente métodos como getters, setters y toString.

El orden natural de los vehículos está dado por el método compareTo, donde se compara primero la marca, luego el modelo y, si ambos coinciden, el precio. Esto permite que los vehículos puedan ordenarse automáticamente en estructuras como TreeSet o mediante el propio método de ordenamiento natural del proyecto.
