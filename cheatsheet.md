## Docker Cheatsheet

* Pull a docker image from dockerHub

```sh
$ docker pull <image-name>
```
* Start a docker container

```sh
$ docker start <container-id>
```

* Stop a docker container

```sh
$ docker start <container-id>
```

* combines `docker` pull and `docker` start

```sh
$ docker run <container-id/image-name>
```

* Show all the running containers

```sh
$ docker ps -a
```

* Run the container in detached terminal mode 

```sh
$ docker run -d <container-id/image-name>
```

* Run the container through a specific port 

```sh
$ docker run -phostport:dockerport <container-id/image-name>
```

* Name your docker container 

```sh
$ docker run --name <container-name>
```


 

