# Linked Data Store Project modules

This is a convencience project that makes it easy to checkout and pull changes form all LDS repos.

> For more information about Linked Data Store, please refer to the [LDS documentation](https://github.com/statisticsnorway/linked-data-store-documentation).


**Git checkout**

`./checkout.sh` will checkout all LDS modules

**Git pull**

`./pull.sh` will pull changes for all LDS modules

**Build**

`mvn clean install`

**Run with Neo4j**

On Windows and Mac you need to configure your *hosts* file: `c:\windows\system32\drivers\etc\hosts` or `/etc/hosts` with `127.0.0.1    db-neo4j`.

`./docker/run-neo4j.sh`
