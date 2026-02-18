# Project 02: Multi-Agent Coordination

## Objective
Implement planner-executor-reviewer orchestration with explicit handoffs.

## Build Requirements
- Agent role contracts documented in code and docs.
- Shared state model with versioning.
- Routing policy with confidence thresholds.
- Failure recovery strategy per handoff.

## Success Checks
- No hidden state mutations.
- Reviewer catches at least one seeded failure in tests.
- Pipeline degrades gracefully under tool outage.
