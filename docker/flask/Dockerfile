FROM python:3.7-alpine
LABEL maintainer "Vanush Misha Paturyan <misha@cs.nuim.ie>"

RUN pip3 install Flask

WORKDIR /app
ENV FLASK_ENV development
ENV FLASK_APP flaskapp/simpleser.py
ENTRYPOINT ["flask","run","--host=0.0.0.0"]

EXPOSE 5000
