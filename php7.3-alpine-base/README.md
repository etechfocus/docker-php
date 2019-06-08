Overview

  - This is to build a custom php docker image with additional utilties:
    * ssh
    * composer

Dockerhub

  - https://hub.docker.com/r/etechfocus/php7.3-alpine-base

How to try it out?
```
  docker run -it --rm etechfocus/php7.3-alpine-base:{VERSION} php --version
```
How to update the image?
```
  docker login --username=etechfocus --password={PASSWORD}
  docker build -t etechfocus/php7.3-alpine-base:{VERSION} .
  docker push etechfocus/php7.3-alpine-base:{VERSION}
```
