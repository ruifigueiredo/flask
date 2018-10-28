# Flask sample

## Run container.

$ docker build -t flask-sample-one:latest .

$ docker run -d -p 5000:5000 flask-sample-one

## Docker Compose.

$ docker-compose up

## Testing Open url

http://localhost:5000

## Note:

change code in /code without rebuild the container.
