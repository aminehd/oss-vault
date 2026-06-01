---
repo: "Agent Governance Toolkit"
slug: agent-governance-toolkit
issues_count: 6
updated: 2026-06-01
---

# Agent Governance Toolkit — Contribution Opportunities

No GFI labels but accepts unsolicited docs/tooling PRs. zeel2104 has 4 PRs. Microsoft name.

← [[../agent-governance-toolkit|Back to Agent Governance Toolkit]]

## Open Issues (6)

- **[#2726 [Proposal] Adversarial Test Suite — 52-Scenario Security Assessment](https://github.com/microsoft/agent-governance-toolkit/issues/2726)** `needs-review:MEDIUM`
  opened 2026-06-01 · 2 comments
  > # [Proposal] Adversarial Test Suite — 52-Scenario Security Assessment  ## Summary  We implemented a comprehensive adversarial test suite for AGT, covering 52 scenarios across: - OWASP Agentic AI Top 1

- **[#2713 feat: minimal-PATH sandbox image for command denylist enforcement](https://github.com/microsoft/agent-governance-toolkit/issues/2713)** `enhancement` `good first issue` `agent-hypervisor` `needs-review:MEDIUM`
  opened 2026-05-31 · 1 comments
  > ## Goal  Split out from #2662. Build a minimal-PATH sandbox container image so command denylist enforcement cannot be bypassed via alternate binary locations.  ## Background  #2662 tracks broader sand

- **[#2695 [Feature]: CI: Enforce agent-os governance parity + adapter contract conformance tests in package-matrix test job (remove soft-fail for this scope)](https://github.com/microsoft/agent-governance-toolkit/issues/2695)** `enhancement` `good first issue` `ci/cd` `needs-review:MEDIUM` `accepted`
  opened 2026-05-30 · 4 comments
  > ### Package  agent-os-kernel  ---  ### Problem Statement  The repository already includes adapter/governance conformance assets in `agent-os` (governance parity checks and adapter contract conformance

- **[#2692 RFC: policy distribution and registries with verifiable trust (ADR-0029)](https://github.com/microsoft/agent-governance-toolkit/issues/2692)** `documentation` `enhancement` `pinned` `architecture` `needs-review:MEDIUM` `Priority: MEDIUM`
  opened 2026-05-29 · 2 comments
  > ## Summary  Open RFC discussion for **ADR-0029: Policy distribution and registries with verifiable trust** (PR #2691). Companion to issue #2638 (AGT Studio) and follow-up to ADR-0008 (cross-org poli

- **[#2667 feat: wire GovernedCallable into hypervisor ring enforcement](https://github.com/microsoft/agent-governance-toolkit/issues/2667)** `enhancement` `help wanted` `agent-mesh` `security` `Priority: HIGH` `accepted`
  opened 2026-05-29 · 0 comments
  > ## Summary  `GovernedCallable` (the core governance wrapper in agent-mesh) evaluates policy rules against context fields but has no integration with the hypervisor ring system. An agent's execution 

- **[#2666 feat: integrate hypervisor ring enforcement into sandbox providers](https://github.com/microsoft/agent-governance-toolkit/issues/2666)** `enhancement` `agent-hypervisor` `security` `Priority: HIGH`
  opened 2026-05-29 · 1 comments
  > ## Summary  The `agent-hypervisor` ring enforcement system (`RingEnforcer`, `RingBreachDetector`, `ActionClassifier`) defines resource constraints per execution ring, including `subprocess_allowed`,
