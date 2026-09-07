<div align="center">

# ⚙️ Dexoron Labs

**We build tools we personally wanted to exist — systems software, games, and web/UI, made to last.**

[![Website](https://img.shields.io/badge/site-dexoron.tech-A912C4?style=flat-square)](https://dexoron.tech)
[![GitHub](https://img.shields.io/badge/GitHub-Dexoron--Labs-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Dexoron-Labs)
[![GitLab](https://img.shields.io/badge/GitLab-dexoron--dev-FC6D26?style=flat-square&logo=gitlab&logoColor=white)](https://gitlab.com/dexoron-dev)
[![Contact](https://img.shields.io/badge/contact-main%40dexoron.su-A912C4?style=flat-square)](mailto:main@dexoron.su)

</div>

---

## About

Dexoron Labs is a small, independent studio — no investors, no roadmap dictated from above, just people building what they think should exist. We don't specialize in a stack or a genre; we've shipped systems software, games, and web/UI, and we'll keep moving wherever the next idea takes us.

The one constant is how a project starts: someone on the team needed a thing that didn't exist, built it, and it turned out useful enough to share. That's the whole origin story behind everything here, DCR included.

## Projects

### 🛠️ [DCR](https://github.com/dexoron/dcr) — Dexoron Cargo Realization

A cross-platform build and dependency manager for C/C++/Assembly, written in Rust, modeled on Cargo's workflow. Site: [dcr.dexoron.tech](https://dcr.dexoron.tech)

- Own dependency registry (`dcr-index`)
- Full package lifecycle management: project scaffolding (`dcr init`, `dcr template`), dependency isolation, and lockfiles (`dcr.lock`)
- Multi-backend build support (GCC, Clang, MSVC, NASM/FASM/GAS) and `clang-tidy` integration (`dcr lint`)
- Distributed via AUR and Homebrew, with a Docusaurus-based documentation site and Crowdin localization

### 💻 [DCR IDE](https://gitlab.com/dexoron-dev/dcr-tool/dcride)

A lightweight, dedicated IDE built specifically for systems programming and the DCR ecosystem.

- Rust + Tauri 2 backend with Svelte 5 reactive frontend, running on Bun
- Shares a `.dcr/` facts store (build info, compiler flags, toolchain state) with the DCR CLI to keep the editor and terminal perfectly synchronized
- Native integration with `compile_commands.json` and DCR build metrics
- Distinct visual identity: dark theme palette, Lucide + Material icon set, designed in Figma

## Philosophy

- **Open source first.** Public from day one, not after it's "ready."
- **Built out of need.** No roadmap-driven feature work — every project starts as a real problem.
- **Small and direct.** No process for the sake of process. Just people shipping what they use.

## Tech

`Rust` · `Tauri 2` · `Svelte 5` · `TypeScript` · `C/C++` · `Python`

## Get in touch

Bug reports and ideas go on the project repos. For anything else — [main@dexoron.tech](mailto:main@dexoron.tech).

---

<div align="center">

*Dexoron Labs — [dexoron.tech](https://dexoron.tech)*

</div>
