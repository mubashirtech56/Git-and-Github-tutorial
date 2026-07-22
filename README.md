## Stages of Git

```bash
U - untracked
A - added or staged
C - Commited
```

## Command of Initialize a git repo

```bash
git init
```

## Command for status

```bash
git status
```

## Command to Check Current status of files

```bash
git status -s
```

## Command to Check saved Check-Points

```bash
git log --oneline --graph
```

## Command to see Branches
```bash
git branch
```
## Command to Create a New Branch
```bash
git branch name-of-new-branch
```

## Command to Switch to branches

```bash
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

## Stashing 

```bash
git stash 
```
# Now want to restore what you stashed 
```bash
git stash apply
```