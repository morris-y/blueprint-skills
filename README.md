# Blueprint Skills

Claude Code plugin for trading strategy lifecycle management with postmortem compliance.

## Skills Included

| Skill | Description |
|-------|-------------|
| `blueprint-plan` | Transform strategy ideas into Linear tickets with PM immune screening |
| `blueprint-develop` | TDD-based strategy implementation with PM regression prevention |
| `blueprint-review` | Security, quality, and PM compliance review before merging |
| `blueprint-optimize` | Post-merge iteration: Linear sync, PM creation, CLAUDE.md updates |

## Installation

### Option 1: Create Personal Marketplace (Recommended)

1. Create your own marketplace repo (e.g., `my-claude-marketplace`)
2. Add this plugin to your marketplace's plugin list
3. Install via: `claude plugins add-marketplace <your-marketplace-repo>`

### Option 2: Direct Installation

```bash
# Clone to local plugins directory
git clone https://github.com/morris-y/blueprint-skills.git ~/.claude/plugins/cache/blueprint-local/blueprint-skills/1.0.0

# Then manually add to ~/.claude/plugins/installed_plugins.json
```

## Usage

After installation and restarting Claude Code:

- `/blueprint-plan` - Start planning a new strategy
- `/blueprint-develop` - Begin TDD implementation
- `/blueprint-review` - Run pre-merge review
- `/blueprint-optimize` - Complete iteration cycle

Or use full qualified names:
- `blueprint-skills:blueprint-plan`
- `blueprint-skills:blueprint-develop`
- `blueprint-skills:blueprint-review`
- `blueprint-skills:blueprint-optimize`

## Core Concepts

### Dual-Layer Memory System

```
./postmortem/ = 深度病历库 (Deep Case History)
                → 完整的事故分析、root cause、详细修复
                → 无行数限制

./CLAUDE.md   = 高频手术准则 (High-Frequency Operating Rules)
                → 只有指令和警告，无解释
                → 严格 ≤ 100 行
```

### Workflow

```
blueprint-plan -> blueprint-develop -> blueprint-review -> blueprint-optimize
                       ^                                           |
                       +-------------------------------------------+
```

## Dependencies

These skills integrate with:
- `ralph-loop` - For iterative refinement loops
- `superpowers` - TDD (`test-driven-development`), debugging (`systematic-debugging`), code review (`requesting-code-review`), planning (`writing-plans`, `executing-plans`), verification (`verification-before-completion`), branch management (`finishing-a-development-branch`)
- `code-review` - PR code review (`code-review`)
- `security-guidance` - Security best practices and vulnerability guidance (in `blueprint-review`)
- `frontend-design` - High-quality frontend interfaces (in `blueprint-develop` when frontend-related)
- `code-simplifier` - Code simplification and refactoring (in `blueprint-develop`, `blueprint-review`)
- `context7` - Comprehensive context gathering (throughout all phases)
- `linear` - Ticket management
- `commit-commands` - Git operations (`commit`, `commit-push-pr`)

## License

MIT
