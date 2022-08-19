## EJERCICIO 1

A partir del siguiente enunciado se desea realiza el modelo entidad-relación.
“Una empresa vende productos a varios clientes. Se necesita conocer los datos
personales de los clientes (nombre, apellidos, cedula, dirección y fecha de nacimiento). Cada
producto tiene un nombre y un código, así como un precio unitario. Un cliente puede
comprar varios productos a la empresa, y un mismo producto puede ser comprado por
varios clientes.
Los productos son suministrados por diferentes proveedores. Se debe tener en cuenta
que un producto sólo puede ser suministrado por un proveedor, y que un proveedor puede
suministrar diferentes productos. De cada proveedor se desea conocer el NIF, nombre y
dirección”.

![t1](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t1.png)

## EJERCICIO 2

A partir del siguiente enunciado se desea realizar el modelo entidad-relación.
“Se desea informatizar la gestión de una empresa de transportes que reparte paquetes
por toda España. Los encargados de llevar los paquetes son los camioneros, de los que
se quiere guardar el cedula, nombre, teléfono, dirección, salario y población en la que vive.
De los paquetes transportados interesa conocer el código de paquete, descripción,
destinatario y dirección del destinatario. Un camionero distribuye muchos paquetes, y un
paquete sólo puede ser distribuido por un camionero.
De las provincias a las que llegan los paquetes interesa guardar el código de provincia y
el nombre. Un paquete sólo puede llegar a una provincia. Sin embargo, a una provincia
pueden llegar varios paquetes.
De los camiones que llevan los camioneros, interesa conocer la matrícula, modelo, tipo y
potencia. Un camionero puede conducir diferentes camiones en fechas diferentes, y un
camión puede ser conducido por varios camioneros”.

![t2](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t2.png)

## EJERCICIO 3

A partir del siguiente enunciado diseñar el modelo entidad-relación.
“Se desea diseñar la base de datos de un Instituto. En la base de datos se desea guardar
los datos de los profesores del Instituto (cedula, nombre, dirección y teléfono). Los
profesores imparten módulos, y cada módulo tiene un código y un nombre. Cada alumno
está matriculado en uno o varios módulos. De cada alumno se desea guardar el nº de
expediente, nombre, apellidos y fecha de nacimiento. Los profesores pueden impartir
varios módulos, pero un módulo sólo puede ser impartido por un profesor. Cada curso
tiene un grupo de alumnos, uno de los cuales es el delegado del grupo”.

![t3](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t3.png)

## EJERCICIO 4

A partir del siguiente supuesto diseñar el modelo entidad-relación:
“Se desea diseñar una base de datos para almacenar y gestionar la información
empleada por una empresa dedicada a la venta de automóviles, teniendo en cuenta los
siguientes aspectos:
La empresa dispone de una serie de coches para su venta. Se necesita conocer la
matrícula, marca y modelo, el color y el precio de venta de cada coche.
Los datos que interesa conocer de cada cliente son el NIF, nombre, dirección, ciudad y
número de teléfono: además, los clientes se diferencian por un código interno de la
empresa que se incrementa automáticamente cuando un cliente se da de alta en ella. Un
cliente puede comprar tantos coches como desee a la empresa. Un coche determinado
solo puede ser comprado por un único cliente.
El concesionario también se encarga de llevar a cabo las revisiones que se realizan a
cada coche. Cada revisión tiene asociado un código que se incrementa automáticamente
por cada revisión que se haga. De cada revisión se desea saber si se ha hecho cambio de
filtro, si se ha hecho cambio de aceite, si se ha hecho cambio de frenos u otros. Los
coches pueden pasar varias revisiones en el concesionario”.

![t4](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t4.png)

## EJERCICIO 5

A partir del siguiente supuesto diseñar el modelo entidad-relación:
“La clínica “SAN PATRÁS” necesita llevar un control informatizado de su gestión de
pacientes y médicos.
De cada paciente se desea guardar el código, nombre, apellidos, dirección, población,
EJERCICIOS MODELO ENTIDAD-RELACIÓN . PÁG. 3
provincia, código postal, teléfono y fecha de nacimiento.
De cada médico se desea guardar el código, nombre, apellidos, teléfono y especialidad.
Se desea llevar el control de cada uno de los ingresos que el paciente hace en el hospital.
Cada ingreso que realiza el paciente queda registrado en la base de datos. De cada
ingreso se guarda el código de ingreso (que se incrementará automáticamente cada vez
que el paciente realice un ingreso), el número de habitación y cama en la que el paciente
realiza el ingreso y la fecha de ingreso.
Un médico puede atender varios ingresos, pero el ingreso de un paciente solo puede ser
atendido por un único médico. Un paciente puede realizar varios ingresos en el hospital”.

