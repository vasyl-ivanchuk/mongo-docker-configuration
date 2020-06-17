# mongo-docker-configuration

Docker compose files to spin up standalone or replica set mongo setup locally.

## Run standalone mongo instance:
```
cd single-node
docker-compose up
```
mongo files will persist in `single-node/data/db`

## Run single node mongo replica set:
```
cd single-node-rs
docker-compose up
```
mongo files will persist in `single-node-rs/data/db`

_Original source (discussion thread):_ https://github.com/docker-library/mongo/issues/246

## Run three nodes mongo replica set:
```
cd multiple-node-rs
docker-compose up
```
mongo files will persist in `multiple-node-rs/data/db`

_Original source:_ https://gist.github.com/crapthings/71fb6156a8e9b31a2fa7946ebd7c4edc