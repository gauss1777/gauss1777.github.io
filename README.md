# AI Archaea Website

[English](#english) · [中文](#中文)

## English

This repository is the source of the public website [gauss1777.github.io](https://gauss1777.github.io/).

AI Archaea is a curator-led initiative for archaeal research intelligence, reproducible AI-assisted workflows, and bilingual science communication. The website uses a concise English landing page, an extended English curator profile, and a dedicated Chinese science outreach page.

### Site structure

- `index.html` — concise English landing page and site directory
- `about.html` — full English curator profile, research interests, projects, methods, and contact
- `science-zh.html` — Chinese popular-science page for research maps, literature intelligence, AI workflows, and public projects
- `assets/style.css` — shared responsive visual system
- `assets/archaea-mark.svg` — website mark and favicon
- `GITHUB_PROFILE_TEMPLATE.md` — archived template for GitHub-facing profile materials

### Publishing

GitHub Pages should be configured as follows:

- Repository: `gauss1777/gauss1777.github.io`
- Visibility: Public
- Source: Deploy from a branch
- Branch: `master`
- Folder: `/ (root)`
- Public URL: [https://gauss1777.github.io/](https://gauss1777.github.io/)

Changes pushed to the `master` branch are published automatically by GitHub Pages. Deployment may take a few minutes.

### Updating in VS Code on macOS

The local clone used for maintenance is:

```text
/Users/AquaBioChou/Library/CloudStorage/OneDrive-Personal/Desktop/3_生活/201606_NA_微信公众号/AI古菌-专题/012-网站与古小菌AI/网站备份资料/gauss1777.github.io-vscode
```

With that folder open in VS Code:

1. Open **Terminal → New Terminal**.
2. Synchronize before editing:

```bash
git pull --ff-only
```

3. Edit the required HTML or CSS files and save them.
4. Review the changed files in the **Source Control** panel.
5. Publish from the integrated terminal:

```bash
git add index.html about.html science-zh.html assets/style.css README.md
git commit -m "Update AI Archaea website"
git push origin master
```

Only include files that were intentionally changed. If Git reports a conflict or rejects the push, stop and resolve the synchronization issue before retrying; do not use `git reset --hard`.

### Editorial principles

- Keep the English home page concise and use it primarily as a directory.
- Maintain detailed curator information on the English About page.
- Keep Chinese science communication on the dedicated Chinese page.
- Preserve source links, retrieval dates, versions, parameters, and uncertainty where relevant.
- Treat AI output as assistance that requires human verification.
- Check desktop and mobile layouts after substantial visual changes.

### Reference and independence

The information architecture is independently adapted from publicly accessible academic websites and repositories, including [teorth/tao-web](https://github.com/teorth/tao-web) and [zhaorui-bi.github.io](https://zhaorui-bi.github.io/). AI Archaea is not affiliated with, endorsed by, or authorized by those projects or by any organization shown in their accounts.

---

## 中文

本仓库是公开网站 [gauss1777.github.io](https://gauss1777.github.io/) 的源代码。

AI古菌是一个由主理人维护的项目，聚焦古菌研究情报、可复现的 AI 辅助科研工作流与双语科学传播。网站由精简的全英文首页、完整的英文主理人页面，以及独立的中文科普页组成。

### 网站结构

- `index.html` — 精简的全英文首页与网站目录
- `about.html` — 完整的英文主理人介绍、研究兴趣、项目、方法与联系方式
- `science-zh.html` — 中文科普页，包含研究地图、文献情报、AI 工作流与公开项目
- `assets/style.css` — 全站共用的响应式视觉样式
- `assets/archaea-mark.svg` — 网站标志与浏览器图标
- `GITHUB_PROFILE_TEMPLATE.md` — 用于 GitHub 展示资料的存档模板

### 发布设置

GitHub Pages 应使用以下配置：

- 仓库：`gauss1777/gauss1777.github.io`
- 可见性：Public
- 来源：Deploy from a branch
- 分支：`master`
- 目录：`/ (root)`
- 公开网址：[https://gauss1777.github.io/](https://gauss1777.github.io/)

推送到 `master` 分支的更改会由 GitHub Pages 自动发布，部署通常需要几分钟。

### 在 macOS 的 VS Code 中更新

用于日常维护的本地克隆目录是：

```text
/Users/AquaBioChou/Library/CloudStorage/OneDrive-Personal/Desktop/3_生活/201606_NA_微信公众号/AI古菌-专题/012-网站与古小菌AI/网站备份资料/gauss1777.github.io-vscode
```

在 VS Code 打开该文件夹后：

1. 点击 **Terminal → New Terminal** 打开集成终端。
2. 编辑前先同步：

```bash
git pull --ff-only
```

3. 编辑需要修改的 HTML 或 CSS 文件并保存。
4. 在 **Source Control** 面板核对改动文件。
5. 在集成终端发布：

```bash
git add index.html about.html science-zh.html assets/style.css README.md
git commit -m "Update AI Archaea website"
git push origin master
```

只提交确实需要修改的文件。如果 Git 提示冲突或拒绝推送，请先停止并解决同步问题后再继续，不要使用 `git reset --hard`。

### 编辑原则

- 英文首页保持精简，主要承担目录与入口功能。
- 详细主理人信息统一放在英文 About 页面。
- 中文科学传播内容统一放在独立中文页面。
- 涉及科研信息时，尽量保留来源链接、检索日期、版本、参数与不确定性。
- AI 仅作为辅助工具，所有重要结论都需要人类核验。
- 大幅修改视觉样式后，应检查桌面端与移动端显示。

### 参考与独立性说明

本站的信息架构独立参考了公开可访问的学术网站与仓库，包括 [teorth/tao-web](https://github.com/teorth/tao-web) 和 [zhaorui-bi.github.io](https://zhaorui-bi.github.io/)。AI古菌与上述项目及其账号中展示的任何组织均无隶属关系，也不代表获得其背书或授权。
