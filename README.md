---
license: other
tags:
- jang
- jang-studio
- macos
- mlx
- quantization
---

# JANG Studio has been consolidated into MLX Studio

JANG Studio is no longer developed or released as a separate application. New installs and active workflows belong to [MLX Studio](https://github.com/hornsan1/mlx-studio-beta), the native model workstation for Apple Silicon. JANG remains the artifact and optimization technology inside that product.

- [MLX Studio repository](https://github.com/hornsan1/mlx-studio-beta)
- [MLX Studio releases](https://github.com/hornsan1/mlx-studio-beta/releases)
- [JANG Studio migration and rollback guide](https://github.com/hornsan1/mlx-studio-beta/blob/codex/mlx-studio-private-beta-lfm/docs/architecture/mlx-studio-consolidation/jang-studio-retirement.md)

## Historical releases remain available

[This repository's Releases page](../../releases) is preserved for rollback, reproduction, checksums, and migration evidence. These builds are not the latest MLX Studio product, and no historical tag or asset is removed by the redirect.

### Last standalone beta

- **Tag:** `v0.2.0-beta-2026-07-14`
- **Asset:** `JANGStudio-macOS-2026-07-14.zip`
- **ZIP SHA-256:** `17f29092b06c65e56e847ad6dddb4e5589626d8989ea770bba1da014e39b8ab7`
- **Source:** `hornsan1/jangq-private@5d5487c27fa81d9f51da27264ae855964e334070`
- **Signature:** ad-hoc / locally signed, not notarized

Apple Silicon is required. Gatekeeper may warn for the historical ad-hoc build; preserve it only when rollback or regression reproduction is needed. Existing model directories can be adopted in MLX Studio without re-quantizing them.
