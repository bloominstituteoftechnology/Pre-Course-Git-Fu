# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * Repository - The most basic element of Git, a repository contains all of the project files including documentation as well as each file's revision history.

 * Git - Version Control - version control allows developers to keep track of every modification made to code base and return to previous versions of the code base if needed.

 * Clone - an exact copy of a repository that lives on your local computer.

 * Fork - a fork is a personal copy of another person's repository that lives on your account. Forks can be freely modified without affecting the repo they were cloned from.

 * History - the history of a repository contains a record of every commit made to the repository as well as who made the commit, the commit message, and other pertinent information.

 * Staging - The staging area is where changes to a file are stored when you use git add.

 * Remote - The remote is the online repository where changes to a repository are stored.

 * Commit - A commit saves the current status of a file or set of files, every commit has a unique ID that allows the repository to restore itself to the status it was in when the commit was made.
 
 * Push - a push saves the current commit to a remote repository.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL
3. After Changes Made: `git status`
4. `git add <file-name>`
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`