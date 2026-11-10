# P4: GitHub README and Version Tags

## Aim:
To create a README file, upload a Git repository to GitHub, and create version tags.

## Procedure:

1. Navigate to the existing portfolio project folder.
2. Create a README.md file.
3. Add project details to the README file.
4. Stage and commit the README file.
5. Create a new repository on GitHub.
6. Connect the local repository to GitHub using a remote URL.
7. Rename the current branch to main.
8. Push the project to GitHub.
9. Create an annotated version tag.
10. Push the version tag to GitHub.
11. Verify the remote repository, tags and repository status.

## Commands:

**1. Navigate to the project folder:**
```bash
cd portfolio
```

**2. Check project files:**
```bash
ls
```

**3. Create README.md:**
```bash
touch README.md
```

**4. Stage the README file:**
```bash
git add README.md
```

**5. Commit the changes:**
```bash
git commit -m "added project readme"
```

**6. Connect the local repository to GitHub:**
```bash
git remote add origin https://github.com/Sanskriti1208/portfolio_for_web_Dev_lab
```

**7. Rename the branch to main:**
```bash
git branch -M main
```

**8. Push the project to GitHub:**
```bash
git push -u origin main
```

**9. Create a version tag:**
```bash
git tag -a v1.0 -m "First release"
```

**10. Push the version tag to GitHub:**
```bash
git push origin v1.0
```

**11. Verify the remote repository:**
```bash
git remote -v
```

**12. Check the created tags:**
```bash
git tag
```

**13. Check repository status:**
```bash
git status
```

## Result:

Successfully created and committed a README file, connected the local Git repository to GitHub, uploaded the project to the remote repository, and created and pushed the version tag v1.0.