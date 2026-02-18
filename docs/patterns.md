# Orchestration Patterns

## Planner-Worker
Use when tasks can be decomposed into independent steps.
- Strength: scalable and parallelizable.
- Risk: planner quality bottlenecks whole system.
- Guardrail: require planner output schema validation.

## Critic-Refiner
Use when output quality matters more than first-pass speed.
- Strength: catches subtle quality issues.
- Risk: feedback loops can oscillate without convergence rules.
- Guardrail: cap iterations and enforce acceptance criteria.

## Router-Specialist
Use when requests vary across domains or tools.
- Strength: high precision per specialist.
- Risk: poor routing creates silent failure.
- Guardrail: route confidence threshold + fallback path.

## Event-Driven Swarm
Use for long-running workflows with asynchronous triggers.
- Strength: resilient and extensible.
- Risk: coordination complexity and duplicate actions.
- Guardrail: idempotency keys and event versioning.
