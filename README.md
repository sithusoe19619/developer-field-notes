# Developer Field Notes

Developer Field Notes is a small personal reference site for Git commands, habits, and reminders to use during bootcamp.

## Live Site

GitHub Pages link: To be added after deployment.

## Features

- Explains the difference between Git and GitHub.
- Shows a daily edit, stage, commit, and push workflow.
- Collects useful Git command reminders.
- Lists files and secrets that should not be committed.

## What I Learned

I learned that Git commits only save staged changes, so checking `git status` and `git diff` before committing helps keep each commit focused.

## Git Practice Evidence

### `git log --oneline`

```text
658762f (HEAD -> main, origin/main, origin/HEAD) Merge pull request #7 from sithusoe19619/feature/responsive-styling
5edc76c (origin/feature/responsive-styling, feature/responsive-styling) add responsive CSS media query for mobile
49287a5 Merge pull request #6 from sithusoe19619/feature/do-not-commit-section
2e5821f (origin/feature/do-not-commit-section, feature/do-not-commit-section) expand do not commit safety section
a0239f6 (origin/feature/add-command-reference-section, feature/add-command-reference-section) Merge pull request #5 from sithusoe19619/feature/command-reference
2778aae (origin/feature/command-reference, feature/command-reference) expand command reference section
4493c2a add initial CSS styles
814d140 add initial HTML structure and README
f9e870c add .gitignore with standard exclusions
```

### `git log --oneline --graph --all`

```text
658762f (HEAD -> main, origin/main, origin/HEAD) Merge pull request #7 from sithusoe19619/feature/responsive-styling
5edc76c (origin/feature/responsive-styling, feature/responsive-styling) add responsive CSS media query for mobile
49287a5 Merge pull request #6 from sithusoe19619/feature/do-not-commit-section
2e5821f (origin/feature/do-not-commit-section, feature/do-not-commit-section) expand do not commit safety section
a0239f6 (origin/feature/add-command-reference-section, feature/add-command-reference-section) Merge pull request #5 from sithusoe19619/feature/command-reference
2778aae (origin/feature/command-reference, feature/command-reference) expand command reference section
4493c2a add initial CSS styles
814d140 add initial HTML structure and README
f9e870c add .gitignore with standard exclusions
```

### `git branch --all`

```text
* main
  feature/command-reference
  feature/do-not-commit-section
  feature/responsive-styling
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
  remotes/origin/feature/command-reference
  remotes/origin/feature/do-not-commit-section
  remotes/origin/feature/responsive-styling
```
