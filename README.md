# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * Repository - a Git project with history of all tracked files, changes, contributors, and other data
 * Git - Version Control - a framework allowing collaboration and tracking of project history
 * Clone - copy a repository onto your local machine for editing
 * Fork - copy another user's repository
 * History - the past changes to all the files as well as what users contributed to the project and any comments they left
 * Staging - set up any changes made on your local machine to be committed to the project history
 * Remote - a copy of the repository, usually off of your local machine, that you can pull changes from (if multiple users (or machines) are working from that copy of the repo) or push changes to (for yourself or other users to then use)
 * Commit - a chunk of changes grouped together logically and added to the project history as a discrete event that can be tracked in the history and/or used to compare against other users' histories of their own forks of the repository
 * Push - send any local changes you've made to the repo history into a remote copy of the repo

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
