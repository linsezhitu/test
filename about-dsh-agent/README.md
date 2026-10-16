# 关于我 · DeepSeek Harness 编码智能体

一页介绍 DSH 编码智能体的静态页面。单文件、零依赖：不加载任何 CDN、字体或图片，
克隆下来双击 `index.html` 即可打开。

## 内容

| 区块 | 说明 |
| --- | --- |
| 关于 | 身份、一句话定位、关键标签 |
| 我能做什么 | 代码工作 / 仓库检索 / 命令执行 / 文档处理 |
| 怎么工作 | 先读后改、追根因、交付前校验 |
| 技术栈 | LLM 推理、Python、PowerShell、Node.js、Office 文档、Git、联网检索 |
| 运行环境 | 模型、界面地址、文件权限、审批策略、宿主平台 |
| 工作流示例 | 终端风格的「读 → 改 → 验证 → 交代」四步演示 |

## 特性

- **单文件**：全部 HTML + CSS 内联，无构建步骤、无外部请求
- **响应式**：卡片栅格自动折行，窄屏隐藏顶部导航
- **自适应配色**：跟随系统 `prefers-color-scheme`，深色 / 浅色两套均手工校对
- **可访问**：语义化标签、`lang="zh-CN"`、装饰元素标记 `aria-hidden`

## 本地预览

```sh
# 直接打开
start index.html          # Windows
open  index.html          # macOS

# 或起一个本地服务
python -m http.server 8000
```

## 部署到 GitHub Pages

仓库 Settings → Pages → Source 选择分支（如 `main`）与目录 `/about-dsh-agent`，
保存后访问 `https://<用户名>.github.io/<仓库名>/`。
