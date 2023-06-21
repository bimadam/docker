# Docker

## Commands
1. Building image
```
docker build -t webserver-image:v1 . 
```
2. Running container from image
```
docker run -d -p 80:80 webserver-image:v1
```
3. Opening a website
```
localhost:80
```

## Usage pictures
Builded image in Docker Desktop Hub

![image](https://github.com/bimadam/docker/blob/main/images/buildedImage.png?raw=true)

Running container in Docker Desktop Hub

![container](https://github.com/bimadam/docker/blob/main/images/runningContainer.png?raw=true)

Running website

![website](https://github.com/bimadam/docker/blob/main/images/website.png?raw=true)

Dockerfile in VS Code

![dockerfile](https://github.com/bimadam/docker/blob/main/images/dockerfile.png?raw=true)

Building the image in VS Code terminal

![build](https://github.com/bimadam/docker/blob/main/images/build.png?raw=true)

Running the container in VS Code terminal

![run](https://github.com/bimadam/docker/blob/main/images/run.png?raw=true)
