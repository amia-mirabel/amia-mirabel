# Amia-Mirabel Codebase Onboarding Guide

Welcome to the Amia-Mirabel repository! This document captures the current state of the codebase and how we expect it to evolve so that you can get productive quickly.

## Repository Overview

At the moment this repository only contains a top-level `README.md`. This is the profile README that GitHub renders on the amia-mirabel account page. No application source code has been committed yet, so the repo is an ideal blank slate for setting up conventions and scaffolding.

The following high-level structure is planned:

```
.
├── docs/                  # Reference and onboarding material
├── src/                   # Application source code (to be added)
├── tests/                 # Automated tests (to be added)
├── .github/               # Workflows and issue templates (optional)
└── README.md              # Profile/landing page content
```

As new code is added we will populate the `src/` and `tests/` directories following language-specific best practices.

## Current Priorities

1. **Establish coding standards** – Decide on the primary programming language, formatting rules, and linting tools before committing application code.
2. **Define project goals** – Clarify the scope of the project so directory structure and dependencies can be planned appropriately.
3. **Set up CI/CD early** – Even a simple automated test or lint workflow helps enforce quality from the first lines of code.

## Getting Started Checklist

- [ ] Align with the team on the initial feature or proof-of-concept to build.
- [ ] Create the corresponding project structure under `src/` and `tests/`.
- [ ] Add linting/formatting configuration (e.g., ESLint + Prettier for JavaScript, Ruff + Black for Python).
- [ ] Introduce a basic CI workflow under `.github/workflows/` once tests are available.

## Suggested Next Steps for You

1. Review the `README.md` to understand how the profile page is currently presented.
2. Draft a proposal for the first module or feature we plan to implement.
3. Prepare a minimal project scaffold (language runtime, package manager files, initial entry point) and open a PR for team review.
4. Collaborate with the team on documenting conventions in this `docs/` directory as the codebase grows.

Welcome aboard, and feel free to expand this guide with any insights you gather!
