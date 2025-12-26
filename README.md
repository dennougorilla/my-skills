# my-skills

Personal collection of AI development skills for Claude Code.

## Installation

In Claude Code, run:

```
/install-skill dennougorilla/my-skills
```

## Available Skills

### domain-extractor

Extract technology-free domain models from codebase. Produces pure business-language specifications that any stakeholder can understand.

**Use for:**
- Understanding legacy code
- Documenting business logic
- Domain modeling
- Business requirements extraction
- Explaining codebase to non-technical stakeholders

**Activation phrases:**
- "What does this codebase do?"
- "Extract the business logic"
- "Document this for stakeholders"

## Structure

```
my-skills/
├── .claude-plugin/
│   └── marketplace.json    # Plugin configuration
├── skills/
│   └── domain-extractor/
│       └── SKILL.md        # Skill definition
├── README.md
└── LICENSE
```

## License

MIT
