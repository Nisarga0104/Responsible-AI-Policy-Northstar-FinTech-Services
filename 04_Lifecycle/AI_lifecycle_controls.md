# AI Lifecycle Controls

| Lifecycle stage | Required governance activity | Evidence / artifact |
|---|---|---|
| Ideation | Register use case and assign preliminary tier | AI Use Case Intake |
| Development | Document data lineage and create model/system documentation | Data lineage record; model/system card |
| Testing | Functional, fairness and adversarial testing proportional to risk | Test results and findings |
| Approval | Obtain sign-off required by risk tier | AI Approval Checklist / decision record |
| Deployment | Prefer phased rollout for High-tier systems | Deployment approval / rollout plan |
| Monitoring | Track performance, fairness and relevant incidents | Monitoring record / risk register |
| Change Management | Reassess material model, data or scope changes | Change assessment |
| Retirement | Execute documented retention/deletion plan | Retirement record |

## Control principles

- Testing is distinct from governance approval.
- Fairness testing is required for Moderate tier and above.
- Adversarial/security testing is required for High tier.
- Human oversight must be meaningful rather than nominal.
- Production monitoring compares observed performance against validation-stage expectations.
- Material changes can reopen the governance decision.
