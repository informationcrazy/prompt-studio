# ⚡️ PromptStudio Pro

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Gemini](https://img.shields.io/badge/AI-Google%20Gemini%202.0%2F2.5-4285F4) ![Tech](https://img.shields.io/badge/Tech-HTML%20%2B%20Tailwind-38bdf8)

**PromptStudio Pro** 是一个轻量级的、基于浏览器的提示词工程（Prompt Engineering）辅助工具。

它完全运行在客户端（单文件 HTML），直接对接 Google Gemini API。它可以帮助你将简短的想法转化为专业的、结构化的提示词（支持 CoT 思维链、角色扮演等技巧），并立即运行测试效果。

## ✨ 核心功能 (Features)

- **🛠 单文件架构 (Single File)**: 没有复杂的构建过程（No Node.js/NPM），下载 `index.html` 双击即可运行。
- **🚀 支持最新模型**: 完美适配 **Gemini 2.5 Flash/Pro** 及 **Gemini 2.0** 系列。
- **🔄 自动模型同步**: 内置 "Sync Models" 功能，自动从 API 拉取您账号可用的最新模型列表。
- **🧠 智能优化 (AI Optimize)**:
  - 自动分析提示词质量并打分 (0-100%)。
  - 使用高级技巧（Role-Play, Chain of Thought, XML Delimiters）重写提示词。
  - 严格的 JSON 模式输出，确保格式稳定。
- **▶️ 实时预览 (Live Test)**: 一键运行优化后的提示词，即时查看模型生成结果。
- **🎨 现代化 UI**: 基于 Tailwind CSS 的玻璃拟态设计 (Glassmorphism)，响应式布局，支持移动端。
- **🔒 隐私安全**: API Key 仅存储在本地浏览器 `localStorage` 中，直接与 Google 服务器通信，不经过任何第三方后端。

## 📦 快速开始 (Quick Start)

1. **获取代码**: 克隆本仓库或直接下载 `index.html` 文件。
2. **运行**: 在浏览器（Chrome/Edge/Safari）中打开 `index.html`。
3. **配置**:
   - 点击右上角的钥匙图标或输入框。
   - 粘贴您的 [Google Gemini API Key](https://aistudio.google.com/app/apikey)。
4. **使用**:
   - 点击 **"Sync Models"** 获取最新模型列表。
   - 在输入框写入简单的想法（例如：“写一个 Python 贪吃蛇游戏”）。
   - 点击 **"AI Optimize"**。
   - 查看评分和优化后的版本，点击 **"Run Test"** 验证效果。

## 📸 截图 (Screenshots)
![截图](
https://github.com/informationcrazy/prompt-studio/blob/main/Screenshot_2026-01-19-21-53-51-393_org.mozilla.firefox-edit.jpg)

## 🔧 技术栈 (Tech Stack)

- **Core**: 原生 HTML5 / JavaScript (ES6+)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (CDN)
- **Icons**: [Lucide Icons](https://lucide.dev/) (CDN)
- **API**: Google Generative AI API (v1beta)

## ⚠️ 注意事项 (Note)

- 本项目需要科学上网环境（取决于您所在地区对 Google API 的访问情况）。
- 请妥善保管您的 API Key。虽然本工具只在本地存储 Key，但在公共电脑上使用后请务必清除浏览器缓存或点击日志栏的 "Clear" 按钮。

## 🤝 贡献 (Contributing)

欢迎提交 Issue 或 Pull Request！由于是单文件项目，请确保修改后的代码依然保持在一个 HTML 文件中，方便分发。

## 📄 许可证 (License)

MIT License.
