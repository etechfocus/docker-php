Overview

  This is to build a custom php+ssh docker image to be used in our deployment pipeline.

Dockerhub

  https://hub.docker.com/r/etechfocus/php-alpine

How to try it out?

  docker run -it --rm etechfocus/php-alpine:{VERSION} php --version

How to update the image?

  docker login --username=etechfocus --password={PASSWORD}
  docker build -t etechfocus/php-alpine:{VERSION} .
  docker push etechfocus/php-alpine:{VERSION}
