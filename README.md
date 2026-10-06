<h1 align="center">Hi, I'm Sep</h1>

<p align="center">
  I build tools that let AI agents do real work on real machines, without giving them the keys to everything.<br>
  Interested in machine learning, scalable systems, and data and computational finance.
</p>

<p align="center">
  <a href="https://github.com/Sep-Fading/miniclaw-windows"><img alt="MiniClaw" src="https://img.shields.io/badge/MiniClaw-agent%20runtime-1f6feb?style=for-the-badge"></a>
  <a href="mailto:sepehr.shamloo3443@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-say%20hi-ea4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

### What I'm working on

**[MiniClaw](https://github.com/Sep-Fading/miniclaw-windows)** is a desktop runtime for coding agents (Codex and Claude Code) that runs their shell commands, file edits and MCP tool servers inside an OS sandbox, with per-folder grants and an approval flow, on macOS and Windows.

The Windows port, done from scratch, meant going deep into the platform:

- A **least-privileged AppContainer sandbox** for every agent command, with a Windows Filtering Platform service that allows only approved hosts through a local proxy
- Handle-relative **file policy** that resists junctions, hard links, 8.3 aliases and alternate data streams
- **Crash-safe cleanup journals** so a killed agent never leaves permissions behind
- A patched **Git**, a private **Node** and a Python hook so real tools run inside the sandbox
- A terminal on **ConPTY**, a setup wizard that installs its own prerequisites, and an update path with rollback

Verified with a native acceptance suite of about 350 tests, including a standard-user run and an independent security review.

### Tools I reach for

<p>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="Svelte" src="https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
  <img alt="Windows" src="https://img.shields.io/badge/Windows%20internals-0078D4?style=flat-square&logo=windows&logoColor=white">
  <img alt="macOS" src="https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white">
  <img alt="Blender" src="https://img.shields.io/badge/Blender-F5792A?style=flat-square&logo=blender&logoColor=white">
  <img alt="Roblox" src="https://img.shields.io/badge/Roblox-000000?style=flat-square&logo=roblox&logoColor=white">
</p>

- **Systems:** process sandboxing, ACLs and tokens, network filtering, pseudo-consoles, crash recovery
- **Agents:** Model Context Protocol servers and clients, approval flows, tool bridges for Codex and Claude Code
- **Product:** desktop web UIs in Svelte, installers that get out of the way, test-first development with native acceptance suites
- **3D and games:** Blender and Roblox Studio pipelines driven by agents, from a prompt to a mesh in the scene

### What I'm interested in

- **Machine learning:** how models are trained, evaluated and put to work as agents that can be trusted with real tasks
- **Scalable systems:** the data paths, isolation boundaries and failure modes that keep large systems honest under load
- **Data and computational finance:** market data pipelines, quantitative models and the engineering that makes them reproducible

### How I like to work

Write the failing test first. Prefer the documented API over the clever trick. Fail closed. Measure before optimising. Leave a written trail of what was verified and what wasn't.

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sep-Fading&show_icons=true&hide_border=true&theme=default" alt="GitHub stats" height="160">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sep-Fading&layout=compact&hide_border=true&theme=default" alt="Top languages" height="160">
</p>
