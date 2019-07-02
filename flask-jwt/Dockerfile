FROM tiangolo/uwsgi-nginx-flask:python2.7-alpine3.8

COPY ./app /app

COPY ./app/requirements.txt /app

RUN pip install -r requirements.txt

