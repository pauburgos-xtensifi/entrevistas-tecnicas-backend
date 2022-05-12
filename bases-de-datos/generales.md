## Tabla de Contenido

- [Teorema CAP](#teorema-cap)
- [Qué son las bases de datos Relacionales? Cuáles son sus ventajas y desventajas?](#qué-son-las-bases-de-datos-relacionales-cuáles-son-sus-ventajas-y-desventajas)
- [Qué son las bases de datos NO Relacionales? Cuáles son sus ventajas y desventajas?](#qué-son-las-bases-de-datos-no-relacionales-cuáles-son-sus-ventajas-y-desventajas)
- [Redis con ttl](#Redis-con-ttl)
- [Lenguaje de consulta SQL](#lenguaje-de-consulta-sql)

# Teorema CAP

En un sistema distribuido de almacenamiento de datos no podemos garantizar consistencia y disponiblidad (para actualizaciones), al tiempo cuando el sistema sufre una partición (queda separado en dos o más islas). Este es el Teorema CAP, por Consistency (Consistencia), Availability (Disponibilidad) y Partition Tolerance (Tolerancia al Particionamiento).

[Más info](https://platzi.com/blog/que-es-el-teorema-cap-y-como-elegir-la-base-de-datos-para-tu-proyecto/)

![teorema-cap](NatiFabbro/entrevistas-tecnicas-backend/imagenes/teorema-cap.png)


# Qué son las bases de datos Relacionales? Cuáles son sus ventajas y desventajas?

Una [base de datos relacional](https://ayudaleyprotecciondatos.es/bases-de-datos/relacional/) es, en esencia, un conjunto de tablas (o relaciones) formadas por filas (registros) y columnas (campos); así, cada registro (cada fila) tiene una ID única, denominada clave y las columnas de la tabla contienen los atributos de los datos.

Las más usadas son:
- Oracle
- MySQL
- Microsoft SQL Server
- PostgreSQL
- DB2


# Qué son las bases de datos NO Relacionales? Cuáles son sus ventajas y desventajas?

Las [bases de datos no relacionales](https://ayudaleyprotecciondatos.es/bases-de-datos/no-relacional/) no trabajan con estructuras definidas. Es decir, los datos no se almacenan en tablas, y la información tampoco se organiza en registros o campos.

Las más usadas son:
- MongoDB
- Cassandra
- CouchDB
- Redis


# Redis con ttl

[Redis](https://redis.io/) es un motor de base de datos en memoria, basado en el almacenamiento en [tablas hash](https://es.wikipedia.org/wiki/Tabla_hash) pero que opcionalmente puede ser usada como una base de datos durable o persistente. 

TTL es un comando de Redis que retorna el tiempo de vida restante de una key. 


# Lenguaje de consulta SQL

Originalmente basado en el álgebra relacional y en el cálculo relacional, [SQL](https://es.wikipedia.org/wiki/SQL) (Structured Query Language) consiste en un lenguaje de definición de datos, un lenguaje de manipulación de datos y un lenguaje de control de datos. El alcance de SQL incluye la inserción de datos, consultas, actualizaciones y borrado, la creación y modificación de esquemas y el control de acceso a los datos. También el SQL a veces se describe como un lenguaje declarativo, también incluye elementos procesales.