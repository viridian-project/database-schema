# database-schema

Definitions and ideas for the Viridian backend database schema.

The database is supposed to hold mainly information, ratings and votings on sustainability aspects of products, producers and labels.

In `asGraph`, the schema is found as a graph: a .graphml file that can be opened e.g. with the graph editor software [yed](https://www.yworks.com/products/yed). A graph shows the interrelations between different parts nicely.

In `asJSON`, the schema is found as JSON documents. It is required to model the DB schema in JSON format since CouchDB (via Hyperledger Fabric) is planned to be used to store the Viridian backend DB.
