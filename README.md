# WebSocket library for Onyx

## Installation

You need to have [Onyx](https://onyxlang.io) installed with at least version `0.1.10` (or newest nightly).

When inside your Onyx project, simply run these commands:

```sh
onyx add websockets
onys sync
```

If you are writing a WebSocket *server*, you need to install the `http-server` package as well.

```sh
onyx add http-server
onys sync
```

If you are writing a WebSocket *client* with `wss://` connections, you need to install the `openssl` package as well.

```sh
onyx add openssl
onys sync
```

## Usage

See the [example](https://github.com/onyx-lang/pkg-websockets/tree/main/example) folder for simple examples of using this package as a client or on a server.

