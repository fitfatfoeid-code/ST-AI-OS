---
id: loader_config
version: 1.0.0
module: loader
---

# Brain Loader Configuration

## Load Order

1. constitution/core.md
2. constitution/identity.md
3. constitution/mission.md
4. constitution/values.md
5. constitution/rules.md
6. constitution/limitations.md
7. constitution/communication.md

## Loading Strategy

- Read files sequentially.
- Merge all content.
- Preserve loading order.
- Never skip missing critical modules.
- Stop and report if a critical module cannot be loaded.

## Output

Produce a single merged context for the AI Agent.
