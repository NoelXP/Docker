FROM ubuntu:latest
MAINTAINER Noel Presti "noelxp@gmail.com"
ENV REFRESHED_AT 2021-5-14
RUN apt-get update
RUN apt-get -y install ruby ruby-dev build-essential redis-tools
RUN gem install sinatra json redis
RUN mkdir -p /opt/webapp

EXPOSE 4567

CMD [ "/opt/webapp/bin/webapp/" ]

