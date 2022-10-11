If You Want  to Build application from Docker file or container image
1. first build the docker file without any extension of that file and rename it as Dockerfile
2.then for building the container use command :
 - > docker build -t myimage/myapp/myContainer/App ./working directory.

3.here -t stand for tag name of your choice.
4.for running the container use this command : 
- > docker run -dp 3000:3000 myimage 