![t5](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t5.png)

## EJERCICIO 6

Se desea informatizar la gestión de una tienda informática. La tienda dispone de una serie
de productos que se pueden vender a los clientes.
“De cada producto informático se desea guardar el código, descripción, precio y número
de existencias. De cada cliente se desea guardar el código, nombre, apellidos, dirección y
número de teléfono.
Un cliente puede comprar varios productos en la tienda y un mismo producto puede ser
comprado por varios clientes. Cada vez que se compre un artículo quedará registrada la
compra en la base de datos junto con la fecha en la que se ha comprado el artículo.
La tienda tiene contactos con varios proveedores que son los que suministran los
productos. Un mismo producto puede ser suministrado por varios proveedores. De cada
proveedor se desea guardar el código, nombre, apellidos, dirección, provincia y número
de teléfono”.

![t6](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t6.png)

## EJERCICIO 7

Pasa el modelo entidad-relación del ejercicio 1 al modelo relacional. Diseña las tablas en
Excel, realiza las relaciones que consideres oportunas e inserta cinco registros en cada
una de las tablas.

## EJERCICIO 8

Pasa el modelo entidad-relación del ejercicio 2 al modelo relacional. Diseña las tablas en
Excel, realiza las relaciones que consideres oportunas e inserta cinco registros en cada
una de las tablas.

## EJERCICIO 9

Pasa el modelo entidad-relación del ejercicio 3 al modelo relacional. Diseña las tablas en
Excel, realiza las relaciones que consideres oportunas e inserta cinco registros en cada
una de las tablas.
¿Cómo quedaría el modelo relacional suponiendo que cada profesor sólo imparte un
módulo y cada módulo es impartido por sólo un profesor?

![t9](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t9.png)

## EJERCICIO 10

Transforma el modelo entidad-relación del ejercicio 4 al modelo relacional. Diseña las
tablas en Excel, realiza las relaciones que consideres oportunas e inserta cinco registros
en cada una de las tablas.
Si un cliente sólo puede comprar un coche en el concesionario, y un coche sólo puede ser
comprado por un cliente, ¿cómo quedaría el modelo relacional?

![t10](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t10.png)

## EJERCICIO 11

Transforma el modelo entidad-relación del ejercicio 5 a modelo relacional. Diseña las
tablas en Excel, realiza las relaciones que consideres oportunas e inserta cinco registros
en cada una de las tablas.

## EJERCICIO 12

Transforma el modelo entidad-relación del ejercicio 6 al modelo relacional. Diseña las
tablas en Excel, realiza las relaciones que consideres oportunas e inserta cinco registros
en cada una de las tablas.

## EJERCICIO 13

Considera la siguiente relación PERSONA-TIENE HIJOS-PERSONA. Una persona puede
tener muchos hijos/as o ninguno. Una persona siempre es hijo/a de otra persona. Los
atributos de la persona son cedula, nombre, dirección y teléfono. Transformarlo al modelo
relacional.

![t13](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t13.png)

## EJERCICIO 14

A partir del siguiente enunciado, diseñar el modelo entidad-relación.
“En la biblioteca del centro se manejan fichas de autores y libros. En la ficha de cada
autor se tiene el código de autor y el nombre. De cada libro se guarda el código, título,
ISBN, editorial y número de página. Un autor puede escribir varios libros, y un libro puede
ser escrito por varios autores. Un libro está formado por ejemplares. Cada ejemplar tiene
un código y una localización. Un libro tiene muchos ejemplares y un ejemplar pertenece
sólo a un libro.
Los usuarios de la biblioteca del centro también disponen de ficha en la biblioteca y sacan
ejemplares de ella. De cada usuario se guarda el código, nombre, dirección y teléfono.
Los ejemplares son prestados a los usuarios. Un usuario puede tomar prestados varios
ejemplares, y un ejemplar puede ser prestado a varios usuarios. De cada préstamos
interesa guardar la fecha de préstamo y la fecha de devolución”.
Pasar el modelo entidad-relación resultante al modelo relacional. Diseñar las tablas en
Excel, realizar las relaciones oportunas entre tablas e insertar cinco registros en cada
una de las tablas.

