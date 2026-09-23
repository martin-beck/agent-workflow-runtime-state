# Agent Workflow Runtime current coordination state

This file is generated. Read `README.md`, then use `tools/handoffctl snapshot`.
Never edit this file directly.

## Open

| Priority | Task | Summary | Next action | Owner |
| --- | --- | --- | --- | --- |
| P1 | [AR-0019](tasks/AR-0019.md): Capability broker and worktree enforcement | Implement capability grants, tool boundaries, isolated worktrees, project bindings, and fail-closed enforcement. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0020](tasks/AR-0020.md): Evidence and oracle bridge implementation | Implement AWQ evidence submission and AWG batched oracle interaction with revision-bound decisions and reusable guidance. | Write and check the versioned specification, then implement only after review. | - |

## Planned

| Priority | Task | Summary | Next action | Owner |
| --- | --- | --- | --- | --- |
| P1 | [AR-0021](tasks/AR-0021.md): Publication and CI implementation | Implement signed-DCO publication, review/merge handoff, CI correlation, and exact-head verification. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0022](tasks/AR-0022.md): Adapter conformance and replay harness | Implement cross-adapter conformance tests, deterministic replay, hostile inputs, and capability mismatch reporting. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0023](tasks/AR-0023.md): End-to-end autonomous development workflow | Integrate planning, execution, quality, oracle discussion, review, merge, recovery, and durable state into one bounded workflow. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0024](tasks/AR-0024.md): Operational CLI, configuration, and onboarding | Provide a documented operator interface for setup, run, observe, resume, diagnose, and safe shutdown. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0025](tasks/AR-0025.md): Security, privacy, and supply-chain assurance | Qualify secret handling, least privilege, dependency provenance, redaction, public evidence, and hostile boundary cases. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0026](tasks/AR-0026.md): Performance and reliability qualification | Measure bounded latency, throughput, recovery, resource use, and failure behavior against explicit specifications. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0027](tasks/AR-0027.md): Fresh-clone release and compatibility lock | Prove reproducible installation, clean-checkout operation, compatibility declarations, release evidence, and rollback. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0028](tasks/AR-0028.md): Umbrella integration and maintenance workflow | Register the runtime in the Agent Workflow family and define its ongoing Coordinator, AWQ, AWG, UI, release, and self-evolution workflow. | Write and check the versioned specification, then implement only after review. | - |

## Done

| Priority | Task | Summary | Next action | Owner |
| --- | --- | --- | --- | --- |
| P0 | [AR-0001](tasks/AR-0001.md): Runtime scope, authority boundaries, and formal specification admission | Establish the runtime charter, authority matrix, and admission rule that every design or conceptual decision is a versioned, machine-checkable specification before implementation. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0002](tasks/AR-0002.md): Versioned normalized session-event protocol | Define the provider-neutral event envelope, ordering, correlation, revision binding, and compatibility rules for agent execution. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0003](tasks/AR-0003.md): Agent adapter capability and lifecycle contract | Define the adapter contract for heterogeneous agent CLIs, including discovery, start, interaction, termination, failure, and capability reporting. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0004](tasks/AR-0004.md): Worktree, project binding, and capability boundary | Define how a runtime session is bound to a project, exact revision, isolated worktree, allowed tools, and authority boundaries. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0005](tasks/AR-0005.md): Supervisor admission, lease, and worker lifecycle | Define admission, leases, heartbeats, cancellation, handoff, stale-worker recovery, and lifecycle state transitions. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0006](tasks/AR-0006.md): Resource, timeout, and process containment contract | Define bounded CPU, memory, disk, network, process-tree, timeout, and cancellation behavior with fail-closed enforcement. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0007](tasks/AR-0007.md): Checkpoint, interruption, and crash recovery | Define durable checkpoints, restart safety, idempotence, replay, interruption, and recovery after host or agent failure. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0008](tasks/AR-0008.md): Privacy-safe event journal and provenance | Define the redacted journal, provenance chain, retention, digesting, and public-safe evidence projection. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0009](tasks/AR-0009.md): AWQ evidence bridge | Define the runtime contract for submitting evidence to Agent Workflow Quality and consuming quality gates without duplicating quality authority. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0010](tasks/AR-0010.md): AWG oracle bridge and discussion admission | Define when uncertainty becomes a batched oracle discussion, how alternatives and confidence are recorded, and how final guidance is bound to revisions. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0011](tasks/AR-0011.md): UI session bridge and safe resume | Define the runtime-facing contract for revision-bound interactive discussions, resumable sessions, safe exit, and validated final events. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0012](tasks/AR-0012.md): Git, branch, and pull-request publication bridge | Define safe branch, commit, review, merge, and publication operations with exact-head and signed-DCO evidence. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0013](tasks/AR-0013.md): CI and external-observation adapter | Define how hosted checks and remote observations are requested, correlated, verified, and distinguished from local qualification. | Write and check the versioned specification, then implement only after review. | - |
| P0 | [AR-0014](tasks/AR-0014.md): Formal runtime models and hostile trace corpus | Define executable models and adversarial traces covering lifecycle, oracle, recovery, publication, and authority invariants. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0015](tasks/AR-0015.md): Codex-compatible reference adapter | Implement a provider adapter against the normalized contract for a Codex-style agent session, with capability discovery and replay fixtures. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0016](tasks/AR-0016.md): OpenCode-compatible adapter | Implement a provider adapter for an OpenCode-style agent session without leaking provider-specific policy into the runtime core. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0017](tasks/AR-0017.md): OpenDesk-compatible adapter | Implement a provider adapter for an OpenDesk-style agent session with explicit unsupported-capability behavior. | Write and check the versioned specification, then implement only after review. | - |
| P1 | [AR-0018](tasks/AR-0018.md): Supervisor implementation | Implement admission, leases, supervision, cancellation, recovery, and lifecycle evidence using the approved formal model. | Write and check the versioned specification, then implement only after review. | - |
