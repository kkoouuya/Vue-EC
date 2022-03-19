FROM python:3.9.2-buster

WORKDIR /usr/src/

ENV LANG C.UTF-8
ENV TZ Asia/Tokyo
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN pip install --upgrade pip
COPY ./requirements.txt .
RUN pip install -r requirements.txt

COPY . .