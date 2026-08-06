# Quality Gates And Checklists

## Architecture Approval

- Problem statement and constraints clear
- Interfaces and failure modes defined
- Scalability and operability considered
- ADR recorded

## Feature Approval

- User outcome and acceptance criteria defined
- Security and privacy impact reviewed
- Test plan approved
- Observability requirements included

## Merge Approval

- CI green for build, lint, test
- Required reviews complete
- Documentation updated
- Changelog entry added when user impact exists

## Release Approval

- Release notes complete
- Rollback plan validated
- Migrations rehearsed
- Monitoring and alerts ready

## Marketplace Approval

- Metadata complete: icon, categories, banner, links
- Licensing and third-party attributions verified
- Security review complete

## Open Source Release Approval

- Public docs and governance files complete
- License compatibility checked
- Support expectations documented

## SDK Release Approval

- API stability and versioning reviewed
- Migration notes prepared
- Compatibility matrix updated

## CLI Release Approval

- Cross-platform behavior verified
- Help output and examples updated
- Upgrade and rollback paths tested

## Breaking Change Review

- Impacted consumers identified
- Migration path documented
- Deprecation timeline communicated

## Performance Gate

- Performance budgets measured
- Regressions triaged and mitigated
- Benchmark report attached

## Accessibility Gate

- Automated and manual checks pass
- Assistive tech validation recorded

## Security Gate

- SAST and dependency scans pass
- Threat model complete for sensitive changes
- Secrets and policy checks pass

## Documentation Gate

- User and operator docs updated
- ADR and RFC references linked
- Examples updated where relevant
