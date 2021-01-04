<div align="center">
  <img alt="dev in docker" src="images/dev-in-docker-logo-wide.png" width="300px">
</div>
<br>
This project provides a basic Docker setup, for building a local development environment with HTTPS support.

## What does it do?
Devindocker run a container with a reverse proxy and load balancer called [Træfik](https://github.com/traefik/traefik). This will be the only container to expose a port to our docker host. The containers of the different projects and the træfik container will be in the same docker network. Træfik will forward the requests from the client to the corresponding container.
<br>
<br>
<div align="center">
	<img alt="dev in docker" src="images/mockup.jpg" width="600px">
</div>
<br>
<br>