![t14](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t14.png)

## EJERCICIO 15

A partir del siguiente supuesto realizar el modelo entidad-relación y pasarlo a modelo
relacional.
“A un concesionario de coches llegan clientes para comprar automóviles. De cada coche
interesa saber la matrícula, modelo, marca y color. Un cliente puede comprar varios
coches en el concesionario. Cuando un cliente compra un coche, se le hace una ficha en
el concesionario con la siguiente información: cedula, nombre, apellidos, dirección y teléfono.
Los coches que el concesionario vende pueden ser nuevos o usados (de segunda mano).
De los coches nuevos interesa saber el número de unidades que hay en el concesionario.
De los coches viejos interesa el número de kilómetros que lleva recorridos.
El concesionario también dispone de un taller en el que los mecánicos reparan los coches
que llevan los clientes. Un mecánico repara varios coches a lo largo del día, y un coche
puede ser reparado por varios mecánicos. Los mecánicos tienen un cedula, nombre,
apellidos, fecha de contratación y salario. Se desea guardar también la fecha en la que se
repara cada vehículo y el número de horas que se tardado en arreglar cada automóvil”.
Pasar el modelo entidad-relación resultante al modelo relacional. Diseñar las tablas en
Excel, realizar las relaciones oportunas entre tablas e insertar cinco registros en cada
una de las tablas.

![t15](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t15.png)

## EJERCICIO 16

La liga de fútbol profesional, presidida por Don Ángel María Villar, ha decidido informatizar
sus instalaciones creando una base de datos para guardar la información de los partidos
que se juegan en la liga.
Se desea guardar en primer lugar los datos de los jugadores. De cada jugador se quiere
guardar el nombre, fecha de nacimiento y posición en la que juega (portero, defensa,
centrocampista…). Cada jugador tiene un código de jugador que lo identifica de manera
única.
De cada uno de los equipos de la liga es necesario registrar el nombre del equipo, nombre
del estadio en el que juega, el aforo que tiene, el año de fundación del equipo y la ciudad
de la que es el equipo. Cada equipo también tiene un código que lo identifica de manera
única. Un jugador solo puede pertenecer a un único equipo.
De cada partido que los equipos de la liga juegan hay que registrar la fecha en la que se
juega el partido, los goles que ha metido el equipo de casa y los goles que ha metido el
equipo de fuera. Cada partido tendrá un código numérico para identificar el partido.
También se quiere llevar un recuento de los goles que hay en cada partido. Se quiere
almacenar el minuto en el que se realizar el gol y la descripción del gol. Un partido tiene
varios goles y un jugador puede meter varios goles en un partido.
Por último se quiere almacenar, en la base de datos, los datos de los presidentes de los
equipos de fútbol (cedula, nombre, apellidos, fecha de nacimiento, equipo del que es
presidente y año en el que fue elegido presidente). Un equipo de fútbol tan sólo puede
tener un presidente, y una persona sólo puede ser presidente de un equipo de la liga.
Pasar el modelo entidad-relación resultante al modelo relacional. Diseñar las tablas en
Excel, realizar las relaciones oportunas entre tablas e insertar cinco registros en cada
una de las tablas.

![t16](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t16.png)

## EJERCICIO 17

