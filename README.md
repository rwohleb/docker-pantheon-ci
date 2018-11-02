# Docker Pantheon CI

This is the source Dockerfile for the [rwohleb/pantheon-ci](https://hub.docker.com/r/rwohleb/pantheon-ci/) docker image.

## Image Contents

- [CircleCI PHP 7.2 Docker base image w/ NodeJS](https://hub.docker.com/r/circleci/php/)
- [Terminus](https://github.com/pantheon-systems/terminus)
- Terminus plugins
  - [Terminus Build Tools Plugin](https://github.com/pantheon-systems/terminus-build-tools-plugin)
  - [Terminus Secrets Plugin](https://github.com/pantheon-systems/terminus-secrets-plugin)
  - [Terminus Rsync Plugin](https://github.com/pantheon-systems/terminus-rsync)
  - [Terminus Quicksilver Plugin](https://github.com/pantheon-systems/terminus-quicksilver-plugin)
  - [Terminus Composer Plugin](https://github.com/pantheon-systems/terminus-composer-plugin)
  - [Terminus Drupal Console Plugin](https://github.com/pantheon-systems/terminus-drupal-console-plugin)
  - [Terminus Mass Update Plugin](https://github.com/pantheon-systems/terminus-mass-update)
- Test scripts
