# DIKWP PilotFactory OS

**DIKWP PilotFactory OS** is an offline, open-source enterprise pilot conversion system for the DIKWP ecosystem. It turns an organization's AI use case portfolio into a DIKWP-aligned pilot opportunity report, paid pilot statement of work, pricing tier recommendation, ROI assumption ledger, partner routing decision, procurement checklist, and official service boundary.

The project is designed as an open-core friendly lead-generation and service-routing layer. The offline core is open source. Official DIKWP registry, signed certification, partner approval, expert-reviewed industry adapter packs, and deployment services remain controlled official value layers.

## What it does

- Scores enterprise AI pilot opportunities by urgency, budget readiness, regulatory pain, data readiness, integration complexity, risk, and DIKWP fit.
- Routes each use case to DIKWP modules such as ProofLedger, IntentGuard, AgentTrace, MemoryLedger, SemanticEnergy, AnswerGraph, AICAP-Gateway, ActiveHealth, LearnPath, SemanticJustice, WorkFuture, QuantLedger, and IntentEconomy.
- Generates a paid pilot statement of work without exposing proprietary delivery playbooks.
- Produces official-service triggers: certification, registry, partner onboarding, audit report, and enterprise adapter needs.
- Creates a Chinese-market-friendly procurement and compliance readiness checklist.

## Quick start

```bash
pip install -e .
pilotfactory analyze examples/sample_enterprise_portfolio.json --policy configs/default_policy.json --out outputs/demo
pilotfactory static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## Boundary

This is not a legal, compliance, investment, medical, or procurement certification tool. It is a pilot scoping and monetization-support system. Official certification, registry signing, legal review, and enterprise deployment require human review and separate authorization.

## Attribution

This project is prepared for the DIKWP / Yucong Duan ecosystem. See `NOTICE` and `CITATION.cff`.
