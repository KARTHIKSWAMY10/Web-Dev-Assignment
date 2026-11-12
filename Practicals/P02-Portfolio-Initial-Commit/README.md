# P2 – Portfolio repo with an initial commit

## Aim
Create a portfolio project, initialise Git, and save its first version as a commit.

## Steps
```bash
mkdir my-portfolio
cd my-portfolio
git init
```

Create an `index.html` file with a basic page:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <p>Student | Aspiring Web Developer</p>
  </header>
  <main>
    <section>
      <h2>About Me</h2>
      <p>Write a short introduction about yourself.</p>
    </section>
  </main>
</body>
</html>
```

Save the file, then run:

```bash
git status
git add index.html
git commit -m "Initial portfolio page"
git log --oneline
```

## Expected result
A local Git repository containing the first commit. Replace the sample introduction with your own details.
