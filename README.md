# AxePPC (public)

This repo contains the **public** app recipe files for AxePPC (built for 5tratumOS and compatible self-hosted app platforms).

It must **not** contain any application source code.

The private build repo publishes the UI image to GHCR; the recipe points at that image and at the node/pool images.

## Current status

- AxePPC is distributed via this repo's recipe files and is mirrored into `WillItMod/umbrel-dev-community-store`.
- Peercoin Core is bundled as a simple multi-arch Docker build in `willitmod-dev-ppc/data/peercoind` (0.15.1ppc).
