# bit-skills

Claude Code plugin marketplace for [bit VCS](https://github.com/bit-vcs/bit).

## Install

```bash
claude plugin marketplace add bit-vcs/bit-skills
claude plugin install bit-skills@bit-skills
```

## Available Skills

### Core (no relay required)

| Skill | Description |
|-------|-------------|
| **bit-issue** | Git-native task management — create, track, search, sub-issues |
| **start-work** | Session coordination — declare scope, detect file overlaps, manage parallel work |

### Automation

| Skill | Description |
|-------|-------------|
| **auto-review** | Structured PR code review |
| **fix-ci** | Investigate and fix CI failures |
| **triage-issue** | Analyze and triage issues |

### Relay (optional, for cross-machine sync)

| Skill | Description |
|-------|-------------|
| **relay-sync** | Synchronize issues/PRs across repositories via relay server |
| **relay-respond** | Push results back to relay rooms |
