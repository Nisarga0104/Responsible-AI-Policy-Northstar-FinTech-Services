# Benchmarking Notes — Responsible AI Policy
Date: 2026-09-13

Purpose: check Northstar's policy structure and principle set against real, currently published
corporate responsible-AI frameworks, so the document reads as informed by real practice rather
than as a generic values statement.

## Search 1 — "Microsoft Responsible AI Standard structure principles 2024"
Result: Microsoft's Responsible AI Standard v2 (public version released 21 June 2022, still
current) is built on **six principles**: Fairness, Reliability and Safety, Privacy and Security,
Inclusiveness, Transparency, and Accountability — with Transparency and Accountability treated as
foundational principles that support the other four. Each principle is broken into goals, and each
goal into specific, checkable requirements — not left as an abstract value. Microsoft also uses
risk tiers ("Sensitive Use," "Restricted Use") that gate which systems need Responsible AI Committee
review before shipping, structurally similar to the four-tier risk classification in Northstar's
Section 5.

## Search 2 — "Google AI Principles 2026 official list responsible AI"
Result: Important nuance — Google's public framework has changed structure over time. The
original 2018 AI Principles (7 objectives + 4 "will not pursue" commitments) are still widely
cited in older secondary sources, but Google's current (2026) public framing has consolidated
into **three broader pillars**: Bold innovation, Responsible development and deployment, and
Collaborative progress — with the operational detail (fairness, safety, privacy, human oversight)
now living underneath "Responsible development and deployment" rather than as separate top-level
principles. **Action for the draft:** if Google is ever named as a benchmark in Northstar's policy
or in your portfolio README, cite the current three-pillar structure, not the outdated 2018
seven-principle list many blogs still repeat uncritically.

## Search 3 — "IBM AI Ethics principles pillars trust transparency 2026"
Result: IBM's framework (in place since 2018, still current) has two layers: **three Principles
for Trust and Transparency** (AI augments human intelligence rather than replacing it; data and
insights belong to their creator; AI must be transparent and explainable) operationalized through
**five Pillars of Trust** (Explainability, Fairness, Robustness, Transparency, Privacy), enforced
by a standing AI Ethics Board that reviews actual use cases — not just a published document.

## What this means for Northstar's policy
1. **Northstar's 11-principle list (Fairness, Accountability, Transparency, Explainability,
   Privacy, Security, Safety, Human Oversight, Robustness, Contestability, Accessibility) is more
   comprehensive than any single real company's public list** — it combines Microsoft's six,
   IBM's five pillars, and adds Contestability and Accessibility, which are more aligned with
   OECD/EU AI Act-style principles than with typical US big-tech lists. This isn't wrong — a
   regulated Indian fintech genuinely has obligations (contestability for adverse credit
   decisions, accessibility for customer-facing channels) that a general-purpose tech company's
   policy doesn't need to cover. But it's worth being explicit about *why* Northstar's list is
   longer, rather than leaving it looking like an uncurated combination of everything.
2. **Real policies compress principles under fewer top-level headings with tiered detail
   underneath**, rather than listing 11 principles flat at the same level (Microsoft: 6 headings,
   2 are explicitly "foundational" umbrellas for the rest; IBM: 3 principles, 5 pillars
   underneath). Northstar's flat 11-item list is not incorrect, but grouping (e.g., Transparency
   + Explainability + Contestability under one "Transparency & Accountability to Customers"
   umbrella) would read more like an actual company standard and less like a checklist.
3. **AI Ethics Board / Governance Committee as an ongoing body, not just a policy artifact** —
   both Microsoft and IBM emphasize a standing, cross-functional review body with real veto power
   over releases, which Northstar's policy already has (the AI Governance Committee, Section 4) —
   this part of Northstar's draft is already well-aligned with real practice.

## RBI reference (same finding as Project 2)
Section 16's RBI reference is generic ("referenced generally; direct legal review required").
Per the Project 2 research pass, the same three named, current regulations apply here and should
replace the generic reference: RBI (NBFC — Outsourcing of IT Services) Directions, 2025; RBI
(NBFC — Cybersecurity, Technology Risk, Resilience and Assurance) Directions, 2026; RBI Digital
Lending Directions, 2025.

## Verified as already accurate — no change needed
- ISO/IEC 42001:2023 citation and its accompanying caveat ("certification demonstrates a
  certified AI management process; it does not, on its own, establish compliance with any
  specific external AI regulation") — accurate and appropriately hedged as originally written.
- DPDP Act commencement framing (staged; substantive obligations effective 13 May 2027) —
  consistent with the verification already done in Project 2's research pass.
