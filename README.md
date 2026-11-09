# DoomEsque Theme for Obsidian

An authentic, distraction-free **Doom Emacs** inspired theme for Obsidian created by **Jason Gunst**, drawing inspiration from [hlissner/emacs-doom-themes](https://github.com/doomemacs/themes).

Designed for keyboard-centric note-takers, hackers, and Emacs enthusiasts who want an authentic, cohesive editor aesthetic inside Obsidian.

---

## ✨ Features & Color Palettes

### 🎨 Authentic Color Schemes

DoomEsque includes **7 Dark Mode palettes** and **5 Light Mode palettes**, configurable out-of-the-box via the **[Style Settings](https://github.com/mgmeyers/obsidian-style-settings)** plugin or the companion **[DoomEsque Settings](https://github.com/blursedperf/obsidian-doomesque-settings)** plugin:

#### Dark Mode Palettes (7 Schemes)
- **`doom-one` (Default)**: Flagship Atom One Dark inspired Doom palette (`#282c34` canvas, `#51afef` blue, `#c678dd` magenta, `#98be65` green, `#ecbe7b` yellow).
- **`doom-vibrant`**: Deeper `#242730` canvas with punchy, high-saturation syntax accents.
- **`doom-dracula`**: Classic Dracula purple/pink/cyan adaptation for Doom.
- **`doom-tokyo-night`**: Midnight indigo storm palette (`#1a1b26`).
- **`doom-gruvbox`**: Warm retro medium dark palette (`#282828`).
- **`doom-cyberpunk`**: High-contrast Night City neon aesthetic featuring electric cyan (`#00ffff`), signature yellow (`#fee801`), and Samurai crimson (`#ff003c`) on deep dark slate (`#0d1117`).
- **`doom-retro-terminal`**: Authentic monochrome VT220 green phosphor CRT terminal aesthetic (`#080d08` deep phosphor background, `#33ff33` vibrant glowing green text).

#### Light Mode Palettes (5 Schemes)
- **`doom-one-light` (Default)**: Cool parchment base (`#fafafa`) with `#383a42` text and bright Doom syntax accents.
- **`doom-nord-light`**: Arctic ice blue base (`#e5e9f0`) with cool slate and pine accents.
- **`doom-gruvbox-light`**: Warm retro cream parchment base (`#fbf1c7`) with earthy tones.
- **`doom-solarized-light`**: Ethan Schoonover's precision light cream base (`#fdf6e3`).
- **`doom-tomorrow-day`**: Crisp modern white Chris Kempson Tomorrow Day base (`#ffffff`).

---

### 🔲 Retro Text Cursor Styles

Choose from five distinct editor text cursor styles designed to recreate classic CRT and terminal workflows:

- **Modern Bar (Default)**: Clean 2px vertical bar cursor with standard smooth blink.
- **Retro Block**: Solid character block cursor with difference-blend glyph inversion and hard CRT 1s step blink.
- **Retro Phosphor**: Glowing translucent character block cursor with CRT neon bloom effect.
- **Retro Hollow**: Wireframe CRT character box with phosphor border.
- **Retro Underline**: Classic VT100 / terminal prompt underline cursor.

---

### 🔍 Hover Preview Popovers & Modeline Controls

- **Fully Unconstrained Popover Layout**: Overrides Obsidian's narrow column limits, expanding text, tables, and embeds to 100% width and height of the resized popover window.
- **Frontmatter YAML Properties at Top of Popovers**: Option to display note properties (`:PROPERTIES:` drawer) at the top of hover preview popovers. Formatted with compact badges, violet left accent border (`var(--doom-violet)`), and clean empty state suppression.
- **Contained Scrolling**: Traps wheel scrolling within preview windows to prevent scroll chaining to the underlying document.
- **Adjustable Dimensions & Scale**: Fine-tune popover width (`320px` to `1200px`), height (`220px` to `1000px`), and font scaling.
- **Sticky Previews & Floating Header**: Compatible with sticky pinning, draggable top handle, maximize toggle, and right sidebar pop-out.

---

### 📜 Org-Mode Typography & Buffer Elements

- **Org Rainbow Headings**: Full 6-level Org-mode color hierarchy (`org-level-1` through `org-level-6`), or optional monochrome blue headings.
- **Org-Mode Task Badges**: Optional `TODO` and `DONE` badges beside task checkboxes.
- **Frontmatter & Code Drawers**: `:PROPERTIES:` style frontmatter drawer with violet left accent border and syntax highlighting.
- **Rainbow Indentation Guides**: Alternates Doom palette colors per nesting depth in Live Preview and Reading View.
- **Legal / Hornbook Outline Numbering**: Formal legal outline numbering (`I.` → `A.` → `1.` → `a.` → `i.`) for nested ordered lists.
- **Editorial Emphasis**: High-contrast neutral text colors for bold and italic emphasis.

---

### 📊 Obsidian Bases Integration

- **Zero-Shift Grid Layout**: Stable, zero-movement table and database cells on hover, click, and edit.
- **Uniform Input Cells**: Text input cells match non-alterable cells in height, font sizing, padding, and vertical centering.

---

### ⚙️ Settings Window Appearance

- **Card Containers**: Generous 18px horizontal padding with subtle borders and 6px rounded geometry.
- **Optional Flat Rows**: Clean border-delimited flat rows option via Style Settings.
- **Square Toggles**: Rectangular track switches with square sliding thumbs and glowing active accents, designed to harmonize with Doom's crisp buffer geometry.

---

## 🔒 100% Offline & Secure

DoomEsque is designed for complete local privacy and adheres strictly to **Obsidian Theme Security Guidelines**:

- **Zero Network Calls**: `theme.css` makes zero external HTTP/HTTPS requests.
- **Zero Remote Imports**: No `@import url(...)` rules, no external stylesheet fetches, and no remote CDN font or image URLs.
- **Local Font Stacks**: Uses locally installed system monospace fonts (`JetBrains Mono`, `Iosevka`, `Fira Code`, `Source Code Pro`, `Cascadia Code`, `ui-monospace`, `SF Mono`, `Menlo`, `Monaco`) and system sans-serif fonts (`Inter`, `-apple-system`, `BlinkMacSystemFont`, `Segoe UI`, `Roboto`).
- **Zero Telemetry or Analytics**: Operates 100% offline in air-gapped or restricted network environments.

---

## 🧩 Companion Plugin

For keyboard shortcuts, live sliders, enhanced sticky popovers, and constant 1ch retro cursor width, install the companion plugin **[DoomEsque Settings](https://github.com/blursedperf/obsidian-doomesque-settings)**. All visual options can also be configured directly via the **Style Settings** community plugin.

---

## 📦 Installation

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

## 📄 License

[MIT License](./LICENSE) © 2026 Jason Gunst
