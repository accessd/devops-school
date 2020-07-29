FROM ubuntu:18.04

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get -qq update \
  && apt-get install -y -q python3 python3-pip \
  && rm -rf /var/lib/apt/lists/*

COPY requirements.txt /app/
WORKDIR /app
RUN /bin/bash -c "pip3 install -q virtualenv && virtualenv /pyenv && source /pyenv/bin/activate \
  && pip3 install -qr requirements.txt"
