# Handoff

Write a clipboard-ready prompt that another agent or fresh session can pick up cold. Based on Peter Steinberger's [OpenClaw handoff](https://github.com/openclaw/agent-skills/tree/main/skills/handoff).

## Use It For

- Delegating work mid-task to another model or fresh session
- Writing a portable, path-free prompt that survives moving between worktrees and machines
- Framing work for an overnight harness or for a teammate's own agent session

## Install

```bash
git clone https://github.com/cbzehner/skill-handoff.git
cd skill-handoff
./install.sh all
```

Install targets:

- `./install.sh claude` installs to `~/.claude/skills/handoff`
- `./install.sh codex` installs to `~/.codex/skills/handoff`
- `./install.sh agents` installs to `~/.agents/skills/handoff`
- `./install.sh opencode` installs to `~/.config/opencode/skills/handoff`
- `./install.sh all --copy` copies files instead of symlinking
