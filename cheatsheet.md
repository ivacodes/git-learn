# GIT cheat sheet or Frequently used commands


## git clone <repo>
Clones a remote repository into your local machine, basically makes a local copy
<repo> is the url of the repo like https://github.com/ivacodes/git-learn

## git add <directory> or <file> or .
Prepares your local changes to be commited. In git wording, changes them to 'Staged'
Only staged changes can be commited.
You can decide if you want to stage a file, folder or all local changes with .
When files are staged, they are ready to be commited with the next command

## git commit -m "put meaningful message here"
The simplest and most used way to commit changes into your branch.
Make sure you put a meaningful message, future you will than you

## git checkout <branch>
Changes your active branch, git checkout main will make main your active branch

## git checkout -b "put-branch-name-here"
Creates a new branch which is the copy of the one you are currently on, and then switches to it.
So if you are on main: git checkout -b "my-new-branch" will create a copy of the main branch, call it my-new-branch and make it active

## git push origin -u my-new-branch
When pushing the first time to a remote repository, we have to set the upstream origin for that branch with origin -u.
This will create a copy of our branch on the remote repository and link our push command to it.
Every following time we are pushing the same branch we can use the next command

## git push
The simplest way to send your branch and changes to the server

## git fetch
Downloads a fresh log of all available branches on the remote repository

## git status
Will tell you if you have changes you need to pull or push, best used after fetch

