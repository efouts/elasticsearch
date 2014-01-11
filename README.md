## ElasticSearch Dockerfile


This repository contains **Dockerfile** of [ElasticSearch](http://www.elasticsearch.org/) for [Docker](https://www.docker.io/)'s [trusted build](https://index.docker.io/u/dockerfile/elasticsearch/) published to the public [Docker Registry](https://index.docker.io/).


### Dependencies

* [dockerfile/java](https://github.com/dockerfile/java)


### Installation

1. Install [Docker](https://www.docker.io/).

2. Download [trusted build](https://index.docker.io/u/dockerfile/elasticsearch/) from public [Docker Registry](https://index.docker.io/): `docker pull dockerfile/elasticsearch`

   (alternatively, you can build an image from Dockerfile: `docker build -t="dockerfile/elasticsearch" .`)


### Usage

    docker run dockerfile/elasticsearch
