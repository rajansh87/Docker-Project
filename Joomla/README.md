## Introduction:
Joomla is a free and open-source content management system (CMS) for publishing web content, developed by Open Source Matters, Inc. 
It is built on a model–view–controller web application framework that can be used independently of the CMS.
Joomla is written in PHP, uses object-oriented programming techniques (since version 1.5) and software design patterns, stores data in a 
MySQL, MS SQL (since version 2.5), or PostgreSQL (since version 3.0) database, and includes features such as page caching, RSS feeds,
printable versions of pages, news flashes, blogs, search, and support for language internationalization.

## Project:
This is the Docker project made with Docker Compose based on Red hat Linux-8 operating system as host. My project uses “Infrastructure as a Code” i.e. “Docker Compose” to launch a full working Joomla setup in one go.

## How to execute:
1. To download image : "docker pull joomla:latest"
2. Go to working directory : "cd /Joomla/"
3. To launch the setup : "docker-compose up"
4. To stop but not remove the setup : "docker-compose stop"
5. To again start the setup : "docker-compose start"
6. To access the .YAML file : Go to "cd/Joomla/"  
7. To run : "vim docker-compose.yml"
8. Your Joomla web environment is now successfully created hosted on your base Red Hat system. 

9. Go to IP(Base Red Hat System) : 8081 to check your Joomla Set up.
   
   example : http://192.168.43.124:8081
   
