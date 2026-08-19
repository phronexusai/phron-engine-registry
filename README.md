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

| Catalog name | Platform | Variant | Tag |
|--------------|----------|---------|-----|
| `llama.cpp-cpu` | linux-x86_64 | cpu | `llama-cpp-cpu-0.1.0` |
| `llama.cpp-cuda` | linux-x86_64 | cuda | `llama-cpp-cuda-0.1.0` |

CUDA builds need an NVIDIA driver compatible with the CUDA 13 runtime; the archive is only `llama-server`.
