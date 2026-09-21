# Contributing to 3T Labs

Thank you for your interest in contributing to **3T Labs**! We welcome contributions of all forms: bug reports, documentation improvements, feature requests, and pull requests.

Please take a moment to review these guidelines before contributing.

---

## Code of Conduct

All contributors and participants across 3T Labs repositories are expected to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before participating.

---

## Getting Started

1. **Find an Issue**: Browse open issues across [3T Labs repositories](https://github.com/3TLabs). Look for labels like `good first issue` or `help wanted`.
2. **Discuss First**: For significant new features or architectural changes, please open an issue or discussion topic before starting work to align on the approach.
3. **Fork & Clone**: Fork the repository to your own GitHub account and clone it locally.

---

## Development Workflow

### 1. Branching & Commits
- Create a feature branch with a descriptive name:
  ```bash
  git checkout -b feat/my-new-feature
  # or
  git checkout -b fix/issue-description
  ```
- Write clear, concise commit messages (prefer [Conventional Commits](https://www.conventionalcommits.org/)):
  - `feat: add new CLI command for cluster discovery`
  - `fix: correct holiday calculation edge case in analyzer`
  - `docs: update deployment instructions in README`

### 2. Code Quality & Standards
- **Go Projects**: Follow standard Go idioms, ensure `go fmt`, `go vet`, and `golangci-lint` pass, and include unit tests (`go test -v ./...`).
- **DevOps / Helm / YAML**: Ensure manifests are valid, linted, and formatted.
- **Python / Other**: Follow PEP 8 and project-specific linting rules.

### 3. Testing
- Make sure all existing unit and integration tests pass.
- Add test coverage for new functionality or bug fixes.

---

## Submitting Pull Requests

1. **Push your branch** to your fork:
   ```bash
   git push origin feat/my-new-feature
   ```
2. **Open a Pull Request**: Fill out the PR template with relevant context, issue references (e.g., `Fixes #123`), and testing steps.
3. **Review Process**: A maintainer will review your pull request, provide feedback, or approve and merge it.

---

## AI Usage Guidelines

When using AI assistance (LLMs, Copilot, ChatGPT, etc.) for contributions to 3T Labs projects:
- **Quality & Understanding**: You are responsible for every line of code or documentation submitted. Verify that AI-generated code is accurate, secure, and tested.
- **No Hallucinated Dependencies**: Double-check imported packages and external APIs.
- **Genuine Context**: PR descriptions and review discussions should clearly describe what changed and why.

---

## Questions & Help

If you need help or have questions:
- Open a discussion in [3T Labs Discussions](https://github.com/orgs/3TLabs/discussions).
- Open an issue in the target repository.
- Reach out to the maintainers: [@stavrosl7](https://github.com/stavrosl7), [@gtourgianas](https://github.com/gtourgianas), or [@zacharatos](https://github.com/zacharatos).
