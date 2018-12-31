# Flask sample

[![dockeri.co](http://dockeri.co/image/ruifigueiredo/flask)](https://registry.hub.docker.com/u/ruifigueiredo/flask/)

## Run container

$ git clone https://github.com/ruifigueiredo/flask.git

$ cd flask/web

$ docker build -t flask-sample-one:latest .

$ docker run -d -p 5000:5000 flask-sample-one

## Build and Run the Service using Docker Compose

Run the following command to build the docker image flask-sample-one from web directory and deploy is as a service

$ docker-compose up

## Testing Open url

http://localhost:5000

## Note:

change code in /code without rebuild the container.

# Flask App with MongoDB using Docker Compose

$ cd flask/flask_compose_sample

## Build and Run the Service using Docker Compose

$ docker-compose build

$ docker-compose up
