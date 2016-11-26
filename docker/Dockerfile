FROM ubuntu:16.04
RUN apt-get update; apt-get upgrade -y

# Get the packages required to run pandoc_resume
ENV TERM=xterm-256color
RUN apt-get install -y git make pandoc context

WORKDIR /root

# Grab the repo so we can make a resume
RUN git clone https://github.com/toddbu/pandoc_resume.git
