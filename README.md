# spark-dcos-docker

## Build

### Pre-requisites
- Spark.tgz (if you want to build a Docker image with a custom spark distribution)

### Instructions
To build from the default Dockerfile
```bash
docker build -t <dockerhub-username>/<project-name>:<tag> .
```

To build from a specific Dockerfile
```bash
docker build -t <dockerhub-username>/<project-name>:<tag> -f <Dockerfile/path>
```

Push to hub.docker
```bash
docker push <dockerhub-username>/<project-name>:<tag>
```

