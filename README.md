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
![image](https://github.com/bimadam/docker/blob/main/runningContainer.png?raw=true)

Running container in Docker Desktop Hub
![container](https://github.com/bimadam/docker/blob/main/buildedImage.png?raw=true)

Running website
![website](https://github.com/bimadam/docker/blob/main/website.png?raw=true)

Dockerfile in VS Code
![dockerfile](https://github.com/bimadam/docker/blob/main/dockerfile.png?raw=true)

Building the image in VS Code terminal
![build](https://github.com/bimadam/docker/blob/main/build.png?raw=true)

Running the container in VS Code terminal
![run](https://github.com/bimadam/docker/blob/main/run.png?raw=true)
