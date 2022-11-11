FROM continuumio/miniconda3:latest

RUN pip install mlflow==1.30.0 psycopg2-binary pymysql boto3

ADD . /app
WORKDIR /app

