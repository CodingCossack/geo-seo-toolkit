# geo-seo-toolkit

Diagnose and verify technical SEO and AI-search visibility for real sites.
Start with [SKILL.md](SKILL.md), which routes to references for public delivery,
content, dynamic pages, crawler controls and measurement.

## Install

```bash
npx skills add CodingCossack/geo-seo-toolkit -g --agent claude-code codex -y
```

Or link a local checkout into the relevant skills directory:

```bash
ln -s /absolute/path/to/geo-seo-toolkit ~/.codex/skills/geo-seo-toolkit
ln -s /absolute/path/to/geo-seo-toolkit ~/.claude/skills/geo-seo-toolkit
```

Invoke it by name when automatic selection would be ambiguous:

```text
Use $geo-seo-toolkit to diagnose why this URL class lost search visibility.
```
