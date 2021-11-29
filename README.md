# React + WASM

This is a simple boilerplate base on Create React App (ejected) and wasm-pack + Rust

Eject from CRA is required in order to add some custom webpack config (`wasm-loader` and update `file-loader`).

WASM modules are packed as npm packages and can be imported locally using `package.json`

No CI/CD set up.