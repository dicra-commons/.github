# Contributing to DiCRA

Thank you for your interest in contributing to DiCRA. As a digital public good, DiCRA thrives on collaborative contributions from a global community of data scientists, developers, researchers, and citizen scientists.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Workflow](#development-workflow)
- [Commit Message Conventions](#commit-message-conventions)
- [Pull Request Process](#pull-request-process)
- [Data Contributions](#data-contributions)
- [Getting Help](#getting-help)

## Code of Conduct

All contributors are expected to adhere to our [Code of Conduct](./CODE_OF_CONDUCT.md). Please read it before participating.

## How Can I Contribute?

### Reporting Bugs

Before creating a bug report, please check existing issues. When you create a bug report, include:

- A clear and descriptive title
- Steps to reproduce the issue
- Expected vs. actual behavior
- Screenshots, if applicable
- Environment details (OS, browser, version)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. Please include:

- A clear use case
- Why this enhancement would benefit DiCRA users
- Possible implementation approaches, if you have ideas

### Contributing Code

1. Fork the repository
2. Create a feature branch from `main`
3. Make your changes following our coding standards
4. Add or update tests
5. Update documentation
6. Submit a pull request

### Contributing Data

Geospatial datasets and validations are at the heart of DiCRA. See the [Data Contributions](#data-contributions) section below.

## Development Workflow

### Branch Naming

- `feature/<short-description>` — new features
- `fix/<short-description>` — bug fixes
- `docs/<short-description>` — documentation only
- `refactor/<short-description>` — code restructuring
- `data/<dataset-name>` — dataset additions or updates

### Local Setup

Each repository has its own setup instructions in its README. Common prerequisites:

- Python 3.10+ (for analytics and APIs)
- Node.js 20+ (for web and JS SDK)
- Docker (for local environment parity)

## Commit Message Conventions

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <description>

[optional body]

[optional footer]
```

**Types:** `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, `data`

**Examples:**

```
feat(api): add endpoint for soil moisture data
fix(web): correct map rendering on mobile devices
data(telangana): add Q4 2025 crop yield validation
```

## Pull Request Process

1. Ensure your PR addresses a single concern
2. Update the relevant documentation
3. Add tests covering your changes
4. Ensure all CI checks pass
5. Request review from a CODEOWNER
6. PRs require at least one approval before merging
7. Squash and merge is preferred for clean history

## Data Contributions

DiCRA's value depends on high-quality, validated geospatial data. Contributions should:

- Include metadata following the [DiCRA Metadata Standard](../data/METADATA.md)
- Provide provenance and licensing information
- Pass automated validation checks
- Be accompanied by sample analyses where possible

## Maintainers

The DiCRA codebase is maintained by **mistEO Private Limited**, the technology partner for DiCRA 2.0, under the stewardship of NABARD and UNDP India. Code reviews, releases, and architectural decisions are coordinated by the mistEO engineering team in collaboration with the platform's stewards.

## Getting Help

- 💬 [GitHub Discussions](https://github.com/orgs/dicra-commons/discussions) — questions and ideas
- 📧 support@dicra.org — official correspondence
- 🐛 Repository issues — bug reports and feature requests specific to a repo

---

By contributing, you agree that your contributions will be licensed under the same license as the repository (typically MIT for code, CC-BY 4.0 for data, unless otherwise specified).
