By using Docker multi-stage build (Dockerfile_v2) approach I can reduce the image size from 510MB to 161MB.

$ docker images
REPOSITORY                TAG             IMAGE ID       CREATED         SIZE
venu1322/django-web-app   0.0.1.RELEASE   d229601c80a4   6 weeks ago     510MB
venu1322/django-web-app   0.0.2.RELEASE   6e5097832f92   5 minutes ago   161MB
