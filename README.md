<div align="center">

# Hi, I'm Jason Cat 👋

## 🌐 [Explore my personal website →](https://jasonbuildai.github.io/)

<sub>更完整的个人介绍、开源贡献、实战项目和持续更新的学习笔记，都在 <a href="https://jasonbuildai.github.io/">jasonbuildai.github.io</a>。</sub>

<p>
  <a href="https://jasonbuildai.github.io/">Home</a> ·
  <a href="https://jasonbuildai.github.io/open-source.html">Open Source</a> ·
  <a href="https://jasonbuildai.github.io/projects.html">Projects</a> ·
  <a href="https://jasonbuildai.github.io/learning.html">Learning</a>
</p>

<sub><a href="https://jasonbuildai.github.io/">个人主页</a> · <a href="https://jasonbuildai.github.io/open-source.html">开源贡献</a> · <a href="https://jasonbuildai.github.io/projects.html">实战项目</a> · <a href="https://jasonbuildai.github.io/learning.html">学习空间</a></sub>

**Focus: AI Agent Runtime & Execution Safety**

<sub>专注方向：AI Agent 运行时与执行安全 —— 让 Agent 跑得起、跑得稳、跑得安全</sub>

**Recent work** <sub>最近在做</sub>: openclaw streaming throughput · OpenSandbox SDK security · loopx Windows coordination

</div>

---

## 🔭 What I Focus On <sub>专注方向</sub>

| Direction | What I work on |
| :--- | :--- |
| 🧠 **Agent Runtime & Reliability**<br><sub>运行时与可靠性</sub> | Session and goal lifecycle, scheduling, locks and leases, quotas, and streaming stability.<br><sub>会话与目标生命周期、调度、锁与租约、配额和流式稳定性。</sub> |
| 🛡️ **Sandboxing & Execution Security**<br><sub>沙箱与执行安全</sub> | Sandbox lifecycle, egress and ingress policy, secret hygiene, and multi-language SDKs and CLIs.<br><sub>沙箱生命周期、网络出入口策略、密钥卫生，以及多语言 SDK 与 CLI。</sub> |
| 🖥️ **Cross-platform Engineering**<br><sub>跨平台工程</sub> | Reliable agent tooling on Windows and WSL, with strong CI and verification gates.<br><sub>让 Agent 工具在 Windows 与 WSL 上稳定可用，并建立可靠的 CI 与验证门禁。</sub> |

## 📊 By the Numbers <sub>数据速览</sub>

> Rolling 12 months · 近 12 个月（截至 2026-10-31）

| Contributions ¹ | Commits | PRs merged | Issues |
| :---: | :---: | :---: | :---: |
| **3,540** | **2,290** | **158** | **185** |

<sub>¹ Includes private contributions · 含私密贡献；GitHub contribution graph, last 12 months</sub>

## 🚀 Selected Contributions <sub>代表贡献</sub>

