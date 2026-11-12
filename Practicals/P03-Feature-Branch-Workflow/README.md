# P3 – Feature-branch Git workflow

## Aim
Practise making a change on a separate branch and merging it into the main branch.

## Commands
Start inside the portfolio repository created in P2.

```bash
git switch -c feature/about-section
```

Add an About section to `index.html`, save the file, then:

```bash
git status
git add index.html
git commit -m "Add about section"
git switch main
git merge feature/about-section
git log --oneline --graph --all
```

If your default branch is named `master`, use `master` instead of `main`.

## Optional: publish the branch
```bash
git push -u origin feature/about-section
```

## Key concepts
- A branch lets you work on a change separately.
- A commit records a snapshot of tracked changes.
- A merge integrates the branch into the current branch.
- Resolve any merge conflicts in the affected files, then add and commit the resolution.

## Expected result
The About section is present on `main`, and the feature branch's commit appears in the Git history.
