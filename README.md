# my-skills

Claude Code Skills Marketplace - Personal collection of AI development skills

## Installation

### 1. Add the Marketplace

In Claude Code, run:

```
/plugin marketplace add dennougorilla/my-skills
```

### 2. Install Plugins

Choose which plugins to install:

```
/plugin install domain-extractor@dennougorilla
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
│   └── marketplace.json          # Marketplace configuration
└── plugins/
    └── domain-extractor/
        ├── .claude-plugin/
        │   └── plugin.json        # Plugin configuration
        └── skills/
            └── domain-extractor/
                └── SKILL.md       # Skill documentation
```

## License

MIT
