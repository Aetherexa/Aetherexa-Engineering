# RFC Example

## Title

Runtime Plugin Interface v2

## Problem

Current plugin lifecycle blocks concurrent plugin loading.

## Proposal

Introduce async lifecycle hooks and compatibility adapter.

## Trade-offs

- Pros: improved startup concurrency
- Cons: compatibility complexity

## Rollout

- Beta flag
- Gradual enablement
- Migration guide
