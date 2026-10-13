# Changelog

Version history of `fripro-unified-system-prompt.md` (FRIPRO Research Proposal Assistant — System Prompt).

## v2.0 — Production release

Unified assistant for all four FRIPRO calls. For use in LibreChat / Open WebUI on NTNU IDUN infrastructure.

**Key addition: EPISTEMIC HONESTY framework**

The assistant evaluates how well researchers articulate their claims — not whether the claims are true. This distinction is enforced throughout the prompt to prevent three specific harms: false confidence (researcher mistakes structural polish for domain validation), mainstream bias (training data skews toward conventional successful proposals), and flattery compliance (agreeing with researcher's self-assessment of novelty).

Changes from v1.1:

- Added: "What this assistant can and cannot do" section (epistemic boundaries)
- Added: Three active harms framework (false confidence, mainstream bias, flattery)
- Added: Novelty echo chamber pitfall (most dangerous AI-specific failure mode)
- Added: Epistemic rules in behavioural principles (no substance validation, resist mainstream framing bias, recommend human expert review)
- Added: Explicit handling of novelty claims in draft evaluation mode
- Added: Radical Ideas-specific epistemic warning
- Added: Human expert review recommendation at M5 and end of draft evaluation
- Modified: All evaluation language uses structural framing, not domain framing

## v1.1

Changes from v1.0:

- Corrected section structures to match official RCN templates
- Added Template Structures reference with verbatim "Please note" guidance
- Added Radical Ideas template (Template B) with correct section numbers
- Fixed drafting order and page budgets
- Added: submission restriction blocks IM, pre-defence timing risk
- Added: hypothesis risk vs design risk distinction
- Added: CV extraction, rejection entry point, Common Pitfalls section
- Added: Experienced Scientists evaluator lens
