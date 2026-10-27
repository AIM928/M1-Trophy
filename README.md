# M1 Trophy for Gunner, HEAT, PC!

M1 Trophy conversion with Trophy APS, M829A4, M1147 AMP, CITV and a remote weapon station.

## Install
Download the **Full.zip** package from [Releases](https://github.com/AIM928/M1-Trophy/releases/latest). Copy its `Mods` folder into the GHPC folder containing `GHPC.exe`. Requires MelonLoader and VanillaAssetUtil. Keep both DLLs and all `M1TrophyAssets` files together.

## Current build
- AMP impact/airburst modes use the middle mouse button and laser range.
- Main-gun sight/ranging refinements; CROWS automatic infantry engagement with limited traverse speed, 1,800 m engagement range and 800 reserve rounds.
- Directional laser warning; AI searches toward a new laser source for about 1–3 seconds and requires visibility before acquisition. Existing engagements continue normally.
- Main-gun loadout: `M829A4Count` and `AMPCount` in `[M1Trophy]` under `UserData/MelonPreferences.cfg`. Default 36 + 4, maximum 40 total; excess AMP is reduced after M829A4 allocation. Restart the game after editing. The public Mod Manager configuration-button integration is still pending.

Test build. Offline checks passed; the latest warning and AI changes still require gameplay verification. Mission reloads may fail with some mod combinations; the cause remains under investigation.

## Credits
Retopologized War Thunder vehicle model and original textures: **Gaijin Entertainment**.
Remote weapon station: **我怕肾虚** (M1A1艾布拉姆斯AMP 我怕肾虚修复版), with upstream CROWS contributors.
GHPC integration and tuning: AIM. Unofficial fan mod; original assets remain the property of their respective owners.
