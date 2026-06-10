# 周报/日报生成器

一个纯网页的 AI 工作报告生成工具，支持自由输入和结构化填写，免费使用，开箱即用。

## ✨ 功能特性

- 日报/周报双模式，字数自动联动调整
- 自由输入 + 结构化表单两种输入方式
- 免费模式：基础模板生成 + 量化数据缺失提示
- AI 模式：润色优化 + 智能扩写（需 API Key）
- 支持 GPT-4o-mini / DeepSeek-chat
- Markdown 渲染，复制带格式
- 导出 .md 文件
- 本地历史记录（最近 50 条）
- 纯本地运行，数据不上传服务器


## 🚀 快速使用

**方式一：直接下载使用**
下载 `index.html`，用浏览器打开即可，无需安装任何依赖。

**方式二：在线体验**
- 主地址：https://jotarou.com/tools/report
- 备用地址：https://jotaroustar.github.io/report-generator

## 🔑 AI 功能需要 API Key

基础模式完全免费，无需密钥。

AI 润色功能需要填入 API Key，推荐使用 [Jotarou API](https://jotarou.com)：
- 支持 GPT-4o-mini / DeepSeek 等模型
- 支付宝充值，按量付费，无月费
- Base URL：https://jotarou.com

当然也可以填入官方 OpenAI / DeepSeek 的密钥，工具完全兼容。

## 🛠 技术栈

- 纯 HTML + CSS + JavaScript，零依赖
- 调用 OpenAI 兼容接口
- 本地 localStorage 存储历史记录

## 📁 文件结构
