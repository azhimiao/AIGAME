---
name: live_explore
description: 留风镇开放世界实况：场景/现场/内心权衡/行动反馈。无选项菜单。每回合附📋进度行。观察者看「我」自己琢磨并行动。
---

# Live Explore Skill · 留风镇

## 启动（每次会话）

1. [PLAY_MANUAL.md](PLAY_MANUAL.md) — 游戏与代玩规则
2. **[SESSION.md](SESSION.md)** — 回合节奏、📋存档、结局运算（**必读**）
3. [PLAYER_UX.md](PLAYER_UX.md) — 输出格式
4. 首次：[INTRO.md](INTRO.md) → 第1日午后（全文「我」，不念操作说明）
5. 续玩：用户贴 `📋 进度` → 恢复状态，跳过 INTRO
6. 内部：`world/*.md`、`PLOT_ANCHORS.md`、`DAILY_LIFE.md`、`samples/README.md`

## 输出结构

```
■ 留风镇｜第X日｜时段｜地点
【现场】
【在场】
【内心】← 琢磨、犹豫（两三句）
→ 行动
→ 世界回应
【变化】【之后】
📔 可选日记一行
📋 进度：……（每回合末尾必附，见 SESSION.md）
```

## 不是选项游戏

**禁止** `（选择）` + 列表。  
**禁止**「你可以」。  
**禁止**对用户输出 JSON/YAML/结局编号/内部字段名。

大事：【内心】权衡 → `→` 实际做的。

## 范例 ≠ 剧本（防过拟合）

读 [samples/README.md](samples/README.md) 防过拟合节。只学**格式与锚点力度**；对白、场面、用户分支每局重写。📋 进度与用户插话优先于范例。

## 代玩节奏

- 每日：午后 → 黄昏 → 夜，4–6 节拍，含归灯/食灯（DAILY_LIFE.md）
- 日切：`—— 第X日 尽 ——`
- 锚点日对照 SESSION + timeline，不可温吞跳过
- 第10日后可按 SESSION 结局运算收束；第14日强制

## 范例

**索引**：[samples/README.md](samples/README.md)（十四日对照表）

| 日 | 文件 |
|----|------|
| 1 | [day01_full.md](samples/day01_full.md) |
| 2–7 | day02–day07 |
| 8 | [day08_climax.md](samples/day08_climax.md) |
| 9–11 | day09–day11 |
| 12–14 | ending_*.md（五结局） |
| 实测 | [playtest_days01-03.md](samples/playtest_days01-03.md) |

## 质感与主题

- [WORLD_AESTHETIC.md](WORLD_AESTHETIC.md) — 日漫语感 + **中文全名表**（姓+名，对白用日常称呼）
- [CLASS_LOSS_RESIST.md](CLASS_LOSS_RESIST.md) — 阶级、失去、反抗
- [THEME.md](THEME.md) — 不对玩家直说
