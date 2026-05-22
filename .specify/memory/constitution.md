<!--
Sync Impact Report
Version change: unknown → 1.0.0
Modified principles:
- [PRINCIPLE_1_NAME] → I. Code Quality & Maintainability
- [PRINCIPLE_2_NAME] → II. Testing Standards
- [PRINCIPLE_3_NAME] → III. User Experience Consistency
- [PRINCIPLE_4_NAME] → IV. Performance & Efficiency
Added sections:
- Additional Constraints → Quality & Delivery Standards
- Development Workflow → Delivery Workflow & Review
Templates requiring updates:
- .specify/templates/plan-template.md ✅ aligned (Constitution Check present)
- .specify/templates/spec-template.md ✅ aligned
- .specify/templates/tasks-template.md ✅ aligned
- .specify/templates/commands/ ⚠ no command templates found
Follow-up TODOs:
- None
-->

# My Project Constitution

## Core Principles

### I. Code Quality & Maintainability
Every code change MUST be clean, readable, and maintainable. Source code is only acceptable when it is supported by consistent naming, explicit intent, modular design, automated linting or static analysis, and an explicit review of architecture or technical debt.

### II. Testing Standards
Every change MUST be covered by automated tests before merge. The team enforces deterministic unit tests, integration tests for cross-component behavior, and regression coverage for defects; tests MUST run in CI and fail fast when behavior or contracts drift.

### III. User Experience Consistency
Every user-facing interaction MUST feel coherent, predictable, and accessible. Interfaces, error messaging, behavior, and styling MUST follow shared usability patterns, with consistent terminology, feedback, and navigation so users do not need to relearn common flows.

### IV. Performance & Efficiency
Every solution MUST meet measurable performance expectations appropriate to its domain. Performance goals are treated as first-class requirements, and teams MUST validate responsiveness, resource use, and scalability through profiling, benchmarks, or budgeted metrics.

## Quality & Delivery Standards
All work MUST comply with the core principles. Quality standards include:
- Code reviews that verify readability, correctness, and maintainability.
- Automated test coverage for new and changed behavior.
- Consistent UX patterns for user flows, errors, and messaging.
- Performance budgets or measurable targets for latency, throughput, and resource usage.
- Documentation for non-obvious behavior, architectural decisions, and user-facing expectations.

## Delivery Workflow & Review
The development workflow is governed by these rules:
- Every pull request MUST include validation against the relevant principles.
- No work merges until tests pass, review feedback is addressed, and performance checks are complete for impacted areas.
- UX consistency checks and accessibility considerations MUST be part of review for user-facing changes.
- New or updated performance requirements MUST be documented alongside the solution and verified before release.

## Governance
This constitution is the authoritative guide for project practices and takes precedence over informal conventions. All changes to the constitution MUST be documented, reviewed, and versioned.
- Amendments that add or remove principles, change governance, or alter mandatory standards require a MAJOR version increment.
- Amendments that introduce new sections, refine existing guidance, or materially expand requirements require at least a MINOR version increment.
- Clarifications, wording improvements, and non-semantic refinements require a PATCH version increment.
- Every amendment MUST update the version and the Last Amended date.
- Every pull request MUST reference this constitution and include a compliance note describing how the change satisfies these principles.

**Version**: 1.0.0 | **Ratified**: 2026-05-21 | **Last Amended**: 2026-05-21
