# docker-tutorial-flask-app
Based on: https://training.docker.com/course/developer---beginner-linux-containers

## To build image
`docker build -t <USERNAME>/myfirstapp .`

## To run the image
`$ docker run -p 8888:5000 --name myfirstapp <USERNAME>/myfirstapp`

## To push the image
`docker push YOUR_USERNAME/myfirstapp`
