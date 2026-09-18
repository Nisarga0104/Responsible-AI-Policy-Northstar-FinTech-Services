# Northstar AI Risk Classification

## Purpose

Northstar uses four internal governance tiers to determine the amount of scrutiny required before and after deployment.

**These are internal governance tiers, not legal classifications.**

| Tier | Example | Governance requirement |
|---|---|---|
| Prohibited / Restricted | Fully automating credit approval/adverse-action decisions without human review; undisclosed inference of protected characteristics | Not permitted |
| High | Material influence on credit, pricing or account-status decisions; sensitive personal data at scale | AI Governance Committee approval; mandatory pre-deployment testing and human oversight |
| Moderate | Customer-facing informational conversational AI; internal AI-assisted document processing | Business Owner + Risk sign-off; standard testing and monitoring |
| Low | Internal productivity AI with no customer-facing output and no sensitive-data access | Business Owner self-assessment |

## Classification questions

1. Does the system materially affect a customer?
2. Can the output cause financial, legal, safety or significant reputational harm?
3. Does the system process sensitive personal data?
4. Can the system take or trigger consequential actions?
5. Is human review meaningful and capable of overriding the outcome?
6. Are external vendors or subprocessors involved?
7. What level of monitoring and testing is proportionate to the use case?

## Governance rule

A change in model, data sources, permissions or system scope can trigger reassessment. Approval is not treated as permanent when the risk profile materially changes.
