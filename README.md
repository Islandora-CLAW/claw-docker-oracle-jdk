# Islandora CLAW: Java Docker Image

[![Docker Stars](https://img.shields.io/docker/stars/islandora/claw-oracle-jdk.svg)](https://hub.docker.com/r/islandora/claw-oracle-jdk/)
[![Docker Pulls](https://img.shields.io/docker/pulls/islandora/claw-oracle-jdk.svg)](https://hub.docker.com/r/islandora/claw-oracle-jdk/)
[![Contribution Guidelines](http://img.shields.io/badge/CONTRIBUTING-Guidelines-blue.svg)](./CONTRIBUTING.md)
[![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](./LICENSE)

## Introduction

Defines the Java Docker image from which we build our Java based images (Tomcat, Karaf, etc), uses Oracle JDK.

Based on the [Base Docker Image](https://github.com/Islandora-CLAW/docker-base).

## Includes

* Oracle Java 8

## Build Arguments

No build arguments are provided.

**Example:**
```bash
docker build -t islandora/claw-oracle-jdk .
```

## Environment Variables

| Variable  | Required | Default |
|-----------|----------|---------|
| JAVA_OPTS | no       |         |

**Example (foreground, auto-remove, interactive shell):**
```bash
docker run --rm -ti islandora/claw-oracle-jdk ash
```

## Notes

Currently this has been tested to work with Tomcat, but only lightly. It is
known to not work with Karaf, and at the moment further development on this
image is halted.

## Maintainers/Sponsors

* UPEI
* discoverygarden inc.
* LYRASIS
* McMaster University
* University of Limerick
* York University
* University of Manitoba
* Simon Fraser University
* PALS
* American Philosophical Society
* common media inc.

Current maintainers:

* [Nigel Banks](https://github.com/nigelgbanks)
* [Nick Ruest](https://github.com/ruebot)

## Development

If you would like to contribute, please get involved by attending our weekly [Tech Call](https://github.com/Islandora-CLAW/CLAW/wiki). We love to hear from you!

If you would like to contribute code to the project, you need to be covered by an Islandora Foundation [Contributor License Agreement](http://islandora.ca/sites/default/files/islandora_cla.pdf) or [Corporate Contributor Licencse Agreement](http://islandora.ca/sites/default/files/islandora_ccla.pdf). Please see the [Contributors](http://islandora.ca/resources/contributors) pages on Islandora.ca for more information.

## License

[MIT](https://opensource.org/licenses/MIT)
