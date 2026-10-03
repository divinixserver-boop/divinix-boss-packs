# Divinix - Custom Boss Packs for Minecraft

Simple, Minecraft-style custom bosses and mobs for **ModelEngine + MythicMobs**, at prices that fit small and starting servers.

> Many models out there are beautiful but expensive. Divinix focuses on the middle ground: blocky models that feel at home in vanilla Minecraft, with **real boss mechanics** and plug-and-play setup, at affordable prices.

## About

I'm Miguel, a mathematician from Spain. I worked for a time as a programmer and I have run my own Minecraft servers for years, so I know first-hand what a server owner needs: packs that install in minutes, work with vanilla items, and can be tuned from plain YAML files. I build my packs with my own tooling (scripts that generate the 3D models, textures and animations) and then test and polish every boss in the real game.

**Contact:** Discord `Migpe45`

## Products

### Ancestral Shaman  -  boss + minions

A tribal shaman with a feather headdress, antlers and a glowing-eyed mask.

![Shaman and magic orb](images/shaman_01_magic_orb.jpg)
![Spirit spikes and skeletons](images/shaman_02_spirit_spikes.jpg)

| Shaman | Skeleton minion |
|---|---|
| ![Shaman front](images/shaman_04_front.jpg) | ![Skeleton minion](images/shaman_03_skeleton_minion.jpg) |

- Throws **3D magic orbs** from his hand (animated projectile model)
- **Spirit Spikes**: a bone-and-rune warning ring on the floor, then a cluster of crystal spikes erupts
- **Summons skeleton minions** (up to 6 alive) that rise from the ground, sprint and claw
- **Blinks away** when a player gets too close, and has a staff bash for melee
- **Phase 2** below 50% health: speed boost and extra skeletons
- 6 custom models: shaman, skeleton, orb, warning ring, crystal spikes, shards

### Ancient Rune Golem  -  boss with a destructible weak point

A mossy stone colossus with floating fists, orbiting rocks, a glowing rune core and a tree growing from its shoulder.

![Ancient Rune Golem](images/golem_01_front.jpg)

| Close-up | Core Beam warning rings | Exposed weak-point rune |
|---|---|---|
| ![Close-up](images/golem_02_closeup.jpg) | ![Core Beam](images/golem_03_core_beam_warning.jpg) | ![Exposed rune](images/golem_04_exposed_rune.jpg) |

- **The golem is invulnerable** until it opens its core and exposes a **floating rune** with its own health bar
- Destroy the rune before it seals again: the golem collapses and is vulnerable for a few seconds
- **Rocket Fist**: the detached right fist flies forward
- **Boulder Throw**, **Rock Rain** (warning rings, then real falling rocks), **Charge** and **Ground Smash**
- **Core Beam**: if you are too slow, the core fires a lightning column on every player's marked spot - move away in time
- Shock waves you dodge by **jumping**
- **Phase 2** below 50% health
- 10 custom models, effects are animated 3D models instead of particle spam

### Fungal Depths  -  dungeon mob pack (2 bosses + 5 room mobs)

A complete set of dungeon mobs for an overgrown, mushroom-infested ruin. **The map is not included**: drop the mobs into your own dungeon or arena.

![The Rotten King](images/fungal_01_rotten_king.jpg)
![Mycelium Matriarch](images/fungal_03_mycelium_matriarch.jpg)

| Capbound | Spore Crawler | Spore Spitter |
|---|---|---|
| ![Capbound](images/fungal_04_capbound.jpg) | ![Spore Crawler](images/fungal_05_spore_crawler.jpg) | ![Spore Spitter](images/fungal_06_spore_spitter.jpg) |

| Root Lurker | Glow Moth | Egg Sac |
|---|---|---|
| ![Root Lurker](images/fungal_07_root_lurker.jpg) | ![Glow Moth](images/fungal_08_glow_moth.jpg) | ![Egg Sac](images/fungal_09_egg_sac.jpg) |

- **The Rotten King (final boss)**: his hits stack an **infection** that you purge by standing in **glowcaps**. In phase 2 the **Great Bloom** marks the whole arena and blasts everyone who is not in the light
- **Mycelium Matriarch (mini-boss)**: root snares, **egg sacs** that hatch into crawlers if you ignore them, and a spore burst you dodge by jumping
- **5 room mobs**: a swarm crawler, a tanky Capbound, a ranged Spore Spitter, an ambushing Root Lurker and a Glow Moth
- 18 custom models. Warning rings, erupting roots, falling spores and the blast are animated 3D models, not particles

### Desert Tomb  -  dungeon mob pack (2 bosses + 5 room mobs)

A sunken Egyptian tomb in sandstone, gold and lapis lazuli. **The map is not included**: drop the mobs into your own dungeon or arena.

![The Pharaoh](images/tomb_01_pharaoh.jpg)
![Jackal Guardian](images/tomb_03_jackal_guardian.jpg)

| Mummy | Sentinel Statue | Sand Priest |
|---|---|---|
| ![Mummy](images/tomb_10_mummy.jpg) | ![Sentinel Statue](images/tomb_05_sentinel_statue.jpg) | ![Sand Priest](images/tomb_07_sand_priest.jpg) |

| Scarab | Jackal |
|---|---|
| ![Scarab](images/tomb_08_scarab.jpg) | ![Jackal](images/tomb_09_jackal.jpg) |

- **The Pharaoh (final boss)**: a curse that stacks and is purged in **glyphs**, a locust plague you jump over, and in phase 2 a **sarcophagus**: he seals himself and you have to break 3 canopic jars, guarded by scarabs, before the Curse Nova hits
- **Jackal Guardian (mini-boss)**: a shield that makes him invulnerable for a few seconds, a sandstorm that pulls you in and desert spears you dodge
- **5 room mobs**: a swarm scarab, a tanky mummy, a ranged sand priest, an ambushing sentinel statue and a pack-hunting jackal
- 17 custom models. Warning rings, the sandstorm, spears and the golden seal are animated 3D models, not particles

## What every pack includes

- Original 3D models, textures and animations (`.bbmodel`, open in Blockbench)
- The MythicMobs pack (mobs + skills) with comments
- An English README: requirements, install steps, spawning, a **tuning cheat-sheet** (health, damage, attack frequency, drops, cooldowns) and troubleshooting
- Vanilla-only drops, so it works on any server (swap them for your own items if you like)
- All chat messages in English

## Requirements

- Paper / Purpur 1.21.x
- MythicMobs 5.x
- ModelEngine R4

## Quality

Each pack is tested in-game on a local Paper 1.21 server before release: animations, hitboxes, textures, console errors and the exact ZIP that gets delivered.

## Where to get them

Coming soon to **MCModels**.

---

*All screenshots are in-game captures (Paper 1.21, ModelEngine R4, MythicMobs 5).*
