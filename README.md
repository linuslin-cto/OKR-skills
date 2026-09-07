<p align="center">
  <strong>简体中文</strong> ·
  <a href="README.en.md">English</a>
</p>

# OKR Skills

面向 Cursor / Claude Code / Copilot 等 Agent 的 **OKR 实操 Skill**：起草与评审目标与关键结果、周一盘点 / 周五胜利会、信心指数、周报与常见坑体检。

仓库：https://github.com/linuslin-cto/OKR-skills

| 语言 | 说明 | Skill 正文 |
|------|------|------------|
| **简体中文（默认）** | 本文 | [`zh-CN/`](zh-CN/) |
| English | [README.en.md](README.en.md) | [`en/`](en/) |

根目录 [`SKILL.md`](SKILL.md) 默认走**中文**；需要英文时跳转 [`en/SKILL.md`](en/SKILL.md)。

## 安装

```bash
npx skills add linuslin-cto/OKR-skills

# 或
git clone https://github.com/linuslin-cto/OKR-skills.git ~/.agents/skills/okr-skills
```

## 目录结构

```
OKR-skills/
├── SKILL.md              # 入口（中文优先，可跳转英文）
├── README.md             # 中文说明（本页）
├── README.en.md          # English
├── NOTICE.md             # 中文版权说明
├── NOTICE.en.md          # English notice
├── LICENSE
├── zh-CN/                # 中文技能包（默认）
│   ├── SKILL.md
│   ├── examples.md
│   ├── cheatsheet.md
│   ├── glossary.md
│   ├── patterns.md
│   └── chapters/
└── en/                   # English skill pack
    └── …
```

## 用法

- 「用 okr-skills 起草下季度公司 OKR」
- 「按 okr-skills 生成周一四象限议程」
- 英文用户见 [README.en.md](README.en.md)；Agent 在英文对话中应加载 [`en/`](en/)

## 出处与版权

方法论提炼自克里斯蒂娜·沃特克（*Radical Focus* / 《OKR工作法》），**非原书全文**。详见 [NOTICE.md](NOTICE.md)。请支持正版。

## 许可

本仓库整理与模板：[LICENSE](LICENSE)（MIT）。
