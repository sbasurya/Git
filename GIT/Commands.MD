# Git 

## Configure Git

Configure the author name and email address to be used with your commits.

```sh
git config --global user.name "Shiva"
git config --global user.email sforcloud@gmail.com.com
```

## Repository Creation 

Create a new local repository
```sh
git init
```

Create a working copy of a local repository
```sh
git clone /path/to/repository
```

## Add files

Add one or more files to staging (index):
```sh
git add <filename>

git add *
```
## Commit

Commit changes to head (but not yet to the remote repository):
```sh
git commit -m "Commit message"
```

Commit any files you've added with git add, and also commit any files you've changed since then:
```sh
git commit -a
```

## Push
Send changes to the master branch of your remote repository:
```sh
git push origin master
```

## Status
Lists all new or modified files to be committed

```sh
git status
```
Shows file differences not yet staged

```sh
git diff
```
Snapshots the file in preparation for versioning
```sh
git add [file]
```
Shows file differences between staging and the last file version
```sh
git diff --staged
```
Unstages the file, but preserves its contents
```sh
git reset [file]
```
Records file snapshots permanently in version history
```sh
git commit -m "[descriptive message]"
```


## Connect to a remote repository

If you haven't connected your local repository to a remote server, add the server to be able to push to it:
```sh
git remote add origin <server>
```

## Branches

Create a new branch and switch to it
```sh
git checkout -b <branchname>
```

Switch from one branch to another
```sh
git checkout <branchname>
```

List all the branches in your repo, and also tell you what branch you're currently in
```sh
git branch
```

Delete the feature branch
```sh
git branch -d <branchname>
```

Push the branch to your remote repository, so others can use it
```sh
git push origin <branchname>
```

Push all branches to your remote repository
```sh
git push --all origin
```

Delete a branch on your remote repository
```sh
git push origin :<branchname>
```

## Update from the remote repository

Fetch and merge changes on the remote server to your working directory
```sh
git pull
```

To merge a different branch into your active branch
```sh
git merge <branchname>
```

View all the merge conflicts:
View the conflicts against the base file:
Preview changes, before merging

```sh
git diff

git diff --base <filename>

git diff <sourcebranch> <targetbranch>
```

After you have manually resolved any conflicts, you mark the changed file
```sh
git add <filename>
```


