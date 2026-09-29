# Git Workflow

## Branches

- `main`: stable, release-ready code.
- `develop`: integration branch.
- `feature/*`: new functionality.
- `fix/*`: non-urgent bug fixes.
- `hotfix/*`: urgent production fixes.
- `refactor/*`: internal code improvements.
- `docs/*`: documentation-only changes.
- `chore/*`: tooling, dependencies and CI changes.

## Naming examples

```text
feature/BE-01-auth
feature/BE-02-product
feature/FE-01-layout
fix/BE-03-order-validation
chore/CI-01-github-actions
```

## Pull Request flow

```text
feature/*
    ↓
Pull Request
    ↓
develop
    ↓
release / verification
    ↓
main
```

## Commit convention

Use Conventional Commits:

```text
feat: add product CRUD
fix: handle invalid product price
refactor: simplify order service
test: add product service tests
docs: update API documentation
chore: configure CI
```

Keep commits focused. Avoid committing generated files, secrets, local configuration or IDE metadata.
