FROM tomcat:9.0
MAINTAINER chris@weewelchie.org

COPY files/tomcat-users.xml /usr/local/tomcat/conf/.
RUN mv /usr/local/tomcat/webapps.dist/manager /usr/local/tomcat/webapps/
COPY files/context.xml /usr/local/tomcat/webapps/manager/META-INF/.

EXPOSE 8080

CMD ["catalina.sh", "run"]
