### Dockerfiles

Dockerfile is a a declarative way of creating our own images. Docker will give us some syntax to create our own images.

File name should Dockerfile.

### How to build image from Dockerfile

```
docker build -t [docker-hub-URL]/(your-username)/[image-name]:version .

### docker build -t docker.io/svelpula999/from:v1 . ### for current directory to build own image 
```

### How to push images to Dockerhub

```
docker push [docker-hub-URL]/(your-username)/[image-name]:version
```
### How to delete all containers at a time

```
docker ps -a -q

docker rm -f `docker ps -a -q`
```