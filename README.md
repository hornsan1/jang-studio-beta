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

- `JANGStudio-macOS-2026-07-05.zip`

## Build details

- App: `JANGStudio.app`
- Platform: macOS, Apple Silicon debug build
- Bundle version: `1`
- Short version: `1.0`
- Executable rebuild time: `2026-07-05 15:18:13 CDT`
- SHA-256: `6c6c603e243c47636c2c06d74bcb2ad1ca4ee0391cc7567ecdfda088113834ae`

## Current verification

- Current source builds cleanly with Xcode.
- Latest Expert Review UI includes Map, Cards, and Table atlas modes.
- Known test gap: `ExpertLabWorkflowFlowTests.test_defaultExpertIdentificationSuitesAreThorough` currently has stale source-string assertions after the newer condensed-card atlas update.
