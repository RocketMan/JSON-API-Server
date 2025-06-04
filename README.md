JSON API Server
===============
[![Build Status](https://github.com/RocketMan/JSON-API-Server/actions/workflows/main.yml/badge.svg?branch=master)](https://github.com/RocketMan/JSON-API-Server)

[![license](https://img.shields.io/github/license/RocketMan/JSON-API-Server)](https://github.com/RocketMan/JSON-API-Server/blob/master/LICENSE)
[![latest version](https://badgen.net/github/release/RocketMan/JSON-API-Server?label=latest)](https://github.com/RocketMan/JSON-API-Server/releases)

Abstract server-side php implementation of the [json api specification](http://jsonapi.org/format/).

This is a fork of the upstream `enm/json-api-server` with post-release
fixes.

## Installation

```sh
composer require rocketman/json-api-server
```

## Documentation
First you should read the docs at [`rocketman/json-api-common`](https://github.com/RocketMan/JSON-API-Common/) where all basic structures are defined.

1. [Json Api Server](docs/json-api-server/index.md)
    1. [Endpoints](docs/json-api-server/index.md#endpoints)
    1. [Usage](docs/json-api-server/index.md#usage)
1. [Request Handler](docs/request-handler/index.md)
    1. [Concept](docs/request-handler/index.md#concept)
    1. [Interface](docs/request-handler/index.md#interface)
    1. [Usage](docs/request-handler/index.md#usage)
1. [Exception handling](docs/exception-handling/index.md)

See [Change Log](CHANGELOG.md) for changes!