A partir del siguiente supuesto diseñar el modelo entidad-relación.
“Se desea informatizar la gestión de un centro de enseñanza para llevar el control de los
alumnos matriculados y los profesores que imparten clases en ese centro. De cada
profesor y cada alumno se desea recoger el nombre, apellidos, dirección, población, cedula,
fecha de nacimiento, código postal y teléfono.
Los alumnos se matriculan en una o más asignaturas, y de ellas se desea almacenar el
código de asignatura, nombre y número de horas que se imparten a la semana. Un
profesor del centro puede impartir varias asignaturas, pero una asignatura sólo es
impartida por un único profesor. De cada una de las asignaturas se desea almacenar
EJERCICIOS MODELO ENTIDAD-RELACIÓN . PÁG. 7
también la nota que saca el alumno y las incidencias que puedan darse con él.
Además, se desea llevar un control de los cursos que se imparten en el centro de
enseñanza. De cada curso se guardará el código y el nombre. En un curso se imparten
varias asignaturas, y una asignatura sólo puede ser impartida en un único curso.
Las asignaturas se imparten en diferentes aulas del centro. De cada aula se quiere
almacenar el código, piso del centro en el que se encuentra y número de pupitres de que
dispone. Una asignatura se puede dar en diferentes aulas, y en un aula se pueden
impartir varias asignaturas. Se desea llevar un registro de las asignaturas que se imparten
en cada aula. Para ello se anotará el mes, día y hora en el que se imparten cada una de
las asignaturas en las distintas aulas.
La dirección del centro también designa a varios profesores como tutores en cada uno de
los cursos. Un profesor es tutor tan sólo de un curso. Un curso tiene un único tutor. Se
habrá de tener en cuenta que puede que haya profesores que no sean tutores de ningún
curso”.
Una vez construido el modelo E-R pasarlo al modelo relacional. Diseñar las tablas en
Excel, hacer las relaciones oportunas e insertar 5 registros en cada una de las tablas.

![t17](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t17.png)

## EJERCICIO 18

“Una empresa necesita organizar la siguiente información referente a su organización
interna.
La empresa está organizada en una serie de departamentos. Cada departamento tiene un
código, nombre y presupuesto anual. Cada departamento está ubicado en un centro de
trabajo. La información que se desea guardar del centro de trabajo es el código de centro,
nombre, población y dirección del centro.
La empresa tiene una serie de empleados. Cada empleado tiene un teléfono, fecha de
alta en la empresa, NIF y nombre. De cada empleado también interesa saber el número
de hijos que tiene y el salario de cada empleado.
A esta empresa también le interesa tener guardada información sobre los hijos de los
empleados. Cada hijo de un empleado tendrá un código, nombre y fecha de nacimiento.
Se desea mantener también información sobre las habilidades de los empleados (por
ejemplo, mercadotecnia, trato con el cliente, fresador, operador de telefonía, etc…). Cada
habilidad tendrá una descripción y un código”.
Sobre este supuesto diseñar el modelo E/R y el modelo relacional teniendo en cuenta los
siguientes aspectos.
• Un empleado está asignado a un único departamento. Un departamento estará
compuesto por uno o más empleados.
EJERCICIOS MODELO ENTIDAD-RELACIÓN . PÁG. 8
• Cada departamento se ubica en un único centro de trabajo. Estos se componen de
uno o más departamentos.
• Un empleado puede tener varios hijos.
• Un empleado puede tener varias habilidades, y una misma habilidad puede ser
poseída por empleados diferentes.
• Un centro de trabajo es dirigido por un empleado. Un mismo empleado puede
dirigir centros de trabajo distintos.
Realizar el diseño de la base de datos en Excel e introducir cinco registros en cada una
de las tablas.

![t18](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t18.png)

## EJERCICIO 19

Se trata de realizar el diseño de la base de datos en el modelo E/R para una cadena de
hoteles.
“Cada hotel (del que interesa almacenar su nombre, dirección, teléfono, año de
construcción, etc.) se encuentra clasificado obligatoriamente en una categoría (por
ejemplo, tres estrellas) pudiendo bajar o aumentar de categoría.
Cada categoría tiene asociada diversas informaciones, como, por ejemplo, el tipo de IVA
que le corresponde y la descripción.
Los hoteles tiene diferentes clases de habitaciones (suites, dobles, individuales, etc.), que
se numeran de forma que se pueda identificar fácilmente la planta en la que se
encuentran. Así pues, de cada habitación se desea guardar el código y el tipo de
habitación.
Los particulares pueden realizar reservas de las habitaciones de los hoteles. En la reserva
de los particulares figurarán el nombre, la dirección y el teléfono.
Las agencias de viaje también pueden realizar reservas de las habitaciones. En caso de
que la reserva la realiza una agencia de viajes, se necesitarán los mismos datos que para
los particulares, además del nombre de la persona para quien la agencia de viajes está
realizando la reserva.
En los dos casos anteriores también se debe almacenar el precio de la reserva, la fecha
de inicio y la fecha de fin de la reserva”.

![t19](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t19.png)

## EJERCICIO 20

