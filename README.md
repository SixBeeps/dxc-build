# dxc-build

Zig build script that builds the DirectX Shader Compiler (DXC) from source. Artifacts are built for Windows, Linux, and macOS which can be found https://github.com/vinterbell/dxc-build/releases/tag/v1.8.2505.

tracking commit 8480bc6c4e5231849531e2a6792783d46295a0bc of dxc upstream.

## Building
```sh
zig build
```
You will end up with dxcompiler, dxil and dxc binaries in `zig-out/bin/`.