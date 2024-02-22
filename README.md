# grpcalculator-rs

This is the companion project to the Dreams of Code YouTube video on [Rust and gRPC with Tonic](https://youtu.be/kerKXChDmsE)

Please see the linked video for more information.

# Requirements

## Rust
In order to run this code, you'll need at least Rust 1.76 installed on your system.

## Protoc
As well as rust, you'll also need the protobuf compiler as well.

### Arch

```
pacman -S protobuf
```

### macOS

```
brew install protobuf
```

# Running

This project contains two binaries, a server and a client.

## Server

```
cargo run --bin server
```

## Client

```
cargo run --bin client
```

# Frontend

There is a companion frontend project that goes with this code found [here](https://github.com/dreamsofcode-io/grpcalculator-web)
