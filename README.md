# Agent Orchestration Lab

A dedicated repository for becoming an expert in agent orchestration through deliberate practice, real builds, and rigorous evaluation.

## Mission
Master how to design, run, evaluate, and harden multi-agent systems that solve real workflows reliably.

## Outcomes
By working this repo consistently, you should be able to:
- Design orchestration architectures (single-agent, planner-worker, event-driven, and hierarchical patterns).
- Implement safe and observable agent workflows with clear control boundaries.
- Build eval loops that detect regressions before release.
- Ship a production-ready orchestration project with guardrails and SLOs.

## 12-Week Learning Arc
1. Weeks 1-3: Foundations and control-flow basics.
2. Weeks 4-6: Multi-agent coordination and tool routing.
3. Weeks 7-9: Evals, safety gates, and failure handling.
4. Weeks 10-12: Production orchestration capstone.

## Repository Map
- `docs/`: principles, roadmap, and competency matrix.
- `design/rinshari-ui`: shared UI/UX doctrine and reference guidance (git submodule).
- `projects/`: staged build tracks from fundamentals to production.
- `experiments/`: short hypothesis-driven tests and outcomes.
- `prompts/`: reusable orchestration prompt templates.
- `evaluations/`: scorecards and release gates.
- `journal/`: weekly reflection and skill-gap tracking.

## Submodule Bootstrap
Clone with submodules:
```bash
git clone --recurse-submodules <your-repo-url>
```

If already cloned:
```bash
git submodule update --init --recursive
```

## Weekly Operating Loop
1. Pick one project milestone and one competency gap.
2. Run at least one experiment and log outcomes.
3. Update your scorecard in `evaluations/scorecard.md`.
4. Record wins, blockers, and next actions in `journal/weekly-log-template.md`.

## Definition of Progress
- You can explain architecture tradeoffs before implementation.
- You can reproduce results with tests and evals.
- You can detect and handle common failure modes (hallucination, deadlock, tool misuse, and silent degradation).

## Start Here
1. Read `docs/roadmap.md` and choose your current phase.
2. Fill the initial baseline in `docs/competency-matrix.md`.
3. Start `projects/01-agent-foundations/README.md`.
