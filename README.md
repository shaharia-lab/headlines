# headlines

A simple tool to fetch news headlines from different news sources.

## Features

- REST Api endpoints. See the OpenAPI schema [here](https://github.com/shaharia-lab/headlines/blob/main/openapi.yaml).
- A basic UI to see the headlines

![image](https://github.com/user-attachments/assets/3c20dda2-a1b0-458a-862b-057648af81c9)


## Installation

### Using Docker

Get the latest version from the [release page](https://github.com/shaharia-lab/headlines/releases)

```bash
docker run -p 8081:8080 ghcr.io/shaharia-lab/headlines:{VERSION}
```

### Using Binary

Download the binary from the [release page](https://github.com/shaharia-lab/headlines/releases)

### Run from source

Please clone the repository and run the following command.

```bash
go run . -port 8080
```

Please go to http://localhost:8080 to see the UI.

## Contribution

It's very easy to add more news sources. Feel free to create a PR or. If you have any issues, please feel free to submit an issue [here](https://github.com/shaharia-lab/headlines/issues).

## License

Please see the license [here](https://github.com/shaharia-lab/headlines/blob/main/LICENSE).
