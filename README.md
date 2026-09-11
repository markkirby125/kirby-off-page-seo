# Off-Page Consensus & Parasite SEO (Kirby Off-Page SEO)

[![Kirby Skills Collection](https://img.shields.io/badge/Kirby_Skills-Collection-blue?style=flat-square&logo=github)](https://github.com/markkirby125/kirby-skills-collection)

You are trying to build off-page authority to rank your primary domain. In the past, it made perfect sense to buy guest posts, blast web2.0 links, and rely solely on your domain's own backlink profile to signal trust to Google.

**In practice, Google's Helpful Content classifiers now demand Multi-Platform Entity Consensus.** If your brand only exists on your own website, Google treats you as a localized anomaly. Furthermore, AI Overviews (AEO) source their answers from high-authority UGC platforms (Reddit, YouTube), not just standard blogs.

If you fail to syndicate your entity across these platforms, you remain invisible to the LLMs powering modern search, losing massive top-of-funnel discovery traffic.

**The Solution:** The `kirby-off-page-seo` skill enforces strict protocols for YouTube transcription SEO, Reddit/Parasite SEO, and AEO Press Release manipulation. It directs your AI agent to syndicate your entity footprint across the web, forcing consensus and hijacking high-authority platforms to funnel traffic back to your core assets.

## 🪄 The Magic Prompt

Copy and paste this directly to your AI (Cursor, Windsurf, Claude Code, Antigravity):

```markdown
@agent Please install the kirby-off-page-seo skill into this workspace.
1. Read the `SKILL.md` file and `references/` directory from this repository: https://github.com/markkirby125/kirby-off-page-seo
2. Identify the correct rules system for our current environment (e.g., `.cursor/rules/` for Cursor, `.windsurfrules` for Windsurf, `.clinerules` for Cline, or `~/.agents/skills/` for Antigravity).
3. Save the contents appropriately. If our environment supports multi-file dispatcher skills, clone the directory structure exactly.
4. Confirm when the installation is complete.
```

## Manual Installation

- **Cursor**: Save `SKILL.md` to `.cursor/rules/kirby-off-page-seo.mdc` and copy `references/`
- **Windsurf**: Save `SKILL.md` to `.windsurfrules` and copy `references/`
- **Antigravity**: Clone this repository directly into `~/.agents/skills/kirby-off-page-seo`

## Tech Stack

- **Format**: Markdown / YAML
- **Compatibility**: Antigravity, Claude Code, Cursor, Windsurf, Cline
