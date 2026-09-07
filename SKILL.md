---
name: okr-skills
description: >-
  Multilingual OKR Agent Skill (EN + zh-CN) inspired by Christina Wodtke / OKR工作法:
  draft and review company·dept·personal OKRs, Monday commit / Friday celebrate,
  confidence index 5/10, weekly reports, cascade, MVP OKRs, anti-pitfalls.
  Use when the user mentions OKR, Objectives and Key Results, confidence index,
  weekly OKR report, 目标与关键结果, 信心指数, 周一盘点, 周五胜利会, or OKR周报.
---

<!-- argument-hint: [en|zh|draft|review|monday|friday|report|pitfalls|ch01–ch06] -->

# OKR Skills (Multilingual)

Open-source Agent Skill for executable OKR practice. Not a reprint of the book.
Attribution: [NOTICE.md](NOTICE.md) · [NOTICE.zh-CN.md](NOTICE.zh-CN.md)

## Language routing (do this first)

| User language / cue | Load from |
|---------------------|-----------|
| Chinese, or terms like OKR工作法 / 关键结果 / 信心指数 / 周报 | **[zh-CN/SKILL.md](zh-CN/SKILL.md)** then that locale’s files |
| English, or terms like key results / confidence index / Monday commit | **[en/SKILL.md](en/SKILL.md)** then that locale’s files |
| Mixed / unclear | Ask once: `EN or 中文?` — default **zh-CN** if the user has been writing Chinese |

After choosing a locale, **follow that locale’s SKILL.md** for task routing, templates, and chapters. Do not mix paths across locales in one answer unless the user asks for bilingual output.

### Locale map

| Locale | Entry | Templates | Chapters |
|--------|-------|-----------|----------|
| 中文 | [zh-CN/SKILL.md](zh-CN/SKILL.md) | [zh-CN/examples.md](zh-CN/examples.md) | [zh-CN/chapters/](zh-CN/chapters/) |
| English | [en/SKILL.md](en/SKILL.md) | [en/examples.md](en/examples.md) | [en/chapters/](en/chapters/) |

Docs: [README.md](README.md) · [README.zh-CN.md](README.zh-CN.md)

## Shared non-negotiables (any language)

1. Progressive disclosure: read the routed file before inventing rules.
2. Ship paste-ready OKR / agenda / report templates in the **user’s language**.
3. Clarify level: company / dept / personal / MVP.
4. Default KR confidence **5/10**; all-hit → check sandbagging; all-miss → recalibrate, don’t quit.
5. OKR ≠ performance appraisal scoring.
6. No long verbatim book narrative; point readers to *Radical Focus* / 《OKR工作法》.
