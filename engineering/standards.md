# Engineering Standards

## Repository Standards

- Every repository has README, CONTRIBUTING, SECURITY, and CHANGELOG.
- Every repository has CI checks for build, lint, test, and security scans.
- Every repository defines ownership via CODEOWNERS.

## Folder Standards

- src for implementation, test for integration where applicable, docs for product-facing docs.
- Keep architecture and domain boundaries explicit through module structure.

## Naming Conventions

- Use descriptive, domain-oriented names.
- Avoid abbreviations unless industry standard.
- APIs use consistent verb and noun patterns.

## Branch Strategy

- Trunk-based development with short-lived feature branches.
- Protected main branch.
- Mandatory status checks before merge.

## Commit Strategy

- Conventional Commits format.
- Atomic commits aligned to one logical change.
- Include issue or decision reference when relevant.

## Semantic Versioning

- MAJOR for breaking changes.
- MINOR for backward-compatible features.
- PATCH for backward-compatible fixes.

## Dependency Policy

- Prefer actively maintained dependencies.
- Pin and periodically update lockfiles.
- Security review for critical dependency changes.

## Documentation Standards

- User and operator impact documented in each change.
- ADR required for significant architectural decisions.

## Testing Standards

- Unit tests for core logic.
- Integration tests for boundaries and adapters.
- End-to-end tests for critical user journeys.
- Flaky tests treated as Sev2 quality incidents.

## Performance Budgets

- Define startup, latency, throughput, and memory budgets per product.
- Enforce budgets in CI where measurable.

## Accessibility Standards

- WCAG 2.2 AA target for user interfaces.
- Keyboard and screen-reader support mandatory.

## Security Standards

- Threat model for sensitive features.
- Least privilege by default.
- Secrets never stored in code or logs.

## API Design Standards

- Explicit versioning.
- Backward compatibility policy documented.
- Consistent error model and pagination patterns.

## Error Handling Standards

- Fail fast on invalid state.
- Return actionable, structured errors.
- Never swallow critical failures.

## Logging Standards

- Structured logs with correlation IDs.
- No sensitive data in logs.
- Severity levels aligned to alert policy.

## Configuration Standards

- Twelve-factor style environment configuration.
- Safe defaults and explicit override paths.

## Internationalization Standards

- Externalize user-facing strings.
- Locale-aware formatting for time, number, and currency.

## Observability Standards

- Traces, metrics, and logs for critical flows.
- SLO dashboards and alerts for key services.

## Telemetry Policy

- Collect minimum necessary telemetry.
- Document schema, retention, and access controls.

## Privacy Policy Engineering Requirements

- Data classification and minimization mandatory.
- Consent and deletion workflows enforceable and testable.

## Code Style

- Formatter and lint rules are authoritative.
- Style debates are resolved via tooling, not review comments.

## Review Requirements

- At least one owner approval.
- Security review for sensitive areas.
- Documentation and tests required for merge.
