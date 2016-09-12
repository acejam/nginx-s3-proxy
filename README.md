# nginx-s3-proxy

[![Build Status](https://travis-ci.org/acejam/nginx-s3-proxy.svg?branch=basic-setup)](https://travis-ci.org/acejam/nginx-s3-proxy)
[![Docker Stars](https://img.shields.io/docker/stars/acejam/nginx-s3-proxy.svg?maxAge=2592000)](https://hub.docker.com/r/acejam/nginx-s3-proxy)
[![Docker Pulls](https://img.shields.io/docker/pulls/acejam/nginx-s3-proxy.svg?maxAge=2592000)](https://hub.docker.com/r/acejam/nginx-s3-proxy)

A Docker container for reverse proxying S3 via nginx

## Quick Start

    docker run -d --name nginx-s3-proxy --restart=always -e S3_BUCKET=your-bucket-here -e AWS_ACCESS_KEY=your-key-here -e AWS_SECRET_KEY=your-secret-key-here -p 80:80 acejam/nginx-s3-proxy

## Config options

This container includes support for various configuration values. These values can be set when calling `docker run` through the use of environment variables.

The following values are configurable:
* `S3_BUCKET`
* `AWS_ACCESS_KEY`
* `AWS_SECRET_KEY`
