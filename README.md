# Pre Course Git Fu

## Terms for learning Git
 * Repository: a "folder" that Git is tracking for version control. 
 * Git - Version Control: tech that keeps track of all committed "save points" history for a repo. Great for distributed teams. 
 * Clone: `git clone` creates a copy of the repo
 * Fork: create a copy of the repo (usually from another GitHub account to your GitHub account)
 * History: `git log` shows the commit history
 * Staging: these are changes you have made to the repo that have not been committed yet.
 * Remote: you can have the origin repo on a sqerver (like GitHub)
 * Commit: `git commit` creates a "save point" in Git
 * Push: `git push` take your commits on your local machine and pushed them to the remote repo.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`