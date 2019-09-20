# Hoist Dockerfile: xh-nginx

[Hoist React](https://github.com/xh/hoist-react/) apps can be deployed
via Docker containers running Tomcat (for Hoist's Grails based back-end)
and nginx (to serve compiled client JS/CSS and other assets).

This repo contains a minimal Dockerfile to build the base nginx
container, which can be used by app-specific Docker deployments with
additional configurations.

This image is
[available on Docker Hub](https://hub.docker.com/r/xhio/xh-nginx/).

----

📫☎️🌎 info@xh.io | <https://xh.io/contact>

Copyright © 2019 Extremely Heavy Industries Inc.
