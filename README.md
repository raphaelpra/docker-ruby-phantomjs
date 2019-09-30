# docker-ruby-phantomjs

A simple Dockerfile to add a [`phantomJS` binary](http://phantomjs.org/download.html) directly into
a prebuilt [`ruby` image](https://hub.docker.com/r/_/ruby/) (for use on those rare occasions
when mounting a Docker volume into an image is not an option...)

The master branch adds `/usr/local/bin/phantomjs v2.1.1` into the `ruby:2.6.4` prebuilt image.

A docker image is automatically built by DockerHub from this repo
and made available at https://hub.docker.com/r/captive/docker-ruby-phantomjs/
