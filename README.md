# nginx-s3-proxy

A Docker container for a custom version of nginx
<!--


[![Build Status](https://travis-ci.org/acejam/docker-bitmessage.svg?branch=basic-setup)](https://travis-ci.org/acejam/docker-bitmessage)
[![Docker Stars](https://img.shields.io/docker/stars/acejam/bitmessage.svg?maxAge=2592000)](https://hub.docker.com/r/acejam/bitmessage)
[![Docker Pulls](https://img.shields.io/docker/pulls/acejam/bitmessage.svg?maxAge=2592000)](https://hub.docker.com/r/acejam/bitmessage)

A Docker container for Bitmessage

## Quick Start

    docker run -d --name bitmessage --restart=always -v /data/bitmessage:/root/.config/PyBitmessage -p 8444:8444 -p 8442:8442 acejam/bitmessage:latest

## Config options

This container includes support for various Bitmessage configuration values. These values can be set when calling `docker run` through the use of environment variables.

The following values are configurable:
* `RPC_USER`
* `RPC_PASS`
* `RPC_INTERFACE`

For example, to run the container with the username "DevUser" and a password of "P@ssw0rd123", you can run the following:

      docker run -d -e RPC_USER="DevUser" -e RPC_PASS="P@ssw0rd123" acejam/bitmessage:latest

## Data persistence

Coming soon! -->
