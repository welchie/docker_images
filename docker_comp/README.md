# Docker Compose files

To buid:
- docker-compose build --no-cache

To run
- docker-compose up -d 

To check status:

- docker ps

e.g.

CONTAINER ID        IMAGE                  COMMAND                  CREATED             STATUS                    PORTS                    NAMES
1048717f2fce        welchie99/tomcat:9.0   "catalina.sh run"        41 minutes ago      Up 41 minutes (healthy)   0.0.0.0:8888->8080/tcp   stravastats_tomcat_1
ad3b09566d9b        postgres:latest        "docker-entrypoint.s…"   3 hours ago         Up 3 hours (healthy)      0.0.0.0:5432->5432/tcp   stravastats_postgres_1

