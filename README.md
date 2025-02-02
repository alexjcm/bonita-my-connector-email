# My Email Connector

[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-yellow.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

## Build

__Clone__ or __fork__ this repository, then at the root of the project run:

`./mvnw clean package`

## Release

In order to create a new release: 
- On the release branch, make sure to update the pom version (remove the -SNAPSHOT)
- Run the action 'Create release', set the version to release as parameter
- When the action is completed, do not forget to manage the release on the nexus (close and release)
- Update the `master` with the next SNAPSHOT version.

## Contributing

We would love you to contribute, pull requests are welcome! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) for more information.

## License

The sources and documentation in this project are released under the [GPLv2 License](LICENSE)

