## Introduction:
PrestaShop is a freemium, open source e-commerce solution.The software is published under the Open Software License (OSL).
It is written in the PHP programming language with support for the MySQL database management system.
PrestaShop is currently used by 300,000 shops worldwide and is available in 60 different languages.

## Project:
This is the Docker project made with Docker Compose based on Red hat Linux-8 operating system as host. My project uses “Infrastructure as a Code” i.e. 
“Docker Compose” to launch a full working PrestaShop setup in one go.

## How to execute:
1. To download image : "docker pull prestashop/prestashop:latest"
2. Go to working directory : "cd /PrestaShop/"
3. To launch the setup : "docker-compose up"
4. To stop but not remove the setup : "docker-compose stop"
5. To again start the setup : "docker-compose start"
6. To access the .YAML file : Go to "cd/Prestashop/"  
7. To run : "vim docker-compose.yml"
8. Your PrestaShop web environment is now successfully created hosted on your base Red Hat system. 

9. Go to IP(Base Red Hat System) : 8081 to check your Ghost Set up.
   
   example : http://192.168.43.124:8081
   
