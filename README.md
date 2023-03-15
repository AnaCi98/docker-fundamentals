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
