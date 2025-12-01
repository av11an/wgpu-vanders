# WGPU-Vanders

## Overview
Some software to mess around with shaders in WASM using wgpu and winit.

## Background
This project is related to the vanders project in the way that I wanted to mess around with shaders. After creating whirl
it made me realize that my CPU power was not going to be enough to learn about shaders and that I needed to quickly switch
to a GPU and use wgsl, instead of converting everything in Rust.

## Helpful Commands

Build WASM files.
```bash
wasm-pack build --target web
```

Build WASM files, without optimizing.
```bash
wasm-pack build --target web --dev
```

Start local server.
```bash
python3 -m http.server
```

