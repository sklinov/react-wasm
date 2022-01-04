# React + WASM

This is a simple boilerplate base on Create React App (ejected) and wasm-pack + Rust

Eject from CRA is required in order to add some custom webpack config.

`@shopify/react-web-worker` is used for handy management of webworker.

WASM modules are packed as npm packages and can be imported locally using `package.json`

WASM module is ran inside Web Worker to insure best performance.

No CI/CD set up.