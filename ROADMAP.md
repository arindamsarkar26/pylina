# pylina Roadmap

A pure-Python Linear Algebra library built from scratch with modern software engineering practices.

## Milestones

- **Week 1: Core I & Setup**
  - [x] Repo scaffolding (`src/` layout, `pyproject.toml`, `uv`, `ruff`, `pytest`)
  - [ ] `Vector` class & custom exceptions (`exceptions.py`)
- **Week 2: Core II & GitHub Workflow**
  - [ ] `Matrix` class, dunder methods (`+`, `-`, `*`, `@`, `==`), indexing, `.to_list()`
  - [ ] `pytest` suite with `numpy` as a dev-only test oracle
  - [ ] GitHub Issues, Feature Branches, Pull Requests, Branch Protection on `main`
- **Week 3: Elimination I & CI**
  - [ ] Elementary row operations & `rref()`
  - [ ] GitHub Actions CI, `mypy` static type checking, `pre-commit` hooks
- **Week 4: Elimination II & Advanced Testing**
  - [ ] `lu()` ($PA = LU$) & `inverse()`
  - [ ] Parametrized `pytest`, fixtures, `pytest-cov` coverage tracking
- **Week 5: Linear Systems, Subspaces & Automation**
  - [ ] `rank()`, `solve()`, and the four fundamental subspaces
  - [ ] CI Matrix Testing (Python 3.11–3.14, Linux/Windows) & post-merge email notifications
- **Week 6: Orthogonality & Documentation**
  - [ ] `det()`, `qr()`, projections, and least squares
  - [ ] NumPy-style docstrings, MkDocs (Material), auto-deploy to GitHub Pages
- **Week 7: Eigenvalues, CLI & Release (`v1.0.0`)**
  - [ ] `eigen()` (eigenvalues & eigenvectors)
  - [ ] `pylina` CLI interface (`[project.scripts]` entry point)
  - [ ] Semantic Versioning, GitHub Releases, Dependabot, TestPyPI / PyPI packaging