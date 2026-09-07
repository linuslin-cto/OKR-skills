# OKR Skills

面向 Cursor / Claude Code / Copilot 等 Agent 的 **OKR 实操 Skill**：起草与评审目标与关键结果、周一盘点 / 周五胜利会、信心指数、周报与常见坑体检。

仓库：https://github.com/linuslin-cto/OKR-skills

## 安装

任选其一：

```bash
# 跨 Agent skills CLI
npx skills add linuslin-cto/OKR-skills

# 或克隆到个人 skills 目录
git clone https://github.com/linuslin-cto/OKR-skills.git ~/.agents/skills/okr-skills
# Claude Code: ~/.claude/skills/okr-skills
# Copilot CLI: ~/.copilot/skills/okr-skills
```

项目内安装：

```bash
git clone https://github.com/linuslin-cto/OKR-skills.git .agents/skills/okr-skills
```

## 目录结构

```
OKR-skills/
├── SKILL.md           # 入口：路由、决策规则、Agent 行为
├── examples.md        # 可粘贴模板（OKR / 周一会 / 周报 / MVP）
├── cheatsheet.md      # 决策表与避坑体检
├── patterns.md        # 可复用模式
├── glossary.md        # 术语
└── chapters/          # 按需加载的分章精炼
    ├── ch01-…md
    └── …
```

## 用法示例

在 Agent 对话中：

- 「用 okr-skills 帮我起草下季度公司 OKR」
- 「按 okr-skills 评审这份 OKR」
- 「生成周一四象限议程」
- 「okr-skills ch05」查看六大场景

## 方法论来源与版权

本仓库是对克里斯蒂娜·沃特克（Christina Wodtke）所著、明道团队翻译的《OKR工作法》中 **可操作框架的结构化提炼**，供 Agent 按需加载；**不是原书全文或故事复述**。

- 请支持作者与正版：[购书 / 了解原著](https://book.douban.com/subject/26829014/)（豆瓣条目供参考）
- 英文原著常见书名：*Radical Focus*（Christina Wodtke）
- 详见 [NOTICE.md](NOTICE.md)

生成链路参考开源工具 [book-to-skill](https://github.com/virgiliojr94/book-to-skill)，本仓库为独立维护的 skill 成品。

## 许可

- 本仓库原创整理与模板文件：见 [LICENSE](LICENSE)（MIT）
- 原书版权归原作者、译者与出版社所有；本项目不主张对原书文本的权利

## 贡献

欢迎 PR：补充行业示例、修正笔误、改进 Agent 路由。请勿提交受版权保护的大段原文。
