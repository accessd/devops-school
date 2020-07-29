FROM ubuntu:18.04

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get -y update \
    # Python
    && apt-get -y install python3 python3-pip \
    && rm -rf /var/lib/apt/lists/*
