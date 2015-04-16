Docker Nginx Static
===============

> Build a docker image that serves static content with Nginx


## Requirements

- [boot2docker](http://boot2docker.io) (not required for Linux)
- a [docker hub](http://hub.docker.com) account

## Building & running your image

- `docker build -t youruser/yourproject .`
- `docker run -d -p 80:80 --name project youruserName/yourproject`
