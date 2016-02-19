FROM ubuntu:14.04

MAINTAINER Claude-Arnaud PERROT "claude-arnaud.perrot@prestashop.com"

RUN apt-get update -qq && apt-get install -qqy nodejs npm git

RUN mkdir /root/.ssh

ADD gitkey /root/.ssh/id_rsa

RUN ssh-keyscan github.com >> /root/.ssh/known_hosts

RUN chmod 400 /root/.ssh/id_rsa
