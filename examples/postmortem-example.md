# Postmortem Example

## Incident Summary

Sev1 API outage due to unbounded retry loop.

## Root Cause

Circuit breaker misconfiguration under dependency timeout storm.

## Corrective Actions

- Add retry budget
- Add dependency timeout guardrails
- Add synthetic failure tests
