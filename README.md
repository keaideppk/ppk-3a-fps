<div align="center">

# ppk

**A single-file, zero-dependency sci-fi harbor tactical FPS that runs in any modern browser.**

[![Play Online](https://img.shields.io/badge/▶_Play_Online-ffb347?style=for-the-badge)](https://keaideppk.github.io/ppk-3a-fps/)
[![Single File](https://img.shields.io/badge/build-single_HTML_file-8d9aa3?style=flat-square)](#technical-notes)
[![Dependencies](https://img.shields.io/badge/runtime_deps-0-2ea44f?style=flat-square)](#technical-notes)
[![Campaign](https://img.shields.io/badge/campaign-4_chapters-d2622a?style=flat-square)](#campaign)
[![License](https://img.shields.io/badge/license-study_%2F_research_only-6e7781?style=flat-square)](#license)

**[▶ Play Now](https://keaideppk.github.io/ppk-3a-fps/)** · [简体中文](README.zh-CN.md)

*No install. No download. No external assets.*

</div>

---

## Table of Contents

- [Features](#features)
- [Campaign](#campaign)
- [Arsenal](#arsenal)
- [Controls](#controls)
- [Technical Notes](#technical-notes)
- [Roadmap](#roadmap)
- [Credits](#credits)
- [License](#license)

---

## Features

A complete shooter campaign packed into one HTML file: four selectable chapters, a seven-slot arsenal with four hand-modelled CAD firearms and two throwable types, four enemy classes rendered as GPU-skinned multi-bone hard-surface models, two multi-phase bosses, a live-rotating tactical radar, and a fully adjustable difficulty system.

| | Feature | Description |
| :--- | :--- | :--- |
| 🎯 | **Four-chapter campaign** | Free chapter select, each with its own layout, hazards and boss. |
| 🔫 | **Seven-slot arsenal** | Four hand-built firearms plus frag / EMP grenades, hot-swappable mid-combat. |
| 🤖 | **GPU-skinned enemies** | Multi-bone hard-surface models with per-part hit detection. |
| 👹 | **Multi-phase bosses** | Destructible parts, shield breaks, forced core exposure, enrage phases. |
| 🗺️ | **Live tactical radar** | Rotating minimap with threat typing and off-screen edge indicators. |
| 🎚️ | **Free difficulty tuning** | Five presets, five continuous sliders, plus a god-mode toggle. |
| 🕹️ | **Input parity** | Keyboard & mouse, gamepad, and touch, all from the same build. |
| 📦 | **Zero dependencies** | One `index.html`. No CDN, no build step, no network calls at runtime. |

---

## Campaign

Each chapter is a self-contained operation with its own objectives, hazards and boss encounter. Cut the uplinks, break the defense line, survive the counter-attack, extract.

| # | Chapter | Setting | Objective | Boss |
| :-: | :--- | :--- | :--- | :--- |
| 01 | **Berth 04 Blockade** | Automated container terminal, rainy night | Sever 3 uplink relays, then extract | — |
| 02 | **Deep-Sea Nexus** | Deep-water joint platform deck | Disable 2 shield generators | **ppk Colossus** |
| 03 | **Dockyard Assembly** | Sectional hull assembly line | Cut 3 power feeds (control tower / foundry / gate pumps) | **Titan Assembly** |
| 04 | **Abyssal Geothermal Ring** | Molten core ring hall | Cut 3 geothermal feeds | **ppk Abyss Wyrm** |

**Environmental hazards** — Ch.3 adds overhead crane drops, sweeping plasma cutters and steam bursts; Ch.4 adds rotating ring corridors and geothermal flows.

---

## Arsenal

Every weapon is procedurally modelled in code — chamfered receivers, milled Picatinny teeth, hollow holographic sights with parallax-corrected glass, hydraulic pistons and braided hoses. No imported meshes.

| Slot | Weapon | Notes |
| :-: | :--- | :--- |
| `1` | **ppk Type-9 Assault Rifle** | Baseline full-auto rifle, idle inspection animation |
| `2` | **ppk Breaker-12 Shotgun** | 8 pellets, shell-by-shell reload interruption |
| `3` | **ppk Thunderclap Railgun** | Charge-up piercing shot, 80%+ ADS scope overlay |
| `4` | **ppk Swarm SMG** | 1020 RPM, 28-round extended mag |
| `5` | **Type-97 Frag Grenade** | LMB high-arc throw / RMB low-roll throw |
| `6` | **Jingzhe EMP Grenade** | Breaks shields, stuns and exposes boss cores |

---

## Controls

| Action | Keyboard & Mouse | Touch |
| :--- | :--- | :--- |
| Move · Sprint · Jump · Crouch | `W` `A` `S` `D` · `Shift` · `Space` · `C` | Left virtual stick |
| Look / Turn | Mouse | Right drag |
| Fire / Aim | `LMB` / `RMB` | On-screen buttons |
| Switch weapon & grenade | `1`–`6` or `Mouse Wheel` | Arsenal bar |
| Quick-draw grenade · Swap frag/EMP | `G` / `Q` (or `T`) | — |
| Reload · Melee · Interact | `R` · `F` · `E` | — |
| Minimap zoom · Pause / difficulty | `M` · `Esc` | — |

---

## Technical Notes

| | |
| :--- | :--- |
| **Rendering** | WebGL 2 via a bundled Three.js build. Custom post stack: TAA-style temporal upscale, SSAO, volumetric sun shafts, bloom, motion blur, filmic tonemapping. |
| **Materials** | Fully procedural PBR generated at boot — brushed steel, anodized aluminium, polymer, rust, coral growth, wetness and rain normals. Zero image assets. |
| **Physics** | AABB collision world with capsule sweep, step-up handling, A\* navigation grid, and a continuous 3D sub-stepped resolver for flying units to eliminate clip-through. |
| **Audio** | 100% synthesized Web Audio: every gunshot, servo, roar and impact is generated from noise, filters and envelopes at load time. |
| **Footprint** | One file, under 2 MB, no runtime network access. |

---

## Roadmap

- [x] Four-chapter campaign with per-chapter bosses
- [x] Seven-slot arsenal, dual-mode grenades, difficulty tuning
- [ ] **Weapon finish system** — Kirin / Storm / Magma procedural skins with emissive pulse
- [ ] **Spawn shield** — brief invulnerability on chapter entry
- [ ] Cosmetic finish selector panel

> The three unchecked items are implemented and verified in the local build; they ship in the next release.

---

## Credits

**Base project** — Built upon the **Claude official demo**.

**Secondary development** — Extended with the **Carbon model**.

**Scope of additions**

1. Four selectable chapters with independent terrain, hazards and objectives
2. Hand-modelled firearms, dual-mode throwables, ADS and reload state machines
3. GPU-skinned multi-bone enemy classes and multi-phase bosses
4. Live tactical radar, free difficulty tuning, tactical supply stations
5. Continuous 3D volume clip-through solver and airspace bounds for flying units

---

## License

**For study, testing and technical exchange only.**

Not for commercial redistribution. The original demo remains the property of its respective authors.

---

<div align="center">

**If you enjoy it, a ⭐ helps.**

</div>
