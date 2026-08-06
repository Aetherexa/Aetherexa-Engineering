# Testing Strategy

## Pyramid

- Unit tests for domain logic
- Integration tests for boundaries and adapters
- End-to-end tests for critical user journeys

## Contract Testing

- API and event contracts validated in CI

## Regression Strategy

- Bug fixes require failing tests before fix where feasible

## Stability

- Flake budget tracked
- Quarantine policy for unstable tests with owner and due date
