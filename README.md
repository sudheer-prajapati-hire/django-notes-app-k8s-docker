# Django Notes App for TWS Community
This is a Django notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
https://github.com/sudheer-prajapati-hire/django-notes-app-k8s-docker.git
```
<img width="1568" height="962" alt="django-app" src="https://github.com/user-attachments/assets/bebac94b-d367-46e7-8c81-cfd3ea458cda" />

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
