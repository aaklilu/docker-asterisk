# Docker Asterisk
Dockerized(Containerized) asterisk server

### Usage
You can simply run the server as follows

```bash
docker run -p 5060:5060 -p 5038:5038 antenehrepos/asterisk-kannel
```

Or 

Build and run the image from the docker file with docker command like so
```bash
docker build -t asterisk
docker run -p 5060:5060 -p 5038:5038 asterisk
```

Or

You can use docker-compose in this repo to just build and run Asterisk.

### Copyright and license
    A docker image to run Asterisk server

    Copyright (C) 2016, Anteneh Aklilu

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see http://www.gnu.org/licenses/.

If you want to bring up both [kannel](https://github.com/antenehrepos/docker-kannel) and asterisk with docker-compose, please look at [this](https://github.com/antenehrepos/docker-telephony) repo.

[![](https://images.microbadger.com/badges/image/antenehrepos/docker-asterisk.svg)](https://microbadger.com/images/antenehrepos/docker-asterisk "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/antenehrepos/docker-asterisk.svg)](https://microbadger.com/images/antenehrepos/docker-asterisk "Get your own version badge on microbadger.com")
