FROM python:3.7

WORKDIR /usr/src/app
RUN pip install rasa
COPY ./UmaBot ./bot
WORKDIR /usr/src/app/bot
CMD rasa run 
EXPOSE 5015
