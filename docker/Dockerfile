# docker build -t ssh-sandbox .
FROM ubuntu:22.04

RUN apt-get -y update
RUN apt-get -y dist-upgrade
RUN apt-get -y install 	openssh-client \
			vim byobu rsync


WORKDIR /root

# docker run -it ssh-sandbox byobu
