# Docker Asterisk
Dockerized(Containerized) asterisk server

You can build and run the image with docker command as
```bash
docker run -p 5060:5060 -p 5038:5038 asterisk
```

Or
You can use docker-compose in this repo to just build and run asterisk.

If you want to bring up both [kannel](https://github.com/antenehrepos/docker-kannel) and asterisk with docker-compose, please look at [this](https://github.com/antenehrepos/docker-telephony) repo.
