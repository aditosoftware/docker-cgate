# docker-cgate
Preconfigured Communigate Pro Server with Testusers

Introduction

This docker image installs CommuniGate Pro using Alpine Linux.
A documentation can be found here:
[https://www.communigate.com/communigatepro/](https://www.communigate.com/communigatepro/)

This docker image is based on the one provided by runningman84.
(https://hub.docker.com/r/runningman84/cgate/)
(https://github.com/runningman84/docker-cgate/)


Installation

docker pull aditosoftware/docker-cgate

Run

docker run --name <name> -d -P -p 8010:8010 -p 8100:8100 -p 25:25 -p 110:110 -p 143:143 aditosoftware/docker-cgate

Connect

docker exec -ti <name> /bin/sh