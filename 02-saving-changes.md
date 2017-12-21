# Saving changes

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

## Temporarily shelves (or stashes) changes you've made to your working copy

    git stash
