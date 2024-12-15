# Git commands

## Git: starting a repository
* `git status` -> check to see which files are being tracked or need to be commited
* `git init` -> use this command inside of your project to turn it into a Git repository and start using Git with that codebase

## Git: staging files
* `git add <file-name>` -> Adds a file to the staging area.
* `git add <file name> <another-file-name> <yet-another-file-name> `
* `git add .` ->  add all file in working directory into git
* `git add --all`
* `git add -A`
* `git rm --catched <file-name>`  -> Removes a file from the Git index (staging area) but does not delete the file from your local filesystem.
* `git reset <file-name>` -> Unstages a file that has been added to the staging area, moving it back to the working directory.
  
### Process of staging
#### Before staging
Working Directory: file.txt (modified)
Staging Area: [empty]
#### After Staging (git add file.txt)
Working Directory: file.txt (unchanged)
Staging Area: file.txt (ready for commit)
#### After Commit (git commit -m "Commit message")
Working Directory: file.txt (unchanged)
Staging Area: [empty]
Repository: file.txt (saved in commit)


## Git: committing to a repository
* `git commit -m "Add 3 files" `-> save your changes into Git, -m means messages
* `git commit --amend -m "enter your messages" `
* `git reset --soft HEAD^ ` -> Undo the last commit but keep the changes staged.

## Git: pulling and pushing from and to repositories
* `git remote add origin <link> ` -> Connect your local repo to a remote one.
* `git push -u origin master`  -> push your changes to your remote repo on Github (or another website)
* `git clone <clone>` -> bring a repo down from the internet (remote repository like Github) to your local machine
* `git pull`  -> pull changes down from the remote repo to your local machine
