# ReForge3D Roadmap

A modern revival of the Torque 3D game engine — bringing classic Torque DNA into 2026+ with better performance, tools, and rendering while staying indie-friendly and fully open source.

## Vision
Create a **lightweight, powerful, and fun-to-use** open-source 3D engine ideal for retro-style FPS, multiplayer games, simulations, and passionate indie projects.

---

## Phases

### Phase 0: Foundation (Current – Q3 2026)
- [x] Fork from active community repo (`TorqueGameEngines/Torque3D`)
- [ ] Clean up repository (README, ROADMAP, CONTRIBUTING, license headers)
- [ ] Set up CI builds (Windows + Linux)
- [ ] Update build system & dependencies (vcpkg, CMake improvements)
- [ ] Create clear contribution guidelines and development branches

**Goal**: Make the project approachable for new contributors.

### Phase 1: Modernization (Q3–Q4 2026)
**High Priority**
- Modern rendering backend (Vulkan + fallback to DX12/OpenGL)
- Improved PBR materials and lighting
- Better multi-threading (job system, parallel scene updates)
- Editor refresh (Dear ImGui integration or hybrid editor)
- Asset pipeline improvements (better glTF support, texture compression)

**Medium Priority**
- Upgrade physics integration (Bullet 3 / PhysX 5)
- Modern input system + better controller support
- Performance profiling tools

### Phase 2: Polish & Features (2027)
- Advanced rendering features (temporal AA, dynamic shadows, global illumination basics)
- Scripting enhancements (better TorqueScript performance + optional C#/.NET binding)
- VR/AR experimental support
- Improved networking tools (easy matchmaking, voice chat hooks)
- Quality-of-life editor tools (better terrain, foliage, prefab system)

### Phase 3: Ecosystem & Stability (2027+)
- Official documentation overhaul
- Example projects / starter kits (FPS, multiplayer, etc.)
- Binary releases + package manager integration
- Community tools (Discord, wiki migration)
- Long-term maintenance plan

---

## Stretch Goals
- WebAssembly / WebGPU export
- Node-based visual scripting
- Built-in modding framework
- High-end AAA-level rendering options (while keeping the lightweight core)

---

## How to Contribute
- See [CONTRIBUTING.md](./CONTRIBUTING.md)
- Check the [Projects board](https://github.com/orgs/TorqueGameEngines/projects/1) for current tasks
- Join the discussion on the [Torque3D forums](https://torque3d.org/forums)

**This is a community-driven project.** Feedback and help are always welcome!

---

*Last updated: July 2026*
