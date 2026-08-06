# Automation System

## GitHub Labels

- type: bug, feature, chore, docs, security, performance
- priority: p0, p1, p2, p3
- status: triage, ready, in-progress, blocked, done
- area: frontend, backend, platform, ai, docs, devex

## GitHub Projects

- Project views by team, quarter, and risk
- Mandatory fields: owner, priority, target release, risk level

## Milestones

- Quarterly milestones for strategic outcomes
- Release milestones for product trains

## Issue Templates

- Bug report
- Feature request
- Spike proposal
- Security report

## Pull Request Template

- Summary, user impact, testing, risks, rollout/rollback, checklist

## Release Automation

- Conventional commits plus changesets
- Automated versioning and release notes generation
- Release workflows gated by quality checks

## CI/CD Standards

- Required checks: build, lint, test, security scan
- Protected branch policies enforced
- Deployment promotion through staged environments

## Dependabot

- Weekly dependency updates
- Security updates prioritized

## Renovate

- Grouped update strategy by ecosystem and risk
- Automerge policy for low-risk patch updates after checks pass

## CodeQL

- Weekly scheduled scanning plus PR-time analysis
- Blocking policy for high severity issues

## Automation Policies

- Automation failures are treated as delivery blockers
- Exceptions require documented risk acceptance
