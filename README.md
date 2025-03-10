# Rust Kata

## Objectives

Learn Rust ecosystem, e.g. structure, modules, package management, testing.

## Pre-requisites

* Install Rust: https://www.rust-lang.org/tools/install
* Install protoc: https://grpc.io/docs/protoc-installation/

## Content of this repository

### Hello World

`cd hello_world`
`cargo run`

### Hello World with Rest API

`cd hello_world_rest`
`cargo run`
`curl http://localhost:3000/hello`

### Hello World with gRPC API

`cd hello_world_grpc`
`cargo run --bin hello-world-grpc-server`

In another terminal: `cargo run --bin hello-world-grpc-client`

### Unit Tests

`cd unit_tests`
`cargo test`

### Mocking

`cd mocking`
`cargo test`

## Tasks

* Define a REST API for your choise of domain.
* Implement the Rust backend for the REST API.
* Define a gRPC API for your choise of domain. 
* Implement the Rust backend for the gRPC API.
* Adapt the Rust REST API backend to act as gateway to call the gRPC server.



