# DoomEsque Theme for Obsidian

An authentic, distraction-free **Doom Emacs** inspired theme for Obsidian created by **Jason Gunst**, drawing inspiration from [hlissner/emacs-doom-themes](https://github.com/doomemacs/themes).

Designed for keyboard-centric note-takers, hackers, and Emacs enthusiasts who want an authentic, cohesive editor aesthetic inside Obsidian.

---

## Features

- **Authentic Color Schemes**:
  - **Dark Mode (Default)**: `doom-one` (`#282c34` base, `#21242b` alt, `#bbc2cf` foreground, `#51afef` blue, `#c678dd` magenta, `#98be65` green, `#da8548` orange).
  - **Light Mode (Default)**: `doom-one-light` (`#fafafa` base, `#f0f0f0` alt, `#383a42` foreground, `#4078f2` blue, `#a626a4` magenta).
  - **Additional Switchable Palettes**: `doom-vibrant`, `doom-dracula`, `doom-tokyo-night`, and `doom-gruvbox` with full RGB alpha-channel and semantic syntax harmony.
- **Org-Mode Buffer Typography & Elements**:
  - Rainbow heading hierarchy (`org-level-1` through `org-level-6`) or optional monochrome headings.
  - Optional `TODO` and `DONE` task list badges alongside checkboxes.
  - Org-styled frontmatter drawers, transclusion embeds, and `#+BEGIN_SRC` code blocks with left accent borders and `font-lock` syntax highlighting.
- **Doom Modeline & Window Chrome**:
  - Bottom status bar styled after `doom-modeline` with the signature colored left mode badge.
  - Flat, clean buffer tabs with active buffer accent highlights.
  - `M-x` Vertico / Ivy / Which-key styled command palette, quick switcher, and context menus.
  - Treemacs / Dired styled file explorer.
- **Refined Settings Window**:
  - Clean, comfortable card containers with 6px rounded geometry and generous 18px horizontal padding (no harsh square backgrounds or zero-padding edges).
  - Smooth pill toggle switches with circular thumbs and glowing active accents.
  - Optional flat border-delimited row style via Style Settings or the companion plugin.
- **Hover Preview & Popovers**:
  - Fully unconstrained preview windows with adjustable width, height, text scaling, and draggable modeline header.
  - Supports sticky preview windows and Super-key sidebar pop-out.
- **Full Device Support**:
  - Optimized for desktop (macOS, Linux, Windows) and mobile (iOS, iPadOS, Android).

---

## 100% Offline & Secure

- **Zero Network Calls**: `theme.css` is completely local and offline.
- **Zero Remote Imports**: No `@import` rules, no external stylesheet requests, and no remote CDN font or image URLs.
- **Local Typography**: Uses locally installed monospace fonts (`JetBrains Mono`, `Iosevka`, `Fira Code`, `Source Code Pro`, `Cascadia Code`, `ui-monospace`, `SF Mono`, `Menlo`, `Monaco`) and system sans-serif fonts (`Inter`, `-apple-system`, `Segoe UI`, `Roboto`).

---

## Companion Plugin

For keyboard commands, live sliders, and enhanced sticky hover previews, install the companion plugin **[DoomEsque Settings](https://github.com/jasongunst/obsidian-doomesque-settings)** or configure options via the **Style Settings** community plugin.

---

## Installation

### From Obsidian Community Themes
1. Open **Settings → Appearance → Themes → Manage**.
2. Search for **DoomEsque** and click **Install and use**.

### Manual Installation
Copy [`manifest.json`](./manifest.json) and [`theme.css`](./theme.css) into your vault's `.obsidian/themes/DoomEsque/` directory:

```bash
mkdir -p "/path/to/your/vault/.obsidian/themes/DoomEsque"
cp manifest.json theme.css "/path/to/your/vault/.obsidian/themes/DoomEsque/"
```

---

## License

[MIT License](./LICENSE) © 2026 Jason Gunst
