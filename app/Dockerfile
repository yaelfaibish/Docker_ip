FROM python:3.10-alpine

WORKDIR /app

RUN pip install flask

RUN pip install redis

COPY  . .

EXPOSE 5000


CMD [ "python" , "app.py" ]