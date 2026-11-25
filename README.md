# Handbook Research

面向工程手册与技术笔记的 Obsidian 主题：强调长文阅读、图表查阅与双语排版。

An Obsidian theme for engineering handbooks and technical notes—tuned for long-form reading, lookup-friendly tables, and bilingual text.

**版本 / Version:** 1.0.0 · **最低 Obsidian / minAppVersion:** 1.5.0 · **作者 / Author:** [Han Chen](https://github.com/chenhan12306) · **许可 / License:** MIT

> 本仓库**尚未**提交 Obsidian 社区主题目录；在通过社区审核前，请使用下方手动安装方式。  
> This repo is **not** listed in the Obsidian Community Themes directory yet. Use manual installation below until you submit and pass review.

## 视觉与功能特性（基于 `theme.css`）

### 亮/暗色模式

- **浅色「暖纸」**：米白背景、墨灰正文、青绿强调色（`--interactive-accent`）。
- **深色「暖炭」**：炭灰背景、浅灰正文、薄荷青强调色。
- 两种模式均在 CSS 中完整定义（`body.theme-light` / `body.theme-dark`）。

### 排版与阅读

- 正文：**衬线体**（Source Serif 4、霞鹜文楷、Noto Serif SC 等回退）；标题与界面：**无衬线体**（Inter、Noto Sans SC 等）。
- 默认正文最大宽度约 **1040 px**（可通过 Style Settings 滑块「正文行宽」或 frontmatter `cssclasses` 调节：`hb-width-narrow` / `normal` / `wide` / `full`）。
- 行高约 **1.8**，段落间距适中；小屏（≤720 px）自动缩小字号与边距。
- 若笔记含 H1，则隐藏重复的内联标题（inline title）。

### 标题层级

- H1：底边强调线；H2：左侧色条；H3/H4：分级字重与颜色；H5/H6：小号大写标签样式。

### 链接、标签与高亮

- 内部链接：虚线下划线，悬停实线；未解析链接单独配色。
- 标签：圆角胶囊样式。
- 高亮（`mark`）：渐变背景；选区使用强调色半透明底。

### 公式与表格

- 块级公式：居中、可横向滚动，无装饰边框。
- 表格：**粘性表头**、斑马纹、悬停行高亮；宽表可横向滚动。

### 图片与图注

- 图片：圆角边框、阴影，默认最大宽度/高度由 Style Settings（「图片最大宽度」「图片最大高度」）控制。
- 图注条：紧跟图片且以 `**图号**` 开头的段落，或 `.hb-caption` / `hb-figure` 结构，显示为居中图注栏。
- 附录宽图：frontmatter `cssclasses: [hb-wide-images]` 可放宽图片宽度。

### 其他

- 引用块、Callout（含 `figure` 类型）样式统一。
- 行内/块代码：等宽字体与边框背景。
- 属性（Properties）区域紧凑卡片样式。
- 侧栏、搜索命中、大纲（Outline）高亮与层级缩进。
- **`@media print`**：打印/PDF 时避免图片、表格、标题分页断裂。
- **`prefers-reduced-motion`**：尊重系统减少动画偏好。

### Style Settings（Obsidian 插件）

主题内嵌 `@settings`（需安装 [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) 插件）可调节：

- 正文行宽（680–1600 px）
- 图片最大宽度（400–1200 px）
- 图片最大高度（30–90 vh）

## 安装 / Installation

### 手动安装（当前推荐）

1. 下载本仓库最新 [Release](https://github.com/chenhan12306/handbook-research/releases) 中的 `theme.css` 与 `manifest.json`（标签须为 `1.0.0`），或克隆仓库。
2. 在库目录下创建文件夹：`.obsidian/themes/Handbook Research/`
3. 将 `theme.css` 与 `manifest.json` 放入该文件夹。
4. 打开 Obsidian → **设置 → 外观 → 主题** → 选择 **Handbook Research**。

> `manifest.json` 中的 `name` 为 `Handbook Research`，主题文件夹名称需与此一致。

### 社区主题商店（待办）

将来若提交至 [community.obsidian.md](https://community.obsidian.md/)，用户可在 Obsidian 内直接浏览安装。提交前请阅读官方说明：[Submit your theme](https://docs.obsidian.md/themes/app-themes/submit-theme)。

仓库需包含：`README.md`、`LICENSE`、`manifest.json`、`theme.css`、根目录 **16:9 截图**（推荐 **512×288**）；并创建与 `manifest.json` 中 `version` **完全一致**的 GitHub Release 标签（如 `1.0.0`，**不要**加 `v` 前缀），附件上传 `manifest.json` 与 `theme.css`。

## 截图 / Screenshots

| 文件 | 说明 |
|------|------|
| `preview/handbook-research-light-512x288.png` | **CSS 结构近似预览**（Headless Chrome 渲染 HTML 样本 + 本主题 CSS），**非** Obsidian 客户端实机截图。 |
| `preview/sample-note-dark.html` | 深色样本 HTML（可自行在 Obsidian 或浏览器中预览）；深色 PNG 未在 CI 环境生成。 |

提交社区商店前，建议在 Obsidian 1.5+ 中用演示库拍摄真实 `screenshot.png`（512×288）并置于仓库根目录。本仓库在获得实机截图前**不**将预览图冒充为商店主图。

## 仓库结构

```
manifest.json   # 主题元数据
theme.css       # 主题样式（自包含，无远程资源引用）
LICENSE         # MIT
README.md       # 本文件
preview/        # 标注清楚的 CSS 预览素材（可选）
```

## 致谢 / Credits

主题由作者 Han Chen 原创，设计目标见 `theme.css` 文件头注释。未捆绑第三方主题代码。