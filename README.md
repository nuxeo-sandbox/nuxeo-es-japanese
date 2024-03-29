## Description
This package provides an elasticsearch / opensearch configuration and mapping for Japanese fulltext search.

## Important Note

**These features are not part of the Nuxeo Production platform.**

These solutions are provided for inspiration and we encourage customers to use them as code samples and learning resources.

This is a moving project (no API maintenance, no deprecation process, etc.) If any of these solutions are found to be useful for the Nuxeo Platform in general, they will be integrated directly into platform, not maintained here.

## Requirements
This plugin requires the ICU and Kurumoji analysis plugins to be installed on the elasticsearch / opensearch nodes.

## How to build
Building requires the following software:
- git
- maven

```
git clone https://github.com/nuxeo-sandbox/nuxeo-es-japanese
cd nuxeo-es-japanese
mvn clean install
```

## Deploying
* Install the marketplace package from the admin center or using nuxeoctl
* Reindex the nuxeo repository

## Test with Docker
```
git clone https://github.com/nuxeo-sandbox/nuxeo-es-japanese
cd nuxeo-es-japanese
docker-compose up
```

## Known limitations
This plugin is a work in progress.

## About Nuxeo
Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands. More information is available at [www.nuxeo.com](http://www.nuxeo.com).
