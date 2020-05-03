## Introduction:
WordPress (WordPress.org) is a free and open-source content management system (CMS) written in PHP and paired with a MySQL or MariaDB database. 
Features include a plugin architecture and a template system, referred to within WordPress as Themes.

## Project:
This is the Docker project made with Docker Compose based on Red hat Linux-8 operating system as host. My project uses “Infrastructure as a Code” i.e. “Docker Compose” to launch a full working Wordpress setup in one go.

## How to execute:
1. To download image : "docker pull Wordpress:5.1.1-php7.3-apache"
2. Go to working directory : "cd /Wordpress/"
3. To launch the setup : "docker-compose up"
4. To stop but not remove the setup : "docker-compose stop"
5. To again start the setup : "docker-compose start"
6. To access the .YAML file : Go to "cd/Wordpress/"  
7. To run : "vim docker-compose.yml"
8. Your Ghost web environment is now successfully created hosted on your base Red Hat system. 

9. Go to IP(Base Red Hat System) : 8081 to check your Ghost Set up.
   
   example : http://192.168.43.124:8081
   
