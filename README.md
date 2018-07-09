# Dockerised phpmetrics for code analysis with HTML reports

Analyse PHP code by running phpmetrics against the code in a docker container and then view the results in another docker container.

## Getting Started

Clone the repo, open docker-compose.yml and change (lines 7 & 16) to the file path of the code you want to analyse.

Run docker compose:

```docker-compose up```

Navigate to http://localhost:8088/ to view the report.

(The reports will also be created locally on your hard drive, the container shows them via nginx.)

## Prerequisites

- Docker needs to be installed.
- Some PHP code to analyse needs to be on your local machine.

## Built With

* [docker](https://www.docker.com/) - The world's leading software containerisation platform.
* [phpmetrics](https://www.phpmetrics.org/) - A static analysis tool for PHP.
* [NGINX](https://www.nginx.com/) - High performance load balancer, web server and reverse proxy.
