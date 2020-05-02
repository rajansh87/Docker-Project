## Introduction:
Ghost is a free and open source blogging platform written in JavaScript and distributed under the MIT License, designed to simplify the process of online publishing for individual bloggers as well as online publications.
Ghost is an entirely open source application which has been downloaded 2,000,000+ times by developers all over the world. It uses a modern technology stack with sensible components and abstractions. We release code which developers love; The inventors of JavaScript, Android and StackOverflow all use Ghost for their blogs.

## Project:
This is the Docker project made with Docker Compose based on Red hat Linux-8 operating system as host. My project uses “Infrastructure as a Code” i.e. “Docker Compose” to launch a full working Ghost setup in one go.

## How to execute:
1. To download image : "docker pull ghost:latest"
2. Go to working directory : "cd /GHOST/"
3. To launch the setup : "docker-compose up"
4. To stop but not remove the setup : "docker-compose stop"
5. To again start the setup : "docker-compose start"
6. To access the .YAML file : Go to "cd/GHOST/"  
7. To run : "vim docker-compose.yml"
8. Your Ghost web environment is now successfully created hosted on your base Red Hat system. 
   Go to IP(Base Red Hat System):8081 to check your Ghost Set up.
