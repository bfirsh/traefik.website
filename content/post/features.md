+++
date = "2015-09-11T00:41:40+02:00"
title = "Features"
weight = 2
type = "post"

+++

- [It's fast](http://docs.traefik.io/benchmarks)
- No dependency hell, single binary made with go
- Rest API
- Multiple backends supported: Docker, Mesos/Marathon, Consul, Etcd, and more to come
- Watchers for backends, can listen change in backends to apply a new configuration automatically
- Hot-reloading of configuration. No need to restart the process
- Graceful shutdown http connections
- Circuit breakers on backends
- Round Robin, rebalancer load-balancers
- Rest Metrics
- [Tiny](https://imagelayers.io/?images=traefik) [official](https://hub.docker.com/r/_/traefik/) docker image included
- SSL backends support
- SSL frontend support (with SNI)
- Clean AngularJS Web UI
- Websocket support
- HTTP/2 support
- Retry request if network error
- [Let's Encrypt](https://letsencrypt.org) support (Automatic HTTPS)
