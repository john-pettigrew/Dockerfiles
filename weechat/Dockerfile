FROM ubuntu
MAINTAINER John Pettigrew <john.pettigrew404@gmail.com>
RUN useradd -ms /bin/bash app
RUN apt-get update
RUN apt-get install -y weechat
USER app
ENV TERM xterm
ENTRYPOINT weechat
