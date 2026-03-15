# Contributing to Detektor

Thank you for your interest in contributing to **Detektor**.

Detektor is the **reference CLI scanner for the OpenPAKT specification**, designed to detect AI agent security risks and produce normalized OpenPAKT reports suitable for CI validation.

We welcome contributions that improve the scanner, example scenarios, and developer experience.

---

## Ways to Contribute

Contributions may include:

* improving the Detektor CLI implementation
* adding or refining detection rules
* contributing security testing scenarios
* improving report generation
* improving documentation
* reporting bugs or unexpected scanner behavior
* suggesting improvements to developer tooling or CI integration

If your proposal affects the **OpenPAKT specification itself**, please submit the change to the **OpenPAKT repository** instead.

---

## Development Principles

Detektor aims to remain **small, predictable, and easy to integrate into CI pipelines**.

Contributions should follow these principles:

* keep implementations **minimal and deterministic**
* avoid introducing unnecessary frameworks
* prioritize **clear and maintainable code**
* ensure generated findings remain **OpenPAKT-compliant**
* preserve compatibility with the current specification version

---

## Reporting Issues

If you encounter a bug or unexpected behavior:

1. Open a GitHub Issue.
2. Provide a clear description of the problem.
3. Include reproduction steps if possible.
4. Include sample input files or configuration where relevant.

This helps maintainers reproduce and resolve issues efficiently.

---

## Pull Requests

Pull requests should be **small, focused, and clearly explained**.

Please ensure that:

* the change clearly relates to an existing GitHub issue
* the change does not introduce unnecessary dependencies
* the CLI output remains stable and deterministic
* generated reports remain compliant with the OpenPAKT report schema
* documentation is updated if behavior changes

Maintainers will review pull requests before merging.

---

## Branch Naming

Contributions should be developed in a dedicated branch and submitted via a pull request to the `main` branch.

Recommended formats:

* `issue/<number>-<short-slug>` for issue-driven work
* `feature/<short-slug>` for new functionality
* `docs/<short-slug>` for documentation changes
* `chore/<short-slug>` for repository maintenance
* `fix/<short-slug>` for bug fixes

Examples:

```text
issue/12-add-prompt-injection-rule
feature/json-report-output
docs/update-cli-usage
chore/add-ci-workflow
fix/report-summary-count
```

Guidelines:

* use **lowercase**
* use **kebab-case** (`-`)
* keep branch names **short and descriptive**
* include the **GitHub issue number** when possible

All changes should be submitted via a **pull request** and reviewed before merging.

---

## Code Style

Detektor is implemented in **.NET**.

Contributors should follow these general guidelines:

* keep classes small and focused
* prefer clear naming over clever abstractions
* avoid unnecessary architectural complexity
* maintain consistent formatting and structure

Where possible:

* CLI behavior should remain **predictable**
* output should remain **stable for CI usage**

---

## Security Contributions

Because Detektor focuses on **AI agent security scanning**, responsible disclosure is important.

If you discover a **security vulnerability in Detektor**, please report it privately instead of opening a public issue.

Contact: security@meisterware.com

Maintainers will review and coordinate fixes before public disclosure when appropriate.

---

## Code of Conduct

All contributors must follow the project's [Code of Conduct](CODE_OF_CONDUCT.md).

We welcome constructive discussion and contributions that help improve the reliability and usefulness of Detektor.
