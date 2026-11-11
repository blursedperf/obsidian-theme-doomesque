# DoomEsque Theme for Obsidian

An authentic, distraction-free **Doom Emacs** inspired theme for Obsidian, bringing classic Emacs buffer aesthetics, Org-mode typography, and iconic color schemes to your vault.

---

## ✨ Core Features

- **🎨 14 Authentic Color Palettes**:
  - **Dark (8)**: `doom-one` (default), `doom-vibrant`, `doom-dracula`, `doom-tokyo-night`, `doom-gruvbox`, `doom-cyberpunk`, `doom-retro-terminal`, `doom-suit-and-tie`.
  - **Light (6)**: `doom-one-light` (default), `doom-nord-light`, `doom-gruvbox-light`, `doom-solarized-light`, `doom-tomorrow-day`, `doom-suit-and-tie-light`.
- **📜 Org-Mode Typography**:
  - 6-level rainbow heading hierarchy (with optional monochrome blue mode).
  - Optional `TODO` and `DONE` task badges beside checkboxes.
  - `:PROPERTIES:` style frontmatter drawer with violet accent styling.
  - Legal outline numbering (`I.` → `A.` → `1.` → `a.` → `i.`) for nested ordered lists.
- **🔲 Retro Text Cursors & Buffer Aesthetics**:
  - Five distinct cursor styles: Modern Bar, Retro Block, Phosphor Glow, Hollow Box, and Underline.
  - Rainbow indentation guides alternating theme accents per nesting depth.
  - Monospace buffer option for a focused hacker aesthetic.
- **🔍 Unconstrained Hover Previews**:
  - Expanded viewports that eliminate artificial column caps.
  - Contained mouse wheel scrolling and frontmatter properties support.
- **📊 Obsidian Bases & Tables**:
  - Stable, zero-shift table grid layout on click and edit.
  - Uniform cell heights, padding, and vertical alignment.
  - Table density (compact / normal / comfortable), gridline style, and zebra striping options.
- **🔒 100% Offline & Private**:
  - Zero network calls, zero `@import` rules, and no remote telemetry.
  - Uses locally installed system fonts.

---

## ⚙️ Configuration

Customize palettes, spacing, typography, and cursor styles using the companion plugin **[DoomEsque Settings](https://github.com/blursedperf/obsidian-doomesque-settings)**, which adds live sliders, keyboard shortcuts, sticky popover controls, and a fixed 1ch retro block cursor engine.

---

## 📦 Installation

### From Obsidian Community Themes
1. Open **Settings → Appearance → Themes → Manage**.
2. Search for **DoomEsque** and click **Install and use**.

### Manual Installation
Copy [`manifest.json`](./manifest.json) and [`theme.css`](./theme.css) into your vault:

```bash
mkdir -p "/path/to/vault/.obsidian/themes/DoomEsque"
cp manifest.json theme.css "/path/to/vault/.obsidian/themes/DoomEsque/"
```

---

## 🎨 Editing Palettes

Each palette block defines raw Doom colors (`--doom-bg`, `--doom-base0`–`8`, accents). The theme paints with **derived tokens** (`--doom-text-faint`, `--doom-text-muted`, `--doom-hairline`, `--doom-border-subtle`, `--doom-border-strong`, `--doom-stripe`, and readable `--doom-<accent>-text` variants) that are generated to meet contrast targets on every palette.

After changing or adding a palette:

```bash
node scripts/palette-tokens.mjs           # contrast report per palette
node scripts/palette-tokens.mjs --write   # regenerate derived tokens
node scripts/palette-tokens.mjs --check   # what CI runs
```

Raw accents are still used for fills, bars and borders; only text uses the `-text` variants.

---

## 📄 License

[MIT License](./LICENSE) © 2026 blursedperf
