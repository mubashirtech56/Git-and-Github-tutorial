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



## Merge a Branch into `main`

```bash
# Step 1: Update your local repository
git checkout main
git pull origin main

# Step 2: Merge the target branch into main
git merge mj

# Step 3: Push the merged changes to the remote repository
git push -u origin main
```

## How to Delete a branch

```bash
git branch -D branch-name
```