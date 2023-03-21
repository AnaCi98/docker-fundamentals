### FROM
Any valid Dockerfile must first begin with a FROM instruction, which initiliaze a new build stage and specifies the base image that subsequent instructions will build upon
This base image is from a public repository like an operating system or a base image for a specific language

### RUN
This execute arbitrary commands. Each instruction is a new layer added on top of your previous layers

### ENV
Enables you to set environment variables in the image

### ADD & COPY
Enable you to copy files into your image. The difference between these two is that COPY can only copy local files and with ADD you can add files from URLs

### CMD 
Define default command for container execution. There can only be one CMD instruction and if there be more that one it will take only the last for take effect
