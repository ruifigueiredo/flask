# Flask sample

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
