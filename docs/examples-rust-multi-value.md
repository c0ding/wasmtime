# Using multi-value

You can also [browse this source code online][code] and clone the wasmtime
repository to run the example locally.

[code]: https://github.com/bytecodealliance/wasmtime/blob/main/examples/multi.rs

This example shows off how to interact with a wasm module that uses multi-value
exports and imports.

## `multi.wat`

```wat
{{#include ../examples/multi.wat}}
```


## `multi.rs`

```rust,ignore
{{#include ../examples/multi.rs}}
```
