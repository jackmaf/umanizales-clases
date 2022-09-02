# Relaciones

Las relaciones, **representadas por un rombo**, sirven para crear relaciones entre entidades. Por convención las relaciones **son verbos que conectan entidades**. Existen entidades multivaluadas o compuestas que tienen vida propia y se relacionan con otras entidades, por lo que se pueden normalizar (concepto que se explicará luego)

![Relaciones](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/relaciones.png)

# Cardinalidad

Es una propiedad de las relaciones que indica la cantidad y correspondencia con la que puede estar relacionada una entidad y puede ser:

- uno a uno (1 a 1)
- uno a varios (1 a n)
- varios a uno (n a 1)
- varios a varios. (n a a)

**Rombos verbos** (tiene, pertenece, es dueño, esta censado, enseña ,etc... )

![Cardinalidad](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/cardinalidad.png)

# Cardinalidad Uno a Uno (1 a 1)

![1 a 1 ejemplo 1](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/1a1principal.png)

![1 a 1 ejemplo 2](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/1a1-1.png)

# Cardinalidad Uno a Muchos (1 a N)

![1 a N ejemplo 1](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/1anprincipal.png)

![1 a N ejemplo 2](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/1an.png)

# Cardinalidad Muchos a Muchos (N a N)

![N a N ejemplo 1](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/nanprincipal.png)

![N a N ejemplo 2](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/nan.png)

# Practiquemos un poco

[Otro ejemplo de cardinalidad](http://www.aulapc.es/lupa_busquedas_posit.html1accesA~A60.00)

![Ejemplos de cardinalidad](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/ejemplos_cardinalidad.jpeg)

![Ejemplos de cardinalidad 2](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/ejemplo_cardinalidad_2.png)

![Ejemplos de cardinalidad 3](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/ejemplo3cardinalidadentida.png)

## Diagrama entidad relacion

![ejemplos_modelo_entidad_relacion](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/ejemplos_modelo_entidad_relacion.jpeg)

## Entidad Asociativa

Una entidad asociativa **es un término utilizado en la teoría entidad-relación**. Una base de datos relacional requiere la implementación de una relación base (o tabla base) **para resolver relaciones "muchos a muchos"**. Una relación base que representa este tipo de entidad se denomina, informalmente, **tabla asociativa**.

Como se mencionó anteriormente, las entidades asociativas se implementan en la estructura de una base de datos utilizando tablas asociativas, que son tablas que **pueden contener referencias a columnas de la misma o de diferentes tablas**.

**Una tabla asociativa (o de unión) mapea dos o más tablas haciendo referencia a las claves primarias (CP) de cada tabla. En efecto, contiene varias claves foráneas (CF), cada una en una relación de muchos a uno desde la tabla asociativa a las tablas individuales**. La CP de la tabla asociativa se compone típicamente de las mismas columnas CF.

- Una entidad asociativa (utilizando Chen notación)

![ejemplos entidad asociativa](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/Ejemplo_entidad_asociativa.png)

- Una entidad asociativa (utilizando un diagrama fisico)

![ejemplos entidad asociativa](https://github.com/jackmaf/umanizales-clases/blob/master/Bases%20de%20Datos/1/ARCHIVOS/ejemplo_diagrama_fisico.png)

# Videos de explicación

- Ejemplo 1 Cardinalidad muchos a muchos
  [![IMAGE_ALT](https://img.youtube.com/vi/UmX4kyB2wfg/0.jpg)](https://www.youtube.com/watch?v=xkqrUYb8AYI)

- Cardinalidad muchos a muchos
  [![IMAGE_ALT](https://img.youtube.com/vi/UmX4kyB2wfg/0.jpg)](https://www.youtube.com/watch?v=R_i5tpbRrYI)

# Otros tipos de diagramas entidad relacion

[Otros tipos de diagramas de entidad relacion](https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model#Cardinalities)

# Fuentes de informacion

https://es.wikipedia.org/wiki/Entidad_asociativa
