FROM continuumio/miniconda3:latest

RUN pip install mlflow==2.0.1 psycopg2-binary pymysql boto3

ADD . /app
WORKDIR /app

