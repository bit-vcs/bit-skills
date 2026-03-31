# bit-skills

Claude Code plugin marketplace for [bit VCS](https://github.com/bit-vcs/bit).

## Install

```bash
claude plugin marketplace add bit-vcs/bit-skills
claude plugin install bit-skills@bit-skills
```

## Available Skills

| Skill | Description |
|-------|-------------|
| **start-work** | Session coordination with bit issue — declare scope, detect file overlaps, manage parallel work |
| **relay-sync** | Synchronize issues and PRs across repositories via relay server |
| **auto-review** | Automated PR code review triggered by relay events |
| **fix-ci** | Investigate and fix CI failures triggered by relay events |
| **triage-issue** | Analyze and triage new issues triggered by relay events |
| **relay-respond** | Push results back to relay rooms after task completion |
