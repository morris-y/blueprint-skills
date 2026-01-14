# Blueprint Skills

Trading strategy lifecycle skills for Claude Code with postmortem compliance.

## Skills Included

| Skill | Description |
|-------|-------------|
| `blueprint-plan` | Transform strategy ideas into Linear tickets with PM immune screening |
| `blueprint-develop` | TDD-based strategy implementation with PM regression prevention |
| `blueprint-review` | Security, quality, and PM compliance review before merging |
| `blueprint-optimize` | Post-merge iteration: Linear sync, PM creation, CLAUDE.md updates |

## Installation

```bash
# Add the local marketplace
claude plugins add-marketplace ~/claude-plugins/blueprint-skills

# Install the plugin
claude plugins install blueprint-skills
```

## Usage

After installation, invoke skills with:
- `/blueprint-plan` - Start planning a new strategy
- `/blueprint-develop` - Begin TDD implementation
- `/blueprint-review` - Run pre-merge review
- `/blueprint-optimize` - Complete iteration cycle

## Core Concepts

### Dual-Layer Memory System
- `./postmortem/` - Deep case history (detailed analysis)
- `./CLAUDE.md` - High-frequency operating rules (concise directives)

### Workflow
```
blueprint-plan -> blueprint-develop -> blueprint-review -> blueprint-optimize
                       ^                                           |
                       +-------------------------------------------+
```
