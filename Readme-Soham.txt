Example of building a simple web application in Docker
The goal is to have an automated deployment of a simple application that includes:

Web server
Database server
Pointing your browser to the /index.php of the Web Server, should result in a query to the mysql DB and a display of the query result in your browser.

The project consists of the following:

- docker-compose.yaml
- Dockerfile
- DockerfileDB
- index.php

To run, just enter 127.0.0.1:8889



