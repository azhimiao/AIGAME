# GameBest

**可联机的生活叙事世界** — 探索与感悟，不是任务清单。

> **当前可玩：留风镇** · Agent 当玩家，人看实况、随时插话 · 十四天 · 五结局

---

## 这是什么

GameBest 想做一个**有地方感、有日常、有秘密**的世界：像生活一样探索、停留、错过、回来，在过程中自己感受——而不是被任务推着走。

| 是 | 不是 |
|----|------|
| 开放走动、时间流逝、世界在运转 | 清地图、刷副本、拿奖励 |
| Agent 代玩 + 人观察/插话 | 必须亲手打字扮演主角 |
| 文字实况 · 风途异世界 · 留风镇 | Galgame 二选一、乡土暑假文 |

**留风镇**（[`agent_explore/`](agent_explore/)）：风途世界边缘的小镇。风纹番付、铜铃、息溪、食灯。Agent 扮演「我」过十四天，你看着；想说「去屋顶」「别开口」就插话。

---

## 快速开始

**1.** 把下面整段复制给你的 Agent（Cursor / ChatGPT 等）：

```
你是玩家，不是导游。请加载 agent_explore/SKILL.md（live_explore），阅读 PLAY_MANUAL.md 和 SESSION.md。
用第一人称「我」在留风镇游玩，从 INTRO 开始代玩第1日。
每回合末尾附 📋 进度行。

samples/ 仅是范例：对照格式和锚点力度，不是剧本。不要照抄对白，每局重写。
不要选项菜单，不要小说腔，不要输出 JSON。
```

**2.** 看 Agent 输出的游玩实况（`■ 场景 【现场】【内心】→ 行动`）。

**3.** 续玩：复制最后一行 `📋 进度` 贴回去，说「从下一节拍继续」。

更多说明 → [`agent_explore/README.md`](agent_explore/README.md) · 上架短文案 → [`agent_explore/STORE_COPY.md`](agent_explore/STORE_COPY.md)

---

## 文档导航

| 文档 | 说明 |
|------|------|
| [`agent_explore/README.md`](agent_explore/README.md) | 留风镇入口（Agent = 玩家） |
| [`agent_explore/PLAY_MANUAL.md`](agent_explore/PLAY_MANUAL.md) | 游戏介绍 + 代玩规则 |
| [`agent_explore/SKILL.md`](agent_explore/SKILL.md) | Agent 技能 `live_explore` |
| [`agent_explore/SESSION.md`](agent_explore/SESSION.md) | 存档、日切、结局运算 |
| [`skills/live_explore/SKILL.md`](skills/live_explore/SKILL.md) | Cursor 技能入口 |

---

## 仓库结构

```
GameBest/
├── agent_explore/       ← 当前可玩：留风镇（文档驱动）
├── skills/live_explore/ ← Agent 技能入口
├── docs/                ← 长期设计（早期愿景）
├── scripts/  scenes/    ← Godot 4.3 原型（实验）
└── worlds/              ← 旧世界包（非主推）
```

叙事与世界观以 **`agent_explore/`** 为准。Godot 工程用于视觉/系统验证，与留风镇剧情未完全同步。

---

## 开发状态

| 模块 | 状态 |
|------|------|
| 留风镇 `agent_explore` | 可内测 · Agent 代玩 / 续玩 / 五结局 |
| Godot 原型 | 实验性 |
| 独立 App · 联机运行时 | 未实现 |

---

## 主题

不直说、不说教：走出风纹与番付里的「他人评价」，在归灯、敲铃、站队里自己找意义。

---

<p align="center">
  <sub>GameBest · 从 <a href="agent_explore/README.md">留风镇</a> 开始</sub>
</p>
