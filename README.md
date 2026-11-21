# OpenBCM SDK 6.5.27 (subset re-host)

This repository re-hosts **only** `sdk-6.5.27/` and `Legal/` from Broadcom's
OpenBCM repository, so that builds don't have to download every SDK release.

- Upstream: https://github.com/Broadcom-Network-Switching-Software/OpenBCM
- Upstream commit: `6d2330ce1b4fc49d681cffcf09af408661be4c62`
- Contents: `Legal/` and `sdk-6.5.27/` exactly as in that commit (git tree
  objects reused, so every file is byte-identical to upstream). The other SDK
  releases, `Firmware/` and the upstream README are omitted. No file is modified.

Licensing: the Software is distributed under Broadcom's licence in
`Legal/LICENSE`. Externally licensed components and their terms are listed in
`Legal/EXTLICENSE`. All proprietary notices in the files are retained.
