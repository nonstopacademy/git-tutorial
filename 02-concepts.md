# git spaces

## WORKING DIRECTORY

holds the actual files

## STAGING/INDEX

keeps track of the snapshots of the files until the staged changes are committed

## REPOSITORY

spaces for commit objects, persistent snapshot, is immutable 

### HEAD

the last commit you've made

# file states

A file in the working tree of a Git repository can have different states

## untracked

the file is not tracked by the Git repository. This means that the file never staged nor committed.

## tracked

committed and not staged

## staged

staged to be included in the next commit

## dirty / modified

the file has changed but the change is not staged

