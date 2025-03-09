na# Git Flow

## Branches

- **main**: Contains the production version of the project.
- **dev**: Development branch. All new features and bug fixes should be merged here before going to the `main` branch.
- **feature/**: For developing new features. Example: `feature/add-login-page`.
- **fix/**: For bug fixes. Example: `fix/navbar-visibility`.
- **refactor/**: For code refactoring. Example: `refactor/optimize-api-calls`.

## Branch Rules

1. Always create a new branch from the updated `dev` branch.
2. Make sure the local `dev` branch is up to date before creating a new branch:

```bash
  git checkout dev
  git pull origin dev
```

3. Create a new branch:

```bash
  git checkout -b feature/feature-name
```

4. If the branch was created incorrectly, stash the changes and create the correct branch:

```bash
  git stash
  git checkout -b feature/correct-name
  git stash pop
```

## Conventional Commits

Use conventional commit messages:

- `feat:` For new features.
- `fix:` For bug fixes.
- `refactor:` For code refactoring.
- `chore:` For miscellaneous tasks like updating dependencies.
- `docs:` For documentation changes.
- `style:` For code formatting and style adjustments.

Example of a commit message:

```bash
  git commit -m "feat: add login functionality"
```

## Pull Requests (PR)

1. All PRs should be opened against the `dev` branch.
2. PRs do not need to be overly detailed. Just provide a brief explanation of what was done.
3. For incomplete PRs, use the prefix `WIP:` (Work In Progress).
4. After approval, always use `squash and merge`, never just `merge`.

Example of a PR:

- **Title:** `feat: add login page`
- **Description:** `Implemented login page with form validation and authentication.`

## Best Practices

- Before merge a PR, make sure all tests are passing.
- Remove commented-out code and unused imports.


