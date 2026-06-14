# 周报/日报生成器

一个纯网页的 AI 工作报告生成工具，支持自由输入和结构化填写，免费使用，开箱即用。

**🔗 在线体验：[jotarou.com/tools/report/](https://jotarou.com/tools/report/)**  
**🔗 GitHub Pages：[jotaroustar.github.io/report-generator](https://jotaroustar.github.io/report-generator)**

---

## ✨ 功能特性

- 日报 / 周报双模式，字数自动联动调整
- 自由输入 + 结构化表单两种输入方式
- 免费模式：基础模板生成 + 量化数据缺失提示
- AI 模式：润色优化 + 智能扩写（需 API Key）
- 支持 GPT-4o-mini / DeepSeek-chat 等模型
- Markdown 渲染，复制带格式
- 导出 .md 文件
- 本地历史记录（最近 50 条）
- 深色 / 浅色模式
- 纯本地运行，数据不上传服务器

---

## 🚀 快速使用

**方式一：直接下载使用**  
下载 `index.html`，用浏览器打开即可，无需安装任何依赖。

**方式二：在线体验**  
- 主地址：https://jotarou.com/tools/report/
- 备用地址：https://jotaroustar.github.io/report-generator

---

## 🔑 API Key 说明

基础模式完全免费，无需密钥。

AI 润色功能需要填入 API Key，推荐使用 [Jotarou API](https://jotarou.com)：
- 支持 GPT-4o-mini / DeepSeek / Claude 等模型
- 支付宝充值，按量付费，无月费
- Base URL：`https://jotarou.com/v1`
- 注册即送 ¥7 试用额度

也可以填入 OpenAI / DeepSeek 官方密钥，接口完全兼容。

---

## 🛠 技术栈

- 纯 HTML + CSS + JavaScript，零依赖，零框架
- 调用 OpenAI 兼容接口（支持任意兼容端点）
- localStorage 本地存储历史记录

---

## 📁 文件结构

```
report-generator/
└── index.html    # 全部代码，单文件交付
```

---

## 🔒 隐私说明

您的工作内容经加密后通过 jotarou.com 单次 API 转发至 AI 模型，系统不留存、不用于训练数据。本地历史记录仅保存在您自己的浏览器中。

---

## 🗂 更多工具

访问 [jotarou.com/tools/](https://jotarou.com/tools/) 查看全部 AI 效率工具。

---

© 2026 jotarou.com · 代码版权所有，禁止直接复制用于商业产品
