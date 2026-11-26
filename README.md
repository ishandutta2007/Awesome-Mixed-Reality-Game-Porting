<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Mixed Reality Game Porting Banner" width="100%">
</p>

# 🥽 Awesome Mixed Reality Game Porting

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Mixed-Reality-Game-Porting/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Mixed-Reality-Game-Porting?style=flat-square&logo=github" alt="Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Mixed-Reality-Game-Porting/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Mixed-Reality-Game-Porting?style=flat-square&logo=github" alt="Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Mixed-Reality-Game-Porting/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Mixed-Reality-Game-Porting?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Mixed Reality & Game Porting Ecosystem

**A Curated List of SaaS Platforms & Open-Source GitHub Projects for Mixed Reality (MR), Virtual Reality (VR), Spatial Computing & Flat-to-VR Game Porting**  
*Targeting Mixed Reality Passthrough Ports, OpenXR Runtimes, Low-Latency Wireless PCVR Streaming, 6DoF Flat-to-VR Modding Injectors & Standalone XR Sideloading*  
📅 **Last updated: November 2026**

This comprehensive guide tracks leading **commercial SaaS/enterprise platforms** and active **open-source repositories** powering **Mixed Reality Game Porting and Spatial Computing**. These industry-grade tools empower XR game developers, indie modders, reverse engineers, and spatial computing architects to convert classic flat-screen 3D games into stereoscopic 6DoF Mixed Reality (`OpenXR` passthrough), stream high-bitrate PCVR wirelessly to standalone HMDs, inject full 6DoF VR motion controls into modern engines (Unreal Engine & Unity), and sideload standalone Android XR binaries.

Whether you are porting retro classics to Meta Quest 3/Pro or Apple Vision Pro, deploying low-overhead OpenXR runtimes on Linux, or setting up wireless Wi-Fi 6E/7 PCVR streaming pipelines, this directory provides authoritative technical benchmarks, pricing tiers, market data, and GitHub star metrics.

---

