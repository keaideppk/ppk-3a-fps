<div align="center">

# ppk · 3A 大作

**A single-file, zero-dependency sci-fi harbor tactical FPS that runs in any modern browser.**
**纯单文件、零外部依赖的硬核科幻港区战术第一人称射击游戏，浏览器打开即玩。**

[![Play Online](https://img.shields.io/badge/▶_Play_Online-立即游玩-ffb347?style=for-the-badge)](https://keaideppk.github.io/ppk-3a-fps/)
[![Single File](https://img.shields.io/badge/build-single_HTML_file-8d9aa3?style=flat-square)](#-technical-notes--技术说明)
[![Dependencies](https://img.shields.io/badge/runtime_deps-0-2ea44f?style=flat-square)](#-technical-notes--技术说明)
[![Campaign](https://img.shields.io/badge/campaign-4_chapters_·_4章-d2622a?style=flat-square)](#-campaign--战役)
[![License](https://img.shields.io/badge/license-study_%2F_research_only-6e7781?style=flat-square)](#-license--许可)

**[▶ Play Now · 立即在线游玩](https://keaideppk.github.io/ppk-3a-fps/)**

*No install. No download. No external assets.*
*无需安装、无需下载、不加载任何外部资源。*

</div>

---

## Table of Contents / 目录

| | |
| :--- | :--- |
| [Features](#-features--核心特性) | 核心特性 |
| [Campaign](#-campaign--战役) | 战役章节 |
| [Arsenal](#-arsenal--军械库) | 军械库 |
| [Controls](#-controls--操作说明) | 操作说明 |
| [Technical Notes](#-technical-notes--技术说明) | 技术说明 |
| [Roadmap](#-roadmap--更新计划) | 更新计划 |
| [Credits](#-credits--来源与致谢) | 来源与致谢 |
| [License](#-license--许可) | 许可 |

---

## Features / 核心特性

> **EN** — A complete shooter campaign packed into one HTML file: four selectable chapters, a seven-slot arsenal with four hand-modelled CAD firearms and two throwable types, four enemy classes rendered as GPU-skinned multi-bone hard-surface models, two multi-phase bosses, a live-rotating tactical radar, and a fully adjustable difficulty system.
>
> **中文** — 一整个射击战役塞进单个 HTML 文件：四章自由选关、七槽位军械库（四把 CAD 手工建模枪械 + 两款投掷物）、四类 GPU 蒙皮多骨骼硬表面敌军、两台多阶段 Boss、实时旋转战术雷达，以及可无级微调的难度系统。

| | Feature / 特性 | Description / 说明 |
| :--- | :--- | :--- |
| 🎯 | **Four-chapter campaign** · 四章战役 | Free chapter select, each with its own layout, hazards and boss. 自由选关，每章独立地形、环境危害与 Boss。 |
| 🔫 | **Seven-slot arsenal** · 七槽位军械库 | Four hand-built firearms plus frag / EMP grenades, hot-swappable mid-combat. 四把精工枪械 + 破片/EMP 手雷，战中随时切换。 |
| 🤖 | **GPU-skinned enemies** · 蒙皮敌军 | Multi-bone hard-surface models with per-part hit detection. 多骨骼硬表面模型，支持部位命中判定。 |
| 👹 | **Multi-phase bosses** · 多阶段 Boss | Destructible parts, shield breaks, forced core exposure, enrage phases. 部位可破坏、护盾击碎、核心强制暴露、狂暴阶段。 |
| 🗺️ | **Live tactical radar** · 实时战术雷达 | Rotating minimap with threat typing and off-screen edge indicators. 旋转小地图，区分兵种并带屏外贴边指引。 |
| 🎚️ | **Free difficulty tuning** · 自由难度调节 | Five presets, five continuous sliders, plus a god-mode toggle. 五档预设 + 五项无级滑块 + 不死护体。 |
| 🕹️ | **Input parity** · 多端输入 | Keyboard & mouse, gamepad, and touch, all from the same build. 键鼠、手柄、触屏，同一份构建全支持。 |
| 📦 | **Zero dependencies** · 零依赖 | One `index.html`. No CDN, no build step, no network calls at runtime. 单个 `index.html`，无 CDN、无构建步骤、运行期零网络请求。 |

---

## Campaign / 战役

> **EN** — Each chapter is a self-contained operation with its own objectives, hazards and boss encounter. Cut the uplinks, break the defense line, survive the counter-attack, extract.
>
> **中文** — 每章都是一次独立行动：切断上行链路、撕开防线、顶住反扑、登艇撤离。

| # | Chapter / 章节 | Setting / 场景 | Objective / 任务 | Boss |
| :-: | :--- | :--- | :--- | :--- |
| 01 | **Berth 04 Blockade**<br>四号泊位封锁线 | Automated container terminal, rainy night<br>自动化集装箱港区 · 雨夜 | Sever 3 uplink relays, then extract<br>切断 3 处上行中继后登艇撤离 | — |
| 02 | **Deep-Sea Nexus**<br>远洋巨轮与中枢决战 | Deep-water joint platform deck<br>深水联体中枢甲板 | Disable 2 shield generators<br>瘫痪 2 座护盾发生器 | **ppk Colossus**<br>ppk巨像 |
| 03 | **Dockyard Assembly**<br>船坞总装厂 | Sectional hull assembly line<br>分段船体总装线 | Cut 3 power feeds (control tower / foundry / gate pumps)<br>切断中控塔、熔铸车间与坞门泵站三段供电 | **Titan Assembly**<br>泰坦总装体 |
| 04 | **Abyssal Geothermal Ring**<br>深渊地热环站 | Molten core ring hall<br>熔核环厅 | Cut 3 geothermal feeds<br>切断 3 处地热供给锁 | **ppk Abyss Wyrm**<br>ppk渊龙 |

**Environmental hazards / 环境危害** — Ch.3 adds overhead crane drops, sweeping plasma cutters and steam bursts; Ch.4 adds rotating ring corridors and geothermal flows.
**第三章**新增天车吊运、等离子切割臂贴地扫掠与蒸汽爆管；**第四章**新增旋转环廊与地热熔流。

---

## Arsenal / 军械库

> **EN** — Every weapon is procedurally modelled in code — chamfered receivers, milled Picatinny teeth, hollow holographic sights with parallax-corrected glass, hydraulic pistons and braided hoses. No imported meshes.
>
> **中文** — 全部枪械均由代码程序化建模：倒角机匣、精铣导轨齿、镂空全息瞄具与消视差镜片、液压杆与编织软管，无任何外部模型资源。

| Slot | Weapon / 武器 | Notes / 说明 |
| :-: | :--- | :--- |
| `1` | **ppk Type-9 Assault Rifle**<br>ppk九式突击步枪 | Baseline full-auto rifle, idle inspection animation<br>基础全自动步枪，含待机审视动画 |
| `2` | **ppk Breaker-12 Shotgun**<br>ppk破浪十二式霰弹枪 | 8 pellets, shell-by-shell reload interruption<br>8 弹丸齐射，支持换弹中途打断 |
| `3` | **ppk Thunderclap Railgun**<br>ppk惊雷式电磁轨道狙击枪 | Charge-up piercing shot, 80%+ ADS scope overlay<br>蓄力穿透射击，开镜 80% 切入高倍镜 |
| `4` | **ppk Swarm SMG**<br>ppk蜂群式冲锋手枪 | 1020 RPM, 28-round extended mag<br>1020 发/分，28 发加长弹匣 |
| `5` | **Type-97 Frag Grenade**<br>ppk九七式破片高爆手雷 | LMB high-arc throw / RMB low-roll throw<br>左键高抛 / 右键贴地低抛 |
| `6` | **Jingzhe EMP Grenade**<br>ppk惊蛰式 EMP 脉冲手雷 | Breaks shields, stuns and exposes boss cores<br>破盾、瘫痪并强制暴露 Boss 核心 |

---

## Controls / 操作说明

| Action / 操作 | Keyboard & Mouse / 键鼠 | Touch / 触屏 |
| :--- | :--- | :--- |
| Move · Sprint · Jump · Crouch<br>移动 · 冲刺 · 跳跃 · 蹲伏 | `W` `A` `S` `D` · `Shift` · `Space` · `C` | Left virtual stick<br>左侧虚拟摇杆 |
| Look / Turn<br>视角 | Mouse<br>鼠标移动 | Right drag<br>右侧拖拽 |
| Fire / Aim<br>开火 / 瞄准 | `LMB` / `RMB`<br>鼠标左键 / 右键 | On-screen buttons<br>屏幕按钮 |
| Switch weapon & grenade<br>切换武器与手雷 | `1`–`6` or `Mouse Wheel`<br>数字键 / 滚轮 | Arsenal bar<br>武器栏 |
| Quick-draw grenade · Swap frag/EMP<br>快捷上手雷 · 互换破片与 EMP | `G` / `Q` (or `T`) | — |
| Reload · Melee · Interact<br>换弹 · 近战 · 交互 | `R` · `F` · `E` | — |
| Minimap zoom · Pause / difficulty<br>小地图缩放 · 暂停与难度 | `M` · `Esc` | — |

---

## Technical Notes / 技术说明

| | |
| :--- | :--- |
| **Rendering / 渲染** | WebGL 2 via a bundled Three.js build. Custom post stack: TAA-style temporal upscale, SSAO, volumetric sun shafts, bloom, motion blur, filmic tonemapping.<br>内置 Three.js 的 WebGL 2 渲染，自研后期管线：时域上采样、SSAO、体积光、辉光、动态模糊、电影级色调映射。 |
| **Materials / 材质** | Fully procedural PBR generated at boot — brushed steel, anodized aluminium, polymer, rust, coral growth, wetness and rain normals. Zero image assets.<br>启动时程序化生成 PBR 贴图：拉丝钢、阳极氧化铝、聚合物、锈蚀、附生物、湿润与雨水法线，零图片资源。 |
| **Physics / 物理** | AABB collision world with capsule sweep, step-up handling, A\* navigation grid, and a continuous 3D sub-stepped resolver for flying units to eliminate clip-through.<br>AABB 碰撞世界 + 胶囊扫掠 + 台阶处理 + A\* 导航网格，并为飞行单位实现连续三维子步进退穿解算，杜绝穿模。 |
| **Audio / 音频** | 100% synthesized Web Audio: every gunshot, servo, roar and impact is generated from noise, filters and envelopes at load time.<br>100% 程序化合成音频：所有枪声、伺服声、咆哮与撞击均在加载时由噪声、滤波器与包络实时生成。 |
| **Footprint / 体积** | One file, ~1.8 MB, no runtime network access.<br>单文件约 1.8 MB，运行期零网络访问。 |

---

## Roadmap / 更新计划

- [x] Four-chapter campaign with per-chapter bosses
- [x] Seven-slot arsenal, dual-mode grenades, difficulty tuning
- [ ] **Weapon finish system** — Kirin / Storm / Magma procedural skins with emissive pulse
- [ ] **Spawn shield** — brief invulnerability on chapter entry
- [ ] Cosmetic finish selector panel

> 以上三项已在本地构建中完成验证，将于下一版本发布。
> The three items above are implemented and verified locally; shipping in the next release.

---

## Credits / 来源与致谢

> **Base project / 基底来源** — Built upon the **Claude official demo**.
> 本项目原版基底源自 **Claude 官方示例**。
>
> **Secondary development / 二次开发** — Extended with the **Carbon model**.
> 在此之上使用 **Carbon 模型** 进行了深度二次开发（二开）。
>
> **Scope of additions / 二开范围**
> 1. Four selectable chapters with independent terrain, hazards and objectives — 四章自由选关，独立地形 / 危害 / 任务目标
> 2. Hand-modelled firearms, dual-mode throwables, ADS and reload state machines — 精工枪械、双模投掷物、开镜与换弹状态机
> 3. GPU-skinned multi-bone enemy classes and multi-phase bosses — GPU 蒙皮多骨骼敌军与多阶段 Boss
> 4. Live tactical radar, free difficulty tuning, tactical supply stations — 实时战术雷达、自由难度调节、战术补给站
> 5. Continuous 3D volume clip-through solver and airspace bounds for flying units — 飞行单位连续三维体积退穿与空域边界解算

---

## License / 许可

> **For study, testing and technical exchange only.**
> 本项目仅供学习、测试与技术交流使用。
>
> Not for commercial redistribution. The original demo remains the property of its respective authors.
> 不得用于商业再分发；原示例版权归其原作者所有。

---

<div align="center">

**If you enjoy it, a ⭐ helps.**
**觉得还不错的话，点个 ⭐ 支持一下。**

</div>