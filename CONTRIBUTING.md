# Contributing to Sovereign Edge Agent OS (SEAO)

Thanks for your interest in contributing to SEAO.

This project is being built with a long-term focus on **security, reliability, and edge-first AI operations**. Contributions are welcome — especially those that improve architecture clarity, safety, and developer experience.

---

## Before You Start

Please:

1. Read the [README.md](README.md)
2. Check existing issues and discussions
3. Follow the coding and commit conventions below

If you want to contribute a major feature, open an issue first to discuss the design.

---

## Ways to Contribute

You can help by contributing:

- Bug fixes
- Documentation improvements
- Security hardening ideas
- Tests and validation utilities
- Edge deployment examples
- Tool sandbox modules
- Policy engine enhancements

---

## Branch Naming Convention

Please use clear branch names:

- `feature/<short-name>`
- `fix/<short-name>`
- `docs/<short-name>`
- `refactor/<short-name>`
- `security/<short-name>`

### Examples
- `feature/agent-loop`
- `fix/tool-timeout-handling`
- `docs/readme-architecture-update`
- `security/prompt-injection-filter`

---

## Pull Request Guidelines

When opening a PR, please include:

- **What changed**
- **Why it changed**
- **How it was tested**
- Screenshots/logs (if UI or behavior changed)
- Any known limitations

### PR Rules
- Keep PRs focused and small where possible
- One logical change per PR
- Update docs if behavior changes
- Do not include unrelated formatting changes

---

## Code Style

### General
- Prefer clear, readable code over clever shortcuts
- Keep modules small and composable
- Add comments where logic is security-sensitive

### Python (Planned Core)
- Follow PEP 8
- Use type hints where practical
- Validate inputs explicitly
- Avoid unsafe dynamic execution patterns

### Security-Sensitive Code
- Default to least privilege
- Fail safely
- Log important decisions (without leaking secrets)

---

## Commit Message Style

Please use clean, descriptive commit messages.

### Recommended format
- `feat: add local agent task loop scaffold`
- `fix: prevent unsafe shell command execution`
- `docs: add security reporting workflow`
- `refactor: split policy engine into modules`
- `test: add validation tests for risk scoring`

---

## Testing (As Project Grows)

Contributors should test changes before submitting PRs.

Planned expectations:
- Unit tests for core modules
- Basic integration checks for agent + tools
- Security checks for policy enforcement paths

If tests are not yet available for your area, include manual verification steps in the PR.

---

## Security Issues

If your contribution touches security-sensitive behavior (tool execution, secret handling, policy checks), please highlight that in the PR description.

For vulnerabilities, do not open a public issue first. See [SECURITY.md](SECURITY.md).

---

## Licensing

By submitting a contribution, you agree that your contributions will be licensed under the **MIT License** used by this repository.

---

## Code of Conduct

Be respectful, constructive, and professional.

SEAO is intended to be a serious engineering project. Good technical debate is welcome; disrespect is not.

---

Thanks for contributing to SEAO.
