# Tomcat 9 Images

Tomcat 9 image including Manager

To build

- docker build --force-rm --rm -t  'TAG_NAME' .

To run

- docker run -it --rm -p 8888:8080 --name 'CONTAINER_NAME' 'TAG_NAME'
