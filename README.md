---
license: other
tags:
- jang
- jang-studio
- macos
- mlx
- quantization
---

# JANG Studio macOS beta

This repo hosts a public macOS beta build of JANG Studio.

## Download

See [Releases](../../releases) for the latest beta build.

## Latest release

- **Tag:** `v0.2.0-beta-2026-07-14`
- **Asset:** `JANGStudio-macOS-2026-07-14.zip`
- **ZIP SHA-256:** `17f29092b06c65e56e847ad6dddb4e5589626d8989ea770bba1da014e39b8ab7`

## Build details

- App: `JANGStudio.app`
- Platform: macOS, Apple Silicon (arm64) release build
- Bundle version: `1`
- Short version: `1.0`
- Source commit: `hornsan1/jangq-private@5d5487c`
- Signature: Ad-hoc / locally signed (not notarized)

## What's new in v0.2.0-beta-2026-07-14

- Intent Prune wizard with keep/drop capability shaping.
- Expert Review now emits `expert_transitions.jsonl` for pruning evidence.
- Evidence-gated prune flow: validate transitions before hard-pruning.
- Atlas visualization with condensed cards, table, and map modes.

## Notes

- Apple Silicon (M-series Mac) required for this build.
- Gatekeeper may warn because the app is ad-hoc signed. Right-click → Open to bypass on first launch.
- Built from the private `hornsan1/jangq-private` source tree.
