# Developer Field Notes

A personal reference site for Git commands, version control concepts, and development habits — built as part of the TTP Summer 2026 Git Solo Workflow assignment.

## Live Site

[https://sithusoe19619.github.io/developer-field-notes/](https://sithusoe19619.github.io/developer-field-notes/)

*(Deploy link — will be live after GitHub Pages is enabled)*

## Features

- Explanation of the difference between Git and GitHub
- The daily developer loop: edit, stage, commit, push
- Reference list of 8 essential Git commands with explanations
- "Things I Should Not Commit" — a guide to .gitignore and secrets hygiene
- Clean, responsive CSS layout

## One Thing I Learned About Git

Git tracks *changes*, not whole files. When you run `git add`, you are not copying a file — you are moving a diff (a set of line-level changes) into a staging area. This means you can stage only part of a file's changes using `git add -p`, giving you fine-grained control over exactly what goes into each commit.

## Git Practice Evidence

*(This section will be updated in Part 5 with git log output)*
