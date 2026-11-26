# Handbook Research

An Obsidian theme for engineering handbooks and technical notes. It is tuned for long-form reading, lookup-friendly tables, math, figures with captions, and bilingual (Latin and CJK) typography.

**Version:** 1.0.2 · **Minimum Obsidian:** 1.5.0 · **Author:** [Han Chen](https://github.com/chenhan12306) · **License:** MIT

## Overview

Handbook Research provides warm light (“paper”) and warm dark (“charcoal”) palettes. Body text uses serif fonts; headings and UI use sans-serif fonts. The default reading measure is about 1040 px (adjustable via Style Settings or `cssclasses` width presets).

This repository is prepared for the Obsidian Community Themes directory. Until it is published there, install manually from the latest [GitHub Release](https://github.com/chenhan12306/handbook-research/releases).

## Features

- **Light and dark modes** — full token sets in `body.theme-light` and `body.theme-dark`
- **Heading hierarchy** — slightly tighter type scale; H2 left bar + light section rule; H3 subtle underline for handbook skimming
- **Tables** — default academic three-line tables with sticky headers; optional **Handbook lookup** mode for denser borders and tighter rows
- **Math** — block and inline formulas with minimal chrome and scroll for wide expressions
- **Images and captions** — framed images; caption bar styling for lines starting with a bold figure label; optional `hb-wide-images` class
- **Links, tags, highlights** — dashed internal links, pill tags, gradient highlights
- **Print / PDF** — rules to reduce bad breaks around figures, tables, and headings
- **Style Settings** (requires [Style Settings](https://github.com/mgmeyers/obsidian-style-settings)) — line/image sliders; **Handbook lookup mode** toggle (denser tables; compact info callouts)
- **Optional note classes** — `hb-dense-tables` (per-note compact tables); `> [!hb-infobox]` or `.hb-infobox` for symbol/property summary boxes

Default profile remains **academic long-form reading** (~1040 px measure, serif body, line-height ~1.8). Wikipedia-inspired ideas (clearer scan lines, quieter external links) were applied in spirit only — no third-party theme CSS or fonts were copied.

## Installation

1. Download `theme.css` and `manifest.json` from the [latest release](https://github.com/chenhan12306/handbook-research/releases) whose tag matches `manifest.json` `version` (e.g. `1.0.2` after publish).
2. Create `.obsidian/themes/Handbook Research/` in your vault.
3. Copy both files into that folder.
4. In Obsidian: **Settings → Appearance → Themes → Handbook Research**.

The theme folder name must match `name` in `manifest.json` (`Handbook Research`).

## Screenshots

| File | Description |
|------|-------------|
| **`screenshot.png`** (repository root) | Real Obsidian capture (512×288). Sidebar/top areas were cropped; the body was **privacy-redacted** with pixelation. Colors and layout reflect the theme; redaction obscures typography detail. **Use this path in the community directory form:** `screenshot.png`. |
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

Original theme by Han Chen. Design goals are documented in the header comment of `theme.css`. No third-party theme code is bundled.

---

## 中文说明

面向工程手册与技术笔记的 Obsidian 主题，强调长文阅读、表格查阅与双语排版。浅色「暖纸」/ 深色「暖炭」双模式；衬线正文 + 无衬线标题；粘性表头、图注栏、Style Settings 行宽与图片尺寸等。安装方式与上文 English **Installation** 相同；社区表单截图路径：`screenshot.png`。