# AI Commands

Quick prompts for ACE + Claude. Type a command in your message to switch modes.

## Install

```bash
npx skills add townie/ai-commands
```

Project install (default):

```bash
npx skills add townie/ai-commands -y
```

Global (all projects):

```bash
npx skills add townie/ai-commands -g -y
```

Claude Code only:

```bash
npx skills add townie/ai-commands -a claude-code -y
```

List without installing:

```bash
npx skills add townie/ai-commands --list
```

Uses the open [skills](https://github.com/vercel-labs/skills) CLI (`npx skills`). Works with Claude Code, Cursor, Codex, OpenCode, and many other agents.

### Manual

Copy `skills/ai-commands/` into your project’s `.claude/skills/` (or agent-equivalent skills dir).

## Commands

### CONTROL
| Command | Effect |
|---------|--------|
| **QUESTIONS FIRST** | Ask useful questions; stop before answering |
| **EXECUTE / JUST DO IT** | Skip questions; do it now (counterpoint still runs) |
| **KEEP SIMPLE** | Brief natural answer; skip extra frameworks |

### ANALYZE
| Command | Effect |
|---------|--------|
| **ASSUMPTION AUDIT** | Expose what must be true for the conclusion to hold |
| **SHOW ME THE OPTIONS** | Broaden options before converging |
| **FIRST PRINCIPLES** | Strip convention and inherited assumptions |

### STRESS TEST
| Command | Effect |
|---------|--------|
| **WHY DOES THIS FAIL?** | Failure modes, weak assumptions, missing risks |
| **COUNCIL** | Contrarian, First Principles, Expansionist, Outsider, Executor |
| **REBUTTAL** | Competitor, internal skeptic, end user |
| **COUNCIL + REBUTTAL** | Both frameworks together |

### VERIFY
| Command | Effect |
|---------|--------|
| **FACT CHECK ONLY** | Verify facts and stop |
| **80/20** | Mostly-good judgment; only high-leverage changes |

## License
MIT
