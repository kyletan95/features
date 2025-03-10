
# sbt (via SDKMAN) (sbt-sdkman)

SBT is an open source build tool for Scala and Java projects, similar to Java's
Maven or Ant. Its main features are: native support for compiling Scala code and
integrating with many Scala test frameworks; build descriptions written in Scala
using a DSL; dependency management using Ivy (which supports Maven-format
repositories); continuous compilation, testing, and deployment; integration with
the Scala interpreter for rapid iteration and debugging; support for mixed
Java/Scala projects

## Example DevContainer Usage

```json
"features": {
    "ghcr.io/devcontainers-contrib/features/sbt-sdkman:2": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| version | Select the version of sbt to install. | string | latest |
| jdkVersion | Select or enter a JDK version to install. | string | latest |
| jdkDistro | Select or enter a JDK distribution to install | string | ms |


