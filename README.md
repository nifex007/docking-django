# Docking Django

Simple Django project setup with Docker


python version: 3.8.2 <br>
Django: 3.1.7


#### SETUP

This setup guide assumes you have docker installed on your machine. 
```
docker build -t docking-django -f .Dockerfile .
```
```
docker run -it -p 80:8888 docking-django
```

Django project now runs at ```0.0.0.0``` , ```localhost``` & ```127.0.0.1```