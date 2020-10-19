# Docker Compose files

To buid:
- docker-compose build --no-cache

To run
- docker-compose up -d 

To check status:

- docker ps

e.g.

<table>
<tr><th>CONTAINER ID</th><th>IMAGE</th><th>COMMAND</th><th>CREATED</th><th>STATUS</th><th>PORTS</th><th>NAMES</th></tr>

<tr><td>1048717f2fce</td><td>welchie99/tomcat:9.0</td><td>"catalina.sh run"</td><td>41 minutes ago</td><td>Up 41 minutes (healthy)</td><td>0.0.0.0:8888->8080/tcp</td><td>stravastats_tomcat_1</td><tr>

<tr><td>ad3b09566d9b</td><td>postgres:latest</td><td>"docker-entrypoint.s…"</td><td><td>3 hours ago</td><td>Up 3 hours (healthy)</td><td>0.0.0.0:5432->5432/tcp</td><td>stravastats_postgres_1</td></tr>
</table>

