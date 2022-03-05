FROM ubuntu
WORKDIR /app
RUN apt-get update && sudo apt install default-jre
COPY HelloWorld.class .
ENTRYPOINT["java","HelloWorld"]
