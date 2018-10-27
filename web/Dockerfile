FROM ubuntu:latest
MAINTAINER Rui Figueiredo <rui.figueiredo@gmail.com>
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
RUN pip install --upgrade pi
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]
