
Minimal Threat Intelligence Search engine

# Start the service-helper.sh script to boot neo4j and rabbitmq

```
$ ./service-helper.sh
```

- Neo4j is accessbile over http://locahost:7474, username=neo4j, password=password1234
- rabbitmq is accessible over http://localhost:5672, username=guest, password=guest

# st4lk3r service


```sh
$ cd ./st4lk3r
$ docker build -t st4lk3r .
$ docker run -d -p5000:5000 st4lk3r
```

- st4lk3r is accessible over http://localhost:5000
