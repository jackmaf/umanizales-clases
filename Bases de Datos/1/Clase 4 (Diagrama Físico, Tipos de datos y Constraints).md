# Diagrama Físico: tipos de datos y constraints

Todo diagrama tiene detallado cada uno de sus parámetros, y estos son **tipos de datos** que se dividen en secciones diferentes, las cuales son:

## 1. Tipos de datos de texto: (CHAR(n), VARCHAR(n), TEXT)

- **1.1. Char(n)** Permite almacenar caracteres y cadenas de texto.
  Este tipo de dato reserva un espacio de memoria del número de caracteres que va a ser ocupado.

**Nota:** Cuando usamos CHAR decimos que la memoria será reservada para la cantidad de bytes que estamos diciendo. Por ejemplo, **si declaramos un CHAR de longitud 20, y guardamos un “Hola” sólo se ocuparán 4 bytes y los otros 16 se llenarán con espacios**.

Al recibir los datos, se les quitarán esos espacios. Y así, pero siempre ocuparán la longitud que definimos, los llenemos de datos o no.

Pero esto tiene algún beneficio, y es que CHAR es más rápido que VARCHAR en cuanto a rendimiento, ya que se sabe de antemano cuál es la longitud de los datos, no como VARCHAR que tiene una longitud variable.

Por cierto, el límite para CHAR es 255.

- **1.2. Varchar(n)** Al igual que char, este reserva espacio en la memoria. Su diferencia radica en que este reserva un mínimo espacio de memoria, y a partir de esta va creciendo o encogiéndose, es eficiente cuando desconocés cual será el tamaño de tu cadena de texto (Su limite es de 255 caracteres).

**Al declarar un tipo de dato como VARCHAR estamos indicando que será como CHAR pero con una longitud variable.**

Lo que significa que sólo reservará memoria para los datos que pongamos, así aunque declaremos un VARCHAR de 255 y pongamos un “hola”, sólo guardará los 4 caracteres (o bueno, no sólo los 4, sigamos leyendo)

**En realidad a veces VARCHAR va a necesitar algunos bytes de más para guardar la longitud de los datos. Es decir, aparte de los datos guarda un prefijo que indica la longitud.**

**Por ejemplo, “hola” ocupa 5 bytes porque la palabra ocupa 4 pero se adiciona un byte para indicar la longitud de “hola”.** Si los datos ocuparan más de 255 bytes entonces se anexaría otro byte, y así. Pero no es tanto como cuando desperdiciamos espacio con CHAR.

El gran límite para VARCHAR es 65,535 bytes.

## Entonces, ¿cuál usar? CHAR vs VARCHAR
**Si vamos a almacenar datos cuyo tamaño sabemos de antemano, es mejor usar CHAR**, pues acelera el rendimiento. **Por ejemplo, el género** (si no nos metemos con esas cosas de LGQBTASDFGHIJKL) podría ser de CHAR(1) para M y H.

O también podemos almacenar hashes de MD5 cuya longitud siempre es 32. Igualmente para IP’s versión 4 que como máximo llegan a tener 15 caracteres con todo y puntos.

Hay que tener cuidado, porque si definimos una longitud fija y no la llenamos estaremos desperdiciando espacio en disco duro.

**En caso de que vayamos a almacenar datos de longitud variable que pueden ser más cortos que el límite, usamos VARCHAR.**

Por ejemplo, si vamos a hacer una app que guarde nombres de usuario entonces podemos definir un VARCHAR(255);

Ahora se registra un usuario llamado “luis”, ocupa 4 caracteres y ya, no llena de espacios los 251 restantes como es el caso de CHAR. Y lo hacemos con la seguridad de que si un nombre se pasa de 255 será truncado, ahorrando espacio.

- **1.3. Text** Su función es guardar cadenas de texto que sean muuuuuy grandes

## 2 Tipos de datos numéros (INTEGER, BIGINT, SMALLINT, DECIMAL(n,s), NUMERIC(n,s))

- **2.1 Integer Número** que no tiene punto decimal, **se usa para declarar un tipo de dato entero** que puede ser **usado para hacer operaciones**. Al usar este tipo de dato nuestra base de datos sabrá que estamos hablando de número y no solo de un simple carácter.

- **2.2 Bigint** Es un subtipo de integer, nos sirve para **declarar números muy grandes**.

- **2.3 Smallint** Subtipo de integer, nos sirve para declarar **números muy pequeños (99 o menos).**

- **2.4 Decimal (n, s) y Numeric (n, s)** Tiene dos parámetros (n y s, en este ejemplo). La primera entrada es para números enteros, y la segunda entrada es para números decimales. **Nos sirve para hacer operaciones mas precisas.**

## 3. Tipos de datos de Fecha/hora (DATE, TIME, DATETIME, TIMESTAMP)

Esta clase de tipos de datos es muy peculiar ya que nos ayuda internamente a tener una bitácora de nuestra base de datos.

- **3.1 Date** Solo contiene la fecha (año, mes y día).

- **3.2 Time** Solo contiene la hora.

- **3.3 Datetime** Es una mezcla de 3.1 y 3.2, contiene fecha y hora.

## 4. Tipos de datos lógicos (BOOLEAN)

- **4.1 Boolean** Este solo puede tener dos valores, funciona como un tipo de dato binario.

Es usado de manera discriminatoria para hacer validaciones.

# Constraints (Restricciones)

Los contraints o restricciones **son los tipos de reglas que vas a permitir que tenga tu base de datos.**

Para ello usamos las siguientes:

- **Not null** Se asegura que tu columna no tenga valores nulos.

- **Unique** Asegura que cada valor en tu columna no se repita.

- **Primary Key** Es una etiqueta muy importante, es una combinación entre not null y unique.Nos permite hacer relaciones entre distintas entidades.

- **Foreign Key** Llave foránea, es el otro lado de una primary key, cuando queremos juntar dos tablas y decir que estan relacionadas entre si, lo que va a suceder es la primary key de una de las tablas se añadirá como foreign key de la otra.

- **Index** Se crea por columna, su función es hacer búsquedas con mayor rapidez. Su única desventaja es que suele volverse lenta cada vez que se añaden nuevos registros

## Urls referencia

https://dev.mysql.com/doc/refman/5.7/en/char.html

https://parzibyte.me/blog/2018/09/25/diferencia-entre-char-y-varchar-en-mysql/

https://ondras.zarovi.cz/sql/demo/?keyword=default
