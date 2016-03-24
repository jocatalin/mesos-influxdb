# mesos-influxdb

[InfluxDB](https://github.com/influxdata/influxdb) framework for Mesos.

This uses the [Mesos-Framework](https://github.com/ContainerSolutions/mesosframework) project. The framework is generic and only becomes a InfluxDB framework with the correct configuration.

# Features
(Features come from the upstream [Mesos-Framework](https://github.com/ContainerSolutions/mesosframework) and [Mesos-Starter](https://github.com/ContainerSolutions/mesos-starter) projects)

- [x] State stored in ZooKeeper
- [x] Mesos Authorisation
- [ ] ZooKeeper Authorisation (should work, requires testing)
- [x] Live horizontal scaling via REST endpoint
- [x] Jar mode (no docker)
- [x] Resource specification (including port)
- [x] Import Kibana.yml settings file
- [x] "Spread" orchestration strategy (Spreads instances across distinct hosts)
- [x] Decoupled from Kibana. Use any version.
- [x] Decoupled from Mesos. Use any version 0.25+.
- [x] Single endpoint to check health of all instances

# Quick start
To start the kibana framework, simply start the mesosframework binary or docker container with a properties file containing your settings.

# License
Apache License 2.0
