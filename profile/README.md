<div align="center">

# MiniClawAgent

**在 iPhone 上运行一个能自己动手干活的 AI 助手**

原生 iOS · 自带 Shell · 可接任意模型 · 开源（GPLv3）

</div>

---

MiniClaw 不是一个只会聊天的 App。它把桌面 Agent 的那套东西搬到了手机上：
文件读写、Alpine Shell、浏览器自动化、MCP 服务、跨会话记忆、子代理，
以及能让你切到后台还继续跑的任务系统。

模型由你自己接——OpenAI、Anthropic、Gemini、DeepSeek，或任何 OpenAI 兼容端点。

## 仓库

| 仓库 | 说明 |
|---|---|
| [MiniClaw](https://github.com/MiniClawAgent/MiniClaw) | iOS 主项目：Agent 循环、工具系统、聊天渲染、插件体系 |
| MiniClaw Plugins | 官方技能 / 规则 / 工具插件集（筹备中） |
| iSH (arm64) | 内置 Shell 运行时，基于 [iSH](https://github.com/ish-app/ish) 的 arm64 定制版（筹备中） |

## 开始

```bash
git clone https://github.com/MiniClawAgent/MiniClaw.git
cd MiniClaw
open MiniClaw.xcodeproj
```

要求 Xcode 15+、iOS 16+。签名请选择你自己的 Team。

## 链接

- 架构说明：[MiniClaw/docs/ARCHITECTURE.md](https://github.com/MiniClawAgent/MiniClaw/blob/main/docs/ARCHITECTURE.md)
- 术语表：[MiniClaw/docs/MiniClaw术语表.md](https://github.com/MiniClawAgent/MiniClaw/blob/main/docs/MiniClaw%E6%9C%AF%E8%AF%AD%E8%A1%A8.md)
- 许可证：[GPL-3.0](https://github.com/MiniClawAgent/MiniClaw/blob/main/LICENSE)
