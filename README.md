# Hi, I'm XiaoShuonb 👋

我是一名专注于 **自建产品系统、实时通信和运营后台** 的独立开发者，喜欢把复杂的业务流程整理成可部署、可观测、可持续迭代的产品。

I build self-hosted product systems with a focus on real-time communication, admin platforms, automation, and reliable delivery.

## What I build

- **Real-time communication**：LiveKit / WebRTC 会议、屏幕共享、弱网策略与跨端客户端。
- **Customer operations**：统一客服工作台、会话与消息流、Outbox、Bridge 和可审计运营。
- **Content & admin platforms**：官网、CMS、会员资源、RBAC、通知和运维控制面。
- **Automation & bots**：Telegram 机器人、多群组运营、菜单、成员登记和业务工作流。
- **Private deployment**：Docker Compose、PostgreSQL、Redis、对象存储、反向代理与可回滚部署。

## Selected projects

| Project | What it is | Stack |
| --- | --- | --- |
| **Meeting** | 小规模屏幕共享会议系统：Web 管理端、LiveKit SFU、Android/iOS 客户端 | Vue 3 · NestJS · LiveKit · WebRTC · Kotlin · Swift |
| **Default Studio** | 官网、内容管理、会员资源与运营后台平台 | Next.js · React · Payload CMS · PostgreSQL |
| **DefaultChat** | 多业务账号客服中台、实时会话、媒体收发与 AI 草稿 | Next.js · Vue · Go · WebSocket · PostgreSQL |
| **DefaultBot** | Telegram 多机器人运营、群组管理、成员登记与财务工作流 | NestJS · Prisma · Telegram Bot API · Redis |
| **LiKaiTech V5** | 私有化控制台、Node.js 服务与 Ubuntu/BaoTa 部署工具集 | Node.js · Express · SQLite · Nginx · FRP |

> 这些项目目前以私有源码为主；公开版、Demo 和可复用组件会在完成脱敏与文档整理后逐步发布。

## Technology

```text
TypeScript / JavaScript   Next.js / React / Vue / Vite
Go                        NestJS / Express / WebSocket
PostgreSQL / Redis        Docker Compose / Caddy / Nginx
LiveKit / WebRTC          Android Kotlin / iOS SwiftUI
```

## Current focus

- 把多端实时通信做得更稳定：采集、编码、QoS、重连和可观测性。
- 把客服与机器人业务做成清晰的领域模型：权限、消息状态、幂等、重试和审计。
- 持续完善私有化交付：健康检查、备份演练、生产 smoke test 与可回滚发布。
- 将成熟的内部能力沉淀为公开 Demo、技术文章和可复用模板。

## Engineering principles

- 先定义数据、权限和 API 契约，再拆分服务。
- 生产配置、密钥、上传文件和运行时数据与源码分离。
- 代码、容器、API、真实设备和外部通道分层验证。
- 让每次发布都能被检查、解释和恢复。

## Contact

- GitHub：[@XiaoShuonb](https://github.com/XiaoShuonb)
- 欢迎通过公开仓库的 Issue / Discussions 交流产品工程、实时通信和私有化部署。

---

*Building useful systems, one reliable release at a time.*
