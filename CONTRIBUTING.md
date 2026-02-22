# Contributing to Selio

Thank you for your interest in contributing to **Selio**.

Selio is an open-source ecosystem for Android and Linux with a strong focus on **security**, **privacy**, and **independence**.  
Contributions are welcome — but only if they follow the rules outlined below.

---

## Scope of Contributions

Only contributions that are explicitly described or requested in existing **Issues** are accepted.

This includes, but is not limited to:
- Bug fixes
- Features
- Documentation
- Tests
- Security-related improvements

Unsolicited refactors, architectural changes, or feature additions **without a corresponding issue** may be closed without review.

---

## Workflow

1. Create a **fork** or a **branch** (depending on your access level)
2. Implement the changes
3. Open a **Pull Request targeting `main`**

All Pull Requests are merged into `main`.  
Releases are built directly from `main`.

---

## Branching Strategy

- There is **no long-lived develop branch**
- All work is merged into `main`
- Releases are created from the current state of `main`

Keep your branches focused and short-lived.

---

## Commit Messages

This project **requires Conventional Commits**.

Valid types include (but are not limited to):

- `feat`
- `fix`
- `docs`
- `chore`
- `refactor`
- `test`
- `build`
- `ci`

Example:
```
feat: add encrypted local storage backend
```

Commits that do not follow this format may be rejected.

---

## Code Style & Formatting

There are **no manual style discussions**.

Code style is enforced automatically through configuration such as:
- Prettier
- dotnet format
- language-specific linters and formatters

If your code does not pass formatting checks, it will not be merged.

---

## Tests

- **Unit tests are mandatory**
- New features must include appropriate tests
- Bug fixes must include regression tests where applicable

Pull Requests without tests may be rejected.

---

## Pull Requests

Each Pull Request must:

- Contain a **short, clear description**
- Reference the relevant **Issue(s)**
- Pass all automated checks
- Follow the existing project structure

### Reviews

- **At least one reviewer approval is required**
- Code reviews are mandatory
- Maintainers reserve the right to request changes or close PRs

---

## Issues

- Each repository contains **Issue Templates**
- Always use the appropriate template
- Provide clear reproduction steps where applicable

Issues marked as **`good first issue`** are recommended for new contributors.

---

## Code of Conduct

This project follows the **Contributor Covenant Code of Conduct**.

By participating, you agree to uphold its standards.  
Unacceptable behavior will not be tolerated.

---

## Security

Security vulnerabilities **must not** be reported via public issues.

Please follow the responsible disclosure process defined in [SECURITY](SECURITY.md).

---

## License

All contributions are licensed under [**AGPL-3.0**](LICENSE).

By contributing, you confirm that:
- You have the right to submit the code
- Your contribution may be redistributed under the AGPL-3.0 license

---

## Final Note

Selio exists because people care about privacy, security, and digital independence.

If you contribute with care, discipline, and respect for these goals —  
**thank you**. Your work matters.
