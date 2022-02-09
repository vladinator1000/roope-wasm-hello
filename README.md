## roope-wasm-hello
A scratch greeting card made with WebAssembly.

## How to install

1. Install Rust if you don't have it https://rustup.rs/
1. Install `wasm-pack` https://rustwasm.github.io/wasm-pack/installer/
1. Use Node 16 `nvm install 16` then `nvm use 16` (this is because of the current webpack version the project uses, will be fixed at some point)
1. Install JavaScript dependencies
```sh
npm install
```

## Run in debug mode

```sh
# Builds the project and opens it in a new browser tab. Auto-reloads when the project changes.
npm start
```

## Build for release

```sh
# Builds the project and places it into the `dist` folder.
npm run build
```

# roope-wasm-hello
