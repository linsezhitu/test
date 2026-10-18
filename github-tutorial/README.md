# GitHub 上手指南 · 交互式教程

一份零基础友好的 GitHub 入门教程，单文件、零依赖：不加载任何 CDN、字体或图片，
克隆下来双击 `index.html` 即可打开。

## 内容

| 区块 | 说明 |
| --- | --- |
| 认识 Git 与 GitHub | 分清「本地版本工具」和「云端托管网站」 |
| 四个核心概念 | 仓库 / 提交 / 分支 / 远程 |
| 实战演练 | 交互式终端，点「下一步」逐步看完一次完整的 push 流程 |
| 常用命令速查 | init / add / commit / push / pull / clone 等 |
| 网页操作 | 新建仓库、传文件、发 PR、开 Issues、Pages 建站 |
| 小测验 | 4 道选择题，点选即时判对错 |

## 相关页面

| 文件 | 说明 |
| --- | --- |
| [`index.html`](index.html) | GitHub 基础入门（概念、终端演练、命令速查、小测验） |
| [`create-repo.html`](create-repo.html) | 如何新建仓库：六步操作 + 小测验 |
| [`upload-files.html`](upload-files.html) | 如何上传文件：五步操作 + 小测验 |
| [`pull-request.html`](pull-request.html) | 如何发起 Pull Request：六步操作 + 小测验 |
| [`issues.html`](issues.html) | 如何开 Issues：五步操作 + 小测验 |
| [`github-pages.html`](github-pages.html) | 如何启用 GitHub Pages：六步操作 + 网址生成器 + 小测验 |

## 特性

- **交互式**：内置终端模拟器（逐步执行 git 命令）与即时反馈的小测验，全程纯 JS，无外部库
- **单文件**：全部 HTML + CSS + JS 内联，无构建步骤、无外部请求
- **响应式**：卡片栅格自动折行，窄屏隐藏顶部导航
- **自适应配色**：跟随系统 `prefers-color-scheme`，深色 / 浅色两套

## 本地预览

```sh
# 直接打开
start index.html          # Windows
open  index.html          # macOS

# 或起一个本地服务
python -m http.server 8000
```

## 部署到 GitHub Pages

仓库 Settings → Pages → Source 选择分支（如 `main`）与目录 `/github-tutorial`，
保存后访问 `https://<用户名>.github.io/<仓库名>/`。
