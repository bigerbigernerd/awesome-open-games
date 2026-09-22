# Awesome Open Games [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![CC0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)](LICENSE) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> 精选**真正可玩的开源游戏**，以及做游戏所需的**引擎、框架、教程和免费素材**。
>
> English version: [README.md](README.md)

这里的“开源”指代码以 OSI 认可（或同等自由）协议发布。
少数*引擎重制版*需要原商业版游戏资源才能运行，已用 🧩 标出。
License 标注仅供参考，请以各仓库的 `LICENSE` 文件为准。

## 目录

- [策略（RTS / 回合 / 4X）](#策略rts--回合--4x)
- [模拟经营](#模拟经营)
- [Roguelike 与地牢](#roguelike-与地牢)
- [RPG 与冒险](#rpg-与冒险)
- [射击](#射击fps--竞技场)
- [平台跳跃与街机](#平台跳跃与街机)
- [竞速与飞行](#竞速与飞行)
- [益智与休闲](#益智与休闲)
- [棋牌与桌游](#棋牌与桌游)
- [音乐节奏](#音乐节奏)
- [多人与派对](#多人与派对)
- [游戏引擎](#游戏引擎)
- [框架与库](#框架与库)
- [叙事与专用工具](#叙事与专用工具)
- [教程与学习](#教程与学习)
- [免费素材](#免费素材)
  - [美术与精灵](#美术与精灵)
  - [音频与音乐](#音频与音乐)
  - [字体](#字体)
  - [素材工具](#素材工具)
- [开发工具与底层库](#开发工具与底层库)
- [社区与活动](#社区与活动)
- [参与贡献](#参与贡献)

---

## 策略（RTS / 回合 / 4X）

- [0 A.D.](https://github.com/0ad/0ad) — 以帝国时代为灵感的历史题材 RTS。`C++` `GPL-2.0 / CC-BY-SA`
- [OpenRA](https://github.com/OpenRA/OpenRA) — 经典命令与征服式 RTS 的现代化引擎。`C#` `GPL-3.0`
- [Beyond All Reason](https://github.com/beyond-all-reason/Beyond-All-Reason) — 快节奏开源 RTS（Spring 引擎系）。`Lua` `GPL-2.0`
- [Warzone 2100](https://github.com/Warzone2100/warzone2100) — 2004 年开源的经典 3D RTS，含完整战役。`C++` `GPL-2.0`
- [Zero-K](https://github.com/ZeroK-RTS/Zero-K) — Spring 引擎 RTS，带物理破坏和地形改造。`Lua` `GPL-2.0`
- [Battle for Wesnoth](https://github.com/wesnoth/wesnoth) — 奇幻回合制策略，海量战役。`C++` `GPL-2.0`
- [FreeCiv](https://github.com/freeciv/freeciv) — 文明式回合制帝国经营。`C` `GPL-2.0`
- [TripleA](https://github.com/triplea-game/triplea) — 轴心与同盟式桌游策略，支持在线对战。`Java` `GPL-3.0`
- [FreeOrion](https://github.com/freeorion/freeorion) — 群星式太空 4X（致敬猎户座之王）。`C++` `GPL-2.0 / CC-BY-SA`
- [Widelands](https://github.com/widelands/widelands) — 工人物语式慢节奏建造策略。`C++` `GPL-2.0`

## 模拟经营

- [OpenTTD](https://github.com/OpenTTD/OpenTTD) — 运输大亨复刻，至今仍在活跃开发。`C++` `GPL-2.0`
- [Simutrans](https://github.com/simutrans/simutrans) — 交通模拟，载具种类极其丰富。`C++` `Artistic`
- [MicropolisJS](https://github.com/graememcc/micropolisJS) — 初代模拟城市源码的 HTML5 移植版。`JavaScript` `GPL-3.0`
- [Unknown Horizons](https://github.com/unknown-horizons/unknown-horizons) — 纪元式 2D 城市建造 + 经济模拟。`Python` `GPL-2.0`
- [OpenRCT2](https://github.com/OpenRCT2/OpenRCT2) — 过山车大亨 2 重制版。🧩 需要原版资源。`C++` `GPL-3.0`
- [OpenLoco](https://github.com/OpenLoco/OpenLoco) — 交通巨人（Locomotion）重制版。🧩 需要原版资源。`C++` `MIT`
- [CorsixTH](https://github.com/CorsixTH/CorsixTH) — 主题医院引擎重制版。🧩 需要原版资源。`Lua` `MIT`
- [FlightGear](https://github.com/FlightGear/flightgear) — 严肃向开源飞行模拟器。`C++` `GPL-2.0`

## Roguelike 与地牢

- [Cataclysm: Dark Days Ahead](https://github.com/CleverRaven/Cataclysm-DDA) — 僵尸末日求生，深度极高的 Roguelike。`C++` `CC-BY-SA`
- [Dungeon Crawl Stone Soup](https://github.com/crawl/crawl) — 现代 Roguelike 的标杆之作。`C++` `GPL-2.0`
- [NetHack](https://github.com/NetHack/NetHack) — 定义了这一类型的经典（1987 年至今）。`C` `NGPL`
- [Angband](https://github.com/angband/angband) — 托尔金式地牢探险，无数变体的祖师爷。`C` `GPL-2.0`
- [BrogueCE](https://github.com/tmewett/BrogueCE) — 极简 ASCII Roguelike Brogue 的社区版。`C` `GPL`
- [Shattered Pixel Dungeon](https://github.com/00-Evan/shattered-pixel-dungeon) — 打磨精良的移动端优先 Roguelike。`Java` `GPL-3.0`
- [Pixel Dungeon](https://github.com/watabou/pixel-dungeon) — 初代开源移动端 Roguelike。`Java` `GPL-3.0`

## RPG 与冒险

- [Veloren](https://github.com/veloren/veloren) — 体素多人 RPG（Cube World 风格）。`Rust` `GPL-3.0`
- [Endless Sky](https://github.com/endless-sky/endless-sky) — 2D 太空贸易战斗（Escape Velocity 风格）。`C++` `GPL-3.0`
- [Naev](https://github.com/naev/naev) — 2D 太空贸易模拟，带剧情战役。`C` `GPL / CC-BY-SA`
- [Pioneer](https://github.com/pioneerspacesim/pioneer) — 精英式太空冒险模拟。`C++` `GPL-3.0`
- [Oolite](https://github.com/OoliteProject/oolite) — 现代版 Elite，支持扩展包。`Objective-C` `GPL-2.0`
- [Vega Strike](https://github.com/vegastrike/Vega-Strike-Engine-Source) — 开放式太空飞行模拟引擎 + 游戏。`C++` `GPL-2.0`
- [Thrive](https://github.com/Revolutionary-Games/Thrive) — 从单细胞进化到太空阶段（孢子式）。`C#` `GPL-3.0`
- [OpenMW](https://github.com/OpenMW/openmw) — 上古卷轴 3 引擎替代品，支持现代特性。🧩 需要原版资源。`C++` `GPL-3.0`
- [VCMI](https://github.com/vcmi/vcmi) — 魔法门之英雄无敌 3 引擎。🧩 需要原版资源。`C++` `GPL-2.0`
- [OpenXcom](https://github.com/OpenXcom/OpenXcom) — UFO: Enemy Unknown 重制版。🧩 需要原版资源。`C++` `GPL-3.0`
- [DevilutionX](https://github.com/diasurgical/DevilutionX) — 暗黑破坏神 + 地狱火的源码移植版。🧩 需要原版资源。`C++`
- [Solarus](https://github.com/solarus-games/solarus) — 塞尔达式 2D ARPG 引擎，自带示例游戏。`C++` `GPL-3.0`
- [Colobot](https://github.com/colobot/colobot) — 编程式策略游戏：给你的机器人写代码。`C++` `GPL-3.0`

## 射击（FPS / 竞技场）

- [Xonotic](https://github.com/xonotic/xonotic) — 社区驱动的快节奏竞技场 FPS。`GPL`
- [ioquake3](https://github.com/ioquake/ioq3) — 持续维护的雷神之锤 3 引擎，众多游戏的基础。`C` `GPL-2.0`
- [OpenArena](https://github.com/OpenArena/gamecode) — 兼容 Q3 的 FPS，自带免费素材。`C` `GPL-2.0`
- [AssaultCube](https://github.com/assaultcube/AC) — 轻量战术多人 FPS。`C` `zlib`
- [Unvanquished](https://github.com/Unvanquished/Unvanquished) — 异形大战人类，FPS/RTS 混合玩法。`C++` `GPL-3.0 / CC-BY-SA`
- [Red Eclipse](https://github.com/redeclipse/base) — 跑酷竞技场射击，自带免费素材。`C++` `zlib / CC-BY-SA`
- [BZFlag](https://github.com/BZFlag-Dev/bzflag) — 3D 多人坦克大战经典。`C++` `LGPL`
- [Freedoom](https://github.com/freedoom/freedoom) — 完全自由的 Doom 兼容游戏 + 素材。`Python`（构建） `BSD-3-Clause`
- [Chocolate Doom](https://github.com/chocolate-doom/chocolate-doom) — 保守、考据向的 Doom 移植版。`C` `GPL-2.0`
- [OpenTyrian](https://github.com/opentyrian/opentyrian) — 纵版射击 Tyrian 的开源移植版。`C` `GPL-2.0`

## 平台跳跃与街机

- [SuperTux](https://github.com/SuperTux/supertux) — 马里奥式平台跳跃，主角是 Tux 企鹅。`C++` `GPL-3.0`
- [Pingus](https://github.com/Pingus/pingus) — 百战小旅鼠式玩法，主角换成企鹅。`C++` `GPL-3.0`
- [Hedgewars](https://github.com/hedgewars/hw) — 百战天虫式炮术对战，主角是刺猬。`Lua`/`Pascal` `GPL-2.0`
- [Teeworlds](https://github.com/teeworlds/teeworlds) — 2D 多人平台射击。`C++` `zlib`
- [DDNet](https://github.com/ddnet/ddnet) — 基于 Teeworlds 的合作竞速平台跳跃。`C++` `zlib`

## 竞速与飞行

- [SuperTuxKart](https://github.com/supertuxkart/stk-code) — 马里奥赛车式竞速，带剧情模式和在线对战。`C++` `GPL-3.0`
- [HexGL](https://github.com/BKcore/HexGL) — 未来风 HTML5 竞速游戏（Three.js）。`JavaScript` `MIT`

## 益智与休闲

- [2048](https://github.com/gabrielecirulli/2048) — 火遍全球的滑块数字游戏原版。`JavaScript` `MIT`
- [Frozen Bubble](https://www.frozen-bubble.org/) — 泡泡龙式街机经典。🌐 官网（含源码）。`GPL-2.0`

## 棋牌与桌游

- [lichess](https://github.com/lichess-org/lila) — 免费在线国际象棋：对战、谜题、分析全都有。`Scala` `AGPL-3.0`
- [Cockatrice](https://github.com/Cockatrice/Cockatrice) — 跨平台卡牌桌游模拟器。`C++` `GPL-2.0`

## 音乐节奏

- [osu!lazer](https://github.com/ppy/osu) — 新一代开源 osu! 客户端。`C#` `MIT`
- [Etterna](https://github.com/etternagame/etterna) — 跳舞机式节奏模拟，主打精准判定。`C++` `MIT`
- [StepMania](https://github.com/stepmania/stepmania) — 经典 DDR 式节奏引擎。`C++` `MIT`

## 多人与派对

- [Space Station 14](https://github.com/space-wizards/space-station-14) — 空间站里的偏执与混乱（SS13 重制）。`C#` `MIT`
- [Mindustry](https://github.com/Anuken/Mindustry) — 自动化塔防 RTS，支持多人合作。`Java` `GPL-3.0`
- [BrowserQuest](https://github.com/mozilla/BrowserQuest) — Mozilla 的 HTML5 MMORPG 实验。`JavaScript` `MPL-2.0`
- [Luanti](https://github.com/luanti-org/luanti) — 体素游戏引擎 + 类 Minetest 沙盒（可开多人服）。`C++` `LGPL-2.1`
- [Terasology](https://github.com/MovingBlocks/Terasology) — 模块化玩法的体素世界。`Java` `Apache-2.0`
- [Armagetron Advanced](https://github.com/ArmagetronAd/armagetronad) — 创战纪式光轮多人对战。`C++` `GPL-2.0`

---

## 游戏引擎

2D/3D 通用引擎。

- [Godot](https://github.com/godotengine/godot) — 开源引擎旗舰：2D + 3D，MIT 协议。`C++` `MIT`
- [Bevy](https://github.com/bevyengine/bevy) — Rust 编写的数据驱动 ECS 引擎。`Rust` `MIT / Apache-2.0`
- [O3DE (Open 3D Engine)](https://github.com/o3de/o3de) — 3A 级 3D 引擎（前 Lumberyard），对 Linux 友好。`C++` `Apache-2.0`
- [Stride](https://github.com/stride3d/stride) — 跨平台 C# 引擎（前 Xenko）。`C#` `MIT`
- [Urho3D](https://github.com/urho3d/Urho3D) — 轻量可嵌入式游戏引擎。`C++` `MIT`
- [OGRE](https://github.com/OGRECave/ogre) — 老牌 3D 渲染引擎。`C++` `MIT`
- [Panda3D](https://github.com/panda3d/panda3d) — 迪士尼/CMU 出品，搭配 Python 很好用。`C++`/`Python` `BSD`
- [jMonkeyEngine](https://github.com/jMonkeyEngine/jmonkeyengine) — 面向新手和独立开发者的 Java 3D 引擎。`Java` `BSD-3-Clause`
- [GDevelop](https://github.com/4ian/GDevelop) — 无代码 2D/3D 引擎，可导出 Web + 手游。`JavaScript` `MIT`
- [Fyrox](https://github.com/FyroxEngine/Fyrox) — Rust 编写的 2D/3D 引擎，自带编辑器。`Rust` `MIT`

## 框架与库

更轻量的框架和渲染库。

- [raylib](https://github.com/raysan5/raylib) — 简单好玩的 C 游戏库，学图形编程首选。`C` `zlib`
- [LÖVE](https://github.com/love2d/love) — Lua 2D 框架，Game Jam 常客。`C++` `zlib`
- [MonoGame](https://github.com/MonoGame/MonoGame) — XNA 继承者，C# 跨平台。`C#` `MS-PL`
- [FNA](https://github.com/FNA-XNA/FNA) — 精准的 XNA 重实现，适合移植老游戏。`C#` `MS-PL`
- [libGDX](https://github.com/libgdx/libgdx) — Java 框架，一套代码跑桌面/安卓/iOS/HTML5。`Java` `Apache-2.0`
- [Cocos2d-x](https://github.com/cocos2d/cocos2d-x) — 成熟的 C++ 手游 2D 框架。`C++` `MIT`
- [Phaser](https://github.com/phaserjs/phaser) — HTML5 2D 游戏框架的事实标准。`JavaScript` `MIT`
- [Excalibur](https://github.com/excaliburjs/Excalibur) — TypeScript 2D 引擎，API 友好。`TypeScript` `BSD-2-Clause`
- [Kaboom](https://github.com/replit/kaboom) — 好玩的新手向 JS 游戏库。`TypeScript` `MIT`
- [HaxeFlixel](https://github.com/HaxeFlixel/flixel) — Haxe 2D 引擎，适合复古风。`Haxe` `MIT`
- [Flame](https://github.com/flame-engine/flame) — 基于 Flutter 的 2D 游戏引擎。`Dart` `MIT`
- [Macroquad](https://github.com/not-fl3/macroquad) — 极简 Rust 游戏库，零配置上手。`Rust` `MIT / Apache-2.0`
- [Pygame](https://github.com/pygame/pygame) — 经典 Python 游戏库（SDL 绑定）。`C`/`Python` `LGPL-2.1`
- [Arcade](https://github.com/pythonarcade/arcade) — 现代 Python 2D 教学库。`Python` `MIT`
- [Three.js](https://github.com/mrdoob/three.js) — 众多网页游戏背后的 WebGL 3D 库。`JavaScript` `MIT`
- [Babylon.js](https://github.com/BabylonJS/Babylon.js) — 全功能网页游戏引擎，自带编辑器和物理。`TypeScript` `Apache-2.0`
- [PlayCanvas](https://github.com/playcanvas/engine) — WebGL 引擎，带多人协作在线编辑器。`JavaScript` `MIT`

## 叙事与专用工具

- [Ren'Py](https://github.com/renpy/renpy) — 视觉小说引擎（Python），已交付数百款游戏。`Python` `MIT`
- [Ink](https://github.com/inkle/ink) — Inkle 的叙事脚本语言（80 Days、Heaven's Vault 同款）。`C#` `MIT`
- [Twine](https://github.com/klembot/twinejs) — 非线性互动故事创作工具。`TypeScript` `GPL-3.0`
- [Adventure Game Studio](https://github.com/adventuregamestudio/ags) — 经典点击式冒险游戏引擎。`C++` `Artistic-2.0`
- [Minestom](https://github.com/Minestom/Minestom) — 自定义 Minecraft 服务器/小游戏的开发库。`Java` `Apache-2.0`
- [WorldEdit](https://github.com/EngineHub/WorldEdit) — Minecraft 建筑党的游戏内地图编辑器。`Java` `GPL-3.0`

---

## 教程与学习

- [Game Programming Patterns](https://github.com/munificent/game-programming-patterns) — 免费的游戏架构名著（另见 [gameprogrammingpatterns.com](https://gameprogrammingpatterns.com/)）。`HTML` `MIT`
- [Godot Demo Projects](https://github.com/godotengine/godot-demo-projects) — 官方 2D/3D 示例，覆盖主要功能。`GDScript` `MIT`
- [Godot 2D Platformer Starter](https://github.com/gdquest-demos/godot-3-beginner-2d-platformer) — GDQuest 的新手平台跳跃教程项目。`GDScript` `MIT`
- [Game Feel Demo](https://github.com/deepnight/gamefeel) — 打击感原型：震屏、粒子、顿帧。`Haxe`
- [MDN: Developing games on the Web](https://developer.mozilla.org/en-US/docs/Games) — Mozilla 的免费 2D/3D 网页游戏教程。🌐
- [GDQuest](https://www.gdquest.com/) — 免费开放的 Godot 教程和学习路线。🌐
- [Bevy Book](https://bevyengine.org/learn/book/getting-started/) — 官方指南，从零做出一个 Bevy 游戏。🌐

---

## 免费素材

自由协议（CC0 / CC-BY / CC-BY-SA / OFL）美术、声音和字体。下载具体素材包时请二次确认协议。

### 美术与精灵

- [Kenney](https://kenney.nl/assets) — 数千套风格统一的 CC0 精灵、瓦片、UI 和 3D 模型。🌐 `CC0`
- [OpenGameArt](https://opengameart.org/) — 社区像素画、精灵、贴图和 3D 模型。🌐 `混合自由协议`
- [itch.io free game assets](https://itch.io/game-assets/free) — 独立素材包，很多是 CC0。🌐 `混合`

### 音频与音乐

- [Freesound](https://freesound.org/) — 大型协作音效库（按 CC0/CC-BY 筛选）。🌐 `混合自由协议`
- [Incompetech](https://incompetech.com/) — Kevin MacLeod 的免费配乐（CC-BY）。🌐 `CC-BY`
- [OpenGameArt audio](https://opengameart.org/art-search-advanced?keys=&field_art_type_tid%5B%5D=13) — 自由协议的音乐 + 音效。🌐 `混合自由协议`

### 字体

- [Google Fonts](https://fonts.google.com/) — 免费字体，多为 SIL OFL，做游戏 UI 正合适。🌐 `OFL`
- [Open Font Library](https://fontlibrary.org/) — 只收自由字体。🌐 `OFL / 自由协议`

### 素材工具

- [Blender](https://github.com/blender/blender) — 3D 建模、雕刻、动画、剪辑一条龙。`C/C++` `GPL`
- [Tiled](https://github.com/mapeditor/tiled) — 标准的 2D 关卡/瓦片地图编辑器。`C++` `GPL-2.0`
- [Audacity](https://github.com/audacity/audacity) — 录制和剪辑游戏音频/音效。`C++` `GPL`

---

## 开发工具与底层库

引擎和游戏共用的底层模块。

- [SDL](https://github.com/libsdl-org/SDL) — 跨平台窗口、输入、音频和 GPU 层。`C` `zlib`
- [SFML](https://github.com/SFML/SFML) — 友好的 C++ 多媒体库。`C++` `zlib`
- [GLFW](https://github.com/glfw/glfw) — 轻量 OpenGL/Vulkan 窗口 + 输入。`C` `zlib`
- [Dear ImGui](https://github.com/ocornut/imgui) — 即时模式 GUI，做工具和调试面板。`C++` `MIT`

---

## 社区与活动

- [itch.io Game Jams](https://itch.io/jams) — 参加 Game Jam，很多参赛作品就是开源的。🌐
- [Ludum Dare](https://ldjam.com/) — 2002 年延续至今的经典 48/72 小时 Game Jam。🌐
- [LibreGameWiki](https://libregamewiki.org/) — 自由游戏的维基目录。🌐

---

## 参与贡献

欢迎投稿！请先读 [CONTRIBUTING.md](CONTRIBUTING.md)——每个条目必须是开源、可玩/可构建，且链接有效。

## License

本列表以 [CC0 1.0 Universal](LICENSE) 发布，可随意使用。
