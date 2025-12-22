---
layout: post
title: "File owner when running with or without user specified"
categories:
  - docker
  - testcontainers
  - mount
---


In this example we will show what is the difference between creating file inside mounted directory 
with container started with or without user/group specified.

We are running examples using WSL, to mimic standard Host Linux filesystem. 
Later we will show that running same directly using Windows command line/PowerShell does not have same issue, 
like we have with Linux filesystem.

All documentation and source-code could be found here [https://github.com/bedla/testcontainers-created-host-file-owner](https://github.com/bedla/testcontainers-created-host-file-owner).
