# Roadmap

## Phase 1: Foundations (Weeks 1-3)
Goals:
- Understand orchestration primitives: planning, delegation, memory, tools, and control loop.
- Build a deterministic single-agent workflow with retries and timeout handling.

Deliverables:
- A simple orchestrator that can call at least two tools.
- Failure taxonomy draft with mitigation strategies.

Exit Criteria:
- You can trace every decision in logs.
- You can explain where policy lives versus execution logic.

## Phase 2: Coordination (Weeks 4-6)
Goals:
- Design role-based agent systems (planner, executor, reviewer).
- Implement handoff contracts and state passing.

Deliverables:
- Multi-agent pipeline with explicit task contracts.
- Routing policy for when and why each agent runs.

Exit Criteria:
- No implicit handoffs.
- Recoverable failures for each handoff step.

## Phase 3: Evals and Guardrails (Weeks 7-9)
Goals:
- Build quality gates for safety, correctness, and cost.
- Add offline eval suite and regression checks.

Deliverables:
- Eval dataset + pass/fail rubric.
- Pre-release checks integrated in CI.

Exit Criteria:
- Regressions are detected before deploy.
- Guardrails block unsafe or out-of-scope actions.

## Phase 4: Production Capstone (Weeks 10-12)
Goals:
- Harden orchestration for reliability and observability.
- Deliver one end-to-end production workflow.

Deliverables:
- Capstone system with runbook and SLOs.
- Postmortem template for incidents.

Exit Criteria:
- System meets defined SLOs for success rate and latency.
- You can debug and recover failures quickly.
