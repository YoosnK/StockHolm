# Contributing Guidelines

Thank you for contributing! To maintain code quality and keep our project organized, please follow these guidelines when making contributions.

---

## Contribution workflow

1. Create a new branch off from main
2. Make your changes
3. Sync with main in the progress to keep track of newest changes
4. Merge main into your branch, fix the merge conflicts
5. Fix any bugs that appear after merging
6. Ensure that your branch does not have merge conflicts with main
7. Open a Pull Request on GitHub, request at least 1 reviewer.

---

## Branch Naming Format
Use the format: `<type>/<short-kebab-case-description>`

* `feat/add-user-auth`
* `fix/fix-checkout-total`
* `docs/update-user-guide`
* `chore/update-dependencies`
* `refactor/split-ui`

---

## ✍️ Commit Message Guidelines

We follow a strict `<category>: <commit message>` conventional commits specification.

### Format
```text
<category>: <short summary in imperative mood>

[optional body explaining *why* the change was made, and detailed description of the changes]

Categories

- feat: A new feature for the user or system

- fix: A bug fix

- docs: Documentation updates only

- style: Formatting, white-space, missing semi-colons (no code logic change)

- refactor: Code changes that neither fix a bug nor add a feature

- test: Adding or updating tests

- chore: Maintenance tasks, dependencies, tooling, or .gitignore updates

```
