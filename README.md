# siddhi-docker
Sample siddhi app with Docker setup from docs

#Steps to run
1)Run docker
docker run -it -p 8006:8006 -v ${PWD}:/apps siddhiio/siddhi-runner-alpine
-Dapps=/apps/HelloWorldApp.siddhi