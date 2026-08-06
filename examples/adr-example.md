# ADR Example

## Context

Need a stable event transport across editor and service runtime.

## Decision

Adopt typed event bus abstraction with pluggable transport adapters.

## Consequences

- Clear contract boundaries
- Slight increase in adapter boilerplate
