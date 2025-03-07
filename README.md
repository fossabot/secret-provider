![Action Status](https://github.com/lensesio/secret-provider/workflows/CI/badge.svg)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Flensesio%2Fsecret-provider.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Flensesio%2Fsecret-provider?ref=badge_shield)
[<img src="https://img.shields.io/badge/docs--orange.svg?"/>](https://docs.lenses.io/4.0/integrations/connectors/secret-providers/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# Secret Provider

Secret provider for Kafka to provide indirect look up of configuration values.


## Installing

Maven
```xml
<dependency>
	<groupId>io.lenses</groupId>
	<artifactId>secret-provider</artifactId>
	<version>2.1.3</version>
</dependency>
```

SBT
```bash
libraryDependencies += "io.lenses" % "secret-provider" % "2.1.3"
```

Gradle
```bash
compile 'io.lenses:secret-provider:2.1.3'
```

## Description

External secret providers allow for indirect references to be placed in an
applications configuration, so for example, that secrets are not exposed in the
Worker API endpoints of Kafka Connect.

For [Documentation](https://docs.lenses.io/4.0/integrations/connectors/secret-providers/).


## Contributing

We'd love to accept your contributions! Please use GitHub pull requests: fork
the repo, develop and test your code,
[semantically commit](http://karma-runner.github.io/1.0/dev/git-commit-msg.html)
and submit a pull request. Thanks!

### Building

***Requires gradle 6.0 to build.***

To build

```bash
gradle compile
```

To test

```bash
gradle test
```

To create a fat jar

```bash
gradle shadowJar
```

You can also use the gradle wrapper

```
./gradlew shadowJar
```


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Flensesio%2Fsecret-provider.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Flensesio%2Fsecret-provider?ref=badge_large)