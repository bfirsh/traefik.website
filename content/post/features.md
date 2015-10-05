+++
date = "2015-09-11T00:41:40+02:00"
title = "Features"
weight = 2
type = "post"

+++

* No dependency hell, single binary made with go
* Simple json Rest API
* Simple TOML file configuration
* Multiple backends supported: Docker, Mesos/Marathon, Consul, Etcd, Zookeper, BoltDB and more to come
* Watchers for backends, can listen change in backends to apply a new configuration automatically
* Hot-reloading of configuration. No need to restart the process
* Graceful shutdown http connections during hot-reloads
* Circuit breakers on backends
* Round Robin, rebalancer load-balancers
* Rest Metrics
* Tiny docker image included
* SSL backends support
* SSL frontend support
* WebUI
