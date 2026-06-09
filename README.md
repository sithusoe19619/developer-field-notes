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
4c57f22 Merge responsive styling improvements
1793586 Improve responsive styling
4523740 Merge do not commit safety section
a6039fa Add do not commit safety section
93c39f2 Merge command reference section
03d4935 Add command reference section
fb81a98 Add initial site styling
5cd7af2 Add initial field notes page and README
0dbbf66 Add gitignore for local files
```

### `git log --oneline --graph --all`

```text
*   4c57f22 Merge responsive styling improvements
|\  
| * 1793586 Improve responsive styling
|/  
*   4523740 Merge do not commit safety section
|\  
| * a6039fa Add do not commit safety section
|/  
*   93c39f2 Merge command reference section
|\  
| * 03d4935 Add command reference section
|/  
* fb81a98 Add initial site styling
* 5cd7af2 Add initial field notes page and README
* 0dbbf66 Add gitignore for local files
```

### `git branch --all`

```text
  feature/command-reference
  feature/do-not-commit-safety
  feature/responsive-styling
* main
```
