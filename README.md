# Stages of Git

```
U - untracked
A - added or staged
C - Commited
```

# Command of Initialize a git repo

```
git init
```

# Command for status

```

git status

```

# Command to Check Current status of files

```

git status -s

```

# Command to Check saved Check-Points

```

git log --oneline --graph

```

# Command to see Branches
```
git branch
```
# Command to Create a New Branch
```
git branch name-of-new-branch
```

# Command to Switch to branches

``` 
git switch branch-name
```

<<<<<<< HEAD
# INSTRUCTION TO MERGE BRANCHES

```
# Step 1 Clone the repository or update your local repository with the latest changes.

git pull origin main


# Step 2 Switch to the base branch of the pull request.

git checkout main

# Step 3 Merge the head branch into the base branch.

git merge mj

# Step 4 Push the changes.

git push -u origin main

```
=======

## Merge a Branch into `main`

Follow these steps to merge the `mj` branch into `main` and push the changes to the remote repository.

```bash
# Step 1: Update your local repository
git checkout main
git pull origin main

# Step 2: Merge the target branch into main
git merge mj

# Step 3: Push the merged changes to the remote repository
git push -u origin main
```

> **Note:** Replace `mj` with the name of the branch you want to merge if it is different.
>>>>>>> mj
