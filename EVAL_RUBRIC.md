# bit-issue Skill Evaluation Rubric

## Scoring (each 1-5)

### 1. Reproducibility (再現性)
Can every documented command be executed successfully?
- 5: All commands pass, no errors
- 4: 1 minor issue (cosmetic/output format)
- 3: 1-2 commands behave differently than documented
- 2: 3+ commands behave differently
- 1: Core commands fail

### 2. Accuracy (正確性)
Does the documentation match actual CLI behavior?
- 5: Zero inaccuracies found
- 4: 1 minor inaccuracy (edge case)
- 3: 1-2 meaningful inaccuracies
- 2: 3+ inaccuracies or 1 major (core workflow wrong)
- 1: Fundamentally misleading

### 3. Clarity (明瞭さ)
Is each section unambiguous? Could an agent follow it without guessing?
- 5: Every section is precise, no room for misinterpretation
- 4: 1 section could be clearer
- 3: 2-3 sections need clarification
- 2: Multiple ambiguous sections
- 1: Confusing throughout

### 4. Completeness (網羅性)
Are all useful commands and flags documented?
- 5: All practical commands covered, nothing missing for typical workflows
- 4: 1 useful command/flag missing
- 3: 2-3 useful things missing
- 2: Major workflow gaps
- 1: Only basics covered

### 5. Agent Usability (エージェント実用性)
Can an AI agent use this skill to autonomously manage issues?
- 5: Agent can complete any issue management task from docs alone
- 4: Agent needs 1 workaround not in docs
- 3: Agent gets stuck on 1-2 common tasks
- 2: Agent frequently needs to guess or experiment
- 1: Docs insufficient for autonomous use

## Target: All dimensions >= 4, average >= 4.5
