## Building the project using docker

Build the docker image. The build step builds the image using the node:argon official node image and then copies the source into the image. This step only builds the image. Note:- the . at the indicates the current directory where Dockerfile is located
```
docker build -t node-mongo-express:0.1 .
```

Run the docker image using the following command
```
docker run -p 3000:3000 -ti node-mongo-express:0.1
```
