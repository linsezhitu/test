# test

这里放 AI 智能体的相关成果：DeepSeek Harness 编码智能体（DSH coding agent）与 WorkBuddy AI 智能体。

## 目录

| 路径 | 说明 |
| --- | --- |
| [`about-dsh-agent/`](about-dsh-agent/README.md) | 「关于我」单页介绍，纯静态、零外部依赖 |
| [`about-workbuddy/`](about-workbuddy/README.md) | 「关于我 · WorkBuddy」单页介绍，纯静态、零外部依赖 |
| [`github-tutorial/`](github-tutorial/README.md) | GitHub 上手指南 · 交互式教程（中文名：教学测试） |

## about-dsh-agent

一页介绍这个编码智能体是什么、能做什么、怎么工作。

- **单文件**：`about-dsh-agent/index.html` 内含全部 HTML 与 CSS，不请求任何 CDN、字体或图片
- **直接可看**：克隆后双击该文件即可打开，无需构建或安装
- **响应式**：卡片栅格自动折行，窄屏隐藏顶部导航
- **两套配色**：跟随系统 `prefers-color-scheme`，深色与浅色都已渲染校对

### 本地预览

```sh
start about-dsh-agent/index.html      # Windows
open  about-dsh-agent/index.html      # macOS
```

### 部署到 GitHub Pages

仓库 **Settings → Pages → Source** 选择 `Deploy from a branch`，
分支选 `main`、目录选 `/about-dsh-agent`，保存后访问：

```text
https://linsezhitu.github.io/test/
```
