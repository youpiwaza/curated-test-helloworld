# Tutum curated hello world

Docker compose file to use as a docker stack, to provide a test web server.

Use of [tutum image](https://hub.docker.com/r/tutum/hello-world/).

Intended to work with Traefik reverse proxy stack, cf. labels.

Currently hard-coded to set to containers for

- [test.masamune.fr](http://test.masamune.fr)
- [test.masamune.fr/sub/](http://test.masamune.fr/sub)

See:

- [Examples & test](https://github.com/youpiwaza/server-related-tutorials/tree/master/01-docker/04-my-tests/09-traefik-curated)
- [Final web serveur ansible project](https://github.com/youpiwaza/ansible-install-web-server)

## TODO

1. Enable docker dedicated user
2. Enable & test HTTPS
3. Use as a j2 template file in main project ?
