# Derrick Xu

Senior Java Backend Engineer / Software Architect based in Edmonton, Alberta.

19 years building backend, payment, financial, and distributed systems. Since 2025 I have been working on a practical problem: how one engineer can lead several AI coding agents on long-running systems without losing control of scope, quality, or release decisions.

## Public Work

- [In-House Payment Platform](https://github.com/Derrickxxm/inhouse-payment-platform)  
  Java 21 / Spring Boot 3 clean-room rebuild, on synthetic data, of the kind of in-house payment platform I led in 2016–2018: YAML-only channel onboarding, four service tiers, failover, idempotent debits, crash recovery without double debits, and daily reconciliation. One command runs eight end-to-end scenarios; 181 Java tests in CI. Built by AI agents under a test-first, review-gated process.

- [Evidence-Gated AI Delivery](https://github.com/Derrickxxm/evidence-gated-ai-delivery)  
  Reference implementation of evidence-gated, owner-signed delivery for AI coding agents: task cards with scope budgets, red tests first, self-hashing evidence receipts, a fail-closed merge gate, and owner sign-off bound to the exact commit. 205 tests and 15 scripted attacks, synthetic data only.

- [Multi-Agent Delivery Playbook](https://github.com/Derrickxxm/multi-agent-delivery-playbook)  
  Runnable synthetic demo: an architect agent commits a scope card and red tests, an executor implements within a fixed budget, and a deterministic gate allows a merge only when review, CI, and the owner's sign-off reference the exact commit. One command replays the happy path and seven blocked attacks; 33 tests.

## How I Work With AI Agents

- Separated roles: an architect agent designs, writes red tests, and reviews; executor agents implement only within the card's scope and may not edit tests.
- Evidence over chat approval: merges need review records, CI, and a signature on the exact commit.
- Failures are recorded in an append-only ledger and turned into regression tests or stricter gates.
- Hard decisions go to a multi-model review with anonymized cross-review and a designated dissenter.

## Links

- LinkedIn: https://www.linkedin.com/in/derrick-xu84
- Site: https://derrickxxm.github.io
