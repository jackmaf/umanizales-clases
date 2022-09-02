![Normalización](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/normalizacion.png)

# Formas normales en Bases de Datos relacionales

La normalización como su nombre lo indica nos ayuda a dejar todo de una forma normal. Esto obedece a las 12 reglas de Codd y nos permiten separar componentes en la base de datos:

# Que es un dato atomico

**Un dato atómico es un dato que ya no se puede dividir, ya sea por conveniencia o por especificación del lenguaje**. Un dato casi siempre siempre se puede dividir más, una palabra en letras y una letra en puntos, pero la mayoría de los casos no es necesario llegar a tanto. **Algunas veces el dato atómico te lo dará el lenguaje como son los datos primitivos (lo mas bajo), en otras ocasiones el paradigma como son los objetos y en otras ocasiones se lo darás tú y la necesidad que tengas sobre el dato**, como en el ejemplo del nombre "Juan Perez" si para tu diseño requieres que el nombre sea atómico (para ahorrar complejidad) ¡así será!, de lo contrario puedes partir en nombre, apellido paterno y apellido materno para poder hacer búsquedas por apellido o búsquedas por nombre. Una función es atómica y no se puede dividir pero esta no es un dato, si nos ponemos "locos" una función se puede ver como una abstracción mas no un dato. Finalmente, una función podría ser un elemento atómico de tu lenguaje pero dato no es (por ejemplo).

Alguien que pueda ver tu base de datos puede decir "pero porque guardaste el nombre así, este se podía dividir mas", y le respondes: si pero yo decidí que fuera atómico porque el programa no necesita mas, el nombre es meramente opcional y no representa nada, nunca habrá búsquedas ni nada, así que decidí que fuera atómico. Como se vio en el ejemplo anterior, también sirve para darse a entender entre diferentes colaboradores de un proyecto, es una propiedad del dato que dice mucho de sí y es importante entenderla y saberla aplicar.

# Ejemplo

## Sin normalizar

![sin normalizar](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/sinfn.png)

## Primera forma normal (1FN)

**Atributos atómicos (Sin campos repetidos o COLUMNAS)**

![fn1](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/fn1.png)

## Segunda forma normal (2FN)

**Cumple 1FN y cada campo de la tabla debe depender de una clave única (REGISTROS O FILAS REPETIDOS).**

![fn2](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/fn2.png)

## Tercera forma normal (3FN)

**Cumple 1FN y 2FN y los campos que NO son clave, NO deben tener dependencias.**

![fn3](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/fn3.png)

## Cuarta forma normal (4FN)

**Cumple 1FN, 2FN, 3FN y los campos multivaluados se identifican por una clave única.**

![fn4](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/fn4.png)

# Primera Forma Normal (1FN)

Esta FN **nos ayuda a eliminar los valores repetidos y no atómicos** dentro de una base de datos.

Formalmente, una tabla está en primera forma normal si:

- Todos los atributos son atómicos. Un atributo es atómico si los elementos del dominio son simples e indivisibles.

- No debe existir variación en el número de columnas.

- Los campos no clave deben identificarse por la clave (dependencia funcional).

- Debe existir una independencia del orden tanto de las filas como de las columnas; es decir, si los datos cambian de orden no deben cambiar sus significados.

**Se traduce básicamente a que si tenemos campos compuestos como por ejemplo “nombre_completo” que en realidad contiene varios datos distintos, en este caso podría ser “nombre”, “apellido_paterno”, “apellido_materno”, etc.**

También debemos asegurarnos que las columnas son las mismas para todos los registros, que no haya registros con columnas de más o de menos.

Todos los campos que no se consideran clave deben depender de manera única por el o los campos que si son clave.

Los campos deben ser tales que si reordenamos los registros o reordenamos las columnas, cada dato no pierda el significado.
