# AI-Native Engineering Workflow

Every AI implementation session follows this sequence.

## 1. Read Context

- Read repository README and relevant subsystem docs
- Read current branch changes and open PR context
- Read incident and support history when related

## 2. Read PRD

- Confirm user outcomes, constraints, and acceptance criteria

## 3. Read RFC

- Confirm intended architecture and trade-offs

## 4. Read ADR

- Confirm non-negotiable architecture decisions

## 5. Read Related Issues

- Gather prior defects, edge cases, and known regressions

## 6. Analyze Risks

- Security, privacy, performance, accessibility, and operability

## 7. Implement

- Apply smallest safe change set
- Keep interfaces stable where possible

## 8. Self Review

- Correctness, tests, docs, and maintainability review

## 9. Architecture Review

- Required for boundary or design-impacting changes

## 10. QA Review

- Validate functional and regression scenarios

## 11. Performance Review

- Verify budgets and regression signals

## 12. Documentation Review

- Update user docs, operator docs, and decision records

## 13. Generate PR Summary

- Problem, approach, risk, test evidence, rollout and rollback notes

## 14. Generate Changelog

- User-visible behavior and migration notes

## 15. Generate Test Report

- Unit, integration, e2e, coverage, and known gaps

## Session Completion Criteria

- All required gates pass
- Reviewer feedback incorporated
- Release readiness confirmed when shipping
