# Claude Finance & Business Skills

## Project Overview
This is a collection of Claude Code skills for professional analysts (Business, Financial, Data, Product, Market Research, Strategy, Risk & Compliance).

## Structure
- `.claude/skills/_shared/` — Shared guidelines and templates referenced by all skills
- `.claude/skills/cross-role/` — Universal skills for all analyst roles
- `.claude/skills/<role>/` — Role-specific skills

## Skill Format
Each skill lives in `.claude/skills/<category>/<skill-name>/SKILL.md` with YAML frontmatter.

## Quality Standards
All skills must follow the guidelines in `_shared/`:
- `quality-guidelines.md` — Pyramid Principle, MECE, actionability
- `anti-hallucination.md` — Source citation, calculation transparency, uncertainty flags
- `output-formats.md` — Consistent Markdown templates

## Conventions
- Skills use `$ARGUMENTS` for user input
- Output is always structured Markdown (tables, headers, sections)
- Every analysis ends with actionable recommendations
- Financial calculations show intermediate steps
- Uncertainty is flagged explicitly with confidence levels
