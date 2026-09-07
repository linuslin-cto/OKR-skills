<p align="center">
  <a href="README.md">简体中文</a> ·
  <strong>English</strong>
</p>

# OKR Skills

Multilingual Agent Skill for drafting/reviewing OKRs, Monday commit / Friday celebrate cadence, confidence index, weekly reports, and pitfall checks.

Repo: https://github.com/linuslin-cto/OKR-skills

| Language | Docs | Skill content |
|----------|------|----------------|
| **简体中文 (default)** | [README.md](README.md) | [`zh-CN/`](zh-CN/) |
| English | This page | [`en/`](en/) |

Root [`SKILL.md`](SKILL.md) defaults to **Chinese**; jump to English at [`en/SKILL.md`](en/SKILL.md).

## Install

```bash
npx skills add linuslin-cto/OKR-skills

# or
git clone https://github.com/linuslin-cto/OKR-skills.git ~/.agents/skills/okr-skills
```

## Layout

```
OKR-skills/
├── SKILL.md          # Entry (Chinese-first, link to English)
├── README.md         # Chinese (repo default)
├── README.en.md      # English (this page)
├── zh-CN/            # Default Chinese skill pack
└── en/               # English skill pack
```

## Usage

- “Draft next quarter company OKRs with okr-skills” → Agent loads [`en/`](en/)
- Chinese users: see [README.md](README.md) and [`zh-CN/`](zh-CN/)

## Attribution

Framework synthesis inspired by Christina Wodtke (*Radical Focus* / 《OKR工作法》). Not a book reprint — see [NOTICE.en.md](NOTICE.en.md). Please support the original work.

## License

MIT — [LICENSE](LICENSE).
