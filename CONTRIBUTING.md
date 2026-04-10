# Contributing to Docker Autoheal

Thank you for your interest in contributing! 

## Commit Message Convention

This project uses [Conventional Commits](https://www.conventionalcommits.org/) for automated versioning and changelog generation.

### Format

```
<type>(<scope>): <subject>
```

### Types

- **feat**: A new feature (triggers minor version bump)
- **fix**: A bug fix (triggers patch version bump)
- **docs**: Documentation changes
- **style**: Code style changes (formatting, missing semicolons, etc.)
- **refactor**: Code refactoring without changing functionality
- **perf**: Performance improvements
- **test**: Adding or updating tests
- **build**: Changes to build system or dependencies
- **ci**: Changes to CI/CD configuration
- **chore**: Other changes that don't modify src or test files
- **revert**: Reverting a previous commit

### Breaking Changes

Add `BREAKING CHANGE:` in the commit body or `!` after the type to trigger a major version bump:

```
feat!: remove support for Node 12

BREAKING CHANGE: Node 12 is no longer supported
```

### Examples

```
feat: add support for Podman socket
fix: handle connection timeout gracefully
docs: update installation instructions
ci: add security scanning with Trivy
```

## Development Workflow

1. Fork and clone the repository
2. Create a feature branch: `git checkout -b feat/my-new-feature`
3. Make your changes
4. Run tests: `cd tests && bash tests.sh`
5. Commit with conventional commit format
6. Push and create a pull request

## Pull Request Process

1. Ensure all tests pass
2. Update documentation if needed
3. Use a conventional commit format for your PR title
4. The PR will be automatically checked for commit message format

## Release Process

Releases are fully automated:
- Merging to `main` triggers semantic-release
- Version is determined by commit types
- CHANGELOG is automatically generated
- GitHub release is created
- Docker images are built and pushed with version tags

You don't need to manually update version numbers or create tags!
