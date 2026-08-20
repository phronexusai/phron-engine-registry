# phron-engine-registry

Public index and GitHub Release assets for **Phron** engine packages.

Phron installs engines from this registry. This tree is the catalog plus published archives, not engine source or build recipes.

## Index

[`packages.json`](./packages.json) — engine list (`url`, `sha256`, `downloadable`).

```
https://raw.githubusercontent.com/phronexusai/phron-engine-registry/main/packages.json
```

Releases: https://github.com/phronexusai/phron-engine-registry/releases

## Current packages

| Catalog name | Platform | Variant | Tag | Asset | Downloadable |
|--------------|----------|---------|-----|-------|--------------|
| `llama.cpp-cpu` | linux-x86_64 | cpu | `llama-cpp-b10306` | `llama-cpp-linux-x86_64-cpu.tar.gz` | yes |
| `llama.cpp-cuda13` | linux-x86_64 | cuda13 | `llama-cpp-b10306` | `llama-cpp-linux-x86_64-cuda13.tar.gz` | yes |

One GitHub Release per llama.cpp version. Variant and platform are the **asset filename**, not the tag.

CUDA 13 builds need an NVIDIA driver that reports CUDA 13.x or newer; the archive is only `llama-server`. `llama.cpp-cuda` is an install alias for `llama.cpp-cuda13`.
