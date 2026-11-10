# P3: Feature-Branch Git Workflow

## Aim:

To understand and implement the feature-branch workflow using Git.

## Procedure:

1. Create a new feature branch.
2. Switch to the feature branch.
3. Create an `about.html` file.
4. Add content to the HTML file.
5. Stage the changes using Git.
6. Commit the changes.
7. Switch back to the main branch.
8. Merge the feature branch into the main branch.

## Commands:

**1. Create a feature branch:**

```bash
git branch feature-about
```

**2. Switch to the feature branch:**

```bash
git switch feature-about
```

**3. Create an about.html file:**

```bash
touch about.html
```

**4. Add content to about.html:**

```html
<title>About Me</title>
```

**5. Stage the file:**

```bash
git add about.html
```

**6. Commit the changes:**

```bash
git commit -m "Added about page"
```

**7. Switch to the main branch:**

```bash
git switch main
```

**8. Merge the feature branch:**

```bash
git merge feature-about
```

**9. View the commit history:**

```bash
git log 
```

## Result:

Successfully created a feature branch, added and committed the `about.html` file, and merged the feature branch into the main branch using Git.
