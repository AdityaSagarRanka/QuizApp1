#This is a sample Image 
FROM python:3
ENV PYTHONUNBUFFERED=1
MAINTAINER Aditya
RUN mkdir /quizapp
WORKDIR /quizapp
COPY requirements.txt /quizapp
RUN pip install -r requirements.txt
COPY . /quizapp

