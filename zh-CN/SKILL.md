---
name: okr-skills
description: >-
  Applies Christina Wodtke-inspired OKR工作法 (Objectives and Key Results): draft/review
  company·dept·personal OKRs, Monday commit / Friday celebrate cadence, confidence
  index 5/10, OKR weekly reports, cascade alignment, MVP board OKRs, and anti-pitfall
  checks. Use when the user mentions OKR、目标与关键结果、季度目标、信心指数、
  周一盘点、周五胜利会、OKR周报、KR写法, or asks to set/review/coach OKRs.
---

<!-- argument-hint: [起草|评审|周一会|周五会|周报|避坑|ch01–ch06|topic] -->

# OKR工作法（Wodtke / 《OKR工作法》框架）

开源 Agent Skill：结构化提炼可执行的 OKR 方法，非原书全文。出处与版权边界见 [NOTICE.zh-CN.md](../NOTICE.zh-CN.md) / [NOTICE.md](../NOTICE.md)。

**语种：** 中文（`zh-CN/`）。English → [../en/SKILL.md](../en/SKILL.md)。根目录多语种路由 → [../SKILL.md](../SKILL.md)。

## Agent 必做规则

1. **先路由再深读**：按下方「任务路由」打开对应文件；未读章节前，勿编造未记载的规则或数字。
2. **输出要可落地**：给用户 OKR / 周报 / 议程时，用可直接粘贴的中文模板（见 [examples.md](examples.md)）。
3. **先问清层级**：公司 / 部门 / 个人 / 项目(MVP)——层级不同，级联与数量规则不同。
4. **默认挑战难度**：KR 信心锚在 **5/10**；全完成要警惕藏实力；全失败要校准而非放弃。
5. **OKR ≠ 绩效考核**：若用户要把 OKR 分直接挂钩加薪晋级，明确劝阻并给一对一替代方案（→ ch06）。
6. **版权**：勿大段复述原书故事或原文；鼓励用户阅读正版《OKR工作法》/ *Radical Focus*。

---

## 任务路由（按需 Read）

| 用户意图 | 先读 |
|----------|------|
| 起草 / 改写 O 与 KR | [cheatsheet.md](cheatsheet.md) → [examples.md](examples.md) → ch04 |
| 评审已有 OKR（挑错） | cheatsheet「常见坑」→ ch05 场景6 → examples 反例 |
| 第一次在公司推行 | ch05「第一次」+ ch04 五因素 |
| 开季度设定会 / 7 步级联 | ch05 场景1、3 |
| 部门难量化（研发/设计/客服） | ch05 场景2 + patterns「教练式」 |
| 周一会怎么开 | ch04 四象限；examples「周一议程」 |
| 周五胜利会 | ch03、ch04 |
| 写/改 OKR 周报 | ch05 场景5；examples「周报」 |
| MVP / 看板功能优先级 | ch05 场景4 |
| 与绩效/年终考核关系 | ch06 |
| 概念查词 | [glossary.md](glossary.md) |
| 模式库 | [patterns.md](patterns.md) |

章节全文：`chapters/ch01` … `ch06`（Topic 索引见文末）。

---

## 核心决策规则（常驻）

| 规则 | 做法 |
|------|------|
| 聚焦 | 公司级通常 **1 个 O**（多独立业务线才多个）；约 **3–4 个 KR** |
| O | 定性、鼓舞、有时限、本团队可独立完成——**不是**「销售额+30%」这种 KPI 句 |
| KR | 回答「如何知道 O 达成了？」；尽量平衡增长 / 质量 / 收入 |
| 难度 | 季初信心 **5/10**；≤3 标红求助；≥7 标绿并检查是否过易 |
| 节奏 | **周一**谈话式四象限担责 → **周五**胜利会庆祝 → 周报公开；**季中不改** OKR |
| 使命 | 先有短使命再设季 O；无使命的 OKR 易方向混乱 |
| 级联 | 公司 → 部门（如何贡献）→ 个人可选且 **一对一**确认 |
| 首次 | 全公司仅 1 个 OKR，或试点团队，或先做项目级 OKR |

一票否决体检：多目标记不住｜周期≤1月当 OKR｜目标=考核数字｜无/不更信心指数｜周一汇报秀｜设完到季末才看。

---

## 输出形态（默认）

除非用户只要口头建议，否则按场景给出结构化块：

- **起草 OKR**：使命（若缺则先草拟）→ O → KR1–3（各附信心 5/10）→ 非目标清单（刻意不做）→ 下周一第一批任务
- **评审 OKR**：逐条 🔴/🟡/🟢 + 改写建议 + 是否挂钩绩效风险
- **周一会**：四象限填空议程（15–30min）
- **周报**：五段式全文

细节模板 → [examples.md](examples.md)；速查表 → [cheatsheet.md](cheatsheet.md)。

---

## Chapter / Topic 索引

| # | 文件 | 要点 |
|---|------|------|
| ch01 | [chapters/ch01-focus-objectives.md](chapters/ch01-focus-objectives.md) | 使命 vs 策略、O/KR 入门 |
| ch02 | [chapters/ch02-discuss-key-results.md](chapters/ch02-discuss-key-results.md) | 共创、砍非关键、坏消息 |
| ch03 | [chapters/ch03-evaluate-results.md](chapters/ch03-evaluate-results.md) | 胜利会、盘点、藏实力 |
| ch04 | [chapters/ch04-success-factors.md](chapters/ch04-success-factors.md) | 五因素、原则、节奏 |
| ch05 | [chapters/ch05-six-scenarios.md](chapters/ch05-six-scenarios.md) | 六场景、7 步、坑 |
| ch06 | [chapters/ch06-final-advice.md](chapters/ch06-final-advice.md) | 与绩效解耦、清单 |

**Topic → 章**：O/KR 写法 ch01/ch04｜聚焦 ch01/ch04/ch05｜信心指数 ch04/ch05｜周一/周五 ch03/ch04｜周报/坑/MVP ch05｜绩效 ch06｜产品团队 OKR ch04

---

## Scope

框架提炼自沃特克 OKR 实践著作（书中含大量叙事案例）。不替代公司制度与法务。完整叙事与细节请阅读正版书籍；本 skill 只保留可执行结构。详见 [NOTICE.zh-CN.md](../NOTICE.zh-CN.md)。
