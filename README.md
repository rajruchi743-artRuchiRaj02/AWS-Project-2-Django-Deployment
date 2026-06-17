# AWS Project 2 - Django Application Deployment on Ubuntu 22.04

## Overview

This project demonstrates deployment of a Django application on AWS EC2 Ubuntu 22.04 using Gunicorn and Nginx.

## Technologies Used

- AWS EC2
- Ubuntu 22.04
- Python 3
- Django
- Gunicorn
- Nginx
- systemd

## Project Architecture

Client Browser
↓
Nginx
↓
Gunicorn
↓
Django Application

## Deployment Steps

1. Launch Ubuntu EC2 Instance
2. Install Python Dependencies
3. Create Django Project
4. Configure ALLOWED_HOSTS
5. Run Database Migrations
6. Test Django Development Server
7. Configure Gunicorn
8. Create Gunicorn Service
9. Configure Nginx Reverse Proxy
10. Deploy Application

## Screenshots

### EC2 Instance Running
![EC2](screenshots/screenshot1-ec2-running.png)

### SSH Login
![SSH](screenshots/screenshot2-ssh-login.png)

### Python Installation
![Python](screenshots/screenshot3-python-version.png)

### Django Application
![Django](screenshots/screenshot4-django-page.png)

### Gunicorn Running
![Gunicorn](screenshots/screenshot5-gunicorn.png)

### Final Deployment via Nginx
![Nginx](screenshots/screenshot6-nginx-final.png)

## Result

Successfully deployed a Django application on Ubuntu 22.04 using Gunicorn and Nginx.