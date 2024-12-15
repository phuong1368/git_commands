# Git commands

# Git: starting a repository
* `git status` -> check to see which files are being tracked or need to be commited
* `git init` -> use this command inside of your project to turn it into a Git repository and start using Git with that codebase

# Git: staging files
* `git add` <file-name> -> track your files and changes with Git
* `git add` <file name> <another-file-name> <yet-another-file-name>
* `git add .` ->  add all file in working directory into git
* `git add --all`
* `git add -A`
* `git rm --catched <file-name>`
* `git reset <file-name>`

# Git: committing to a repository
* `git commit -m "Add 3 files" `-> save your changes into Git, -m means messages
* `git reset --soft HEAD^ `
* `git commit --amend -m "enter your messages" `

# Git: pulling and pushing from and to repositories
* `git remote add origin <link> `
* `git push -u origin master`  -> push your changes to your remote repo on Github (or another website)
* `git clone <clone>` -> bring a repo down from the internet (remote repository like Github) to your local machine
* `git pull`  -> pull changes down from the remote repo to your local machine