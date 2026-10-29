# ESAT Physics Notes · 物理备考工具包

> 个人备考整理的 ESAT 物理学习材料，**非 UAT‑UK 官方文档**，仅供学习自用，请勿商用；考试内容与要求请以官方发布的 ESAT Guide 原版文件为最终依据。

两份**单文件静态 HTML** 工具，无需后端、无需安装、无需注册，浏览器直接打开即可使用，完整适配电脑与手机。

## 包含内容

| 文件 | 说明 |
| --- | --- |
| [review-notes.html](./review-notes.html) | **弱项复习讲义 + 考纲自查清单**：按考纲模块逐条讲解，配中文释义、公式与易错提示，可勾选掌握状态，模块进度自动统计。 |
| [flashcards.html](./flashcards.html) | **概念 Flashcards 闪卡**：点击翻转的回忆卡片，正面问题、背面答案，支持按模块筛选、关键词搜索、随机洗牌。 |
| [index.html](./index.html) | 导航首页，作为在线访问入口。 |

## 在线访问（GitHub Pages）

本仓库开启 GitHub Pages 后，可通过以下网址直接在线使用：

```
https://<你的用户名>.github.io/esat-physics-notes/
```

**开启方法**：仓库 `Settings` → `Pages` → Source 选择 `main` 分支、`/ (root)` 目录 → Save，等待 1–2 分钟即可。

> 注意：免费账户的 **Private 私有仓库无法开启 Pages**；如需在线访问，请将仓库设为 Public。

## 本地使用

1. 直接下载本仓库的 HTML 文件；
2. 双击 `index.html`（或任意一个 HTML 文件），用浏览器打开即可；
3. 不联网也能完整运行（页面字体通过 CDN 加载，离线时回退为系统字体，不影响使用）。

## 重要提示

- **学习进度保存在浏览器本地（localStorage）**：自查清单的勾选状态、卡片记录不会上传到任何服务器，GitHub 也不会保存你的进度。
- **清除浏览器缓存、使用无痕模式或更换设备 / 浏览器后，进度会丢失**，需要重新勾选。
- 页面为纯静态文件，不收集任何个人信息。

## 来源说明

- 内容整理参考：UAT‑UK《ESAT Guide – Physics》
- 本仓库为个人学习笔记，不代表官方立场；如发现内容有误，欢迎以 Issue 指出。

## 目录结构

```
esat-physics-notes/
├── index.html          # 导航首页
├── review-notes.html   # 复习讲义 + 自查清单
├── flashcards.html     # 概念闪卡
└── README.md
```
