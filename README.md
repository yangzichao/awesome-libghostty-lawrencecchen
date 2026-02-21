# Awesome libghostty [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of projects and resources built with `libghostty` and `libghostty-vt`.

This list is focused on actively maintained, technically relevant projects (terminals, multiplexers, browser/editor integrations, and developer tooling).

Last audited: 2026-02-21

## Contents

- [Core Resources](#core-resources)
- [Terminal Apps](#terminal-apps)
- [Multiplexers and Session Tools](#multiplexers-and-session-tools)
- [Web and Editor Integrations](#web-and-editor-integrations)
- [Agent-Focused Workspaces](#agent-focused-workspaces)
- [Closed-Source Products](#closed-source-products)
- [Other Awesome Lists](#other-awesome-lists)
- [Research Audit](#research-audit)
- [Contributing](#contributing)

## Core Resources

- [ghostty-org/ghostty](https://github.com/ghostty-org/ghostty) - Upstream Ghostty project and home of `libghostty`.
- [libghostty API Reference](https://libghostty.tip.ghostty.org/index.html) - Generated API docs for embedding and integration.
- [libghostty is coming](https://mitchellh.com/writing/libghostty-is-coming) - Original announcement and ecosystem context.

## Terminal Apps

- [manaflow-ai/cmux](https://github.com/manaflow-ai/cmux) - Ghostty-based macOS terminal with vertical tabs and notifications for AI coding agents.
- [blaine/fantastty](https://github.com/blaine/fantastty) - macOS terminal built on `libghostty` with workspaces, notes, and tmux-backed persistence.
- [vivy-company/vvterm](https://github.com/vivy-company/vvterm) - Ghostty-powered SSH client for iOS/iPadOS/macOS.
- [ocnc/spectty](https://github.com/ocnc/spectty) - iOS SSH and Mosh terminal with Metal rendering and Ghostty-inspired architecture.
- [codymullins/dotty](https://github.com/codymullins/dotty) - `.NET` terminal emulator using `libghostty`.
- [dindin12138/Husk](https://github.com/dindin12138/Husk) - Wayland terminal daemon written in C++ and powered by `libghostty`.
- [arya-s/phantty](https://github.com/arya-s/phantty) - Windows terminal renderer using `libghostty-vt`.
- [tapthaker/ghostty-android](https://github.com/tapthaker/ghostty-android) - Android terminal project using `libghostty-vt` and Jetpack Compose (early-stage).
- [sidequery/ghostree](https://github.com/sidequery/ghostree) - Agent/worktree-focused Ghostty fork.

## Multiplexers and Session Tools

- [neurosnap/zmx](https://github.com/neurosnap/zmx) - Session persistence tool that restores state via `libghostty-vt`.
- [monotykamary/openmux](https://github.com/monotykamary/openmux) - Terminal multiplexer using `libghostty-vt` for terminal state.
- [psyclyx/vanish](https://github.com/psyclyx/vanish) - Lightweight multiplexer with state preservation on top of `libghostty-vt`.
- [seruman/hauntty](https://github.com/seruman/hauntty) - Go daemon for persistent sessions backed by Ghostty VT parsing in WASM.
- [seruman/bootty](https://github.com/seruman/bootty) - Zig CLI/daemon for terminal automation with ghostty-vt.

## Web and Editor Integrations

- [coder/ghostty-web](https://github.com/coder/ghostty-web) - Ghostty terminal emulation for the web with xterm.js-compatible API.
- [wiedymi/restty](https://github.com/wiedymi/restty) - Web terminal library powered by `libghostty-vt`, WebGPU/WebGL2, and `text-shaper`.
- [0xBigBoss/vscode-bootty](https://github.com/0xBigBoss/vscode-bootty) - VS Code terminal extension backed by `libghostty-vt` via WASM.
- [mvfti/jupyterlab-ghostty-terminal](https://github.com/mvfti/jupyterlab-ghostty-terminal) - JupyterLab terminal extension powered by `libghostty`.
- [philipp-spiess/electron-libghostty](https://github.com/philipp-spiess/electron-libghostty) - Electron integration for embedding native `libghostty` surfaces.
- [Snoupix/browstty](https://github.com/Snoupix/browstty) - Zig/WASM experiment to run Ghostty terminal emulation in browsers.

## Agent-Focused Workspaces

- [supabitapp/supacode](https://github.com/supabitapp/supacode) - Native macOS coding-agent command center built with `libghostty`.
- [coder/mux](https://github.com/coder/mux) - Agent multiplexer with browser and desktop UX; closely related to `ghostty-web`.

## Closed-Source Products

- [OrbStack](https://orbstack.dev/) - Docker/Linux environment on macOS with Ghostty-powered terminal integration.
- [Echo](https://replay.software/echo) - iOS/iPadOS SSH and Mosh client built on Ghostty technology.
- [Commander](https://commanderai.app/) - Native macOS workspace for coding agents with embedded Ghostty-based terminal UX.

## Other Awesome Lists

- [Uzaaft/awesome-libghostty](https://github.com/Uzaaft/awesome-libghostty) - Community-maintained list with open-source and commercial projects.
- [jc00ke/awesome-libghostty](https://github.com/jc00ke/awesome-libghostty) - Minimal starter list.

## Research Audit

- [2026-02-21 ecosystem audit](research/2026-02-21-audit.md) - Discovery queries, repositories reviewed, and inclusion decisions.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting additions.

## License

[MIT](LICENSE)
