# Workflow Test Repository

This repository is used to test the organization-wide GitHub Actions workflows.

## Workflows Being Tested

1. **Standard Repository Setup**: Automatically labels issues and PRs, adds comments, and tracks issue status
2. **Release Management**: Generates release PRs with all pending issues

## Test Cases

### Standard Repository Setup

- [ ] Create an issue without mentioning CONTRIBUTING.md
- [ ] Create an issue that mentions CONTRIBUTING.md
- [ ] Create a draft PR that references an issue
- [ ] Mark the PR as ready for review
- [ ] Merge the PR to develop
- [ ] Verify that labels are applied correctly

### Release Management

- [ ] Create issues and merge PRs to develop
- [ ] Run the release workflow
- [ ] Verify that a release PR is created with all pending issues

## Implementation Notes

This repository documents challenges encountered during implementation and their solutions.
# Test PR Status Tracker
