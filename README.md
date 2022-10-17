# Docker-compose-CC

### See docker images

```
    docker images
```

### See docker images ids

```
    docker image ls -q
```

Remove all docker images

```
    docker image rm -f $(docker image ls -q)
```

### See docker containers

```
    docker ps -a
```

### See all docker containers ids

```
    docker container ls -aq
```

Remove all docker containers

```
    docker container rm -f $(docker container ls -aq)
```

### See docker containers running

```
    docker ps
```

### See docker containers logs

```
    docker logs -f <container_id>
```

### Remove docker images

```
    docker rm <image_id>
```

# Docker Compose

### Docker compose build
    
    ```
        docker-compose build
    ```

### Docker compose up

    ```
        docker-compose up
    ```