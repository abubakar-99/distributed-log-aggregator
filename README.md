# distributed-log-aggregator

![Go](https://img.shields.io/badge/Go-1.22-00ADD8?logo=go) ![License](https://img.shields.io/badge/License-MIT-green) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Collects and streams logs from microservices to a queryable store.

## Overview

This tool provides a production-ready implementation focused on performance, security, and developer experience. Built with modern best practices and designed for real-world deployment.

## Features

- **High performance** — optimized for low latency and high throughput
- **Production ready** — proper error handling, logging, and observability
- **Well tested** — unit and integration tests included
- **Easy to deploy** — Docker support out of the box

## Installation

```bash
git clone https://github.com/abubakar-99/distributed-log-aggregator
cd distributed-log-aggregator
go mod tidy
```

## Usage

```bash
go run cmd/main.go
```

## Architecture

```
distributed-log-aggregator/
├── src/
│   ├── main.go
│   ├── core/
│   └── utils/
├── tests/
├── docs/
├── Dockerfile
└── README.md
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

## License

[MIT](LICENSE)
