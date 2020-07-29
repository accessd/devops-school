# DevOps School 7

## Use docker-compose

We have 2 services:

    builder
    web


`builder` - setups python requirements for app.
`web` - runs uwsgi server.

We're using `virtualenv` to place dependencies in separate directory.

## How to use

Run:

    docker-compose up -d

Visit http://your-public-ip:8080
