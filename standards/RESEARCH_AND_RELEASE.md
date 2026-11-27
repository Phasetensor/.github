# Research and release standards

Status: proposed engineering baseline; individual project requirements may be stricter.

## Research lifecycle

Define the intended users, concrete problem, existing solutions, gap, mathematical specification, and falsifiable benchmark before implementation. Record assumptions and limitations. Compare against relevant baselines under matched resource budgets; report uncertainty, seeds, environment, backend, and all material costs. Negative results are valid outcomes.

## Engineering baseline

Use Python 3.11 or later as the initial compatibility target, subject to dependency compatibility. Prefer a src layout, pyproject.toml, typed public APIs, pytest, Ruff, and mypy. NumPy and SciPy may be used as needed; quantum backends should be optional where possible. Hypothesis, uv, Hatchling, Sphinx and ASV are preferred where useful, not mandatory dependencies.

Each library should include README, LICENSE (after approval), CITATION.cff, CHANGELOG, tests, examples, docs, and reproducible benchmarks. Aim for at least 90% coverage of testable source code; justify exceptions and independently test numerical correctness.

## Release gate

Require passing CI, reference or analytical validation, documented uncertainty and limitations, reproducible benchmark results, public API documentation, and a clean-environment installation test. Build and inspect wheel and source distribution. Use semantic versioning and PyPI Trusted Publishing when configured; verify package availability and release links before advertising them. Archive releases with a DOI when available.

Initial release target is 0.1.0; 1.0.0 requires a stable public API and documented validation. No fixed intermediate version milestones are mandatory.

## Licensing

Apache-2.0 is the proposed default, pending explicit approval and confirmation of rights and dependency compatibility. This document does not grant a license.
