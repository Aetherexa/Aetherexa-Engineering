# GitHub Repository Settings For Public Release

This checklist captures required GitHub UI settings that cannot be fully enforced through repository files.

## Repository Profile

- Description:
  - Aetherexa Foundation Engineering Operating System: standards, playbooks, templates, and AI-native workflows for building software products.
- Website:
  - https://github.com/aetherexa/aetherexa-foundation
- Topics:
  - engineering-os
  - software-architecture
  - engineering-standards
  - developer-experience
  - software-quality
  - software-security
  - release-engineering
  - ai-engineering
  - documentation
  - open-source
- Social preview image:
  - Use assets/social-preview.svg

## Branch Protection (main)

- Require pull request before merging
- Require approvals: minimum 1 (recommended 2 for governance changes)
- Require status checks before merging:
  - CI
  - CodeQL
- Require conversation resolution before merging
- Restrict force pushes
- Restrict deletions

## Discussions

Enable GitHub Discussions and create categories:
- Announcements
- Ideas
- Q&A
- Show and Tell
- RFC Proposals
- Release Feedback

## Milestones

Create baseline milestones:
- v1.0.0 Public Release
- v1.1.0 Workflow Maturity
- v1.2.0 Policy As Code

## Projects

Create a project board named:
- Foundation Operating System Roadmap

Suggested columns:
- Backlog
- Ready
- In Progress
- Review
- Done

## Environments

Create a release environment with required reviewers for protected release operations.
