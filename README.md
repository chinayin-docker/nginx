# Nginx Image

[![Docker Image CI](https://github.com/chinayin-docker/nginx/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/chinayin-docker/nginx/actions/workflows/ci.yml)
![Docker Image Version (latest semver)](https://img.shields.io/docker/v/chinayin/nginx?sort=semver)
![Docker Image Size (latest semver)](https://img.shields.io/docker/image-size/chinayin/nginx?sort=semver)
![Docker Pulls](https://img.shields.io/docker/pulls/chinayin/nginx)

Nginx (pronounced "engine-x") is an open source reverse proxy server for HTTP, HTTPS, SMTP, POP3, and IMAP protocols, as
well as a load balancer, HTTP cache, and a web server (origin server). The nginx project started with a strong focus on
high concurrency, high performance and low memory usage. It is licensed under the 2-clause BSD-like license and it runs
on Linux, BSD variants, Mac OS X, Solaris, AIX, HP-UX, as well as on other *nix flavors. It also has a proof of concept
port for Microsoft Windows.

### Supported tags and respective `Dockerfile` links

![](https://img.shields.io/docker/v/chinayin/nginx/1.22)

### Image Variants

- `nginx:<version>`

### Usage

You can use the image directly, e.g.

```
docker run --rm -it chinayin/nginx:1.22.0
```

The images are built daily and have the security release enabled, so will contain any security updates released more
than 24 hours ago.

You can also use the images as a base for your own Dockerfile:

```
FROM chinayin/nginx:1.22
```
