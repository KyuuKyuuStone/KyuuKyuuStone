# Built by [九川 (KyuuKyuuStone)](https://github.com/KyuuKyuuStone)

**Jiuchuan (九川) / KyuuKyuuStone. AI tools and embedded, one person. TypeScript desktop + C on ESP32. All open source.**
*The stone isn't being cute — its gravity is just stronger.*

一个人在写 AI 工具和嵌入式。TypeScript 写 Windows 桌面软件，C 写 ESP32 上的掌机。都开源。

*One person building AI tools and embedded things. TypeScript for Windows desktop
software, C for a handheld on ESP32. All open source.*

---

## 在做的东西 / What I'm building

### [cadre-heihei](https://github.com/KyuuKyuuStone/cadre-heihei) · TypeScript

Windows 桌面端多智能体协作客户端。你对「主管」AI 说想法，主管把它拆成任务派给
「员工」AI（设计师、前端、后端）；员工各自在独立会话里执行并向主管汇报，主管对
照完成条件验收，再把结论交给你 ——「已证实 / 未决 / 风险」分开报。

内核基于 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)（MIT），
Electron，数据全部留在本机 `~/.dsh`。

`在维护` · `MIT`

*A multi-agent workspace for Windows desktop. You describe an idea to the Lead AI;
the Lead breaks it into tasks and assigns them to crew agents — designer, frontend,
backend. Each crew member works in its own session and reports back; the Lead
verifies against the completion criteria and hands you a verdict with
confirmed / open / risk separated.*

*Built on DeepSeek Harness (MIT), Electron, everything stored locally in `~/.dsh`.*

`Active` · `MIT`

### [monkeymetal-console](https://github.com/KyuuKyuuStone/monkeymetal-console) · C

ESP32-S3 上的开源 2D 黑白掌机，C 语言实现。

`在维护` · `MIT`

*An open-source 2D monochrome handheld on ESP32-S3, written in C.*

`Active` · `MIT`

### [claude-code-heihei](https://github.com/KyuuKyuuStone/claude-code-heihei) · TypeScript

桌面端 Claude Code 工作台，cadre-heihei 的前身。已冻结于 v1.7.9，不再更新。

`已冻结` · `MIT`

*A desktop workbench for Claude Code, the predecessor to cadre-heihei.
Frozen at v1.7.9.*

`Frozen` · `MIT`

---

## 现在在做什么 / Now

主线是 cadre-heihei —— 把「主管 / 员工 / 验收」这套协作做成一个能天天用的桌面工具，
不是做成一个演示。另外在推进 monkeymetal-console 的固件和外壳。

*Main focus is cadre-heihei — turning the lead / crew / verify loop into a desktop
tool you'd actually use every day, not a demo. On the side, pushing firmware and
enclosure work for monkeymetal-console.*

---

## 联系 / Contact

提 Issue 就行，三个项目都在 GitHub 上：[@KyuuKyuuStone](https://github.com/KyuuKyuuStone)
天津 / Tianjin

---

各项目许可独立，均为 MIT。 / Each project is licensed separately, all MIT.
