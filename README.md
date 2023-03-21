## Introduction to Docker

In this repository you can see some basic concepts of docker and the most used commands

I hope it helps!

Basic commands:

- Build the image
```
docker build
```

- Use `docker ps -q` to pass the list of all running containers and stop them

```
docker stop $(docker ps -q)
```
- You can directly tag images, won't overwrite the existing image that you have on your machine, it will create a new tag that points to that image

```
docker tag
```

- Will list all the images their repositories and tags

```
docker images
```

- Is used to run a container

```
docker run 
```

Note: containers are not immutable like images are
