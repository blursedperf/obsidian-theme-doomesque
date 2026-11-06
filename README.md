# DoomEsque Theme for Obsidian

An authentic, distraction-free **Doom Emacs** inspired theme for Obsidian created by **Jason Gunst**, drawing inspiration from [hlissner/emacs-doom-themes](https://github.com/doomemacs/themes).

Designed for keyboard-centric note-takers, hackers, and Emacs enthusiasts who want an authentic, cohesive editor aesthetic inside Obsidian.

---

## Features

- **Authentic Color Schemes**:
  - **Dark Mode Palettes**:
    - `doom-one` (Default Atom One Dark inspired background `#282c34`, `#51afef` blue, `#c678dd` magenta, `#98be65` green)
    - `doom-vibrant` (Deeper `#242730` canvas with punchy, high-saturation syntax accents)
    - `doom-dracula` (Classic Dracula purple/pink/cyan palette adapted for Doom)
    - `doom-tokyo-night` (Midnight indigo storm palette `#1a1b26`)
    - `doom-gruvbox` (Warm retro medium dark `#282828`)
  - **Light Mode Palettes**:
    - `doom-one-light` (Default cool parchment `#fafafa` base, `#f0f0f0` alt, `#383a42` text, `#4078f2` blue, `#a626a4` magenta)
    - `doom-nord-light` (Arctic ice blue `#e5e9f0` base, `#d8dee9` alt, Polar Night `#2e3440` text, Frost `#3b6ea8` blue, `#4f894c` green)
    - `doom-gruvbox-light` (Warm retro cream parchment `#fbf1c7` base, `#ebdbb2` alt, `#3c3836` text, `#cc241d` red, `#79740e` green)
    - `doom-solarized-light` (Ethan Schoonover's precision light cream `#fdf6e3` base, `#eee8d5` alt, `#586e75` text, `#268bd2` blue)
    - `doom-tomorrow-day` (Crisp modern white `#ffffff` base, `#f2f2f2` alt, `#4d4d4c` text, Tomorrow `#4271ae` blue, `#c82829` red)
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

For keyboard commands, live sliders, and enhanced sticky hover previews, install the companion plugin **[DoomEsque Settings](https://github.com/blursedperf/obsidian-doomesque-settings)** or configure options via the **Style Settings** community plugin.

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
