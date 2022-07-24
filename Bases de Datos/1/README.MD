# Pequeña historia Persistencia de la información

![Pequeña historia Persistencia de la informacion](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/Persistencia%20de%20la%20informacion.png)

# Historia de las DB (BASES DE DATOS

[![IMAGE_ALT](https://img.youtube.com/vi/UmX4kyB2wfg/0.jpg)](https://www.youtube.com/watch?v=pXt5ouY1okE)

# ¿Que es una base de datos?

Una base de datos es una recopilación organizada de información o datos estructurados, que normalmente se almacena de forma electrónica en un sistema informático. Normalmente, una base de datos está controlada por un sistema de gestión de bases de datos (DBMS). En conjunto, los datos y el DBMS, junto con las aplicaciones asociadas a ellos, reciben el nombre de sistema de bases de datos, abreviado normalmente a simplemente base de datos.
[mas informacion Oracle](https://www.oracle.com/co/database/what-is-database/)

Las bases de datos surgen de la necesidad de conservar la información más allá de lo que existe en la memoria RAM.

[![IMAGE_ALT](https://img.youtube.com/vi/UmX4kyB2wfg/0.jpg)](https://www.youtube.com/watch?v=6S8A-1jBD5Y)

# Antes de las bases de datos relacionales

anteriormente se usaban bases de datos basadas en archivos, el cuál era texto plano fácil de guardar, pero difícil de extraer, por esto se inventaron las bases de datos relacionales.

## Ejemplos:

[1. Phones](https://github.com/codeforamerica/ohana-api/blob/master/data/sample-csv/phones.csv)

[2. Addresses](https://github.com/codeforamerica/ohana-api/blob/master/data/sample-csv/addresses.csv)

Las bases de datos basadas en archivos eran datos guardados en texto plano, fáciles de guardar pero muy difíciles de consultar y por la necesidad de mejorar esto nacen las bases de datos relacionales. Su inventor Edgar Codd dejó ciertas reglas para asegurarse de que toda la filosofía de las bases de datos no se perdiera, estandarizando el proceso, Codd invento el algebra relacional

Es importante que sea fácil de guardar y extraer, En 1990 Codd se preocupó porque los sistemas de gestión de bases de datos (SGBD) que decían ser relacionales, no lo eran. En la práctica es difícil cumplir las 12 pero, un SGBD es más relacional cuantas más reglas cumpla

Las Reglas y mandamientos de Edgar Frank Ted Codd)

**Regla 0:** Regla de fundación.
a) Cualquier sistema que se proclame como relacional, debe ser capaz de gestionar sus bases de datos enteramente mediante sus capacidades relacionales.

**Regla 1:** Regla de la información.
a) Todos los datos deben estar almacenados en las tablas
b) Esas tablas deben cumplir las premisas del modelo relacional
c) No puede haber información a la que accedemos por otra vía

**Regla 2:** Regla del acceso garantizado.
a) Cualquier dato es accesible sabiendo la clave de su fila y el nombre de su columna o atributo
b) Si a un dato no podemos acceder de esta forma, no estamos usando un modelo relacional

**Regla 3:** Regla del tratamiento sistemático de valores nulos.
a) Esos valores pueden dar significado a la columna que los contiene
b) El SGBD debe tener la capacidad de manejar valores nulos
c) El SGBD reconocerá este valor diferenciándolo de cualquier otro
d) El SGBD deberá aplicársele la lógica apropiada
e) Es un valor independiente del tipo de datos de la columna

**Regla 4:** Catálogo dinámico en línea basado en el modelo relacional.
a) El catálogo en línea es el diccionario de datos
b) El diccionario de datos se debe de poder consultar usando las mismas técnicas que para los datos
c) Los metadatos, por tanto, se organizan también en tablas relacionales
d) Si SELECT es una instrucción que consulta datos, también será la que consulta los metadatos

**Regla 5:** Regla comprensiva del sublenguaje de los datos completo.
a) Al menos tiene que existir un lenguaje capaz de hacer todas las funciones del SGBD
b) No puede haber funciones fuera de ese lenguaje
c) Puede haber otros lenguajes en el SGBD para hacer ciertas tareas
d) Pero esas tareas también se deben poder hacer con el “lenguaje completo”

