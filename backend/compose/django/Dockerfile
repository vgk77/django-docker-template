FROM python:3.11

ENV PYTHONUNBUFFERED 1
ENV PYTHONDONTWRITEBYTECODE 1

RUN mkdir /app
WORKDIR /app

ADD requirements.txt /app/
RUN pip install --no-cache-dir -r requirements.txt

COPY . /app/