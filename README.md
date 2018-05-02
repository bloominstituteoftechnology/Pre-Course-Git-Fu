# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * Repository - A git repository contains, among other things, the following: A set of commit objects. A set of references to commit objects, called heads
 * Git - Version Control - a system for tracking changes in computer files and coordinating work on those files among multiple people
 * Fork - copies a repository to a remote online repository. Forking a repository allows you to freely experiment with changes without affecting the original project
 * Clone - copies a repository to a local offline repository. The repository has its own history, manages its own files, and is a completely isolated environment from the original
 * History - a graph of snapshots of the entire repository. These commit snapshots can have multiple parents, creating a history that looks like a graph instead of a straight line
 * Staging - a step before the commit process in git. That is, a commit in git is performed in two steps: staging and actual commit
 * Remote - a URL where it could be your repository on GitHub, or another user's fork
 * Commit - records changes to the local offline repository
 * Push - records changes to the remote online repository

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