**Regla 6:** Regla de actualización de vistas.
a) Las vistas tienen que mostrar información actualizada
b) No puede haber diferencias entre los datos de las vistas y los datos de las tablas base

**Regla 7:** Alto nivel de inserción, actualización, y cancelación.
a) La idea es que el lenguaje que maneja la base de datos sea muy humano
b) Eso implica que las operaciones del lenguaje de manipulación de los datos (DML) trabajen con conjuntos de filas a la vez
c) Para modificar, eliminar o añadir datos, no hará falta programar de la forma en la que lo hacen los lenguajes de tercera generación como C o Java

**Regla 8:** Independencia física de los datos.
a) Cambios en la física de la BD no afecta a las aplicaciones ni a los esquemas lógicos
b) El acceso a las tablas (elemento lógico) no cambia porque la física de la base de datos cambie

**Regla 9:** Independencias lógicas de los datos.
a) Cambios en el esquema lógico (tablas) de la BD no afectan al resto de esquemas
b) Si cambiamos nombres de tabla, o de columna o modificamos información de las filas, las aplicaciones (esquema externo) no se ven afectadas
c) Es más difícil de conseguir

**Regla 10:** Independencia de la integridad.
a) Las reglas de integridad (restricciones) deben de ser gestionadas y almacenadas por el SGBD

**Regla 11:** Independencia de la distribución.
a) Que la base de datos se almacene o gestione de forma distribuida en varios servidores, no afecta al uso de esta ni a la programación de las aplicaciones de usuario
b) El esquema lógico es el mismo independientemente de si la BD es distribuida o no

**Regla 12:** La regla de la no subversión.
a) La base de datos no permitirá que exista un lenguaje o forma de acceso, que permita saltarse las reglas anteriores.

# TIPOS DE BASES DE DATOS

Existen muchos tipos diferentes de bases de datos. La mejor base de datos para una organización específica depende de cómo pretenda la organización utilizar los datos.

**Bases de datos relacionales.** Las bases de datos se hicieron predominantes en la década de 1980. Los elementos de una base de datos relacional se organizan como un conjunto de tablas con columnas y filas. La tecnología de bases de datos relacionales proporciona la forma más eficiente y flexible de acceder a información estructurada.

**Bases de datos orientadas a objetos.** La información de una base de datos orientada a objetos se representa en forma de objetos, como en la programación orientada a objetos.

**Bases de datos distribuidas.** Una base de datos distribuida consta de dos o más archivos que se encuentran en sitios diferentes. La base de datos puede almacenarse en varios ordenadores, ubicarse en la misma ubicación física o repartirse en diferentes redes.

**Almacenes de datos.** Un repositorio central de datos, un data warehouse es un tipo de base de datos diseñado específicamente para consultas y análisis rápidos.

**Bases de datos NoSQL NO RELACIONALES.** Una base de datos NoSQL, o base de datos no relacional, permite almacenar y manipular datos no estructurados y semiestructurados (a diferencia de una base de datos relacional, que define cómo se deben componer todos los datos insertados en la base de datos). Las bases de datos NoSQL se hicieron populares a medida que las aplicaciones web se volvían más comunes y complejas.

**Bases de datos orientadas a grafos.** Una base de datos orientada a grafos almacena datos relacionados con entidades y las relaciones entre entidades.

**Bases de datos OLTP.** Una base de datos OLTP es una base de datos rápida y analítica diseñada para que muchos usuarios realicen un gran número de transacciones

[![IMAGE_ALT](https://img.youtube.com/vi/UmX4kyB2wfg/0.jpg)](https://www.youtube.com/watch?v=vvsqP1f1JJs)

# Tipos de bases de datos mas utilizados actualmente:

![tipos de bases de datos mas utlizados](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/7.png)

# RBD (Bases de datos relacionales)

![RBD](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/8.png)

# Bases de datos NO relacionales

![No Relacionales 1](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/9.png)
![No Relacionales 1](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/10.png)
