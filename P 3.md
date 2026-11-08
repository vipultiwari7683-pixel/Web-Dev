# P3: Feature-Branch Git Workflow

## Objective
To understand and practise the Git feature-branch workflow.

## Work Completed
1. Created a feature branch named `feature-about-section`.
2. Switched to the feature branch.
3. Updated the About Me section in `index.html`.
4. Staged and committed the changes.
5. Switched back to the `main` branch.
6. Merged the feature branch into `main`.

## Git Commands Used

```bash
git branch feature-about-section
git switch feature-about-section
git add index.html
git commit -m "Add About section to portfolio"
git switch main
git merge feature-about-section
git log --oneline --all --graph
git status
```

## Result
Successfully created a feature branch, committed changes, and merged them into the main branch.