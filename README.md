[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/gurraoptimus/rusty/tree/rust?quickstart=1)

# Rusty
## [Web app Rusty](src/main.rs)


<!-- TABLE OF CONTENTS -->
## Table of Contents
* [Installation](#install)
* [Setup](#setup)
* [Serve](#serve)

## install
1. ### install rust
````
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
````
## setup
2. ### setup trunk

````
cargo install trunk
rustup target add wasm32-unknown-unknown
````
## serve
3. ### Run Trunk

````
trunk serve
````