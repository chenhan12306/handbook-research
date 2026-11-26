# Handbook Research

An Obsidian theme for engineering handbooks and technical notes. It is tuned for long-form reading, lookup-friendly tables, math, figures with captions, and bilingual (Latin and CJK) typography.

**Version:** 1.0.2 · **Minimum Obsidian:** 1.5.0 · **Author:** [Han Chen](https://github.com/chenhan12306) · **License:** MIT

## Overview

**Note body (1.0.1 unchanged):** warm “paper” / “charcoal” palettes, serif body, ~1040 px measure, line-height ~1.8, heading hierarchy, sticky tables, MathJax, caption bars, print rules.

**What’s new in 1.0.2:** a restrained **encyclopedia-style workspace chrome** (sidebars, ribbon, tabs, view header, status bar, command palette) with cooler neutral surfaces and 1px borders — **without** changing the warm reading surface or copying the Wikipedia community theme. Also includes CSS lint cleanups (`!important` / `:has` reductions) with **no intended change** to body typography colors.

Design cues from public wiki-style UIs (flat toolbars, thin borders) were applied in spirit only; **no** Wikipedia CSS, fonts, or logos were used.

## Features

- **Light and dark modes** — body tokens in `body.theme-light` / `body.theme-dark` (teal accent, unchanged)
- **Academic reading surface** — same as release **1.0.1** (headings, tables, math, captions, images)
- **Workspace chrome** — ribbon (~36px), tab bar with accent underline on active tab, muted file tree / outline hovers, lighter scrollbars, flat modals & command palette
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

正文阅读体验与 **1.0.1 发布版一致**（暖纸/暖炭、青绿强调、行宽与表格/公式/图注）。**1.0.2** 主要优化 **Obsidian 程序界面**（侧栏、标签、Ribbon、状态栏等）的克制百科工具栏风格；**不**复制 Wikipedia 主题代码。Style Settings 与 `hb-width-*` / `hb-wide-images` 类名用法不变。社区截图路径仍为 `screenshot.png`。