# Docker-Project
These are the projects based on my learning from IIEC RISE 1.0 DOCKER training given by Vimal Daga Sir.
## RISE-ID: RISE 2020.51.8.1

## Requirements:
1. Yum configured
2. Docker Community Edition installed
3. Internet Connectivity

## Initial Setup:
1. To start Docker : "systemctl start docker"
2. To check status of Docker : "systemctl status docker"
3. To install mysql image : "docker pull mysql:5.7"
4. To install mysql client software : "yum install mysql"
5. To install docker-compose : Run following commands without quotes

a.  "sudo curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose"

b.  "sudo chmod +x /usr/local/bin/docker-compose"
