# Contributing

Thank you for your interest in contributing! This guide covers the conventions used across all repositories in this organization.

## Getting Started

1. Fork the repository
2. Create a feature branch from `main` or `master`
3. Make your changes
4. Submit a pull request

## Commit Messages

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>: <description>

[optional body]

[optional footer]
```

### Types

| Type | Description |
|------|-------------|
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation only changes |
| `refactor` | Code change that neither fixes a bug nor adds a feature |
| `test` | Adding or updating tests |
| `ci` | Changes to CI/CD configuration |
| `chore` | Maintenance tasks (dependencies, configs) |

### Examples

```
feat: add user authentication endpoint
fix: resolve race condition in worker pool
ci: add terraform plan workflow for ELK stack
docs: update API reference for v2 endpoints
```

## Branch Naming

Use descriptive branch names with a prefix:

```
feat/add-metrics-export
fix/resolve-login-timeout
ci/refactor-terraform-workflows
docs/update-contributing-guide
```

## Pull Requests

- Fill out the PR template completely
- Keep PRs focused — one logical change per PR
- Ensure CI checks pass before requesting review
- Link related issues using `Closes #123`

## Issues

- Use the provided issue templates (Bug Report, Feature Request)
- Search existing issues before creating a new one
- Provide as much context as possible

## Code Style

- Follow the existing code style in the repository
- Run linters and formatters before committing
- No `any` types in TypeScript
- No empty catch blocks

## Questions?

Open a discussion or issue in the relevant repository.
