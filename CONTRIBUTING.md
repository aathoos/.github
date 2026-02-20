# Contributing to Aathoos

Thank you for your interest in contributing to Aathoos! We welcome contributions from everyone — whether it's a bug fix, a new feature, documentation improvements, or just opening an issue.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Features](#suggesting-features)
  - [Submitting a Pull Request](#submitting-a-pull-request)
- [Development Workflow](#development-workflow)
- [Commit Messages](#commit-messages)
- [Pull Request Guidelines](#pull-request-guidelines)

---

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

---

## Getting Started

1. **Fork** the repository you want to contribute to.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
3. **Add the upstream remote** so you can pull in future changes:
   ```bash
   git remote add upstream https://github.com/aathoos/<repo-name>.git
   ```
4. **Install dependencies** (refer to the repo's README for specific instructions).

---

## How to Contribute

### Reporting Bugs

Before opening a bug report:
- Search existing issues to see if it has already been reported.
- Make sure you are on the latest version.

When filing a bug, include:
- A clear and descriptive title
- Steps to reproduce the issue
- Expected vs. actual behavior
- Your environment (OS, runtime version, etc.)
- Relevant logs or screenshots

### Suggesting Features

We love hearing new ideas! Open an issue with:
- A clear description of the feature
- Why it would be useful
- Any examples or references that might help

### Submitting a Pull Request

1. **Create a branch** from `main` in your fork:
   ```bash
   git checkout -b feat/your-feature-name
   ```
2. **Make your changes.** Keep them focused — one concern per PR.
3. **Test your changes** before submitting.
4. **Push** your branch to your fork:
   ```bash
   git push origin feat/your-feature-name
   ```
5. **Open a Pull Request** against `aathoos/<repo-name>:main`.
6. Fill in the PR template if one is provided.

---

## Development Workflow

- Always branch off `main`.
- Keep your fork up to date:
  ```bash
  git fetch upstream
  git rebase upstream/main
  ```
- Avoid unrelated changes in the same PR.

---

## Commit Messages

Use clear, descriptive commit messages. We follow a loose version of [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>: <short summary>

Examples:
feat: add support for custom themes
fix: resolve null pointer in parser
docs: update installation steps
chore: bump dependency versions
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

---

## Pull Request Guidelines

- PRs should have a clear title and description.
- Reference any related issues using `Closes #<issue-number>`.
- Keep PRs small and focused — large PRs are harder to review.
- Be responsive to review comments.
- A maintainer will merge your PR once it is approved.

---

We appreciate every contribution, big or small. Thank you for helping make Aathoos better!
