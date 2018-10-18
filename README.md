# elasticsearch-cluster-docker-compose
It'll create an elasticsearch servers cluster by docker compose.

## How to use
You could use the docker-compose command to start a cluster.

```sh
# in the root path of this project
docker-compose up -d
```
## Note
The only thing you should know is when it deployed on **linux servers**, you'd better set the volumes permission first like: 

```sh
chown -R 1000:1000 /data/es/
```
