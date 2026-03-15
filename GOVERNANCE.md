Status: Informational

# Detektor Governance

Detektor is maintained by the **Meisterware** organisation.

The project aims to provide a **small, practical reference implementation** of AI agent security scanning aligned with the **OpenPAKT specification**.

Detektor focuses on deterministic security scanning suitable for **CI pipelines and DevSecOps workflows**.

---

## Project Maintainers

The project maintainers are responsible for:

* reviewing and merging pull requests
* maintaining the codebase and documentation
* ensuring alignment with the OpenPAKT specification
* guiding the overall direction of the project

Maintainers may delegate responsibilities to trusted contributors over time.

---

## Scanner Evolution

The scanner evolves through **versioned releases**.

Changes are proposed through **GitHub issues and pull requests** and reviewed by maintainers before inclusion.

Maintainers aim to keep the scanner:

* minimal
* deterministic
* CI-friendly
* aligned with the OpenPAKT specification

Maintainers make the final decision on whether a change is accepted into the scanner.

---

## Relationship to OpenPAKT

Detektor is a **reference scanner implementation** for the OpenPAKT specification.

Specification changes are governed separately through the **OpenPAKT specification repository**.

When the OpenPAKT specification evolves, Detektor may update its implementation to support new versions while maintaining compatibility where practical.

---

## Versioning

Detektor follows **Semantic Versioning**.

Version numbers follow the format:

```text
MAJOR.MINOR.PATCH
```

Version changes indicate:

* **Major** – breaking changes to CLI behavior or report output
* **Minor** – new scanner capabilities or rules
* **Patch** – bug fixes, internal improvements, or documentation updates

---

## Decision Making

Project decisions are made through **open discussion in GitHub issues and pull requests**.

Maintainers consider:

* technical correctness
* alignment with the OpenPAKT specification
* implementation simplicity
* long-term maintainability

Final decisions are made by the project maintainers.

---

## Governance Evolution

This governance model is intentionally **minimal for early project stages**.

As the Detektor ecosystem grows, the governance model may evolve to support:

* additional maintainers
* structured release processes
* broader community participation.
