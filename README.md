# Docker sbt-scala image

Docker image for continuous [sbt](http://www.scala-sbt.org)-[scala](http://scala-lang.org) integration testing.
[Coursier](https://github.com/alexarchambault/coursier) sbt plugin is included for faster artefacts fetching and [Scoverage](https://github.com/scoverage/sbt-scoverage) for code coverage.

Available versions (sbt/scala): `0.13.13/2.11.8`

## Getting started

- install [docker](https://docs.docker.com/engine/installation/)
- run
```shell
docker run -it --rm charafau/sbt-scala
```

- or build from this sources
```shell
docker build github.com/charafau/docker-sbt-scala
```

## License

Forked from [scala-sbt](https://github.com/zifeo/scala-sbt) under the [Apache 2.0 License](https://github.com/charafau/docker-sbt-scala/blob/master/LICENSE) with updated versions and inclusions.
