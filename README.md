# gocd-agent-docker
Embedded docker within GoCD Agent container


Based on latest build of gocd-agent. You can check for more info on
the [official page]([gocd-agent](https://hub.docker.com/r/gocd/gocd-agent/).

This image has an already embedded docker client and docker-compose binary, so just by defining the `DOCKER_HOST` environment var in your pipeline you are ready to run related docker commands in your GoCD jobs.

Don't forget to set the host and port (i.e.: `172.17.0.1:2375`)
