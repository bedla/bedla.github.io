---
layout: post
title: "Running Docker in Docker with shared Volume mounts from Host filesystem using Windows (and WSL)"
categories:
  - docker
  - testcontainers
  - mount
  - volume
  - wsl
  - dind
---

In the article we will show mounting shared Host filesystem and running Docker container from already started Docker container (Docker in Docker).
We will walk through running solely from Windows command line or using [WSL](https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux) terminal.

All documentation and source-code could be found here [https://github.com/bedla/docker-inception-mount](https://github.com/bedla/docker-inception-mount).
