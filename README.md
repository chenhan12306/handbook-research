# Handbook Research

An Obsidian theme for engineering handbooks and technical notes. It is tuned for long-form reading, lookup-friendly tables, math, figures with captions, and bilingual (Latin and CJK) typography.

**Version:** 1.0.2 · **Minimum Obsidian:** 1.5.0 · **Author:** [Han Chen](https://github.com/chenhan12306) · **License:** MIT

## Overview

**Reading surface (1.0.2):** cool **clean paper** in light mode (`#fcfdfe`) and **cool charcoal** in dark (`#181b20`), with a unified **academic handbook blue** accent (`#1d5fa7` light / `#6cb0ff` dark). Typography, ~1040 px measure, line-height ~1.8, heading hierarchy, sticky tables, MathJax, caption bars, and print rules follow the same structure as release **1.0.1** — only the surface and accent palette changed.

**Workspace chrome (1.0.2):** Wikipedia **Vector-inspired** app UI — light blue tab-bar gradient, square active tabs merging into the page, 0px radii on controls, file-tree encyclopedia blues, flat settings/modals. Chrome tokens (`--hb-vector-*`) stay aligned with the cool surfaces above.

Design cues from public wiki-style UIs were applied in spirit only; **no** Wikipedia CSS, fonts, or logos were used.

## Features

- **Light and dark modes** — cool paper/charcoal surfaces, academic blue accents, Vector-style chrome
- **Academic reading layout** — serif body, sans headings/UI; tables, math, captions, images unchanged in structure
- **Workspace chrome** — tab gradient, seamless active tab, muted side dock, 1px borders, square inputs/buttons
- **Style Settings** — line width and image size sliders ([plugin](https://github.com/mgmeyers/obsidian-style-settings))
- **Per-note classes** — `hb-width-narrow|normal|wide|full`, `hb-wide-images`

## Installation

1. Download `theme.css` and `manifest.json` from the [latest release](https://github.com/chenhan12306/handbook-research/releases) whose tag matches `manifest.json` `version` (e.g. **1.0.1** today; **1.0.2** after you publish it).
2. Create `.obsidian/themes/Handbook Research/` in your vault.
3. Copy both files into that folder.
4. **Settings → Appearance → Themes → Handbook Research**.

## Screenshots

| File | Description |
|------|-------------|
| **`screenshot.png`** (repository root) | Real Obsidian capture (512×288), privacy-redacted. Community form path: `screenshot.png`. |
| `preview/*` | CSS/HTML approximations only — not substitutes for `screenshot.png`. |

## Repository layout

```
manifest.json
theme.css
screenshot.png
LICENSE
README.md
preview/
```

## Credits

Original theme by Han Chen. Header comment in `theme.css` describes reading goals. No third-party theme CSS bundled.

---

## 中文说明

**1.0.2** 在保留 **1.0.1 排版结构**（行宽、标题层级、三线表、公式、图注、打印、`hb-width-*` / `hb-wide-images`）的前提下，将正文与界面统一到 **清爽冷白纸 + 沉稳学术蓝**（浅色 `#1d5fa7`，深色 `#6cb0ff`），并与 Vector 风格程序界面（浅蓝顶栏、直角标签、侧栏百科蓝）同色温衔接。左下角仓库栏等次级表面使用 `#f8f9fa` / `#f1f4f8`，避免暖米灰割裂。社区截图路径仍为 `screenshot.png`。