| Project | ⭐ | What I did |
| :--- | ---: | :--- |
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | 393K | Fixed streaming re-projection stalls across HTML, JSX, code-block, and list boundaries; contained tool-call text leaks.<br><sub>修复 HTML、JSX、代码块与列表边界的流式重投影卡顿，并收敛工具调用文本泄漏。</sub> |
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | 84.5K | Added native Windows process spawning and PATH resolution; hardened search payloads, large inputs, and symlink tests.<br><sub>实现原生 Windows Agent 启动与 PATH 解析，并增强异常搜索载荷、超大输入与 symlink 测试。</sub> |
| [agentscope-ai/QwenPaw](https://github.com/agentscope-ai/QwenPaw) | 36.5K | Made session-state persistence atomic and aligned channel configuration types with the built-in registry.<br><sub>实现会话状态的原子化持久化，并使通道配置类型与内置注册表保持一致。</sub> |
| [opensandbox-group/OpenSandbox](https://github.com/opensandbox-group/OpenSandbox) | 16.2K | Hardened the Go, JS, Kotlin, and C# SDKs across tenant-key isolation, SSE wake retries, idempotent writes, file-transfer timeouts, and non-UTF-8 CLI output.<br><sub>加固 Go、JS、Kotlin 与 C# SDK，覆盖租户密钥隔离、SSE 唤醒重试、幂等写入、文件传输超时与非 UTF-8 CLI 输出。</sub> |
| [loopx-project/loopx](https://github.com/loopx-project/loopx) | 6.4K | Added Windows machine identity for task leases, interrupted Goal recovery, UTF-8 report artifacts, CI and canary gates, and signed NSIS updates.<br><sub>实现任务租约的 Windows 机器标识、中断 Goal 恢复、UTF-8 报告产物、CI 与 canary 门禁，以及 NSIS 签名更新。</sub> |
| [apache/maka](https://github.com/apache/maka) | 5.9K | Closed secret-redaction gaps for fine-grained GitHub PATs and shared redactors; added bounded Electron install retries in CI.<br><sub>补齐细粒度 GitHub PAT 与共享脱敏器中的密钥脱敏漏洞，并为 CI 中的 Electron 安装增加限时重试。</sub> |
| [the-open-agent/openagent](https://github.com/the-open-agent/openagent) | 5.7K | Added fallback-aware auto chat titles, resilient usage metadata, a Windows GUI (UIA) automation tool, and configuration fixes.<br><sub>实现带回退的聊天标题自动生成、用量元数据容错、Windows GUI（UIA）自动化工具，并修复配置问题。</sub> |
| [FireRedTeam/FireRed-OpenStoryline](https://github.com/FireRedTeam/FireRed-OpenStoryline) | 3.6K | Strengthened session-restore invariants, config-secret redaction, drag-and-drop uploads, typed errors, and retries.<br><sub>强化会话恢复不变量、配置密钥脱敏、拖拽上传、类型化错误与重试机制。</sub> |
| [0xsline/OpenChatCut](https://github.com/0xsline/OpenChatCut) | 2.7K | Isolated Windows verification suites; added Ctrl-chord shortcuts, whisper.cpp token grouping, and local media import.<br><sub>隔离 Windows 验证套件，并实现 Ctrl 组合快捷键、whisper.cpp 分词与本地媒体导入。</sub> |

> … and 15+ more repositories — HiRoute, agentbench, casdoor, langchain-ai/deepagents and others.
> <sub>另外还有 15+ 个仓库的贡献。</sub>

## 🤝 Community & More <sub>社区与日常</sub>

- Member of [@the-open-agent](https://github.com/the-open-agent) and [@effectorHQ](https://github.com/effectorHQ)<br><sub>两个开源组织的成员</sub>
- Long-term goal: keep making AI agents run **fast, steady and safe** in open source<br><sub>长期目标：持续让 AI Agent 在开源世界里跑得稳、跑得安全</sub>
- Off the keyboard: football ⚽, exploring new places 🌍, meeting people with stories ✨<br><sub>代码之外：足球、到处走走、认识有故事的人</sub>
- Always learning — there will always be people better than me, and that's a good thing.<br><sub>永远在学习——总有人比我更强，而这正是好事。</sub>

## 📫 Get in Touch <sub>联系我</sub>

<p align="center">
  <a href="mailto:jasonbuildai@gmail.com"><strong>Email</strong></a> ·
  <a href="https://github.com/JasonBuildAI"><strong>GitHub</strong></a> ·
  <strong>WeChat</strong> <code>HJN522312MOST</code>
</p>

<p align="center"><i>Happy to talk about agents, sandboxes and runtime reliability — or just to say hi.</i><br/>
<i>欢迎交流 AI Agent、沙箱与运行时可靠性——也欢迎单纯打个招呼。如果我的工作对你有帮助，一颗 ⭐ 或一个关注就是最大的鼓励。</i></p>

<p align="center"><strong>🌐 Learn more at <a href="https://jasonbuildai.github.io/">jasonbuildai.github.io</a></strong><br/>
<sub>想了解更多？欢迎访问我的个人网站。</sub></p>
