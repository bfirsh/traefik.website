+++
date = "2015-09-11T00:41:21+02:00"
title = "Get it"
weight = 5
type = "post"

+++

- The simple way: grab the latest binary from the [releases](https://github.com/containous/traefik/releases) page and just run it with the [sample configuration file](https://raw.githubusercontent.com/containous/traefik/master/traefik.sample.toml):

```shell
./traefik -c traefik.toml
```

- Use the tiny Docker image:

```shell
docker run -d -p 8080:8080 -p 80:80 -v $PWD/traefik.toml:/etc/traefik/traefik.toml traefik
```

- From sources:

```shell
git clone https://github.com/containous/traefik
```

You can find the complete documentation [here](https://docs.traefik.io).
