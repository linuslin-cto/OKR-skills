# OKR Skills

Multilingual Agent Skill (**English** + **简体中文**) for drafting/reviewing OKRs, Monday commit / Friday celebrate cadence, confidence index, weekly reports, and pitfall checks.

Repo: https://github.com/linuslin-cto/OKR-skills

| Language | Docs | Skill content |
|----------|------|----------------|
| English | [README.md](README.md) | [`en/`](en/) |
| 简体中文 | [README.zh-CN.md](README.zh-CN.md) | [`zh-CN/`](zh-CN/) |

Root [`SKILL.md`](SKILL.md) is a **language router**. Agents should open `en/SKILL.md` or `zh-CN/SKILL.md` based on the user’s language.

## Install

```bash
npx skills add linuslin-cto/OKR-skills

# or
git clone https://github.com/linuslin-cto/OKR-skills.git ~/.agents/skills/okr-skills
```

## Layout

```
OKR-skills/
├── SKILL.md              # Multilingual router (entry)
├── README.md / README.zh-CN.md
├── NOTICE.md / NOTICE.zh-CN.md
├── LICENSE
├── en/                   # English skill pack
│   ├── SKILL.md
│   ├── examples.md
│   ├── cheatsheet.md
│   ├── glossary.md
│   ├── patterns.md
│   └── chapters/
└── zh-CN/                # Simplified Chinese skill pack
    ├── SKILL.md
    ├── examples.md
    └── …
```

## Usage

- “Draft next quarter company OKRs with okr-skills”
- 「用 okr-skills 评审这份 OKR」
- Agent picks `en/` or `zh-CN/` from your language, then follows that locale’s router.

## Attribution

Framework synthesis inspired by Christina Wodtke (*Radical Focus* / 《OKR工作法》). Not a book reprint — see [NOTICE.md](NOTICE.md). Please support the original work.

## License

MIT for this repository’s compilation and templates — [LICENSE](LICENSE).
