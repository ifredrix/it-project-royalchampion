# IT Project — Code Name: Royal Champion

**Skill Directory for Native Desktop Application Development** — Progressive Disclosure Edition.

This repository is a **Skill** optimized for Claude (Code / Claude.ai). Unlike a
single monolithic `SKILL.md`, it uses a small parent file + 6 per-category
reference files, so Claude only reads the content that is actually relevant to
the user's request — saving tokens on every skill invocation.

> **Scope:** native desktop applications on Windows, macOS, and Linux
> (WPF, WinForms, WinUI 3, Swift/SwiftUI, Qt, GTK, JavaFX, Avalonia).
> For web/SaaS projects, see the sister repository `it-project-codename-grandwarden`.

## Repository Structure

```javascript
it-project-codename-royalchampion/
├── SKILL.md                 # compact routing file (always loaded first)
└── reference/
    ├── technical.md           # Software Architect, Lead Developer, Desktop App Developer, System & Integration Developer
    ├── project-management.md  # Project Manager, Scrum Master
    ├── design.md              # UX Designer, UI Designer, UX Researcher
    ├── testing.md             # QA Engineer (Manual), QA Automation Engineer, Security Tester
    ├── infrastructure.md      # DevOps Engineer, SysAdmin, Release Manager
    └── strategy.md            # Product Manager, Product Owner
```

17 roles across 6 categories, covering the full SDLC of a native desktop
application: strategy, design, development, testing & security, deployment &
infrastructure, and project management.

## How It Saves Tokens

- The frontmatter `description` is kept short but still contains all trigger keywords.
- `SKILL.md` contains a **routing table** — Claude knows exactly which single
file to open for a given request.
- Detailed role descriptions live in `reference/*.md` and are only read on demand.
- No duplicated content across files.

## How to Use

### Option 1 — Claude Code (recommended)

```powershell
# from your project folder (Windows)
git clone https://github.com/ifredrix/it-project-codename-royalchampion.git
xcopy /E /I "it-project-codename-royalchampion" ".claude\skills\royalchampion"
```

Claude Code automatically loads `SKILL.md` and only opens `reference/*.md`
when needed.

### Option 2 — Claude.ai (web)

1. Go to **Settings → Capabilities → Skills** (or upload via chat, depending on your plan).
2. Upload `SKILL.md` as the skill definition.
3. When Claude needs details on a role, attach only the single relevant file
from `reference/` — not the whole folder.

## Contributing

If you find roles or skills that are less relevant to native desktop
development, or wish to add new technologies, feel free to open an **issue** or
submit a **pull request**.

## License

MIT — see [LICENSE](LICENSE).

## Donate

Like this skill? Support me (Bitcoin): **1HZ2h3yyYULFT4jEGwB5ESAZUhBj7kPUa2**

---

> *"Built for the desktop. Engineered for the native experience."*
