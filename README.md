[![Node.js CI](https://github.com/stbestichhh/lcs-cloud-storage-docs/actions/workflows/node.js.yml/badge.svg)](https://github.com/stbestichhh/lcs-cloud-storage-docs/actions/workflows/node.js.yml)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# lcs-cloud-storage documentation

## About
This website provides documentation for lcs-cloud-storage server application. There you will find about instalation, deployment, CLI and API usage, contributing and etc.

## Getting started

### Prerequisites

* yarn `npm i -g yarn` or `corepack enable`

> [!IMPORTANT]
> **Node.js 18.x+** version must be installed in your OS.

### Deploy localy

1. Clone the repository

```shell
$ https://github.com/stbestichhh/lcs-cloud-storage-docs
```

2. Install dependencies

```shell
$ yarn install
```

3. Start the local server

  * Development
    ```shell
    $ yarn start
    ```

  * Production
    ```shell
    $ yarn build
    $ yarn start:prod
    ```

#### or deploy without installing

```shell
$ docker build -t lcs-cloud-storage-docs:0.0.1 .
$ docker run -p <port>:3000 lcs-cloud-storage-docs:0.0.1
```

## Authors

* [@stbestichhh](https://github.com/stbestichhh)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE)
