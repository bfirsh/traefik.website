+++
date = "2015-09-11T00:41:21+02:00"
title = "Get it"
weight = 5
type = "post"

+++

* The simple way: grab the latest binary from the [releases](https://github.com/containous/traefik/releases) page and just run it with the [sample configuration file](https://raw.githubusercontent.com/containous/traefik/master/traefik.sample.toml):

```
./traefik traefik.toml
```

* Use the tiny Docker image:

```
docker run -d -p 8080:8080 -p 80:80 -v $PWD/traefik.toml:/traefik.toml containous/traefik
```

* From sources:

```
git clone https://github.com/containous/traefik
```

You can find the complete documentation [here](https://github.com/containous/traefik/blob/master/docs/index.md).

Come talk to us! <script async defer src="https://traefik.herokuapp.com/slackin.js?large"></script><br>

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/containous/traefik/blob/master/LICENSE.md)
