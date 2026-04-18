# Beatly for Claude Code

**A procedurally generated soundtrack, composed live while Claude Code works.**

Not a playlist. Every note is synthesized in real time by a local SuperCollider engine and scored to what Claude Code is doing right now — tool calls, diffs, tests going green, blockers, breakthroughs. The music _is_ the agent's run.

Built from [getbeatly/beatly](https://github.com/getbeatly/beatly).

## Install

```
/plugin marketplace add getbeatly/claude-code
/plugin install beatly@beatly
```

## Requirements

- SuperCollider installed system-wide
- `scsynth` on `PATH`
- `sclang` on `PATH`