Imagina que una agencia de seguros de tu municipio te ha solicitado una base de datos
mediante la cual llevar un control de los accidentes y las multas. Tras una serie de
entrevistas, has tomado las siguientes notas:
“Se desean registrar todas las personas que tienen un vehículo. Es necesario guardar los
EJERCICIOS MODELO ENTIDAD-RELACIÓN . PÁG. 9
datos personales de cada persona (nombre, apellidos, dirección, población, teléfono y
cedula).
De cada vehículo se desea almacenar la matrícula, la marca y el modelo. Una persona
puede tener varios vehículos, y puede darse el caso de un vehículo pertenezca a varias
personas a la vez.
También se desea incorporar la información destinada a gestionar los accidentes del
municipio. Cada accidente posee un número de referencia correlativo según orden de
entrada a la base de datos. Se desea conocer la fecha, lugar y hora en que ha tenido
lugar cada accidente. Se debe tener en cuenta que un accidente puede involucrar a varias
personas y varios vehículos.
Se desea llevar también un registro de las multas que se aplican. Cada multa tendrá
asignado un número de referencia correlativo. Además, deberá registrarse la fecha, hora,
lugar de infracción e importe de la misma. Una multa solo se aplicará a un conductor e
involucra a un solo vehículo.”
Realiza el modelo E-R y pásalo al modelo relacional. Diseña después las tablas en
Excel, realiza las relaciones oportunas entre ellas e inserta cinco registros en cada una
de las tablas.

![t20](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t20.png)

## EJERCICIO 21

Una agencia de viajes desea informatizar toda la gestión de los viajeros que acuden a la
agencia y los viajes que estos realizan. Tras ponernos en contacto con la agencia, ésta
nos proporciona la siguiente información.
“La agencia desea guardar la siguiente información de los viajeros: cedula, nombre, dirección
y teléfono.
De cada uno de los viajes que maneja la agencia interesa guardar el código de viaje,
número de plazas, fecha en la que se realiza el viaje y otros datos. Un viajero puede
realizar tantos viajes como desee con la agencia. Un viaje determinado sólo puede ser
cubierto por un viajero.
Cada viaje realizado tiene un destino y un lugar de origen. De cada uno de ellos se quiere
almacenar el código, nombre y otros datos que puedan ser de interés. Un viaje tiene un
único lugar de destino y un único lugar de origen”.
Realizar el modelo E-R y pasarlo al modelo de datos relacional. Diseñar las tablas en
Excel, realizar las oportunas relaciones entre tablas e introducir cinco registros en cada
una de las tablas.

![t21](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t21.png)

## EJERCICIO 22

Una empresa desea diseñar una base de datos para almacenar en ella toda la
información generada en cada uno de los proyectos que ésta realiza.
“De cada uno de los proyectos realizados interesa almacenar el código, descripción,
cuantía del proyecto, fecha de inicio y fecha de fin. Los proyectos son realizados por
clientes de los que se desea guardar el código, teléfono, domicilio y razón social. Un
cliente puede realizar varios proyectos, pero un solo proyecto es realizado por un único
cliente.
En los proyectos participan colaboradores de los que se dispone la siguiente información:
nif, nombre, domicilio, teléfono, banco y número de cuenta. Un colaborador puede
participar en varios proyectos. Los proyectos son realizados por uno o más colaboradores.
Los colaboradores de los proyectos reciben pagos. De los pagos realizados se quiere
guardar el número de pago, concepto, cantidad y fecha de pago. También interesa
almacenar los diferentes tipos de pagos que puede realizar la empresa. De cada uno de
los tipos de pagos se desea guardar el código y descripción. Un tipo de pago puede
pertenecer a varios pagos”.

![t22](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/t22.png)

Ejercicios de practica:
Identificar y graficar usando la notacion chen las entidades y atributos de los siguientes sistemas:

1. Biblioteca virtual (Kindle Books)
2. Tienda virtual de Ropa
3. Tienda virtual de Electrodomesticos
4. Tienda virtual de mascotas
5. Tienda virtual de medicamentos
6. Tienda virtual de bisuteria
7. Tienda virtual de peliculas
8. Tienda virtual de automoviles
9. Tienda virtual de motocicletas
10. Tienda virtual de bicicletas

url:

https://bdalfonso.blogspot.com/2013/06/modelo-err-ejercicios-resueltos.html
