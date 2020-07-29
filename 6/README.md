# DevOps School 6

## Pack simple hello world app to docker

We need to build app with `maven` inside image, so use multi-stage builds.

## How to use

Build:

    docker build -t boxfuse .

Run container with:

    docker run --name boxfuse -p 8080:8080 -d boxfuse

Visit http://your-public-ip:8080/hello-1.0

That's it!
