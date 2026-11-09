# Hi, I'm Wutthichai

I build complete systems from scratch: shipped mobile software, browser games, real-time WebGL experiences, and the measurement tools that tell me when they fail.

First-year Computer Science student.

---

## Flagship work

**[The Crystal Ballroom](projects/crystal-ballroom/README.md)** · [explore the live 3D scene](https://crystal-ballroom-lunaria.web.app/)

[![A walkable crystal ballroom with a glass dome, chandeliers, stained glass, and Lunaria](projects/crystal-ballroom/hall.png)](https://crystal-ballroom-lunaria.web.app/)

A walkable fantasy hall built with a scripted Blender-to-Three.js pipeline. The scene combines stained glass, a reflective floor, lighting effects, collision, and Lunaria, a rigged and animated character. [Build notes and credits](projects/crystal-ballroom/README.md).

`Blender · Three.js · WebGL · 3D character animation`

**[ROMNGAO](https://github.com/sacmaib80-cmyk/demo-sites)** · [walk through the house](https://sacmaib80-cmyk.github.io/demo-sites/estate/)

[![A two-storey house at dusk with its lights on, surrounded by large trees, rendered from the site's 3D model](https://raw.githubusercontent.com/sacmaib80-cmyk/demo-sites/main/estate/art/sun-1745-960.webp)](https://sacmaib80-cmyk.github.io/demo-sites/estate/)

A housing-development site for a fictional project. You can walk through every room in the browser, climb the stairs, and drag the time of day to change the light. The floor plan, 3D model, collision, and walking routes all read from one data file. The first screen is a still rendered from that model; the 3D scene loads only when you enter the house.

`Three.js · WebGL2 · progressive rendering · no build step`

**[ตั้งใจดี](https://github.com/sacmaib80-cmyk/demo-sites)** · [open the shop](https://sacmaib80-cmyk.github.io/demo-sites/order-bill/) · [owner view](https://sacmaib80-cmyk.github.io/demo-sites/order-bill/owner.html)

[![A top-down market stall on blue tarpaulin with round trays of dried goods and a yellow paper bill](https://raw.githubusercontent.com/sacmaib80-cmyk/demo-sites/main/thumbs/order-bill.webp)](https://sacmaib80-cmyk.github.io/demo-sites/order-bill/)

An ordering system for a fictional small shop: customers fill a paper-style bill and get a PromptPay QR, and the owner manages orders, prices, and products. It is designed for Google Sheets and Apps Script. The live demo runs that backend in the browser against a simulated Google, and it has not yet run on real Google services.

`Vanilla JS · Google Apps Script · PromptPay QR`

**[MERIDIAN ONE](https://github.com/sacmaib80-cmyk/meridian-pen)** · [live](https://sacmaib80-cmyk.github.io/meridian-pen/)

A scroll-driven product site whose pen, internals, lighting, ink trace, and post-processing are generated live in raw WebGL2. No image or 3D-model assets.

`WebGL2 · procedural geometry · IBL · adaptive resolution`

**[DEEPWARD](https://github.com/sacmaib80-cmyk/deepward)** · [live](https://sacmaib80-cmyk.github.io/deepward/)

A bilingual vertical-city game-site concept where one depth value drives chronology, light, palette, copy, interface readouts, and scene transitions.

`Vanilla JS · WebGL2 · i18n · 61 browser checks`

**[SakuraQ](https://github.com/sacmaib80-cmyk/sakuraq)** · [web app](https://sakuraq-b7f96.web.app/welcome.html)

<a href="https://github.com/sacmaib80-cmyk/sakuraq"><img src="https://raw.githubusercontent.com/sacmaib80-cmyk/sakuraq/main/screens/sakuraq-1-home.png" width="240" alt="SakuraQ home screen: daily points, a mascot in a room scene, and the bottom navigation"></a>

A quest-style focus system shipped as an Android APK and installable PWA. Recent iterations added calendar-based plans, user-defined goal tags, cloud sync, OS-level alarms, and full-scene cosmetics.

`Vanilla JS · Capacitor · Firebase · PWA`

**[WebStudy](https://github.com/sacmaib80-cmyk/webstudy)** · [live lab](https://sacmaib80-cmyk.github.io/webstudy/)

Five accepted real-time graphics experiments kept beside executable checks for shaders, simulations, interaction, layout, and frame cost.

`WebGL2 · GPU simulation · browser QA`

---

## Systems and games

**[AI Flow](https://github.com/sacmaib80-cmyk/ai-flow)**

A live, evidence-first map of local automations, logs, scheduler state, failures, and verified data paths.

`Node.js · WebSocket · SQLite`

**[Pixel Clash](https://github.com/sacmaib80-cmyk/pixel-clash)**

[![Two pixel fighters trading blows under a torii gate at night](https://raw.githubusercontent.com/sacmaib80-cmyk/pixel-clash/main/screens/pixelclash-loop.gif)](https://github.com/sacmaib80-cmyk/pixel-clash)

A peer-to-peer pixel fighter with four-character rooms, fixed-step simulation, code-drawn art, combos, and finishers.

`React · Canvas 2D · WebRTC · Capacitor`

**[Moonfall](https://github.com/sacmaib80-cmyk/moonfall)** · [play](https://sacmaib80-cmyk.github.io/moonfall/)

[![A black werewolf with red eyes on a cobbled path outside a lamp-lit village inn at night](https://raw.githubusercontent.com/sacmaib80-cmyk/moonfall/main/screens/wolf.png)](https://sacmaib80-cmyk.github.io/moonfall/)

A real-time werewolf game in a 3D village modeled entirely in code, with line of sight that stops at walls and shutters that open. Playable in the browser against bots.

`Three.js · WebGL · Node.js · WebSocket`

**[SakuraQ Native](https://github.com/sacmaib80-cmyk/sakuraq-native)**

A deliberate native rewrite of SakuraQ with timestamp-safe timers and 22 tests around scoring and abuse cases.

`Kotlin · Jetpack Compose · DataStore`

**[Code Dojo](https://github.com/sacmaib80-cmyk/code-dojo)** · [live](https://sakuraq-b7f96.web.app/dojo/)

[![Three people in one Code Dojo code room: remote carets, a remote pointer, and run output](https://raw.githubusercontent.com/sacmaib80-cmyk/code-dojo/main/screens/dojo-code-room.png)](https://github.com/sacmaib80-cmyk/code-dojo#code-room)

A teaching site with 217 exercises across 21 progressively unlocked stages. The live version now also has shared code and flowchart rooms, multi-user cursors, TypeScript diagnostics, and saved code runs; the repository holds the standalone exercise app.

`HTML · CSS · JavaScript · TypeScript tooling · realtime collaboration`

---

## Reusable engineering

**[webgl-kit](https://github.com/sacmaib80-cmyk/webgl-kit)**

Dependency-free WebGL2 modules for shaders, IBL, fluids, heightfields, ribbons, and adaptive quality, with real browser compilation checks.

**[web-kit](https://github.com/sacmaib80-cmyk/web-kit)**
Small scroll, motion, localisation, asset, video, and browser-audit utilities extracted from visual-site production work.

---

## How I work

I prefer evidence over presentation claims: runnable checks, real-device constraints, measured frame cost, release artefacts, and notes about what is still incomplete.
