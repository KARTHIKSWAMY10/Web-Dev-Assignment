# P4 – GitHub README and version tags

## Aim
Document a project with a README and mark a stable version using a Git tag.

## Example README.md
```markdown
# My Portfolio

A simple personal portfolio website built with HTML and CSS.

## Features
- Introduction and About section
- Skills
- Projects
- Contact information

## Run locally
1. Clone or download this repository.
2. Open index.html in a web browser.

## Author
Your Name
```

## Git commands
```bash
git add README.md
git commit -m "Add project README"
git tag -a v1.0.0 -m "First portfolio release"
git tag
git show v1.0.0
```

To publish commits and the tag to GitHub:

```bash
git push origin main
git push origin v1.0.0
```

## Key concepts
- README files explain what a project does and how to use it.
- A tag is a named reference to a particular commit.
- Annotated tags store a message and tag metadata.
