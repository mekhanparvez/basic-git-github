# Basic Git & Github commands

- Get started by creating a new file or uplading an existing file.
- Every repository should include a README LICENSE and .gitignore file

## Create a GitHub Repository using the Command Line

**1. Create a New Repository on the command line**

```
echo "# enter-project-heading" >> README.md
git init
git add README.md
git commit -m "enter-commit-message"
git branch -M main
git remote add origin "enter-github-repo-url"
git push -u origin main
```

**2. push an Existing Repository from the command line**

```
git remote add origin "enter-github-repo-url"
git branch -M main
git push -u origin main
```

**3. Clone a Repository from github**

```
git clone "enter-github-repo-url"

```
