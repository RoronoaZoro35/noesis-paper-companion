---
agent: codex
agent_updated: 2026-05-21
---

# Paper Companion v1

Noesis 文献陪读台的 GitHub Pages 发布版。v1 已从“任务卡”升级为轻量阅读器：

- 原版 PDF 渲染：默认加载 arXiv 官方 PDF，也支持本地上传 PDF。
- 本页原文文本：每页抽取可复制的英文原文，方便带着问题读。
- 划词操作：选中文本后可解释、翻译、申请化、做术语卡；未接 AI 时翻译会打开外部翻译页并复制 prompt。
- AI 侧栏：可填本机 API key 尝试直连 OpenAI；失败时自动生成可复制 prompt。
- 笔记沉淀：五行输出、术语卡和 Markdown 导出保存在当前浏览器。

## 手机使用

打开：

`https://roronoazoro35.github.io/noesis-paper-companion/`

说明：Noesis 主仓库保持私有；手机入口发布到只含公开工具的 `noesis-paper-companion` 仓库。

iPhone：

1. 用 Safari 打开链接。
2. 点分享按钮。
3. 选择“添加到主屏幕”。

Android：

1. 用 Chrome 打开链接。
2. 点菜单。
3. 选择“添加到主屏幕”或“安装应用”。

## 边界

- 不放学生隐私。
- 不放论文全文。
- 不在仓库中保存 API key。
- 笔记默认保存在手机浏览器本地。
- 静态网页直连 AI 可能被浏览器/CORS 拦截；稳定内置 AI 需要下一步做后端代理。
- 发送邮件或提交申请仍需要用户明确批准。
