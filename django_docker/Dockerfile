FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /django_docker
WORKDIR /django_docker
COPY django-requirements.txt /django_docker/
RUN pip install -r django-requirements.txt
COPY . /django_docker/
