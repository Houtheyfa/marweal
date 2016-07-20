###############################################
# Dockerfile to build a sample python WSGI Web app 
##############################################
# Base image is python

FROM python:latest

# Auther 
MAINTAINER Houtheyfa Abbes <doufa94@gmail.com>

# Define a volume 
VOLUME /pyapp

# change workdir
WORKDIR /pyapp

# Install requirements 
RUN pip install uwsgi uwsgitop Flask


CMD ["uwsgi","uwsgi.ini"]