## 📑 Table of Contents
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [💼 SaaS & Commercial Hosted Platforms](#-saas--commercial-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ Recommended Toolchains for Custom Porting](#️-recommended-toolchains-for-custom-porting)
- [🤝 How to Contribute](#-how-to-contribute)
- [☕ Support](#-support)
- [📈 Star History](#-star-history)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

> [!NOTE]
> The global spatial computing and mixed reality gaming market is estimated at **$28.5 billion in 2025** and projected to exceed **$112 billion by 2031**, progressing at a CAGR of 25.8%.
> 
> The sector exhibits **moderate-to-high concentration in foundational hardware and operating system runtimes** (dominated by Meta Horizon OS, Valve SteamVR, Apple visionOS, and HTC VIVE), while exhibiting **high fragmentation across the application modding layer, spatial streaming utilities, collaborative 3D authoring tools, and indie sideloading ecosystems**. As open standards like **OpenXR** and open-source injectors (**UEVR**, **Monado**, **WiVRn**) mature, the developer tooling tier continues to foster vibrant, decentralized community innovation.

---

## 💼 SaaS & Commercial Hosted Platforms

The following table details leading commercial platforms, SaaS spatial services, and enterprise streaming runtimes supporting Mixed Reality game deployment, desktop streaming, and spatial authoring, sorted descending by company scale (valuation / market capitalization / parent revenue).

| 🏢 Platform | 📝 Overview & Core Features | 💰 Starting Pricing | 🎁 Free Tier / Trial Limit | 📈 Company Scale (Valuation / Revenue) |
| :--- | :--- | :--- | :--- | :--- |
| **[Meta Quest Link & Horizon OS SDK](https://meta.com)** | Official PC-to-Quest wired/wireless Air Link runtime, Spatial SDK with high-res passthrough, scene mesh anchors & hand tracking. | **Free** ($0 for runtime & developer SDKs; Meta Quest headset hardware required) | **Free Forever** (Unlimited access to Link runtime, Horizon OS SDKs, samples, and OpenXR debugging tools) | **~$1.55 Trillion** *(Meta Market Cap / $164B+ Annual Revenue)* |
| **[SteamVR & Steam Link (Valve)](https://steampowered.com)** | Industry-standard PCVR compositor, OpenXR runtime, and ultra-low-latency wireless headset streaming client. | **Free** ($0 runtime & streaming client; commercial games sold separately) | **Free Forever** (Completely free for PCVR streaming, OpenXR debugging, and developer workshop deployment) | **~$8.0 Billion+** *(Valve Corporation estimated valuation / $13B+ ARR)* |
| **[Viveport (HTC VIVE)](https://viveport.com)** | Commercial XR content distribution ecosystem and cross-headset runtime supporting VIVE XR Elite, Focus Vision & PCVR. | **$12.99 / month** *(Viveport Infinity subscription for unlimited game library access)* | **14-Day Free Trial** (Full access to curated library of 1,000+ VR/MR titles; basic storefront account is free forever) | **~$1.2 Billion** *(HTC Corp Market Cap / $300M+ Annual Revenue)* |
| **[Gravity Sketch](https://gravitysketch.com)** | Cloud-connected collaborative 3D spatial modeling, rapid prototyping, and architectural Mixed Reality design suite. | **$99.00 / month** per user *(Enterprise tier; custom advanced security & SSO available)* | **Free Forever Individual Tier** (Unlimited sketching, basic cloud storage, and personal non-commercial export tools) | **~$200 Million** *(Venture valuation; $33M+ total funding raised)* |
| **[Immersed](https://immersed.com)** | Cloud-synced virtual workspace projecting multiple high-framerate virtual monitors into Mixed Reality passthrough. | **$9.99 / month** *(Immersed Pro tier with unlimited virtual screens & high-res passthrough portals)* | **Free Forever Basic Plan** (Up to 2 virtual desktop screens, 1080p stream resolution, standard Wi-Fi mode) | **~$150 Million** *(Publicly traded / SPAC valuation; Visor hardware ecosystem)* |
| **[Varjo Reality Cloud & Teleport](https://varjo.com)** | Enterprise cloud-rendered XR streaming and photorealistic mixed-reality digital twin collaboration platform. | **$1,500 / month** *(Enterprise Cloud Streaming seat license for low-latency photorealistic streaming)* | **30-Day Free Trial** (Full evaluation trial for enterprise teams, including sample high-fidelity twin models) | **~$120 Million** *(Enterprise XR valuation; backed by EQT Ventures & Lifeline)* |
| **[Bigscreen VR](https://bigscreenvr.com)** | Cloud-connected social VR/MR cinema, ultra-low latency desktop streaming, and spatial watch-parties across Quest and PCVR. | **Free core app** ($3.99 - $14.99 per commercial 3D movie rental or custom spatial cinema environments) | **Free Forever Core App** (Unlimited personal desktop streaming, public/private rooms up to 15 users, free YouTube/Twitch rooms) | **~$40 Million** *(Venture backed; True Ventures & Andreessen Horowitz seed)* |
| **[ShapesXR](https://shapesxr.com)** | Collaborative cloud 3D spatial design and MR prototyping platform to storyboard passthrough layouts and export to Unity/Figma. | **$12.00 / month** per editor *(Team plan with multi-user real-time co-presence & cloud syncing)* | **Free Forever Starter Plan** (Up to 3 collaborative spaces, 100MB cloud asset storage, unlimited viewer seats) | **~$35 Million** *(Venture valuation; Supernode Global & Boost VC backed)* |
| **[SideQuest](https://sidequestvr.com)** | Premier indie VR/MR app marketplace, wireless ADB sideloading hub, and developer distribution platform for standalone XR. | **Free** ($0 for developers and gamers; optional developer promotional ads starting at $150/campaign) | **Free Forever** (Unlimited game sideloading, headset ADB tweaking, backup tools, and community APK hosting) | **~$25 Million** *(Venture funded; backed by Google Ventures & Palmer Luckey)* |
| **[Virtual Desktop](https://vrdesktop.net)** | Commercial ultra-low-latency wireless PCVR and spatial desktop streaming suite with AV1/HEVC encoding and VDXR OpenXR runtime. | **$19.99** one-time purchase *(Meta Quest Store / Pico Store / Apple Vision Pro)* | **No Permanent Free Plan** (No free version; standard 14-day / 2-hour refund window applies via Meta Quest Store) | **~$15 Million** *(Bootstrapped independent studio by Guy Godin; multi-million dollar annual revenue)* |

---

## 🔓 Open-Source GitHub Projects

The following repositories represent the open-source backbone of Mixed Reality game porting, OpenXR runtimes, flat-to-VR injectors, stereoscopic emulators, and wireless streaming layers. 

Sorted descending by **GitHub Stargazer Count**:

1. **[three.js](https://github.com/mrdoob/three.js)** [![Stars](https://img.shields.io/github/stars/mrdoob/three.js?style=social&color=white)](https://github.com/mrdoob/three.js/stargazers)  
   The industry-defining JavaScript 3D library featuring native WebXR device managers, spatial anchors, stereoscopic camera rigs, and browser-based Mixed Reality passthrough rendering.
2. **[scrcpy](https://github.com/Genymobile/scrcpy)** [![Stars](https://img.shields.io/github/stars/Genymobile/scrcpy?style=social&color=white)](https://github.com/Genymobile/scrcpy/stargazers)  
   High-performance Android screen mirroring and control utility over USB/Wi-Fi, universally used by XR developers to capture, debug, and monitor standalone headset passthrough feeds at ultra-low latency.
3. **[Godot Engine](https://github.com/godotengine/godot)** [![Stars](https://img.shields.io/github/stars/godotengine/godot?style=social&color=white)](https://github.com/godotengine/godot/stargazers)  
   Full-featured open-source 2D/3D game engine featuring built-in OpenXR support, Android/Quest APK export pipelines, scene understanding, passthrough blending, and hand-tracking APIs.
4. **[A-Frame](https://github.com/aframevr/aframe)** [![Stars](https://img.shields.io/github/stars/aframevr/aframe?style=social&color=white)](https://github.com/aframevr/aframe/stargazers)  
   Web-first virtual reality and mixed reality framework based on HTML/Three.js, enabling instantaneous cross-platform WebXR spatial applications across Quest, Vision Pro, and desktop browsers.
5. **[Dolphin Emulator](https://github.com/dolphin-emu/dolphin)** [![Stars](https://img.shields.io/github/stars/dolphin-emu/dolphin?style=social&color=white)](https://github.com/dolphin-emu/dolphin/stargazers)  
   Legendary GameCube and Wii emulator with stereoscopic rendering forks and OpenXR hooks allowing classic console titles to be experienced with true depth and 6DoF camera hacks.
6. **[PPSSPP](https://github.com/hrydgard/ppsspp)** [![Stars](https://img.shields.io/github/stars/hrydgard/ppsspp?style=social&color=white)](https://github.com/hrydgard/ppsspp/stargazers)  
   Fast, cross-platform PlayStation Portable emulator featuring native VR rendering mode, 6DoF head-tracking hooks, and stereoscopic Mixed Reality viewport injection.
7. **[BepInEx](https://github.com/BepInEx/BepInEx)** [![Stars](https://img.shields.io/github/stars/BepInEx/BepInEx?style=social&color=white)](https://github.com/BepInEx/BepInEx/stargazers)  
   Universal Unity (.NET/Mono/IL2CPP) plugin injector and modding framework providing the foundational runtime for community Flat-to-VR ports (*Outer Wilds*, *Risk of Rain 2*, *Lethal Company*, *Subnautica*).
8. **[ALVR (Air Light VR)](https://github.com/alvr-org/ALVR)** [![Stars](https://img.shields.io/github/stars/alvr-org/ALVR?style=social&color=white)](https://github.com/alvr-org/ALVR/stargazers)  
   Leading open-source wireless PCVR streaming server and client transmitting SteamVR frames over Wi-Fi/USB to Meta Quest, Pico, Apple Vision Pro, and Android XR headsets.
9. **[Relativty](https://github.com/relativty/Relativty)** [![Stars](https://img.shields.io/github/stars/relativty/Relativty?style=social&color=white)](https://github.com/relativty/Relativty/stargazers)  
   Open-source, DIY VR headset architecture featuring 120Hz display firmware, SLAM tracking algorithms, and an affordable custom stereoscopic build pipeline.
10. **[UEVR (Praydog Universal Unreal VR Injector)](https://github.com/praydog/UEVR)** [![Stars](https://img.shields.io/github/stars/praydog/UEVR?style=social&color=white)](https://github.com/praydog/UEVR/stargazers)  
    Groundbreaking open-source injector converting thousands of flat-screen Unreal Engine 4 and 5 games into full 6DoF stereoscopic VR/MR experiences with native 3D UI and motion controller support.
11. **[Revive](https://github.com/LibreVR/Revive)** [![Stars](https://img.shields.io/github/stars/LibreVR/Revive?style=social&color=white)](https://github.com/LibreVR/Revive/stargazers)  
    Pioneering open-source compatibility layer allowing Oculus/Meta PCVR exclusive games to render on OpenXR and SteamVR-compatible headsets.
12. **[LÖVR](https://github.com/bjornbytes/lovr)** [![Stars](https://img.shields.io/github/stars/bjornbytes/lovr?style=social&color=white)](https://github.com/bjornbytes/lovr/stargazers)  
    Simple, ultra-fast Lua framework for building 3D, Virtual Reality, and Mixed Reality games, compiling cleanly to standalone Meta Quest APKs and desktop OpenXR.
13. **[WiVRn](https://github.com/WiVRn/WiVRn)** [![Stars](https://img.shields.io/github/stars/WiVRn/WiVRn?style=social&color=white)](https://github.com/WiVRn/WiVRn/stargazers)  
    High-performance, open-source OpenXR streaming server and Android headset client built directly on Monado, delivering native Linux PCVR streaming without SteamVR overhead.
14. **[vrperfkit](https://github.com/fholger/vrperfkit)** [![Stars](https://img.shields.io/github/stars/fholger/vrperfkit?style=social&color=white)](https://github.com/fholger/vrperfkit/stargazers)  
    Open-source VR modder post-processing toolkit providing fixed foveated rendering, AMD FidelityFX Super Resolution (FSR), and NVIDIA NIS upscaling directly into DX11 VR games.
15. **[OpenXR-SDK](https://github.com/KhronosGroup/OpenXR-SDK)** [![Stars](https://img.shields.io/github/stars/KhronosGroup/OpenXR-SDK?style=social&color=white)](https://github.com/KhronosGroup/OpenXR-SDK/stargazers)  
    Foundational open-source cross-platform API standard from Khronos Group unifying VR and Mixed Reality hardware access, stereoscopic swapchains, and passthrough layers.
16. **[SlimeVR Tracker Server](https://github.com/SlimeVR/SlimeVR-Server)** [![Stars](https://img.shields.io/github/stars/SlimeVR/SlimeVR-Server?style=social&color=white)](https://github.com/SlimeVR/SlimeVR-Server/stargazers)  
    Open-source DIY full-body tracking (FBT) server connecting IMU-based trackers to SteamVR, VRChat, and standalone Quest MR games without base stations.
17. **[SlimeVR ESP Firmware](https://github.com/SlimeVR/SlimeVR-Tracker-ESP)** [![Stars](https://img.shields.io/github/stars/SlimeVR/SlimeVR-Tracker-ESP?style=social&color=white)](https://github.com/SlimeVR/SlimeVR-Tracker-ESP/stargazers)  
    Microcontroller firmware for open-source DIY IMU full-body motion tracking on ESP8266 and ESP32 boards.
18. **[StereoKit](https://github.com/StereoKit/StereoKit)** [![Stars](https://img.shields.io/github/stars/StereoKit/StereoKit?style=social&color=white)](https://github.com/StereoKit/StereoKit/stargazers)  
    Lightweight, code-first C# open-source Mixed Reality library built natively on OpenXR with spatial input, hand tracking physics, and cross-platform Quest/PC/HoloLens deployment.
19. **[CitraVR](https://github.com/amwatson/CitraVR)** [![Stars](https://img.shields.io/github/stars/amwatson/CitraVR?style=social&color=white)](https://github.com/amwatson/CitraVR/stargazers)  
    Native standalone Meta Quest port of the Citra Nintendo 3DS emulator bringing stereoscopic 3D screens, Mixed Reality passthrough backgrounds, and 6DoF motion controller mapping.
20. **[OpenXR-Toolkit](https://github.com/mbucchia/OpenXR-Toolkit)** [![Stars](https://img.shields.io/github/stars/mbucchia/OpenXR-Toolkit?style=social&color=white)](https://github.com/mbucchia/OpenXR-Toolkit/stargazers)  
    Community-standard OpenXR API layer providing advanced foveated rendering, custom resolution overrides, color grading, and hand-tracking emulation for OpenXR flight sims and ported games.
21. **[SideQuest Desktop](https://github.com/SideQuestVR/SideQuest)** [![Stars](https://img.shields.io/github/stars/SideQuestVR/SideQuest?style=social&color=white)](https://github.com/SideQuestVR/SideQuest/stargazers)  
    Official open-source desktop client for SideQuest, facilitating wireless ADB sideloading of custom XR APKs, game mods, texture pack installs, and system diagnostics.
22. **[mario64mr](https://github.com/lucas-martinic/mario64mr)** [![Stars](https://img.shields.io/github/stars/lucas-martinic/mario64mr?style=social&color=white)](https://github.com/lucas-martinic/mario64mr/stargazers)  
    Groundbreaking open-source native Mixed Reality port of *Super Mario 64* featuring 6DoF stereoscopic camera controls, physics-based object collision with your real-world room, and live passthrough gameplay.
23. **[Stardust XR](https://github.com/stardustxr/server)** [![Stars](https://img.shields.io/github/stars/stardustxr/server?style=social&color=white)](https://github.com/stardustxr/server/stargazers)  
    Open-source spatial Linux display server and 3D Wayland compositor enabling 2D desktop apps and spatial 3D widgets to run natively inside a unified Mixed Reality workspace.

---

## 🛠️ Recommended Toolchains for Custom Porting

To build and port high-performance Mixed Reality games, leverage the following battle-tested stacks:

- **Classic PC 3D Games to MR**: Use **UEVR** (Unreal Engine 4/5) or **BepInEx + UUVR** (Unity titles) paired with **OpenXR-Toolkit** to inject 6DoF camera tracking, stereoscopic rendering, and spatial controller bindings.
- **Standalone Android XR Ports**: Pair native C/C++ game engine decompilations with **Khronos OpenXR-SDK** or compile directly with **Godot Engine + Godot OpenXR Vendors Plugin** or **StereoKit** for native standalone `.apk` packaging.
- **Wireless PCVR to Standalone Headset Streaming**: Deploy **ALVR** or **WiVRn** (backed by the **Monado** OpenXR runtime) alongside **scrcpy** for low-latency Wi-Fi 6E/7 streaming without proprietary runtime bloat.

---

## 🤝 How to Contribute

Contributions are warmly welcomed! Help expand this ecosystem:

1. **Fork the Repository** to your GitHub account.
2. **Add or Update Entries** in `README.md` following the table or list schema.
3. Ensure all links point to official repositories, platforms, or project documentation.
4. Verify repository star links point directly to the stargazers page.
5. **Open a Pull Request** with a concise summary of the addition or correction.

---

## ☕ Support

If you find this curated Mixed Reality Game Porting directory helpful for your development, porting projects, or research, please consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork and contribute** new open-source ports, injectors, or benchmarks.
- 📢 **Share with fellow XR developers** and game modding communities.
- ☕ **Buy me a coffee**: Sponsor ongoing open-source curation and development via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Mixed-Reality-Game-Porting&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Mixed-Reality-Game-Porting&type=date&legend=top-left)
[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Mixed-Reality-Game-Porting&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Mixed-Reality-Game-Porting&type=date&legend=top-left)

---

## ⚖️ Disclaimer

- This curated list is maintained for educational, research, and developer community purposes.
- Trademarks, game titles, and brand names (e.g., Meta, Valve, SteamVR, HTC VIVE, Apple, Nintendo) belong to their respective copyright holders. Mentioning them does not imply official endorsement or affiliation.
