# OKR Skills

多语种 Agent Skill（**简体中文** + **English**）：起草/评审 OKR、周一盘点 / 周五胜利会、信心指数、周报与避坑体检。

仓库：https://github.com/linuslin-cto/OKR-skills

| 语言 | 说明文档 | Skill 正文 |
|------|----------|------------|
| 简体中文 | [README.zh-CN.md](README.zh-CN.md) | [`zh-CN/`](zh-CN/) |
| English | [README.md](README.md) | [`en/`](en/) |

根目录 [`SKILL.md`](SKILL.md) 为**语种路由**：Agent 按用户语言再进入 `zh-CN/SKILL.md` 或 `en/SKILL.md`。

## 安装

```bash
npx skills add linuslin-cto/OKR-skills

# 或
git clone https://github.com/linuslin-cto/OKR-skills.git ~/.agents/skills/okr-skills
```

## 目录结构

```
OKR-skills/
├── SKILL.md                 # 多语种路由入口
├── README.md / README.zh-CN.md
├── NOTICE.md / NOTICE.zh-CN.md
├── LICENSE
├── zh-CN/                   # 中文技能包
│   ├── SKILL.md
│   ├── examples.md
│   ├── cheatsheet.md
│   ├── glossary.md
│   ├── patterns.md
│   └── chapters/
└── en/                      # 英文技能包
    └── …
```

## 用法

- 「用 okr-skills 起草下季度公司 OKR」
- “Review these OKRs with okr-skills”
- Agent 按你的语言选择 `zh-CN/` 或 `en/`，再按该语种内路由加载模板与章节。

## 出处与版权

方法论提炼自克里斯蒂娜·沃特克（*Radical Focus* / 《OKR工作法》），**非原书全文**。详见 [NOTICE.zh-CN.md](NOTICE.zh-CN.md)。请支持正版。

## 许可

本仓库整理与模板： [LICENSE](LICENSE)（MIT）。
