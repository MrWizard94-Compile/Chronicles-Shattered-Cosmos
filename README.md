# Chronicles of the Shattered Cosmos

> Hyper-realism meets deep magic, industrial automation, and terrifying dimensional exploration — physics, destructible blocks, infinite render distance, and dark arcane research.

**Minecraft 1.20.1 · Forge 47.x · CurseForge-format modpack**

## Overview

| Spec | Detail |
|------|--------|
| Title | Chronicles of the Shattered Cosmos |
| Version | Minecraft 1.20.1 |
| Loader | Forge 47.x |
| Primary focus | Immersion / hyper-realism + dark magic + dimensions |
| Difficulty | Dark-Souls-style boss fights |
| Pack version | 0.1.0 (foundation) |

> ⚠ **Reality check:** This concept lists the most version-risky mods of the five (Thaumcraft 7, Physics Mod Pro, Sodium/Lithium). See `docs/MODLIST.md` for what is actually available on Forge 1.20.1 and the recommended substitutions. The vision is intact; some named mods need swaps.

## Repository layout

| Path | Purpose |
|------|---------|
| `manifest/manifest.json` | CurseForge manifest (Forge 1.20.1). `files[]` resolved at packaging time. |
| `overrides/config/` | Pack configs (committed) |
| `overrides/mods/` | Local mod jars (gitignored; `.gitkeep` tracked) |
| `docs/CONCEPT.md` | Original design vision |
| `docs/MODLIST.md` | Curated roster + **availability corrections** |

## Status

🌱 **Foundation scaffolded.** Structure, manifest, and curated roster in place. Several concept mods are not available on Forge 1.20.1 and have substitutions flagged in `docs/MODLIST.md` — resolve those before packaging.

## Building / CurseForge export

1. Drop mod jars into `overrides/mods/` to test in a local Forge 1.20.1 instance.
2. Resolve each mod's `projectID` / `fileID` into `manifest/manifest.json` `files[]`.
3. Zip `manifest.json` + `overrides/` per the CurseForge modpack spec; publish via the CurseForge author dashboard.

## Related

- [JanusPrime orchestration](https://github.com/MrWizard94-Compile/JanusPrime)
- Sibling concept packs: Aethelgard, Aetheria, Aetherial Convergence, Omniverse Odyssey
