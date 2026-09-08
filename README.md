# Royal Champion — Skill (Progressive Disclosure Edition, English)

Restructured version of `it-project-codename-royalchampion` optimized for token
efficiency on Claude (Code / Claude.ai): a very small parent SKILL.md + 6
per-category reference files, so Claude only reads what is actually relevant.

## Structure

```javascript
royalchampion-skill-en/
├── SKILL.md                 # compact routing file (always loaded)
└── reference/
    ├── technical.md           # Software Architect, Lead, Dev, Integration
    ├── project-management.md  # PM, Scrum Master
    ├── design.md              # UX, UI, Researcher
    ├── testing.md             # QA Manual, QA Automation, Security
    ├── infrastructure.md      # DevOps, SysAdmin, Release Manager
    └── strategy.md            # Product Manager, Product Owner
```

## How to Use on Windows

### Option 1 — Claude Code (recommended)

```powershell
# from your project folder
mkdir .claude\skills\royalchampion
xcopy /E /I "C:\path\to\royalchampion-skill-en" ".claude\skills\royalchampion"
```

Claude Code automatically loads `SKILL.md` and only opens `reference/*.md` when needed.

### Option 2 — Claude.ai (web)

1. Go to Settings -> Capabilities -> Skills (or upload via chat, depending on plan).
2. Upload `SKILL.md` as the main skill.
3. When Claude needs details on a role, paste only the single relevant reference file.

## Token-Saving Principles

- The frontmatter description is kept short but still contains trigger keywords.
- SKILL.md contains a routing table so Claude knows exactly which file to open.
- No duplicated content across files.
