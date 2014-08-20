---
layout: post
title:  "Stop all Docker containers"
date:   2014-08-22 19:00:00
categories: How-to
---

[Docker](https://www.docker.com/ "Docker - Build, Ship, and Run Any App, Anywhere") is a fantastic tool to create lightweight containers for any application or stack, powered by LXC, which I'm a big fan of. later, I will write a blog post about it for people who don't know much about Docker.

One of the missing command in docker CLI is `docker stop all` to stop all containers at once, and as usual there is nothing impossible.

The following command is actually tow commands in one:
```bash
docker stop $(docker ps -a -q)
```
The first one is `docker stop` to stop container, and the second one `docker ps -a -q` is to list all the running containers.

And also you can use the same workaround to remove running containers
```bash
docker rm $(docker ps -a -q)
```

Have fun :)
