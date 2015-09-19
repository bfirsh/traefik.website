+++
date = "2015-09-11T00:41:21+02:00"
title = "Get it"
weight = 100
type = "post"
class="post last"

+++

* The simple way: grab the latest binary from [![the Github releases page](https://img.shields.io/github/downloads/EmileVauge/traefik/latest/total.svg)](https://github.com/emilevauge/traefik/releases) and just run it with the sample configuration file:

```
./traefik traefik.toml
```

* Use the tiny Docker image:

```
docker run -d -p 8080:8080 -p 80:80 -v $PWD/traefik.toml:/traefik.toml emilevauge/traefik
```

* From sources:

```
git clone https://github.com/EmileVauge/traefik
```

[![Circle CI](https://img.shields.io/circleci/project/EmileVauge/traefik.svg)](https://circleci.com/gh/EmileVauge/traefik)

[![Forks](https://img.shields.io/github/forks/EmileVauge/traefik.svg)](https://github.com/EmileVauge/traefik)

[![Stars](https://img.shields.io/github/stars/EmileVauge/traefik.svg)](https://github.com/EmileVauge/traefik)

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/EmileVauge/traefik/blob/master/LICENSE.md)
