# Copilot Instructions for skills-introduction-to-github

## Repository Overview

This is a GitHub Skills exercise repository for the "Introduction to GitHub" course. It guides learners through the fundamentals of GitHub, including creating branches, committing files, opening pull requests, and merging pull requests.

## Repository Structure

- `.github/workflows/` — GitHub Actions workflows that check learner progress at each step of the exercise.
- `.github/steps/` — Markdown files containing the instructions shown to learners at each step.
- `.github/images/` — Screenshots and images used in the step instructions.
- `README.md` — Landing page linking learners to the exercise issue.

## Exercise Steps

The exercise walks learners through these steps in order:

1. **Create a branch** — Create a branch named `my-first-branch` from `main`.
2. **Commit a file** — Add a new file to the `my-first-branch` branch.
3. **Open a pull request** — Open a pull request from `my-first-branch` to `main`.
4. **Merge the pull request** — Merge the pull request into `main`.

## Coding Conventions

- Workflow files follow the naming convention `<step-number>-<step-name>.yml`.
- Step instruction files follow the naming convention `<step-number>-<step-name>.md`.
- Workflows use `skills/exercise-toolkit` reusable workflows and `GrantBirki/comment` action for posting feedback comments on the exercise issue.

## How Copilot Should Help

- When suggesting changes to workflow files, preserve the existing structure and use of reusable workflows from `skills/exercise-toolkit`.
- When updating step instruction files, maintain the learner-friendly tone and the `:keyboard: Activity:` format.
- Do not introduce dependencies or tools beyond what is already used in the repository.
