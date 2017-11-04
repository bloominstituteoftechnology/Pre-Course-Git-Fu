# Pre Course Git Fu

## Terms for learning Git
 * Repository -a place where the history of your work is stored. It often lives in a .git subdirectory of your working copy
 * Git - Version Control - 
 * Clone - a copy of a repository. it has its own history, manages its own files, and is a completely isolated environment from the original repository. this is usually kept on your local machine
 * Fork - a copy of a repository associated with your github account. this is the online copy
 * History - the commit history of a repo or branch of a repo
 * Staging -The staging area is a simple file, generally contained in your Git directory, that stores information about what will go into your next commit.
 * Remote -the place where your code is stored
 * Commit -a record of changes to the repository 
 * Push -saves commits made on your local branch to a remote repo

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`