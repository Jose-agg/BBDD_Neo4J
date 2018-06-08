# Base de Datos Neo4J #

Este repositorio alberga el script de creación de una base de datos basada en grafos y una serie de consultas de ejemplo sobre la misma. Para la creación se utiliza Neo4J y para las consultas el lenguaje Cypher.

## Ficheros ##

El fichero **BBDD.cypher** contiene el script de creación de la base de datos. Para ello es necesario cumplir el siguiente formato.

```cypher
CREATE (X:Y{A:'B', A:'B', A:'B'...});	// Creación
CREATE UNIQUE(X)-[:Z]->(X´);	// Unión
```
*Leyenda*:
- X: Nombre del grafo
- Y: Tipo de grafo
- A: Caracteristica del grafo
- B: Valor de la caracteristica
- Z: Nombre/Tipo de conexión entre el grafo X y el X´

Por otro lado, el fichero **Consultas.txt** contiene seis consultas que se han realizado sobre la base de datos y el resultado que devuelven.