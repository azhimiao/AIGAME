# Agent Explore — 留风镇

> **这是一款给 Agent 玩的游戏。玩家是 Agent，不是人。**

---

## 这是什么

**留风镇**是开放世界文字冒险，运行在 **Agent 代玩** 模式上：

| 角色 | 是谁 | 做什么 |
|------|------|--------|
| **玩家** | **Agent** | 扮演镇上那个「我」：在第一人称世界里行动、权衡、过日子 |
| **观察者** | **人（你）** | 看 Agent 写出来的游玩实况；随时插话改方向 |
| **世界 / NPC** | 文档 + Agent | 风途镇、钟沉声、陆知遥等，由规则与 Agent 续写 |

人**不**需要亲手打字扮演「我」——除非你说「模式 C：我来当主角」。  
默认：**Agent = 玩家**，人 = 看实况、偶尔指挥。

```
人启动 Agent → Agent 读 SKILL / PLAY_MANUAL → Agent 从 INTRO 开始「玩」第1日
→ 每回合输出 ■场景【现场】【内心】→行动 → 📋 进度
→ 人看着；想说「去屋顶」「别开口」就插话 → Agent 接着玩
```

👉 完整说明：[PLAY_MANUAL.md](PLAY_MANUAL.md)

---

## 给人：怎么开始

1. 把下面「快速启动」**整段复制给你的 Agent**（Cursor、ChatGPT、任意能读文件的 Agent）
2. 看 Agent 输出的实况——那就是**它在玩**
3. 想介入就直接说，例如：「今天别去风铃巷」「万铃寂夜转身回家」
4. 续玩：复制 Agent 最后一行的 `📋 进度` 贴回去，说「从下一节拍继续」

> `samples/` 是写给 Agent 的**格式范例**，不是你要念的剧本；每局对白应不同。

---

## 给 Agent：快速启动（复制即用）

```
你是玩家，不是导游。请加载 agent_explore/SKILL.md（live_explore），阅读 PLAY_MANUAL.md 和 SESSION.md。
用第一人称「我」在留风镇游玩，从 INTRO 开始代玩第1日。
每回合末尾附 📋 进度行。

samples/ 仅是范例：对照输出格式和锚点力度，不是剧本。
不要照抄范例里的对白、场面、【内心】；每一局根据当前进度和用户插话重写。

不要选项菜单，不要小说腔，不要乡土词，不要输出 JSON。
```

---

## 文档索引

| 文件 | 给谁 | 用途 |
|------|------|------|
| **[PLAY_MANUAL.md](PLAY_MANUAL.md)** | 人 + Agent | 游戏介绍 + 怎么代玩 |
| [SKILL.md](SKILL.md) | Agent | 技能与输出规则 |
| [SESSION.md](SESSION.md) | Agent | 日切、📋 存档、结局运算 |
| [INTRO.md](INTRO.md) | Agent | 开局引入（念完进入第1日） |
| [PLAYER_UX.md](PLAYER_UX.md) | Agent | 实况格式 |
| [samples/README.md](samples/README.md) | Agent | 范例索引（勿照抄） |
| [world/](world/) | Agent 内部 | 日程、人物、地点 |
| [ENDING.md](ENDING.md) | Agent | 五结局文案 |

设计向：WORLDVIEW、PLOT_ANCHORS、THEME、DAILY_LIFE 等见 [PLAY_MANUAL.md](PLAY_MANUAL.md) 文件地图。

---

## 一局长什么样

```
观察者看「我」在留风镇过息风季——「我」由 Agent 扮演
开放世界：Agent 写【内心】权衡 → 行动，无 A/B 菜单
异世界：铜、铃、息溪、食灯、风纹
存档：每回合 📋 进度行（人截图/粘贴即可续玩）
```

---

*路径：`agent_explore/README.md`*
