# 关于我 · WorkBuddy AI 智能体

一页介绍 WorkBuddy 的静态页面。单文件、零依赖：不加载任何 CDN、字体或图片，
克隆下来双击 `index.html` 即可打开。

## 内容

| 区块 | 说明 |
| --- | --- |
| 关于 | 身份、一句话定位、关键标签 |
| 我能做什么 | 研究与写作 / 数据与分析 / 构建应用 / 多模态生成 / 系统访问 / 专家协作 |
| 三种工作模式 | Agent（你说我做）/ Plan（先想后做）/ Ask（只聊不动手） |
| 一次典型的工作流 | 终端风格的「分析 → 思考 → 执行 → 拿结果 → 迭代 → 呈现」六步演示 |
| 技术栈 | Python、Node.js、Web、云服务、文档处理、Git、联网检索、多模态 |
| 生态与运行环境 | 身份、专家、插件、技能、工作目录、界面 |

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

仓库 Settings → Pages → Source 选择分支（如 `main`）与目录 `/about-workbuddy`，
保存后访问 `https://<用户名>.github.io/<仓库名>/`。
