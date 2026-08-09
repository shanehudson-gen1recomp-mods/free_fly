# free_fly (Official mirror)

Installable releases of the **Free Fly** mod for [gen1recomp](https://github.com/bryanthaboi/gen1recomp).

A party member that knows FLY can take off and free-roam over the overworld, then land anywhere walkable.

![Demo](https://raw.githubusercontent.com/shanehudson-gen1recomp-mods/monorepo/main/.github/free_fly-demo.gif)

Grab the newest `.zip` from [Releases](https://github.com/shanehudson-gen1recomp-mods/free_fly/releases) and install it in-game: **MODS > Import mod .zip**. Installed copies get update checks through the launcher automatically.

Source code and issues live in the [mods monorepo](https://github.com/shanehudson-gen1recomp-mods/monorepo); this repo only hosts releases.

## Tested alongside

Third-party mods this release was run alongside, with the exact
versions used. Later versions of these mods may change behavior; if a
combo misbehaves, check the version you have against this list first.

| Mod | Version tested | Notes |
|---|---|---|
| [Dramatic Shape Voxel Mod](https://github.com/DramaticShape/DramaticShapeVoxelMod) | 1.6.2 | flight clears voxel rooftops, camera and tilt-shift follow, first-person cockpit view |
| Battle Art voxel fork | 1.7.6 | FreeMove flight pass-through verified on the fork too |
| [Wilds of Kanto](https://github.com/gamecorner-033/Gen1PC-OverworldEncounters) (`overworld_wild_spawns`) | 1.12.1 | follower trailers fly or wait out flight; STAY choices survive |
| Overworld Wild Encounters (`overworld_encounters`) | 0.0.5 | its ground roamers cannot start battles against an airborne player |
| [PokePC Followers](https://github.com/gamecorner-033/PokePCFollowers) | 0.5.1 | FLYING follower trails in the air, others wait for landing |
| [Quick Select](https://github.com/Roxas2712/pokemon-quick-select) | 1.0.1 | FLY WHISTLE shortcut |
| QoL Toggles (`qol_toggles`) | 1.12.0 | FIELD MOVES ALL unlocks FREEFLY without teaching the move |
| Gen1 Modern UI (`gen1_modern_ui`) | 0.8.3 | free_fly 1.5.1 broke its modern menus (our old overworld draw hook tripped its renderer check); fixed in 1.5.2, also update wild_skies to 1.6.2 if installed |

## All mods in this family

- [Double Battles](https://github.com/shanehudson-gen1recomp-mods/double_battles) (`double_battles`): Wild and trainer double battles: 1v2, 2v2 and trainer pairs, in classic, wide and 3D.
- **Free Fly** (`free_fly`, this repo): A party member that knows FLY can take off and free-roam over the overworld, then land anywhere walkable.
- [Wild Skies](https://github.com/shanehudson-gen1recomp-mods/wild_skies) (`wild_skies`): Ambient flying Pokémon from the local encounter table roam the sky in loose flocks, resting on streets and rooftops.
- [Dev Hook Inspector](https://github.com/shanehudson-gen1recomp-mods/dev-hook-inspector) (`dev-hook-inspector`): Developer tool: a HOOKS entry on the START menu lists every installed mod's public exports and events.