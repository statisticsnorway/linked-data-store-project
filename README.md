# Linked Data Store Project modules

This is a project that makes it easy to checkout and pull changes form all LDS repos.

**Git checkout**

`./checkout.sh` will checkout all LDS modules

**Git pull**

`./pull.sh` will pull changes for all LDS modules

**Build**

`mvn clean install`

**Run with Neo4j**

On Winodows and Mac you need to configure your *hosts-file*: `c:\windows\system32\etc\hosts` or `/etc/hosts` with `127.0.0.1    db-neo4j`.

`./docker/run-neo4j.sh`
