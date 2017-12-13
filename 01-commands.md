# Setting up

## Tell Git who you are

    git config --global user.name "YOUR NAME"
    git config --global user.email YOUR@EMAIL.ADDRESS

## Create a new local repository

    git init

## Connect to a remote repository

    git remote add origin <SERVER>

## Clone a repository from remote server

    git clone username@host:/path/to/repository

# Commons

## List the files you've changed and those you still need to add or commit

    git status

## Add one or more files to staging (index)

    git add <FILENAME>

    git add .

## Commit changes to head (not yet to the remote repository)

    git commit -m "MESSAGE"
    git commit -a

## Send changes to the master branch of your remote repository

    git push origin <BRANCHNAME>

## Fetch and merge changes on the remote server branch to your working directory

    git pull origin <BRANCHNAME>

# Branch

## Create a new branch and switch to it:

    git checkout -b <BRANCHNAME>

## Switch branch

    git checkout <BRANCHNAME>

## List all the branches in your repo, and also tell you what branch you're currently in

    git branch

## Merge a different branch into your active branch

    git merge <BRANCHNAME>

## Delete the branch

    git branch -d <BRANCHNAME>

# Inspection

## git log

    git log --oneline --graph --decorate --all

###  to see which files were involved in each commit

    git log --stat

### to see the actual changes that were made

    git log --patch

## List all currently configured remote repositories

    git remote -v
    git remote show origin


