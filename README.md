# AxePPC (public)

This repo contains the **public** app recipe files for AxePPC (built for 5tratumOS and compatible self-hosted app platforms).

It must **not** contain any application source code.

The private build repo publishes the UI image to GHCR; the recipe points at that image and at the node/pool images.

## Current status

- Current dev-store package version: `0.2.30-dev`
- Mirrored dev-store package: `WillItMod/umbrel-dev-community-store/willitmod-dev-ppc`
- Miner endpoint: `stratum+tcp://<host-ip>:8765`
- For the cross-project version matrix and release/changelog pointers, see `https://github.com/WillItMod/AxeSuite/blob/main/docs/releases.md`.
- AxePPC is distributed via this repo's recipe files and is mirrored into `WillItMod/umbrel-dev-community-store`.
- Peercoin Core is bundled as a simple multi-arch Docker build in `willitmod-dev-ppc/data/peercoind` (0.15.1ppc).
