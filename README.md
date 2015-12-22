# dockerNeo4j
Having fun with Neo4j


```
docker run \
  --detach \
  --publish=7474:7474 \
  --volume=~/neo4j/data:/data \
  herrhelms/neo4j:latest
```
