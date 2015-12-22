# dockerNeo4j
Having fun with Neo4j

This repo can be found on [Docker Hub](https://hub.docker.com/r/herrhelms/neo4j/).

### interactive with CLI
```
docker run \
  --interactive \
  --rm \
  --publish=7474:7474 \
  --volume= $HOME/neo4j/data:/data \
  herrhelms/neo4j:latest
```

### as daemon in the background
```
docker run \
  --detach \
  --publish=7474:7474 \
  --volume= $HOME/neo4j/data:/data \
  herrhelms/neo4j:latest
```

