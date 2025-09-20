# Section 01: This is for learning version controlling

## Step 01 : Create a repository github.com

## Step 02 : Create a folder in local machine

## Step 03 : Open the project folder in VSCode

## Step 04 : Open the terminal of VSCode

- Use one of (bash/cmd/git bash)

## Step 05 : Check the git version

```bash
git -v
```

## Step 06 : Initialize a git repo using

```bash
git init
```

## Step 07 : Check the git status

```bash
git status
```

## Step 08 : Add files to the git using

```bash
# Add all files in the current folder
git add .

# Add all files regardless of the folder we are in
git add -A
```

## Step 09 : Commit the changes with a meaningful commit message

```bash
# Always should be meaningful, concise and relevant
git commit -m "Initial project commit"
# ex: This commit will: "Update script file"
# ex: This commit will: "Refactor current logic"
```

## Step 10 : Check if there's any existing remote urls

```bash
git remote -v
```

## Step 11 : Check if there's any existing remote urls

```bash
git remote add origin git@github.com:<remote-url>

# ex: git remote add origin git@github.com:shalithadev/react-basics-b-05.git
```

## Step 12 : Check if the remote url configured without a issue

```bash
git remote -v
```

## Step 13 : Make sure the default branch is your `main` branch

```bash
git branch -M main
```

## Step 14 : Push the local commits to the remote/cloud branch

```bash
git push -u origin main
```

## Step 15 : Check if the changes are there in the remote

---

# Section 02

## Step 16 : Do a file change

## Step 17 : Check file change in VSCode

## Step 18 : Check file change in the terminal using

```bash
git status
```

## Step 19 : Repeat step 08

## Step 20 : Proper commit message

```bash
git commit -m "Update the steps documentation"
```

## Step 21 : Push the changes the existing branch

```bash
git push
```

## Step 22 : Create a new branch called `dev` from `main` branch

```bash
git checkout -b dev
```

## Step 23 : Publish the branch to remote `origin dev`

```bash
git push -u origin dev
```

## Step 24 : Repeat step 08

## Step 25 : Create a PR (Pull Request) from github and merge it to main

```bash
# Navigate between branches
git checkout main
git checkout dev

# Check the changes/status between local and remote
git fetch

# Checkout to main branch
git checkout main

# Pull the changes to local form remote main branch
git pull

git checkout
```
