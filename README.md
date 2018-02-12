[![Circle CI](https://circleci.com/gh/codeworksio/docker-jenkins.svg?style=shield "CircleCI")](https://circleci.com/gh/codeworksio/docker-jenkins)&nbsp;[![Size](https://images.microbadger.com/badges/image/codeworksio/jenkins.svg)](http://microbadger.com/images/codeworksio/jenkins)&nbsp;[![Version](https://images.microbadger.com/badges/version/codeworksio/jenkins.svg)](http://microbadger.com/images/codeworksio/jenkins)&nbsp;[![Commit](https://images.microbadger.com/badges/commit/codeworksio/jenkins.svg)](http://microbadger.com/images/codeworksio/jenkins)&nbsp;[![Docker Hub](https://img.shields.io/docker/pulls/codeworksio/jenkins.svg)](https://hub.docker.com/r/codeworksio/jenkins/)

Docker OpenJDK 8
================

Continuous Integration server.

Installation
------------

Builds of the image are available on [Docker Hub](https://hub.docker.com/r/codeworksio/jenkins/).

    docker pull codeworksio/jenkins

Alternatively you can build the image yourself.

    docker build --tag codeworksio/jenkins \
        github.com/codeworksio/docker-jenkins

Testing
-------

    make build test
