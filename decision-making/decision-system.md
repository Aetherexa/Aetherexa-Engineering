# Decision System

## Decision Trees

- Reversible and low-risk: team-level owner decides.
- Reversible and high-risk: team lead plus architecture reviewer.
- Irreversible and low-risk: domain owner plus engineering manager.
- Irreversible and high-risk: architecture council approval required.

## Escalation Paths

1. Feature owner
2. Team lead
3. Engineering manager
4. Principal architect
5. Engineering leadership council

## Approval Matrix

- Product behavior change: product manager plus engineering owner
- Architecture change: principal architect plus domain owner
- Security-sensitive change: security engineer plus owner
- Release-blocking risk: release manager plus engineering manager

## Ownership Matrix

- Responsible: implementation owner
- Accountable: team lead or manager
- Consulted: architecture, security, QA, design
- Informed: stakeholders and support

## Risk Matrix

- Likelihood: low, medium, high
- Impact: low, medium, high, critical
- Actions: accept, mitigate, transfer, avoid

## Technical Debt Framework

- Classify debt: accidental, strategic, obsolete, dependency
- Score debt by risk, drag, and remediation effort
- Allocate fixed sprint capacity to debt reduction

## Priority Matrix

- User value
- Strategic alignment
- Risk reduction
- Effort and time-to-impact

## Trade-off Framework

- Evaluate correctness, speed, cost, complexity, and flexibility
- Make trade-offs explicit in RFC and PR
- Record rejected alternatives
