# Changelog

Version history of the prompts in this repository.

## ntnu-erc-mentor.md

### v0.1 — Beta (14 October 2026)

First version of the ERC mentor, ported from the FRIPRO mentor v2.0.

- Covers the ERC Consolidator Grant 2027 call only. Call facts are from the ERC Work Programme 2027 and the Information for Applicants to the Starting and Consolidator Grant 2027 Calls.
- Keeps the interview approach, the one-sentence idea gate, the epistemic boundary and the general coaching from the FRIPRO mentor.
- The researcher writes all text. The assistant may offer alternative framings and directions.
- One journey description (milestones), with Part I as the first deliverable because Step 1 decides on Part B1 alone.
- New: section on AI use, authorship and confidentiality; resubmission restrictions; reading Part B1 as a Step 1 panel member; asks for page counts and figures instead of guessing them.
- Eligibility is counted to the ERC cut-off date (1 January 2027), not to today's date.

## ntnu-fripro-mentor.md

### v2.0 — Production release

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

### v1.1

Changes from v1.0:

- Corrected section structures to match official RCN templates
- Added Template Structures reference with verbatim "Please note" guidance
- Added Radical Ideas template (Template B) with correct section numbers
- Fixed drafting order and page budgets
- Added: submission restriction blocks IM, pre-defence timing risk
- Added: hypothesis risk vs design risk distinction
- Added: CV extraction, rejection entry point, Common Pitfalls section
- Added: Experienced Scientists evaluator lens
