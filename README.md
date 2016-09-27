# docker-ruby-phantomjs

A simple Dockerfile to add the `phantomJS` binary directly into a prebuilt `ruby` image
(for those rare occasions when mounting a Docker volume into an image is not an option...)

The master branch extends `ruby:2.3.1` and adds `/usr/local/bin/phantomjs v2.1.1`

A docker image is automatically built / made available at https://hub.docker.com/r/prime8/docker-ruby-phantomjs/
