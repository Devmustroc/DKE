# RUN ubuntu image
FROM ubuntu:22.04

#Update install curl and clean lists apt 
RUN apt-get update && apt-get install -y curl \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
#create a direcory
RUN mkdir /home/Codes

#Create a username 
ENV USER Devmust
ENV SHELL /bin/bash
ENV LOGNAME Devmustroc

CMD ["bash"]