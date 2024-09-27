# wasm-test

## wasmtime

```bash
curl https://wasmtime.dev/install.sh -sSf | bash
```

## Compiler

```bash
rustup target add wasm32-wasi
```

## Build

```bash
cargo build --target wasm32-wasi
```
