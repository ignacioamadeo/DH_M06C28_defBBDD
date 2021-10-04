1º : Definición de las relaciones y 5 ejemplos de c/u (uno a uno / uno a muchos / muchos a muchos):

Un registro es un conjunto de datos singulares que representan un valor de cada atributo en una misma entidad o “tabla”. Sería lo que es una “fila” de datos en excel.

+ Un tipo de relación 1 a 1 significa que por cada registro en 1 entidad, sólo existe 1 registro en otra entidad.

Ejemplos 1 a 1:

1) Un listado de personas (nombre, apellido, dni) vinculado a vestimentas que llevan puestas (tipo de remera, color, talle, tipo de pantalón, marca de zapatillas).
2) Un listado de tipos de edificios construidos (cantidad de pisos, altura, cantidad de departamentos) vinculado a sus terrenos (superficie de terreno, valor, ubicación).
3) Un listado de personas (nombre, apellido, dni) vinculado a permisos únicos de circulación por COVID (número de permiso, tipo de permiso).
4) Un listado de países (nombre, población) vinculado a datos de posicionamiento geográfico (latitud, longitud).
5) Un listado de estudiantes (nombre, apellido, dni) vinculado a legajo estudiantil (número de legajo, anotaciones).

+ Un tipo de relación 1 a muchos refiere a que 1 registro de una entidad puede relacionarse con varios registros de otra.

Ejemplos 1 a muchos:

1) Personas propietarias de un vehículo (nombre, apellido, dni) y registro automotor (patente, número de motor, chasis). Una persona puede ser propietaria de más de 1 vehículo. 1 vehículo sólo puede tener 1 propietario.
2) Un listado de pacientes (nombre, apellido, dni) vinculado a turnos con médicos (tipo de especialidad, horario, lugar). Un paciente puede tener más de 1 turno. 1 médico sólo puede atender a 1 persona por turno.
3) Sistema de venta de entradas a recitales online: 1 persona (nombre, apellido, dni) vinculada a entradas de diferentes shows (número de asiento, nombre de show). Una persona puede tener más de 1 entrada. Cada entrada sólo puede tener 1 persona propietaria.
4) Persona (nombre, apellido, dni) con productos de un carrito de compras (número de stock de producto, tipo de producto, nombre de producto). Una persona puede tener varios productos en el carrito, pero un producto (entendido como número de stock) sólo puede tener 1 persona.
5) Listado de domicilios (calle, altura) y personas con domicilio real en ellas (nombre, apellido, dni). 1 domicilio puede tener varias personas pero 1 persona solo puede tener 1 domicilio real en el DNI.

+ Un tipo de relación muchos a muchos refiere a que pueden haber varios registros de una entidad vinculados a otros varios registros en otra entidad.

Ejemplos muchos a muchos:
1) Un listado de países (nombre, población, localización) vinculado a tipos de religión principal que posee.
2) Un listado de personas (nombre, apellido, dni) a suscripciones (servicio, costo, modo de pago).
3) Un listado de animales (especie, tipo, color) a países del mundo (nombre, población, localización).
4) Un listado de personas (nombre, apellido, dni) vinculado a modelos de vehículos (color, marca, año de fabricación).
5) Una encuesta: un listado de personas (edad, género) vinculado a una tipificación de una respuesta de una encuesta. 

2º : Investigar que es un SGBD (cuales son los mas famosos)

Un Sistema de Gestión de Bases de Datos es una interfaz que permite visualizar y manipular la información ordenada contenida en una o más bases de datos y sus relaciones. Esto se puede realizar mediante diferentes lenguajes, siendo SQL uno de los más usados para bases de datos relacionales.

Los más conocidos son Oracle, MySQL y SQL Server.

3º : En que se diferencian las relacionales de las no relacionales 

Las bases de datos relacionales permiten vincular entidades y atributos de diferentes entidades mediante relaciones estructuradas, sin alterar los originales. Por otro lado, las no relacionales usan objetos con diferentes propiedades, que no permiten ser estructuradas o tipificadas en una tabla convencional. 
