# wasmtime_runtime_layer

[![Crates.io](https://img.shields.io/crates/v/wasmtime_runtime_layer.svg)](https://crates.io/crates/wasmtime_runtime_layer)
[![Docs.rs](https://docs.rs/wasmtime_runtime_layer/badge.svg)](https://docs.rs/wasmtime_runtime_layer)

`wasmtime_runtime_layer` implements the `wasm_runtime_layer` abstraction interface over WebAssembly runtimes for Wasmtime.

## Optional features

**cranelift** - Enables executing WASM modules and components with the Cranelift compiler, as described in the Wasmtime documentation. Enabled by default.

**winch** - Enables executing WASM modules and components with the Winch compiler, as described in the Wasmtime documentation.