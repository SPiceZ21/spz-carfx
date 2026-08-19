# spz-carfx

> Custom vehicle particle effects · `v1.0.0`

## Overview

`spz-carfx` is an asset-only resource. It streams the custom particle libraries other
modules trigger for backfire flames, nitrous purges and tire smoke. There is no Lua — the
`.ypt` files are registered as PTFX asset files and consumed by
[spz-physics](../spz-physics/README.md).

## Assets

| File | Type | Contents |
|---|---|---|
| `stream/core.ypt` | PTFX | Core vehicle particle library |
| `stream/veh_xs_vehicle_mods.ypt` | PTFX | Extended vehicle modification effects |

Both are declared in `fxmanifest.lua` via `data_file 'PTFX_ASSET_FILE'`.

## Dependencies

None. Ensure it before any resource that triggers its effects.

---

Part of [SPiceZ-Core](../README.md) · GPL-3.0
